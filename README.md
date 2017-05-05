# Flowmoji

Flowmoji is a messaging app built on [Signal](https://github.com/WhisperSystems/Signal-iOS) for even more secure communication. Should an encrypted be compromised an attacker, current end-to-end encryption applications function such that the message is guaranteed to contain valuable information. With enough resources, any attacker can brute-force decrypt an intercepted message or take advantage of as-of-yet unknown vulnerabilities in the Signal protocol.

The premise of this project is to flood an attacker with bogus, encrypted messages in an attampt to overwhelm their resources. Using this  application, only a small percentage of intercepted encrypted messages will contain valuable information.

The user is unaware of the messages being sent back and forth between two application hosts, since the application automatically filters out messages that match the Flowmoji bogus message format.

## Cryptography Notice

This distribution includes cryptographic software. The country in which you currently reside may have restrictions on the import, possession, use, and/or re-export to another country, of encryption software. 
BEFORE using any encryption software, please check your country's laws, regulations and policies concerning the import, possession, or use, and re-export of encryption software, to see if this is permitted. 
See <http://www.wassenaar.org/> for more information.

The U.S. Government Department of Commerce, Bureau of Industry and Security (BIS), has classified this software as Export Commodity Control Number (ECCN) 5D002.C.1, which includes information security software using or performing cryptographic functions with asymmetric algorithms. 
The form and manner of this distribution makes it eligible for export under the License Exception ENC Technology Software Unrestricted (TSU) exception (see the BIS Export Administration Regulations, Section 740.13) for both object code and source code.

## License

Copyright 2014-2017 Open Whisper Systems

Licensed under the GPLv3: http://www.gnu.org/licenses/gpl-3.0.html
