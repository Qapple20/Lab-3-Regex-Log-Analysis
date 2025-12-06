# Lab 3 Regex Log Analysis

Objective

This project focused on developing the ability to extract meaningful security insights from raw log data using regular expressions. The goal was to detect authentication anomalies, idenitfy malicious patterns, and analyze system activity by applying advanced text-processing techniques across large datasets. This lab strengthened core SOC analyst skills such as parsing logs, identifying patterns of compromise, and building detection logic

Skills Learned

- Constructing and applying regex patterns for security-focused data extraction
- Identifying failed login attempts, suspicious IP behavior, and repeated attack patterns
- Analyzing large authentication and system logs to detect anomalies
- Understanding how log formats reflect system behavior and attacker techniques
- Translating unstructured log data into structured, actionable intelligence

Tools Used

- grep/egrep/regex for pattern detection and log parsing
- Linux CLI utiliites for filtering, searching, and transforming text datasets
- System log files such as auth logs and HTTP access for log analysis
- Standard Linux environment for hands-on threat hunting workflows


Steps

1. Used grep with regular expressions to extract failed SSH login attempts from a large authentication log, demonstrating targeted log filtering
   <img width="468" height="271" alt="image" src="https://github.com/user-attachments/assets/eb4022db-5d35-4c50-8851-fdb33baa94e3" />

2. Applied regex to isolate IP addresses associated with repeated login failures, supporting brute-force detection analysis
   <img width="468" height="228" alt="image" src="https://github.com/user-attachments/assets/debb4ca6-fe94-44ef-a987-bbed66da3682" />

3. Filtered successful login events using pattern matching to compare normal user behavior against suspicious access patterns
   <img width="468" height="323" alt="image" src="https://github.com/user-attachments/assets/69b43470-2928-4d56-9a6c-1f944629692f" />

4. Used advanced grep flags to search authentication logs recursively and highlight specific security-relevant keywords
   <img width="468" height="195" alt="image" src="https://github.com/user-attachments/assets/b7351447-6ee0-4f02-9741-f0628ff713e0" />

5. Peformed regex-based extraction of timestamps and usernames from log entries to build a structured view of authenticated activity
    <img width="468" height="293" alt="image" src="https://github.com/user-attachments/assets/db8d6a48-512f-4e66-9a33-d4d66cea2c7a" />

6. Analyzed SSH log entries to identify trends in a failed authentication attempts and potential brute-force indicators
    <img width="468" height="306" alt="image" src="https://github.com/user-attachments/assets/a0cde331-3d01-4e1b-b7ad-02cb51071d7c" />

7. Used multi-condition regex filters to isolate events tied to suspicious IP addresses across entire log sets
    <img width="468" height="202" alt="image" src="https://github.com/user-attachments/assets/4ef13006-d01c-4685-a1c8-265b22473d8c" />
