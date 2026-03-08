Project Overview
The primary goal was to demonstrate how password-cracking tools like John the Ripper (JtR) are used to identify and exploit weak passwords through various attack methodologies.

Environment & Tools
Operating System: Kali Linux.
Virtualization: Oracle VirtualBox.
Primary Tool: John the Ripper (v1.9.0-jumbo-1).
Technologies: Wordlists, Hash Algorithms (MD5, SHA-1, SHA-512).

Key Methodologies Covered
The lab explored three distinct password cracking techniques:
Dictionary Attack: Utilizing precompiled wordlists to find matches for target hashes.
Brute-Force Attack: Systematically trying every character combination (exhaustive but time-consuming).
Hybrid Attack: Combining wordlists with common variations (e.g., adding numbers or symbols to dictionary words).

Lab Execution & Results
Setup: Configured a secure virtual environment and verified JtR installation.
Cracking Process: Performed successful cracking of weak passwords (e.g., 123456) from simulated password files.
Hash Analysis: Analyzed the differences between cracking insecure hashes (like MD5) and more modern, complex hashes (like SHA-512).
Findings: Demonstrated that password strength is heavily dependent on length, complexity, and the security of the underlying hash algorithm.

Ethical & Legal Considerations
This project was conducted strictly for educational purposes within a controlled lab environment.
Ethical hacking requires explicit consent and adherence to legal frameworks like CFAA and GDPR to prevent unauthorized access and protect personal data.
