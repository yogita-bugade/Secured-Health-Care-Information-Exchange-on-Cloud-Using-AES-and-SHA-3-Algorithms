<h1>Secured Health Care Information Exchange on Cloud using advanced cryptographic techniques>

<b>The project aims to enhance the security of health record management systems by mitigating risks and minimizing breaches posed by hackers. Leveraging advanced cryptographic techniques, including ECDH (Elliptic Curve Diffie-Hellman) for secure key exchange, AES (Advanced Encryption Standard) for robust symmetric encryption, and SHA-256 for hashing, the implementation is tailored for a C# and ASP.NET environment. Additionally, the project integrates with Microsoft SQL Server 2012/2014, ensuring secure storage and retrieval of sensitive health data through a multi-layered encryption approach. The objective is to implement a comprehensive solution involving multiple encryption steps to provide robust protection to confidential health records stored in the SQL Server database.
</b>
<br />
<br />

<p align="center">
<img src="https://i.imgur.com/Zhxegxi.png" height="85%" width="85%" alt="RDP event fail logs to iP Geographic information"/>
</p>

<h2>Technologies Used</h2>

- <b>PowerShell:</b> Facilitates automation and task execution for efficient scripting in the File Integrity Monitor (FIM) project.
- <b>Hashing Algorithms (SHA-512):</b> Generates unique fingerprints (hashes) to verify file integrity within the FIM system.
- <b>Automation:</b> Enhances efficiency and reliability by automating file hash collection and monitoring processes in the FIM project.


<h2>Description</h2>
Follow this step-by-step process to build a File Integrity Monitor (FIM) using PowerShell. The FIM will serve as a practical demonstration to deepen your understanding of data integrity in the cybersecurity domain.
</p>

<b>1. Collect Baseline or Begin Monitoring:</b> <br />
- The script will prompt the user to choose between collecting a new baseline or monitoring files with an existing baseline.
- If the user selects to collect a new baseline, the script will gather hashes for all monitored files and store them in a baseline text file.

<b>2. File Hashing:</b> <br />
- File hashing involves creating a digital thumbprint (hash) for each file.
- The baseline.txt file will contain file names along with their corresponding hashes.

<b>3. Monitoring with Baseline:</b> <br />
- If the user chooses to begin monitoring with a saved baseline, the script loads baseline hash files into a dictionary.
- Continuously, the script checks each file's hash against the baseline. Any changes trigger an alert.

<b>4. Alert Notification:</b> <br />
- If a file's hash differs from the baseline, the script notifies the user or administrator about the file change.

<b>5. Conclusion::</b> <br />
- Now that we have an overview, follow the step-by-step process to set up the File Integrity Monitor and deepen your understanding of integrity in the realm of cybersecurity. Happy coding!

<h2 align="center">Ensuring File Integrity: Alerting Against Changes and Deletions</h2>
<p align="center">
<img src="https://i.imgur.com/bEjWmmY.jpg" height="85%" width="85%" alt="Image Analysis Dataflow"/>
</p>


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
