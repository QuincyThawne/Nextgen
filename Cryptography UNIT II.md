# Cryptography UNIT II - Questions and Answers

1. *Analyze how the mixcolumns operation contributes to the avalanche effect in AES, and why this property is essential for security.*  
   *Answer:* MixColumns introduces diffusion and makes small changes in input affect many output bits.

2. *Block ciphers use a symmetric key for both encryption and _____.*  
   *Answer:* decryption.

3. *In AES, why is finite field arithmetic used for encryption and key expansion?*  
   *Answer:* It introduces non-linearity and confusion.

4. *What technique is often used to enhance the security of DES by applying the algorithm multiple times with different keys?*  
   *Answer:* Triple DES (3DES).

5. *In DES, how many rounds of encryption are performed on a 64-bit block of data?*  
   *Answer:* 16 rounds.

6. *Which of the following statements about block ciphers is incorrect?*  
   *Answer:* They are typically faster than stream ciphers.

7. *DES uses a symmetric key algorithm, which means that:*  
   *Answer:* The same key is used for both encryption and decryption.

8. *Which component in DES is responsible for performing substitution and permutation operations on the data?*  
   *Answer:* S-boxes.

9. *A block cipher with a block size of 128 bits and a key length of 256 bits would have how many possible keys?*  
   *Answer:* 2^256.

10. *Analyze the factors that organizations should consider when choosing between AES-128, AES-192, and AES-256 for their cryptographic needs.*  
    *Answer:* Performance and security requirements influence key length selection.

11. *The _____ process in block ciphers involves scrambling the plaintext using a secret key.*  
    *Answer:* encryption.

12. *When might a block cipher be preferred over a stream cipher in a cryptographic application?*  
    *Answer:* When a high level of parallelism is required.

13. *In a secure communication system, Alice wants to ensure that her data is both confidential and tamper-proof. Which cryptographic technique should she use?*  
    *Answer:* Block cipher.

14. *The block size of AES is _____ bits.*  
    *Answer:* 128.

15. *Justify why AES-192 is considered to have a balanced level of security and how it compares to AES-128 and AES-256.*  
    *Answer:* AES-192 offers a compromise between speed and security.

16. *If a block cipher operates on 64-bit blocks and uses a 128-bit key, how many possible keys exist for this cipher?*  
    *Answer:* 2^128.

17. *Identify the incorrect statement about round key generation in AES.*  
    *Answer:* Round keys are the same for each round.

18. *In a block cipher, what is the size of the block that is processed at a time?*  
    *Answer:* Variable size.

19. *Which statement about the mixcolumns operation is incorrect?*  
    *Answer:* It is used only in encryption.

20. *Is it true or false that block ciphers are resistant to brute-force attacks as long as they have a sufficient key length?*  
    *Answer:* True.

21. *Justify the importance of the sub bytes transformation in AES and its impact on security.*  
    *Answer:* It enhances diffusion and contributes to non-linearity.

22. *The Data Encryption Standard (DES) operates on blocks of data that are:*  
    *Answer:* 64 bits.

23. *AES _____ has _____ rounds in its encryption process.*  
    *Answer:* 128, 10.

24. *What is the primary purpose of a block cipher?*  
    *Answer:* To encrypt blocks of data at a time.

25. *Which mode of operation is used in the DAA?*  
    *Answer:* Cipher Block Chaining mode.