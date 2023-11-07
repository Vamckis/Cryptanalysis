# Cryptanalysis

## Cryptography
- It is a process of creating hidden data.
- Most popular cryptographuc algoritms are publicly known. But, Cryptographic method is strong because of its mechanisms to create, store and share the secret key
### Key Terminology:
- Encryption: Scramble data to protect it from unauthorised access.
- Decryption
- Cipher: Encryption algorithm
  - Block Ciphers : Operates on fixed size of input. Used for Data at Rest.
  - Stream Ciphers: Operates on Random size input. Used for Data at Transit.
- Interception: Attacker can cut communication and redirect messages to themselves.
- Eaves dropping
- Manipulation
- Notations:
  - EK(M) = C (E: Encryption, K: Key, M: Message)
  - DK(C) = M (D: Decryption, C: Ciphertest)
- 3 states of data:
  - Data at Rest : Data in Harddisk (Encryption can be used)
  - Data in Transit: Data sent over network (Encryption can be used)
  - Data in Process : Data in memory (We cannot use Encryption effectively)
- Key Size: if Key length is n, Key size is 2 to power n. 
- Entropy: Degree of uncertainity. Aim of cipher is to reach maximum entropy.
- PRNGS: Pseudo Random number generators
- Security degrees:
  - Computationally secure: Resistance against Brute force attacks
  - Semantically Secure: Resistance against obtaining original message from cipher text
  - Perfect Secrecy = Computationally secure + Semantically Secure
<img width="834" alt="Screenshot 2023-11-07 at 7 05 31 PM" src="https://github.com/Vamckis/Cryptanalysis/assets/71128825/0fb8196b-37a4-4f13-8e61-8879d90a5ad4">
 
### Symmetric ciphers
### Asymmetric ciphers
