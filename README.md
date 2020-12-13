# Advanced-Encryption-Standard-AES-for-data-encryption
**Advanced Encryption Standard(AES) protocol will be used to encrypt data, with usage of PHC winner argon2 to generate key** 
### Advanced Encryption Standard(AES)
[Advanced Encryption Standard](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard), also known by its original name Rijndael (Dutch pronunciation: [ˈrɛindaːl]), is a specification for the encryption of electronic data established by the U.S. National Institute of Standards and Technology (NIST) in 2001.

### **Argon2**
Argon2 is the industry specified hashing algorithm. Winner of [Password Hashing Competition](https://www.password-hashing.net/), argon2 is the latest and most secured password hashing algorithm.

### Overview of the prgram
The user will input a file and password, and the program will return the salt, iv(initialization vector), hashed_password(will not be same or related in anyway to the key) and encrypted data. In no manner will the key, password or the original file will be stored on the system. At each time the user wants to access the data. Key will be generated and the user has to input the password.
