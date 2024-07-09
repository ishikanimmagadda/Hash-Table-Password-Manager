# Hash-Table-Password-Manager
Implement a hash table and use it to create a basic password manager

Description:

Should be able to store usernames and hashed passwords
Have a command-line UI that lets users add, retrieve and delete passwords

Specifications:

Implement a hash function to map usernames to bucket indices, choose a hash function strategy to minimize the odds of collisions, and if collisions do happen, ensure that lookup is still efficient
Implement a secure one way hashing function for passwords. When the user enters a new password - ensure that only this hash is stored
Create a ‘login’ mechanism, where the user can enter a username and password (compare the hash with the existing hash) and if it matches output a logged in message
