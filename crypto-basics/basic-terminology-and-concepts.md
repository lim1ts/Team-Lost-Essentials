# Overview

Cryptography or cryptology is the practice and study of mathematical techniques for secure communication in the presence of third parties called adversaries. It is not the only means of providing information security, but just one set of techniques.



> Using the power of Mathemagic, you can multiply power, subtract hope, and cube-root the dreams of man himself. This is a strange, abstract school of magic that has a way of driving its users insane.
>
> * Dungeons of Dredmor, Mathemagic



The CIA triad of confidentiality, integrity, and availability is at the heart of information security, and is listed as follows:



| Keyword | Definition |
| :--- | :--- |
| Confidentiality | Information is not made available to unauthorized individuals, entities or processes. |
| Integrity | To maintain integrity means maintaining and assuring the accuracy and completeness of data. The data cannot be modified in an unauthorized or undetected manner. |
| Availability | Information or data must be available as required. |
| Non-repudiation | One party of a transaction cannot deny having received a transaction nor can the other party deny having sent a transaction |

### Substitution Ciphers

The basic substitution ciphers are block ciphers that substitute symbols by other symbols.

> A block cipher is an encryption scheme that breaks a plaintext into a block of fixed length T, and encrypts each block at a time.

There are different types of substitution ciphers.  
Homophonic substitution ciphers replaces each symbol in a plaintext message block with a randomly chosen string.  
Polyaphabetic substitution ciphers replaces each symbol with multiple substitution alphabets.

Substitution ciphers by themselves are not enough to achieve security - it is too easily cracked. Many other books will delve into why this is so, but not here. Substitution ciphers are obsolete in modern times.



### One-Time-Pad\(OTP\)

To illustrate OTP, observe the following:

```
Let key length = m
Where the key is a random m bit string. [ K = {0,1}^m ]
Encryption algorithm is defined by: Enc(Message) = K ⊕ Message
The encryption creates a Ciphertext, a m-bit string {0,1}^m

Decryption algorithm is defined by Dec(Ciphertext) = K ⊕ Ciphertext

Assume a string of votes, Y and N. Where string v = {y,n} ^m.
string v = v1 ...vn with the OTP scheme with key-length n. 

Thus the ciphertext is C = K ⊕ v.

Say the adversary has the ciphertext C = C1 ...Cn, where Ci is the i-th bit of C. 
Say the adversary knows that v1 = 1. 
It can deduce that K1, the first bit of K, is 1 ⊕ C1. 
But having K1 tells it nothing about the other bits of K, and hence v2,...,vn remain hidden
```

#### What is perfect secrecy? 

Perfect secrecy is the notion that, given an encrypted message \(or ciphertext\) from a perfectly secure encryption system \(or cipher\), absolutely nothing will be revealed about the unencrypted message \(or plaintext\) by the ciphertext.

OTP is one such example.

A perfectly secret cipher has a couple of other equivalent properties:

* Even if given a choice of two plaintexts, one the real one, for a ciphertext, you cannot distinguish which plaintext is the real one \(perfect message indistinguishability\)
* There is a key that encrypts every possible plaintext to every possible ciphertext \(perfect key ambiguity\) \(\* this is true only if the keys used are the same size as the messages\)



