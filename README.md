# Implementation-of-RSA-Algorithm

Utility Functions

❖ compute_gcd(x,y):Computesthegreatestcommondivisoroftwonumbersusing
the Euclidean algorithm.

RSA Encryption and Decryption Functions

❖ rsa_encryption(public_key,plain_text):EncryptsamessageusingtheRSA algorithm.

❖ rsa_decryption(private_key,cipher_text):DecryptsaciphertextusingtheRSA algorithm.

Prime Number Generation and Primality Testing Functions

❖ prime_gen(bits):Generatesaprimenumberwithaspecifiedbitlengthusing probabilistic primality testing.


❖ prime_check(num,iterations):PerformstheMiller-Rabintesttocheckforprimality of a number.
Key Pair Generation Function

❖ generate_rsa_keys(bit_size):GeneratesapairofRSApublicandprivatekeys
based on a given bit size, ensuring their validity and compatibility.

Main Program

❖ Requests the bit length for prime numbers from the user. ❖ Generates RSA public and private key pairs.

❖ Requests an integer message from the user to encrypt. ❖ Encrypts the message using the public key.

❖ Decrypts the encrypted message using the private key.

❖ Outputs the generated keys, encrypted message, and decrypted message.
