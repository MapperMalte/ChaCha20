# ChaCha20
ChaCha20 Flutter

ChaCha20 generates a cryptographically random cipherstream from a key, a 32-bit-block-counter and a 96-bit-nonce that can be XORed with a plaintext to cipher or decipher it.

The nonce does not have to be unpredictable, but it must never be used twice with the same key.

ChaCha20 is often used in conjuntion with an authenticator like Poly-1305, see https://www.rfc-editor.org/rfc/rfc7539#section-2.5
