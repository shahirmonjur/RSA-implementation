# RSA Algorithm Implementation

I wrote this program for one of my Cybersecurity course assignments trying to understand the the RSA algorithm in a simple way and scrapped a few line of code and then put it into an html file to view it as a webpage.  

![image](https://github.com/user-attachments/assets/4d29e2e3-ad16-4aa8-a7fd-3926d41d1c2a)


RSA Algorithm 

  - Key Generation:
    - Select two distinct prime numbers, p and q.
    - Compute n = p * q.
    - Calculate Euler’s totient function: φ(n) = (p - 1) * (q - 1).
    - Choose an integer e such that 1 < e < φ(n) and gcd(e, φ(n)) = 1.
    - Determine the private key d such that (d * e) % φ(n) = 1.

  - Encryption:
    - Convert each character in the plaintext message to its ASCII value.
    - Encrypt each character using the formula:

            EncryptedCharacter = (ASCII_Value^e) % n

  - Decryption:

      Decrypt each character using the formula:

            DecryptedCharacter = (EncryptedCharacter^d) % n

Convert the decrypted ASCII values back to characters to get the original message.


![image](https://github.com/user-attachments/assets/932e7349-408c-426e-9486-83675280149a)


![image](https://github.com/user-attachments/assets/b4779df3-58e1-4084-b4f2-7ef5924b692e)

Thank you.
