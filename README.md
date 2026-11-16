# NETWORKWALKS-WK3-PROJECT
FILES PASSWORD CRACKING CTF PRACTICAL LAB DOCUMENTATION 

This document serves as my personal practical documentation for the file password cracking and Capture The Flag (CTF) cybersecurity labs I completed across two structured modules on Networkwalks. 
Through hands-on practical exercises, I utilized both CLI and GUI password-cracking tools in Module 1 to crack three encrypted PDF files, and applied the Networkwalks cracking tool in Module 2 to analyze target PDFs, recover passwords (1qaz2wsx and password1), and capture all required verification flags.

1. Practical Lab Overview

Password cracking is a foundational discipline in penetration testing and security auditing, illustrating why strong password complexity and resilient cryptographic hashing are essential. 
Across these two practical modules, I personally extracted cryptographic hashes from encrypted PDF documents, executed wordlist-based dictionary attacks across command-line, graphical, and web-based environments, documented access controls and outcomes per target file, and captured three authenticated Networkwalks flags.
What I Accomplished Across Both Modules
Module 1 — CLI & GUI Offline PDF Cracking: I used John the Ripper (CLI) and Johnny (GUI) to extract hashes and successfully crack three encrypted PDF files.
Module 2 — Networkwalks Tool Practical Evaluation: I used the Networkwalks password-cracking tool against three target PDF files—observing access denied on PDF 1 while successfully cracking PDF 2 and PDF 3.
Credential & Hash Recovery: I extracted $pdf$ hashes and recovered the cleartext passwords (1qaz2wsx and password1) for PDF 2 and PDF 3 using the Networkwalks tool.
CTF Flag Extraction & Verification: I unlocked the target files and verified my practical work by capturing three distinct Networkwalks flags.
  Tools & Methodologies Used by Module
Module
Tool(s) Utilized
Interface
Scope & Outcome
Module 1 Project
John the Ripper (jtr)
CLI (Command-Line Interface)
Hash extraction & dictionary attacks; 3 encrypted PDF files successfully cracked.
Module 1 Project
Johnny
GUI (Graphical User Interface)
Visual session management & wordlist cracking; 3 encrypted PDF files successfully cracked.
Module 2 Project
Networkwalks Cracking Tool
Web / Platform Lab Tool
Tested against 3 PDFs: Access denied on PDF 1; PDF 2 & PDF 3 successfully cracked.

   My Practical Walkthrough & Technical Findings
3.1 Module 1 Project: John the Ripper (CLI) & Johnny (GUI)
In the Module 1 practical project, I focused on local password auditing using both command-line and graphical workflows. I used John the Ripper (CLI) to extract and attack the PDF password hashes via terminal commands, and Johnny (GUI) to manage cracking sessions visually, monitor candidate attempts, and inspect cracked credentials. Through this combined CLI and GUI workflow, all 3 encrypted PDF files in Module 1 were successfully cracked.
  Module 2 Project: Networkwalks Tool & Target File Results
In the Module 2 practical project, I used the dedicated Networkwalks password-cracking tool to evaluate three encrypted PDF targets (PDF 1, PDF 2, and PDF 3). While access was denied on PDF 1, the wordlist attack against the extracted $pdf$ hashes succeeded on both PDF 2 and PDF 3, recovering the passwords 1qaz2wsx and password1:
Target File
Tool Used
Status / Access Result
Recovered Password / Notes
PDF 1
Networkwalks Tool
Access Denied
Target remained locked / protected against wordlist match
PDF 2
Networkwalks Tool
Successfully Cracked
1qaz2wsx
PDF 3
Networkwalks Tool
Successfully Cracked
password1
Extracted PDF Hash Sample
Networkwalks Tool
Hash Verified ($pdf$)
$pdf$4*4*128*-1060*1*16*55d1a5c14175da449753199e44971d32*32*777fd021a7f3c5ae598c0c6495c7f76e...

  CTF Flags I Captured
Upon completing the Module 1 (John the Ripper CLI / Johnny GUI) and Module 2 (Networkwalks tool) practical exercises and unlocking the cracked PDF files, I retrieved and verified the following three flags:
Practical Challenge
Flag I Captured
Challenge 1: Initial File Cracking Flag (Flag1)
nw{cybersecurity_flag_captured_2608}
Challenge 2: Persistence / John the Ripper Flag
nw{networkwalks_persistence_jtr_270521}
Challenge 3: Final Lab Completion Flag
nw{networkwalks_flag_260821_1}

   Visual Proof of My Practical Work
The screenshots below provide visual verification of the password recovery process on the Networkwalks tool and the three flags I captured across my hands-on practical labs.
<img width="720" height="1600" alt="1000178498" src="https://github.com/user-attachments/assets/ded20b7f-f81f-4901-a381-9a480b2f5069" />
<img width="446" height="548" alt="1000178660" src="https://github.com/user-attachments/assets/b9baad5b-9781-4490-bd1a-4f65027f4c9d" />
<img width="418" height="585" alt="1000178662" src="https://github.com/user-attachments/assets/178973f8-9720-48ed-98dc-32f00cd7f08c" />
<img width="720" height="1600" alt="1000178501" src="https://github.com/user-attachments/assets/b51ea474-0f60-4832-952b-3935d97ebb19" />
<img width="720" height="1600" alt="1000178502" src="https://github.com/user-attachments/assets/7387b83b-0f5a-414f-8455-dff80aef9097" />
<img width="282" height="389" alt="1000178658" src="https://github.com/user-attachments/assets/645360b6-6309-4de4-8f1c-ce28f86f5fb5" />

Screenshot_20261116_105326_Chrome.jpg -->
   Educational Disclaimer
I compiled this documentation strictly for educational purposes and to showcase my hands-on cybersecurity practical skills developed through authorized coursework on Networkwalks. Password cracking and security auditing techniques must only be performed on systems and files with explicit authorization.

