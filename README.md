# SSS-System
With SSS You need no TSL or SSL certificate, SSS is the next generation security for your visitors, all at no cost. An SSL certificate brings you alone no added value of security that you do not need with SSS also. You can also use SSS together with TLS and are in a break in the TLS / SSL protected system.


Background SSS

1. Encrypt the communication with a high standard cryptographic
2. To defend their users against network -Sniffing
3. To protect against replay attacks
4. Ban System


How does SSS?

SSS uses a symmetric encryption with AES. A few queries run on the Asymmetric encryption (RSA). RSA is only for the conclusion of (exchange) Security Keys on AES base used. SSS also brings a Ban system to inquire goal and inquire proxy automatically to block on request:

- The client requests a public key from the server
- Server returns the current public key to the client
- Client generates text, which is compared encrypted with the public key and sends it back to the server
- Server accepts the key from "Step 3" and decrypts it using the private key
- The decrypted text from "Step 4" is the key used for symmetric communication with AES.

This key is stored in the current session of the server and the browser's local storage.

For keys that are stored on the server, the client uses to start symmetrical communication with AES. All data sent from the client / server will be encrypted with AES.
