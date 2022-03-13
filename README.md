# Encryption

> An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about Encryption.
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.


## About Encryption
**One of the best ways to protect the data transferred over the Internet is encryption.**

- Encryption is a way of converting plaintext into ciphertext (an encoded text that is not understandable by the third party). 

![encryption-introdcution](https://github.com/paulveillard/cybersecurity-encryption/blob/main/img/1.png)

> Encryption requires the use of an encryption key and an encryption algorithm. The key is used to encrypt/decrypt the plaintext into ciphertext. How that key is used to encrypt the plaintext is defined by the encryption algorithm. Both the receiver and the sender must have the encryption key.



## Encryption Algorithms

![encryption](https://github.com/paulveillard/cybersecurity-encryption/blob/main/img/typesof-encryption.png)

### Symmetric key 
> Symmetric key algorithms use the same key to both encrypt and decrypt data. They are generally faster than asymmetric key algorithms and are often used to encrypt large blocks of data. Algorithms you'll hear mentioned include DES, TripleDES, RC5, and AES (the standard for the U.S. government). Either TripleDES or AES is required when encrypting stored credit card numbers.


### Asymmetric key
> Asymmetric key algorithms require two encryption keys: one to encrypt the data and the other to decrypt the data. It doesn't matter which one does which function; it's just that you can't use only one key to both encrypt and decrypt data. These algorithms are typically used for authentication; for example, they're used during an SSL or VPN "handshake" to verify that the client knows the server to which it's trying to connect. Once the verification is complete, a "session key" is exchanged by the client and server, and symmetric key encryption is used for the actual data transmission. Asymmetric key algorithm types include RSA and Elliptic Curve.

### Hash 
> Hash algorithms produce a result that is not decryptable. They are typically used for comparing two values to ensure they're the same. For example, digital signature verification uses a hash function to ensure that the signed document has not been altered. Because a hashed value cannot return the original value, this method provides the most secure form of storing data and is the most appropriate method when the original (cleartext) form is not required. MD5 and SHA-1 are two examples of hash algorithms.


## Table of Contents

- [Introduction](#introduction)
- [Types of Encryption](#types-of-introduction)
