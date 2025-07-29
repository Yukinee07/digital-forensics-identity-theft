**Identity Theft Simulation**  
Course: CSCI 2304 Intelligent Systems  
Team: Nasi Kandar  

## Project Overview

This project simulates a comprehensive digital forensics investigation of an identity theft case, focusing on uncovering and concealing digital evidence through advanced steganography, cryptography, and obfuscation techniques. The investigation involves white-hat forensic analysis to extract hidden messages and black-hat tactics to embed concealed data, demonstrating practical knowledge and application of cybersecurity principles.
# Digital Forensics & Steganography Investigation  
---

## Recognition & Context  
- Conducted as part of the CSCI 2304 Intelligent Systems course, semester I 2024/2025  
- Scenario: Investigating a suspected cybercriminal's laptop containing steganography tools and encrypted files  
- Emphasis on uncovering hidden data, secret keys, and obfuscated messages with forensic software  

---

## Features & Methodology

### White Hat Investigation
- Analyzed suspicious files using forensic tools including S-Tools, QuickStego, MP3Steno, and Morse code decoders.  
- Extracted multiple hidden messages across various file types (images, audio, documents) revealing passwords and critical evidence.  
- Applied decryption methods such as ROT ciphers, Base64 decoding, password cracking, and metadata analysis to systematically uncover evidence.

### Black Hat Implementation
- Created multiple layers of concealed evidence employing Morse code, steganography, ROT13 obfuscation, encrypted RAR archives, and HTML inspect-element hiding.  
- Embedded secret messages within images, audio files, documents, and video descriptions using a variety of concealment techniques.  
- Developed step-by-step documentation and recovery procedures to ensure reproducibility and thorough testing of evidence concealment.

---

## Tools Used
- **S-Tools**: Steganography for hiding/retrieving messages in image files  
- **QuickStego**: Text hiding and extraction in images  
- **MP3Steno**: Audio steganography analysis  
- **Morse Code Translator (online)**: Decoding Morse code messages  
- **DCode Tools**: ROT cipher decoding, Base64 converters, and other cryptographic utilities  
- **SpamMimic**: Simulation of spam message encryption  
- **WinRAR/7zip**: Password-protected archives  

---

## Project Structure

- `final_report.pdf` — Complete project report detailing investigation process, findings, and recommendations.  
- `digital_evidence/` — Folder containing analyzed and created evidence files such as images, audio, documents with steganography and encryption.  
- `tools_reference.md` — List of tools, websites, and software used during the investigation.  
- `workflow_diagrams/` — Visual flowcharts and step-by-step guides for investigation and evidence concealment.  

---

## Summary of Key Findings

- Successfully uncovered 6 layers of hidden evidence using steganography and cryptography techniques.  
- Implemented 8 advanced concealment scenarios incorporating password protection, metadata obfuscation, and layered encryption.  
- Demonstrated proficiency in both white-hat forensic recovery and black-hat evidence hiding tactics.  
- Achieved a comprehensive understanding of digital forensic methodologies applicable to real-world investigation scenarios.

---

## Challenges & Recommendations

- Managing multiple encryption layers required systematic password tracking and workflow standardization.  
- Diverse file types necessitated a standardized toolkit for effective analysis and concealment.  
- Detailed documentation and version control enhanced reproducibility and team coordination.

Recommended improvements include advanced multi-layer encryption, improved tool automation, and comprehensive training scenarios to adapt to emerging steganographic techniques.

---

## How to Use This Repository

1. **Review the final report** (`final_report.pdf`) for full context and detailed explanation of findings and techniques.  
2. **Explore digital evidence files** to practice extracting hidden messages using the tools referenced.  
3. **Follow workflow diagrams** for guided step-by-step investigation and concealment processes.  
4. Use this project as a practical reference for learning digital forensics and steganography in academic or professional settings.

---

## Contact & Collaboration

For questions, feedback, or collaborations, please open an issue or contact the project contributor(s) via GitHub.

---

> This project exemplifies hands-on experience with key cybersecurity concepts, bridging theoretical knowledge with real-world application in digital investigation and data concealment.

