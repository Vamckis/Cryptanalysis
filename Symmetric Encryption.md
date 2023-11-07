## Symmetric Encryption
- Same key used for E & D
- PKCS (Public Key Cryptography Standards) are 15 widely accepted standards.
### Types:
- Monoalphabetic sunstitution ciphers
  - Caesar / Shift cipher: We shift alphanumerical characters based on seed. (e.g: shift 3 characters forward)
  - General sunbstitution cipher: We create a mixed alphabet and send message with matching letter.
    - It can be broken by frequency analysis.
    - <img width="516" alt="Screenshot 2023-11-07 at 7 16 00 PM" src="https://github.com/Vamckis/Cryptanalysis/assets/71128825/9335b2e8-d8ab-4107-ac14-54b2a629a7bc">
- Polyalphabetic subsitition ciphers
  - Vigenere cipher
  - One-Time pad 
- Transposition / Permutation Ciphers (Non Key)
- Modern block ciphers: Uses subsitution an Transposition together.
  - DES (Data Encryption Standard)
  - 3DES (Triple DES) : E(E(E(M))) = C
  - AES (Advanced Encryption standard)
 
  ### Modes in Symmetric Encryption
  - ECB : Not semantically secure. Not recommanded for images. Recommanded only for small text.
    - <img width="860" alt="Screenshot 2023-11-07 at 7 39 48 PM" src="https://github.com/Vamckis/Cryptanalysis/assets/71128825/61e18672-e93e-4ecc-bc66-7bdd2858af0f">   
  - CBC : Uses IV (Initialization vector) at beginning of cipher. This introduces additional randomness and avoids pattern matching.
    - <img width="423" alt="Screenshot 2023-11-07 at 7 40 02 PM" src="https://github.com/Vamckis/Cryptanalysis/assets/71128825/2e6c9444-0238-40e1-86e8-423a5ce9587e"> 
  - CFB: Similar to CBC, IV is added to Block Cipher. No padding is required.
  - OFB: 
    - <img width="424" alt="Screenshot 2023-11-07 at 7 42 44 PM" src="https://github.com/Vamckis/Cryptanalysis/assets/71128825/23aeb65f-c956-4152-a1d6-bc9161cf6ecf">
  - CTR: Nonce(random characters) is used instead of IV.
    - <img width="379" alt="Screenshot 2023-11-07 at 7 44 40 PM" src="https://github.com/Vamckis/Cryptanalysis/assets/71128825/8c2155ba-9b9e-463d-8502-93a24e5e7843">
   
