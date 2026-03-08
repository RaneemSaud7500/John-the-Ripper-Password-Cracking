# Password Security Auditing with John the Ripper

##  Project Overview
The objective was to demonstrate how John the Ripper identifies weak passwords using wordlists and hash algorithms.


##  Environment & Tools

* **Operating System**: Kali Linux.

* **Virtualization**: Oracle VirtualBox.

* **Primary Tool**: John the Ripper v1.9.0-jumbo-1.

* **Hash Algorithms**: Support for various types including MD5 and SHA-1.


##  Attack Methodologies

The lab explored three primary password cracking methods:

* **Dictionary Attacks**: Rely on a precompiled wordlist of likely passwords, comparing each to the target hash.

* **Brute-Force Attacks**: Systematically try every possible character combination until the correct password is found.

* **Hybrid Attacks**: Combine dictionary speed with brute-force thoroughness by adding common variations to wordlist entries.


##  Lab Execution & Findings

* **Vulnerability Assessment**: Simple passwords like "password123" are highly probable to be found quickly using wordlists.

* **Cracking Results**: Successfully cracked weak passwords (e.g., "123456" and "larry") using different hashing methods.

* **Algorithm Impact**: Older algorithms like MD5 are faster to crack because they often lack complexity and modern "salt" mechanisms.


##  Ethical & Legal Considerations

* **Consent**: Explicit permission must be secured before attempting to crack any password.

* **Legal Compliance**: Unauthorized password cracking is illegal under laws like the CFAA and GDPR.

* **Responsibility**: Ethical hackers must always respect privacy and operate within strictly defined boundaries.


##  Security Recommendations

* **Password Policy**: Organizations must enforce policies requiring minimum length and complexity for all passwords.

* **Layered Defense**: Multi-Factor Authentication (MFA) should be mandated as an essential second layer of protection.
