# Akira-Ransomware-Analysis-Reverse-Engineering
In this project, I conducted a detailed malware analysis of the Akira ransomware, focusing on its behavior, functionality, and impact. As a beginner in cybersecurity and malware analysis, my goal was to gain hands-on experience in reverse engineering and dynamic analysis while documenting my findings in a structured report.

Objectives
Static Analysis: Decomposing the malware binary to extract useful artifacts without executing it.

Dynamic Analysis: Running the malware in a controlled environment to observe its real-time behavior.

Reverse Engineering: Using Ghidra to analyze the ransomware’s code structure, functions, and encryption mechanisms.

Behavioral Analysis: Using Any.Run Interactive Sandbox to monitor the malware's execution and collect Indicators of Compromise (IoCs).

Threat Intelligence & Documentation: Extracting key insights to help security researchers and analysts understand the malware’s impact.

Approach & Methodology
Environment Setup

Created a safe and isolated analysis environment using a virtual machine to prevent unintended execution on the host system.

Used Ghidra for reverse engineering and Any.Run for behavioral analysis.

Static Analysis

Extracted strings and analyzed the PE headers, import tables, and functions.

Identified suspicious API calls that indicate ransomware behavior, such as encryption routines and file manipulation.

Dynamic Analysis

Executed the malware in Any.Run to observe its file encryption behavior, registry modifications, and network activity.

Captured screenshots of the ransomware’s execution and ransom note.

Reverse Engineering

Decompiled the binary in Ghidra to analyze key functions and understand how the encryption works.

Identified attacker messages within the binary.

Key Findings
The malware encrypts files and appends a custom extension.

A ransom note is displayed to the victim, demanding payment for decryption.

Uses anti-analysis techniques to evade detection.

Conclusion
This project provided hands-on experience in malware analysis and reverse engineering. By documenting my findings, I aim to contribute to the cybersecurity community and improve my skills in threat intelligence and incident response.
