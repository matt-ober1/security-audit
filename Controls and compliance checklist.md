# Controls and compliance checklist

**Controls assessment checklist**

| Yes | No  | Control                                                             |
| --- | --- | :------------------------------------------------------------------ |
|     | X   | Least Privilege                                                     |
|     | X   | Disaster recovery plans                                             |
|     | X   | Password policies                                                   |
|     | X   | Separation of duties                                                |
| X   |     | Firewall                                                            |
|     | X   | Intrusion detection system (IDS)                                    |
|     | X   | Backups                                                             |
| X   |     | Antivirus software                                                  |
|     | X   | Manual monitoring, maintenance, and intervention for legacy systems |
|     | X   | Encryption                                                          |
|     | X   | Password management system                                          |
| X   |     | Locks (offices, storefront, warehouse)                              |
| X   |     | Closed-circuit television (CCTV) surveillance                       |
| X   |     | Fire detection/prevention (fire alarm, sprinkler system, etc.)      |

---


**Compliance checklist**

Payment Card Industry Data Security Standard (PCI DSS)

| Yes | No  | Best practice                                                                                                |
| --- | --- | :----------------------------------------------------------------------------------------------------------- |
|     | X   | Only authorized users have access to customers’ credit card information.                                     |
|     | X   | Credit card information is stored, accepted, processed, and transmitted internally, in a secure environment. |
|     | X   | Implement data encryption procedures to better secure credit card transaction touchpoints and data.          |
|     | X   | Adopt secure password management policies.                                                                   |

General Data Protection Regulation (GDPR)

| Yes | No  | Best practice                                                                                                     |
| --- | --- | :---------------------------------------------------------------------------------------------------------------- |
|     | X   | E.U. customers’ data is kept private/secured.                                                                     |
| X   |     | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach. |
|     | X   | Ensure data is properly classified and inventoried.                                                               |
| X   |     | Enforce privacy policies, procedures, and processes to properly document and maintain data.                       |

System and Organizations Controls (SOC type 1, SOC type 2\) 

| Yes | No  | Best practice                                                                              |
| --- | --- | :----------------------------------------------------------------------------------------- |
|     | X   | User access policies are established.                                                      |
|     | X   | Sensitive data (PII/SPII) is confidential/private.                                         |
| X   |     | Data integrity ensures the data is consistent, complete, accurate, and has been validated. |
|     | X   | Data is available to individuals authorized to access it.                                  |

---


**Recommendations for Enhanced Security Implementations**

Firstly, it is recommended to limit employee access to sensitive personally identifiable information (SPII), such as credit card details, to only those employees whose roles necessitate such access. This measure enhances security by reducing the risk that a compromised employee account could lead to unauthorized access to sensitive data.

Additionally, encrypting customer data is imperative, as it serves as a critical barrier against potential threat actors. I recommend using either AES-256 or RSA encryption. AES-256 is a symmetric encryption algorithm, utilizing the same key for both encryption and decryption, and is known for its speed and efficiency with a slight trade-off in security. On the other hand, RSA is an asymmetric encryption algorithm that employs separate keys for encryption and decryption, offering higher security albeit at a slower speed. Both encryption methods are effective, and the choice between them can be based on organizational preference.

Another essential improvement is the implementation of a secure password policy. Best practices dictate that passwords should be a minimum of 12 characters and include a combination of uppercase letters, lowercase letters, special characters, and numbers. Enforcing this policy is crucial, ensuring that accounts cannot be created unless they meet these standards. Adopting these controls will help your company comply with the Payment Card Industry Data Security Standard (PCI DSS) and System and Organization Controls (SOC) best practices.

Furthermore, it is advisable to implement an Intrusion Detection System (IDS), such as SNORT. An IDS monitors network activity and alerts administrators to any suspicious behavior, allowing for prompt investigation and response to potential incidents.

Equally important is the establishment of a comprehensive disaster recovery plan, coupled with regular data backups. In the event of a ransomware attack, having data backups is vital to maintaining business operations and mitigating the financial impact.

Lastly, while it is commendable that the IT department monitors and maintains legacy systems, it is crucial to establish a regular maintenance schedule. Legacy systems are inherently more susceptible to vulnerabilities and exploits compared to long-term support systems.
