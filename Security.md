### What Is SSH

It is a secure alternative to the non-protected login protocols (such as telnet) and insecure file transfer methods (such as FTP).

### How Dose The SSH Protocol Work

The protocol works in the client-server model, which means that the connection is established by the SSH client connecting to the SSH server. 

An *SSH key* is an access credential in the SSH protocol.

Its function is similar to that of user names and passwords

Important concepts in public key cryptosystems (密码系统) are:

- Key pairs that consists of a public key and a private key.

- Public key cryptography algorithms such as: RSA, DSA, and ECDSA.

In a public-key cryptosystem, a public key is a key 

In SSH, public key cryptography is used for authenticating computers and users.

SSH keys grant access similar to user names and passwords, 

### public-key Cryptography

Symmetric cryptography (对称加密): you have one key, and you use it to encrypt ("lock") and decrypt ("unlock") your data.

Asymmetric or "public-key" cryptography (非对称加密)

"private key"是“我”独有的，"public key"是可以任意分发出去的。

"Keys" are just numbers - big, long numbers with many digits.

If anyone, even you, encrypt ("lock") something with your public key, only you can decrypt it ("unlock") with your secret, private key.

任何人用"public key" 加密，只有“我”能用"private key"解密。

If you encrypt (“lock”) something with your private key, anyone can decrypt it (“unlock”), but this serves as a proof you encrypted it: it’s “digitally signed” by you.

“我”用"private key"加密，任何人都可以用"public key"解密。

### Connecting to Github with SSH

Using the SSH protocol, you can connect and authenticate to remote servers and services. 

With SSH keys, you can connect to GitHub without supplying your username or password at each visit.