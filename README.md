# Security on mobile cloud computing using cipher text policy and attribute based encryption scheme
## scenario.
- User want to store data in cloud but dont want their data can seen by everyone. So user want to know who will see their data and give permission to some people to access their data.

- When data owner want to upload data, they will encrypt it using public key. Subsequently, a policy, which decides the conditions of those having the privilege to grant access to the database will be created. So the data will be stored in database include the public key, the policy and the ciphertext is encrypted using public key. The dataowner will have privilege to access and decrypt data using private key. Whoever have policy match policy of ciphertext will decrypt and see data.
- model:
![model_system](https://github.com/superKool/CP-ABE/blob/main/mobile_cloud.pdf)


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