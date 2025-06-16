HOW IT WORKS:

Generates 2 prime numbers and calculates n and phi of n from the 2 prime numbers.
After that it creates the public key (now e) and from that it generates the private key(now d).
We give a message, i have given "Testing Encryption" and turning it into an integer.
Then taking the "message encoded" to the power of e(public key) mod n.

Decryption works the same but its inversed,taking the "ciphertext" to the power of d(Private key) mod n.

The public key is used for encrypting the message.
The private key is used for the decryption of the message.