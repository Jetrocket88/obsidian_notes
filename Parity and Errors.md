[[Digital Electronics]]

#flashcards/eee/digital_electronics
What is parity?
?
Parity is a form of error checking in data, where an extra bit is added to a word to modify the number of 1's in the word
<!--SR:!2026-11-06,3,250-->

What are the two forms of parity?
?
Even parity and Odd parity
<!--SR:!2026-11-06,3,250-->

What are the two parts to a parity system?
?
Generator and Checker
<!--SR:!2026-11-04,1,190-->

Assuming even parity, what bit could we add to the end of this word?
0100100
?
0
<!--SR:!2026-11-06,3,250-->

Assuming even parity, what bit could we add to the end of this word?
0101001
?
1
<!--SR:!2026-11-06,3,250-->

How do we determine if an error has occurred in a parity system?
?
Check the number of 1 bits to see if they align with parity
<!--SR:!2026-11-06,3,250-->

What is one of the thing that a parity system cannot detect?
?
Two errors
<!--SR:!2026-11-06,3,250-->

What is one of the main drawbacks of error correction?
?
It always requires transmission or storage of redundant information
<!--SR:!2026-11-04,1,230-->

What are the three ways we might correct errors?
?
Automatic Repeat Requests (ARQ)
Forward Error Correction (FEC)
Hybrid (ARQ)
<!--SR:!2026-11-04,1,170-->

How does Automatic Repeat Request work to correct errors?
?
The receiver must first decide if there was a loss of data (error detection)
If the transmitter does not receive an "OK" signal from the receiver, then the transmitter just sends
it again. This just works by sending another packet or "frame" of data
<!--SR:!2026-11-04,1,230-->

What are the three types of ARQ?
?
Stop and Wait
Go-Back-N
Selective Repeat
<!--SR:!2026-11-05,2,230-->

How does Stop and Wait ARQ work?
?
Transmits one data frame at a time and waits for acknowledgement before advancing
(i.e. One at a time)
<!--SR:!2026-11-06,3,250-->

How does Go-Back-N ARQ work?
?
Transmits multiple frames in one Window of pre-determined size, The receiver then acknowledges
and identifies the last frame of the group that was received correctly. The transmitter then winds
back and then started from that last correctly received frame.
(i.e. Send a decent amount and then rewind from last correct)
<!--SR:!2026-11-04,1,230-->

How does Selective Repeat ARQ work?
The transmitter sends multiple frames in Windows, even in cases of error. The receiver selectively
rejects and requests failed frames, that are retransmitted individually.
(i.e. Send a decent amount and then resend the ones that were wrong individually)
(Mix of the first two options)

How does Forward Error Correction work?
?
Redundant information is added to the message or word.
The redundant information often uses some sort of error-correcting code.
The error-correcting code allows the receiver to detect and locate errors in the original information.
<!--SR:!2026-11-04,1,230-->

What are some of the main points of Forward Error Correction?
?
No resending is required (backchannel)
They have a limit on the maximum quantity of errors that can be successfully corrected
In the event of no-errors, we still had to transmit lots of redundant info
<!--SR:!2026-11-04,1,210-->

How do Hybrid Schemes work?
?
They use a mix of FEC and ARQ to save on the amount of redundant data being sent, while providing a fallback when error correction fails.
<!--SR:!2026-11-04,1,230-->












