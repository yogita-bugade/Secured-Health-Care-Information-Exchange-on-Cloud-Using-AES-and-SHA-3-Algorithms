<h1>Secured Health Care Information Exchange on Cloud using advanced cryptographic techniques(ECDH, AES and SHA-256)</h1>

<b>The project aims to enhance the security of health record management systems by mitigating risks and minimizing breaches posed by hackers. Leveraging advanced cryptographic techniques, including ECDH (Elliptic Curve Diffie-Hellman) for secure key exchange, AES (Advanced Encryption Standard) for robust symmetric encryption, and SHA-256 for hashing, the implementation is tailored for a C# and ASP.NET environment. Additionally, the project integrates with Microsoft SQL Server 2012/2014, ensuring secure storage and retrieval of sensitive health data through a multi-layered encryption approach. The objective is to implement a comprehensive solution involving multiple encryption steps to provide robust protection to confidential health records stored in the SQL Server database.
</b>
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/ppIlHk9.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

<p align="center">
<img src="https://i.imgur.com/bgW2aDV.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

<p align="center">
<img src="https://i.imgur.com/EU9NPXx.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

<h2>Technologies Used</h2>

- <b>Visual Studio:</b> Visual Studio serves as the integrated development environment (IDE) for the project. It provides a comprehensive set of tools and features for C# and ASP.NET development. Developers use Visual Studio to write, debug, and manage the project's codebase efficiently. The IDE streamlines the development process, offering features such as code editing, debugging, version control integration, and project management.
- <b>Microsoft SQL Server 2012/2014:</b> Microsoft SQL Server is employed as the relational database management system (RDBMS) for storing and managing health records. SQL Server ensures data integrity, security, and reliability. The choice of SQL Server 2012/2014 facilitates efficient and secure storage of sensitive health data. The database is utilized for storing encrypted health records, and it integrates seamlessly with the project to support secure data retrieval and management. The SQL Server platform also enables the implementation of necessary database-related functionalities, such as queries, transactions, and data backup.

<p>These technologies work in tandem to provide a robust development environment, facilitate secure storage of health records, and support the implementation of encryption mechanisms using ECDH, AES, and SHA-256 for enhanced security in the health record management system.


<h2>Description</h2>
To implement ECDH, AES, and SHA-256 in the "Secured Electronic Health Record Management System" project, you can follow these steps:
</p>

<b>1. Generate ECDH Key Pair:</b> <br />
- Create a class to handle ECDH key generation and key exchange. Use the ECDiffieHellmanCng class to generate and exchange keys.

<b>2. Exchange Public Keys:</b> <br />
- Implement a secure mechanism to exchange public keys between the entities involved in the key exchange.

<b>3. Generate Shared Secret:</b> <br />
- Use the received public key and your private key to compute the shared secret. Store the shared secret securely.

<b>4. Derive Encryption Key and IV:</b> <br />
- Implement a key derivation function to derive an encryption key and an initialization vector (IV) from the shared secret.

<b>5. Encrypt and Decrypt with AES:</b> <br />
- Use the derived encryption key and IV to perform symmetric encryption and decryption using AES. Integrate this into the data storage and retrieval processes.

<b>6. Hashing with SHA-256:</b> <br />
- Use SHA-256 for hashing sensitive information, such as patient data or verification purposes.

<h3 align="center">A simple code snippet for the ECDH key exchange and AES encryption/decryption.</h3>
<h6 align="center">Note that this is a basic example, and you should adapt it to fit your specific project structure and requirements</h6>
<p align="center">
<img src="https://i.imgur.com/w36Y5wl.png" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>

<b>Conclusion:</b> <br />
- IT-related services, such as cloud computing, offer efficient solutions with minimal user knowledge about technology. The ability to store, manage, improve, and access data through third-party cloud service providers via the Internet has become an integral part of modern computing. Despite the convenience, ensuring robust data security in cloud services is imperative. This project addresses this concern through the utilization of advanced cryptographic techniques, specifically ECDH, AES, and SHA-256.
- The choice of SHA-256 in the cryptographic process adds an additional layer of security to the project. SHA-256, as a hashing algorithm, provides benefits such as data integrity and non-repudiation. It ensures that the data stored in the cloud remains tamper-resistant, maintaining the trustworthiness of health records.
- ECDH is employed for key exchange, reducing the complexity of operations and enhancing the overall efficiency. The combination of AES with ECC further optimizes and secures the data. The use of ECC, with its low-key size, proves to be advantageous over other cryptographic techniques, contributing to the overall security posture of the system.
- While the project significantly improves security in cloud-based health record management, the need for continuous advancements in cryptographic techniques remains evident. Future research could focus on strengthening the hybrid approach by introducing multiple security layers, thereby enhancing productivity and efficiency. By consistently evolving and fortifying security measures, the project aims to contribute to the ongoing development and expansion of secure cloud computing practices in the realm of health information management.

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
