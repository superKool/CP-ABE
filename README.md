# Security cloud computing using cipher text policy and attribute based encryption scheme
## scenario.
- User want to store data in cloud but dont want their data can seen by everyone. So user want to know who will see their data and give permission to some people to access their data.

- When data owner want to upload data, they will encrypt it using public key. Subsequently, a ciphertext policy, which decides the conditions of those having the privilege to grant access to the database will be created. So the data will be stored in database include the public key, the ciphertext policy and the ciphertext is encrypted using public key. The dataowner will have privilege to access and decrypt data using private key. Whoever have ciphertext policy match policy of ciphertext will decrypt and see data.
- Key will be generated from user include private key and private key, public key will be used to encrypt data and send to server, private key will be store at users to decrypt data, even administrator of cloud cannot read content of data of data owner because they do not have private or have ciphertext policy to decrypt data.
- model:
![model_system](https://github.com/superKool/CP-ABE/blob/main/systemModel.png)


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