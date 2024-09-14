# RSA Algorithm Implementation

I wrote this program for my Cybersecurity course assignment trying to implement the RSA algorithm in a simple way in Javascript and then putting it into an html file to view it as a webpage. 

## Features

- User inputs two prime numbers (p and q).
- User inputs a plaintext message.
- The program calculates:
  - Public key (`n`, `e`) using the input prime numbers.
  - Private key (`n`, `d`) using the public key and Euler’s Totient function (`phi`).
- The program encrypts the plaintext message using the public key.
- The program decrypts the encrypted message using the private key.
- Displays both encrypted and decrypted messages.

## Files

- **index.html**: Contains the HTML structure, including input fields for prime numbers and the plaintext message, a button to apply the RSA algorithm, and a display area for results.
- **JavaScript (embedded in the HTML)**: Contains the RSA algorithm implementation, including:
  - Input validation for prime numbers and message.
  - Calculation of the public and private keys.
  - Functions for encryption and decryption of the message.
  - Display of results on the page.
