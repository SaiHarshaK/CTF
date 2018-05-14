# Ciphers

## Affine
The Affine cipher is a monoalphabetic substitution cipher
#### Encryption
e(x) = (ax + b) mod m  
You need to pick the 'a' and it must be coprime with the length of the alphabet.b is the magnitude of the shift.  
Here, 'a' is assigned 0; 'b' is assigned 1; 'c' is assigned 2 ; so on...  
default alphabet string is abcdefghijklmnopqrstuvwxyz
#### Decryption
d(x) = a^-1(x - b) mod m.  
'a' was picked such that it is coprime with the length of the alphabet.b is the magnitude of the shift.  
Please refer,How to find multiplicative inverse (x^-1 mod n) to find a^-1.  

## Atbash
The Atbash cipher is a very common, simple cipher. It was for the Hebrew alphabet, but modified here to work with the English alphabet.
#### Encryption
When encoded, an 'A' becomes a 'Z', 'B' turns into 'Y', etc.
#### Decryption
(encryption is decryption too)When decoded, an 'A' becomes a 'Z', 'B' turns into 'Y', etc.

## Baconian
There are two versions. The first uses the same code for I and J, plus the same code for U and V. The second uses distict codes for every letter.  
key1 = { 'A' : 'AAAAA' , 'B' : 'AAAAB' , 'C' : 'AAABA' ,'D' : 'AAABB' ,'E' : 'AABAA' ,'F' : 'AABAB' ,'G' : 'AABBA' ,'H' : 'AABBB' ,'I' : 'ABAAA' ,'J' : 'ABAAA' ,'K' : 'ABAAB' ,'L' : 'ABABA' ,'M' : 'ABABB' ,'N' : 'ABBAA' ,'O' : 'ABBAB' ,'P' : 'ABBBA' ,'Q' : 'ABBBB' ,'R' : 'BAAAA' ,'S' : 'BAAAB' ,'T' : 'BAABA' ,'U' : 'BAABB' ,'V' : 'BAABB' ,'W' : 'BABAA' ,'X' : 'BABAB' ,'Y' : 'BABBA' ,'Z' : 'BABBB'  }  
	key2 = { 'A' : 'AAAAA' , 'B' : 'AAAAB' , 'C' : 'AAABA' ,'D' : 'AAABB' ,'E' : 'AABAA' ,'F' : 'AABAB' ,'G' : 'AABBA' ,'H' : 'AABBB' ,'I' : 'ABAAA' ,'J' : 'ABAAB' ,'K' : 'ABABA' ,'L' : 'ABABB' ,'M' : 'ABBAA' ,'N' : 'ABBAB' ,'O' : 'ABBBA' ,'P' : 'ABBBB' ,'Q' : 'BAAAA' ,'R' : 'BAAAB' ,'S' : 'BAABA' ,'T' : 'BAABB' ,'U' : 'BABAA' ,'V' : 'BABAB' ,'W' : 'BABBA' ,'X' : 'BABBB' ,'Y' : 'BBAAA' ,'Z' : 'BBAAB'  }
#### Encryption
Replace each letter with a group of 5 letters consisting of 'letter_1' and 'letter_2'.
#### Decryption
Seperate the encrypted message into groups of 5 letters and Refer one of the keys to decrypt it.

## Base64
Base64, also known as MIME encoding, translates binary into safe text. It is used to send attachments in email and to change small bits of unsafe high-character data into stuff that is a lot nicer for text-based system.
#### Encryption
Refer [this](https://www.base64encode.org/)
#### Decryption
Refer [this](https://www.base64encode.org/)

## Bifid
The Bifid cipher is considered a more secure cipher because it breaks the message apart into two separate streams and then recombines them. 
#### Encryption
Refer [this](https://www.dcode.fr/bifid-cipher)
#### Decryption
Refer [this](https://www.dcode.fr/bifid-cipher)

# Caesarian Shift
This is a standard Caesarian Shift cipher encoder, also known as a rot-N encoder and is also a style of substitution cipher.  
#### Encryption
Assign,A=0, B=1, ..., Z=25. Now, *add* a constant (the shift), then apply modulo 26 (alphabet length) to the result.This is the coded text.
#### Decryption
Assign,A=0, B=1, ..., Z=25. Now, *subtract* a constant (the shift), then apply modulo 26 (alphabet length) to the result.This is the decrypted text.

<To Be updated>
#### Encryption
#### Decryption

#### Encryption
#### Decryption

#### Encryption
#### Decryption

#### Encryption
#### Decryption

#### Encryption
#### Decryption

#### Encryption
#### Decryption


