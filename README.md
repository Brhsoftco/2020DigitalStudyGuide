# 2020DigitalStudyGuide

# Topic 1

<h2> Recognise and Describe </h2>

<h3> Encryption </h3>

<li><i>Criteria: 
  <ol>
    - Recognise and describe encryption and authentication strategies appropriate for securing data transmissions and their differences
  </ol>
  <ol>
    - features of symmetric (Data Encryption Standard — DES, Triple DES, AES — Advanced Encryption Standard, Blowfish and Twofish) and assymetric (RSA) encryption algorithms
   </ol>
  <ol>
    - how data compression, encryption and hashing are used in the storage and transfer of data
  </ol>
</i></li>

<br>

<b>Encryption</b>
Encryption is the process of scrambling data so that only the desired party can understand that information. In more technical terms it is the process of converting plain text to cipher text.
<br>
  ```
  "Hello"  --->  [encryption]  --->  "SNifgNi+uk0="
  plaintext                          ciphertext
  ```
<br>

In modern time there are two main types of Cryptography algorithms used to protect our data over transfer, symmetric and asymmetric key encryption.

<br>
<b>Symmetric Key Encryption</b>
Symmetric key encryption, also known as a symmetric algorithm, is a type of encryption that uses one key to encrypt and decrypt data, a secret key, a public key and a private key. <i>"Keys are random bits that are used by the algorithm to transform the material into its encoded format and back to plain text." - (Encryption 101, 2020)</i>. Some advantages to using symmetric key encryption include its encryption speed and efficiency for large projects with disadvantages cosisting of its need to keep the secret key, this can become tricky when dealing with multiple locations.
<br>

<li><b>Symmetric Key Ciphers<b>
<ol>- DES: A 64 bit block cipher that uses a 56-bit key.</ol>
<ol>- Triple DES (3DES): Uses three separate 56 bit encryption keys. The message is encrypted using one key, encrypted again using a second key and further encrypted by using either a first or third key.</ol>
<ol>- AES: A variant of [the] Rijndael [block cipher], with a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits. - (Advanced Encryption Standard, 2020)</ol>
<ol>- Twofish: A symmetric block cipher which operates on 128 bit blocks and employs 16 rounds with key lengths up to 256 bits.</ol>
<ol>- Blowfish: A symmetric block cipher which operates on 64 bit blocks and employs 16 rounds with key lengths up to 448 bits and uses large key-dependant S-boxes [S-box: "<i>a basic component of symmetric key algorithms which performs substitution"</i> - (S-box, 2020)].</ol>
</li>
  
<br>
<b>Asymmetric Key Encryption</b>
Asymmetric key encryption, also known as an asymmetric algorithm, is a type of encryption that uses two seperate keys, with one being used to encrypt and the other to decrypt data. The key pair being referenced as a public key and private key. The public key is used to send the message and the private key being the one to decrypt said message. Some advantages to using asymmetric key encryption include its encryption extended functionality and its scalability for larger projects with its main disadvantage being the speed of the algorithm.
<br>

<li><b>Asymmetric Key Ciphers<b>
<ol>- RSA: "".</ol>
</li>
 





# References
- Cloudflare. 2020. What Is Encryption? | Types Of Encryption. [online] Available at: <https://www.cloudflare.com/learning/ssl/what-is-encryption/> [Accessed 3 September 2020].

- EDUCAUSE. 2020. Encryption 101. [online] Available at: <https://www.educause.edu/focus-areas-and-initiatives/policy-and-security/cybersecurity-program/resources/information-security-guide/toolkits/encryption-101> [Accessed 3 September 2020].

- Stubbs, R., 2020. An Overview Of Symmetric Encryption And The Key Lifecycle. [online] Cryptomathic.com. Available at: <https://www.cryptomathic.com/news-events/blog/an-overview-of-symmetric-encryption-and-the-key-lifecycle> [Accessed 3 September 2020].

- En.wikipedia.org. 2020. Advanced Encryption Standard. [online] Available at: <https://en.wikipedia.org/wiki/Advanced_Encryption_Standard> [Accessed 3 September 2020].

- En.wikipedia.org. 2020. S-Box. [online] Available at: <https://en.wikipedia.org/wiki/S-box> [Accessed 3 September 2020].

- En.wikipedia.org. 2020. Blowfish (Cipher). [online] Available at: <https://en.wikipedia.org/wiki/Blowfish_(cipher)> [Accessed 3 September 2020].
