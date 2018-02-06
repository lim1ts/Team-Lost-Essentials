# Symmetric Encryption

Symmetric-key algorithms are algorithms for cryptography that use the **same cryptographic keys** **for both encryption **of plaintext **and decryption** of ciphertext.

## Block Ciphers and their mode of operation

Block cipher is a deterministic algorithm operating on fixed-length groups of bits, called a block, with an unvarying transformation that is specified by a symmetric key. Each **mode of operation** is an **algorithm** that uses a block cipher to provide an information service such as confidentiality or authenticity. A block cipher by itself is only suitable for the secure cryptographic transformation \(encryption or decryption\) of one fixed-length group of bits called a block.

A mode of operation describes how to repeatedly apply a cipher's single-block operation to securely transform amounts of data larger than a block.

### ECB Mode:

![](/assets/ecb.png)

ECB mode is insecure, because every plaintext will lead to the same ciphertext.

