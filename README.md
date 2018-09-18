PadBuster - Automated script for performing Padding Oracle attacks

Author: Brian Holyfield - Gotham Digital Science (labs@gdssecurity.com)

Credits to J.Rizzo and T.Duong for providing proof of concept web exploit
techniques and S.Vaudenay for initial discovery of the attack. Credits also
to James M. Martin (research@esptl.com) for sharing proof of concept exploit
code for performing various brute force attack techniques.

PadBuster is a Perl script for automating Padding Oracle Attacks. PadBuster  
provides the capability to decrypt arbitrary ciphertext, encrypt arbitrary plaintext, 
and perform automated response analysis to determine whether a request is vulnerable 
to padding oracle attacks.

PadBuster is released under the Reciprocal Public License 1.5 (RPL1.5)
http://www.opensource.org/licenses/rpl1.5

UPDATE: Added a Dockerfile so we it's possible to build a Docker image from this and run PadBuster in a container. There's also a public image available.

`docker run 4armed/padbuster <options>`
