# RSA-Cryptosystem


RSA(Rivest-Shamir-Aldeman) is a public key cryptosystem. It is used for secure message transfer.


Steps for RSA :-
1. The user first enters two prime numbers(p & q) and then the message(m) to be securely transferred.
2. RSA encryption - using the public key 'e', the cipher text(c) is found using the formula -> c = m^e mod n, where n is the product of p and q.
3. RSA decryption - a private key exponent(d) is found using the formula -> d * e = 1 mod µ(n), where µ(n) = (p-1)(q-1). Now the message can be retrieved by the formula -> m = c^d mod n.
