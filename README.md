# Security cloud computing using cipher text policy and attribute based encryption scheme
## Scenario.
- Data owner want to store data in cloud but dont want their data can seen by everyone. So user want to know who will see their data and give permission to some people to access their data.
## Detail the process of allocating keys in the context of data storage for sales websites using symmetric cryptography according to CP-ABE mechanism
- In the context of storing data for an e-commerce website using the CP-ABE symmetric encryption scheme, the key allocation process is carried out as follows:

 + Access policy determination: Before issuing keys, the access policy needs to be determined, which means deciding which users are allowed to access the data encrypted with this key. The access policy is given in the form of a logical description of user attributes and/or data attributes.

 + Private key creation: After determining the access policy, the system will create a private key for each user based on their attributes and the access policy. This private key creation process will use symmetric encryption algorithms, such as AES, to generate a unique secret key based on the user's attributes.

 + Public key creation: After having private keys for each user, the system will create corresponding public keys to encrypt the data. The public key is generated based on the data attributes and the access policy.

 + Data encryption: After having a public key, the system will use it to encrypt the data before storing it on the system. This encryption process will use symmetric encryption algorithms, such as AES, to encrypt the data using the corresponding public key.

 + Private and public key storage: Finally, the system will store both private and public keys on the system. Private keys will be stored privately for each user, while public keys will be stored publicly to allow other users to encrypt data.

-model:
![model_system](https://github.com/superKool/CP-ABE/blob/main/systemModel.png)

- When data owner want to upload data, they will encrypt it using public key. Subsequently, a ciphertext policy, which decides the conditions of those having the privilege to grant access to the database will be created. So the data will be stored in database include the public key, the ciphertext policy and the ciphertext is encrypted using public key. The dataowner will have privilege to access and decrypt data using private key. Whoever have ciphertext policy match policy of ciphertext will decrypt and see data.
- Key will be generated from user include private key and private key, public key will be used to encrypt data and send to server, private key will be store at users to decrypt data, even administrator of cloud cannot read content of data of data owner because they do not have private or have ciphertext policy to decrypt data.


Subject  | Description  
--- | ---
Protected Assets  | data of user
Related-Party | Cloud service
Security Goal | Prevent attacker to stole data and prevent people have privilege to access sensitive data.


- Member:

Name | ID | mail | presentation |  database  | agorithm | UI
--- | --- | ---  | --- | --- | --- | ---
Nguyễn Đức Vương  | 21522809 | 21522809@gm.uit.edu.vn | v |  | v| |
Nguyễn Thanh Tài  | 21521398  | 21521398@gm.uit.edu.vn |  | v | | v|