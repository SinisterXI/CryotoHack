# RSA
RSA, first described in 1977, is the most famous public-key cryptosystem. It has two main use-cases:

Public key encryption enables a user, Alice, to distribute a public key and others can use that public key to encrypt messages to her. Alice can then use her private key to decrypt the messages.
Digital signatures enable Alice to use her private key to "sign" a message. Anyone can use Alice's public key to verify that the signature was created with her corresponding private key, and that the message hasn't been tampered with.
Although RSA's security is based on the difficulty of factoring large composite numbers, in recent years the cryptosystem has received criticism for how easy it is to implement incorrectly. Major flaws have been found in common deployments, the most notorious of these being the ROCA vulnerability which led to Estonia suspending 760,000 national ID cards.

These challenges introduce you to the many footguns of RSA, and soon see you performing attacks which have caused millions of dollars of damage in the real world.
