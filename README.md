java c
ECSE308F23: INTRODUCTION TO COMMUNICATION SYSTEMS AND NETWORKS
Assignment 1 (covering modules A,B,C)
FALL 2024
A1. Illustrate a situation in which circuit switching is more beneficial than packet switching.
A2. Illustrate how noise and interference can affect the signal detection quality.
A3. What are the advantages and disadvantages of the layered protocol stack design?
A4. What are the different between the segment, packet and frame. in the context of TCP/IP protocol stack?
A5. What are the differences between multiplexing and multiple-access? Give some examples.
A6. A 1Mbps satellite link is used to connect two cities. Suppose that the distance from the satellite to each city is 36,000km, the signal is propagated at the speed of light (3 × 108m/s), and the signal processing time over the satellite is negligible. Calculate the time required to transmit a 1MB data packet and receive a 100B acknowledgement packet.
A7. A signal x(t) = sin (2πt) is transmitted through a 2-path channel, one path with amplitude gain of 0.8 and delay of 0.5s, and the other path with amplitude gain of -0.2, and delay of 0.6s. The received signal is the sum of 2 components. Plot the received signal.
A8. Suppose that the TCP/IP protocol stack is used where an application needs to transmit 1,000 bytes of data. Each of the headers at the transport and internet layers is 50-byte long. At the data link layer, the maximum admissible frame. length for transmission on the link is 500 bytes. In addition, for each frame, the data link layer adds a header of 50 bytes. Calculate the total number of header overhead bits needed for transmitting 1000 bytes of information.
B1. Why frequency-domain analysis is important in understanding the characteristics of a signal?
B2. Define the bandwidth of a signal.
B3. How channel attenuation affects its bandwidth? What is the relationship between the signal bandwidth and the channel bandwidth?
B4. Define the channel capacity? According to Shannon’s formula for capacity of AWGN channel, what are the fundamental communication resources?
B5. Why it is important to twist the wires in twisted pair cable?
B6. Multimode transmission is not desirable in optical fiber?
B7. Find the frequency components and the amplitude of each of those components for a square wave with periodof 2π, which is defined in one period

B8. Calculate the thermal noise power spectral density of a wireless channel operating at 30oC. Suppose that the bandwidth of this channel is 1MHz, calculate the thermal noise power in W and in dBW.
B9. Suppose that a voice signal with a bit rate of 64Kbps is transmitted over a 4KHz bandwidth channel. Calculate the minimum SNR to support this transmission? Suppose that the noise power spectral density is N0 = 5.7 × 10-10 w/Hz, calculate the minimum signal power to support this transmission.
B10. A twisted pair cable have an attenuation of 15dB/km. Suppose that the input power of the transmission line is 0.1W. Calculate the output power after 1km. Suppose that the minimum detectable signal power at the receiver is 0.01W. Recalculate t代 写ECSE308F23: INTRODUCTION TO COMMUNICATION SYSTEMS AND NETWORKS Assignment 1 FALL 2024Matlab
代做程序编程语言he maximum cable length in this case.
B11. Calculate the free-space path loss attenuation of a GEO, a MEO and a LEO satellite which hover at 36,000km, 20,000km and 2,000km above the earth surface accordingly. Given that the operation frequency is 30GHz.
B12. Plot the modulated waveform. of the binary sequence 00011011 using OOK, BFSK, BPSK and 4-QAM.
C1. What is the difference between error detection and error correction mechanisms?
C2. What is the main difference in the error recovery mechanism between ARQ and FEC?
C3. What is flow control?
C4. In error detection, why it is not possible for the receiver to detect all erroneous bit pattern?
C5. In a (n, k) code, what are the number or data bits and added bits? What is the ratio between the number of valid codewords and the number of total codewords?
C6. Define Hamming distance? Show that the minimum Hamming distance of 1-D parity check is 2.
C7. Describe the mechanism of generating a CRC code and that for CRC error detection.
C8. Draw the shift register implementation of the CRC scheme with G(x)=x3+1. Illustrate the encoding and error detection process of the data pattern of "1101” (assuming no error).
C9. Find the Hamming distance between the following codewords: A=(000000), B=(101010), C=(000111). What is the minimum distance of this set of codewords A, B,C ?
C10. Stop-and-Wait is used on an error-free communication channel with the transmission bit rate of 100kbps and the propagation time of 50ms. The frame. size is 100bits, assume that the ACK frame. size and the processing delay is negligible
a. Find the channel utilization.
b. To increase the channel utilization, the frame. size is increased, what is the minimum frame. size to have the channel utilization at least 10%?
C11. Using 16-bit Internet checksum:
a. Calculate the Internet checksum for the four 16-bit words of data as follows: E308 E309 00FF 0F0F.
b. Suppose that the received data and checksum are contaminated with error as follows: E308 E309 00FF 0F0E 29DF. Verify that the Internet checksum can detect the error.
c. Find an example of a 2-bit error that can fool Internet checksum for the above data and checksum.
C12. Let G(x) = x3  + 1, and the information bits to be transmitted are 1101.
a. Find the corresponding CRC codeword.
b. If the CRC codeword in a. is contaminated with an error pattern expressed as E(x) = x3 + x2, show that the above CRC coding scheme can detect the erroneous data.
c. Find a 2-bit error pattern that can fool the CRC scheme in a.
C13. A transmission link with a bit error rate of p = 0.001 is used for transferring 10-byte frames. Calculate
a. The probability that there is exactly one error bit in the received frame?
b. What is the frame. error probability, i.e., the probability that the received frame. contains at least one error bit?
c. If the frame. length is halved, what is the frame. error probability?
C14. In HDLC, for a bit stream of 11111100 11111000, what is the actual transmitted bit stream after bit stuffing?







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
