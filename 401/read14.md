# BCrypt


## How to store passwords
---

- a simple approach to storing passwords is to create a table in our database that maps a username with a password.
- the security strength and resilience depends on how the password is stored.

### Simple approach

- use cleartext -akin to writing passwords down in a piece of digital paper.

### Secure approach: Hash Functions

- Use a mechanism known as **hashing**.
- Hashing means to chop something up into small peices. To make it look like a confused mess.
-  hash functions behave as one way functions by using mathmatical operations that are extremely difficult and cimbersome to revert such as the modulo operator.
- The ouput if a secure hash function is not easy to predict.
- A hashing function takes arbitrary inputs and transforms them into outputs of a fixed length.

### Limitations of Hash Functions

- Not all cryptographic algorithms are suitable for the modern industry. At the time of this writing, MD5 and SHA-1 have been reported by Google as being vulnerable due to collisions. The SHA-2 family stands as a better option
- Due to rainbow tables, hashing alone is not sufficient to protect passwords for mass exploitation. To mitigate this attack vector, hashing must integrate the use of cryptographic salts.

## Why should you use BCRYPT to has passwords?

---

### Bcrypt
- designed by Niels Provos and David Mazieres in 1999.
- Using a Key Factor, Bcrypt is able to adjust the cost of hashing. 
- with key factor changes, the has output can be influenced.
-slows down the cracking process until its no longer a viable strategy.


## Resouces/Citations
---

- [Hashing Passwords](https://auth0.com/blog/hashing-passwords-one-way-road-to-security/)
- [Bcrypt](https://danboterhoven.medium.com/why-you-should-use-bcrypt-to-hash-passwords-af330100b861)
- [jbcrypt](https://www.mindrot.org/projects/jBCrypt/)
