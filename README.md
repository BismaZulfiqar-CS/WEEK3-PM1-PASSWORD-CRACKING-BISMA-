**WEEK 3 – CYBERSECURITY: PASSWORD CRACKING PRACTICAL**

**Author:** Bisma  
**Project Module:** Week 3 – Project Module 1  
**Topic:** Password Cracking Using John the Ripper and Networkwalks

---

**1. Project Overview**

This practical focuses on understanding password security and exploring password-recovery techniques using different cybersecurity tools.

During this activity, I worked with John the Ripper (JTR) through Johnny GUI and Networkwalks online tools. I performed PDF hash extraction, configured the password-recovery application, recovered passwords and completed a dictionary attack.

The practical helped me understand how password hashes are used in password recovery and how weak passwords can be vulnerable to dictionary-based attacks.

**2. Tools and Technologies Used**

- John the Ripper (JTR)
- Johnny GUI
- Online PDF Hash Extractor
- Networkwalks Hash Calculator
- Networkwalks Online Password Cracker
- Dictionary Attack
- Notepad
- Windows Operating System

---

**3. Method 1 – Password Recovery Using John the Ripper and Johnny**

**Step 1 – Open Johnny Application**

I downloaded and opened Johnny GUI, which provides a graphical interface for working with John the Ripper. I explored the application and prepared it for the password-recovery activity.

<img width="86" height="81" alt="Johnny " src="https://github.com/user-attachments/assets/b376983f-ad89-4479-922c-0f492108c2e8" />

**Step 2 – Configure Johnny with John the Ripper**

I opened the Johnny settings and located the `john.exe` executable inside the extracted John the Ripper `run` folder. I selected the executable to connect Johnny with the John the Ripper engine.

<img width="873" height="684" alt="Johnny Configuration" src="https://github.com/user-attachments/assets/16c57411-6d3b-4720-8ea3-bcda7eb8540e" />

**Step 3 – Extract PDF Hashes**

I used an online PDF hash extraction website to upload the password-protected PDF files. The website generated the corresponding hash values.

I copied the extracted hashes and saved them in text files using Notepad so that they could be imported into Johnny.

<img width="872" height="685" alt="Johnny Passoword" src="https://github.com/user-attachments/assets/dfa83f82-3d90-4261-bf57-157800dd59d0" />

**Step 4 – Recover Passwords Using Johnny**

I opened the prepared hash file in Johnny and started a new password-recovery attack. The application processed the hash and tested possible password combinations.

The practical was successful, and I recovered three passwords using Johnny.

<img width="1366" height="730" alt="Johnny_Configuration 3" src="https://github.com/user-attachments/assets/e3a59613-3705-4a09-a271-9e4af727cd60" />


---

**4. Method 2 – Password Cracking Using Networkwalks**

**Step 1 – Generate a PDF Hash Using Networkwalks**

I accessed the Networkwalks Hash Calculator and uploaded a password-protected PDF file. The tool extracted a compatible PDF hash, which was used for the next stage of the activity.

<img width="880" height="645" alt="Screenshot 2026-11-19 214129" src="https://github.com/user-attachments/assets/d6f392cf-a827-40b0-856f-6fa88680f9f7" />

**Step 2 – Perform a Dictionary Attack**

I accessed the Networkwalks Online Password Cracker and selected the dictionary attack method. The tool tested possible passwords from its dictionary against the supplied hash.

The attack completed successfully and displayed the recovered password as `password1`.
<img width="1366" height="730" alt="Screenshot 2026-11-19 205942" src="https://github.com/user-attachments/assets/c6d9c000-4b60-470b-ba2c-bc671c2673c3" />

**Step 3 – Capture Completion Flags**

After completing the practical activities, I captured the congratulations and completion-flag screens provided by the Networkwalks platform as evidence of the completed exercises.

<img width="531" height="748" alt="My Locked PDF2 screenshot" src="https://github.com/user-attachments/assets/fe60d7cd-e346-4183-8a8f-e3340ce1525f" />

---

**5. Results and Outcomes**

The practical activities were completed successfully.

- Opened and configured Johnny GUI with John the Ripper.
- Extracted hashes from password-protected PDF files.
- Prepared hash files for password-recovery testing.
- Successfully recovered three passwords using Johnny.
- Generated a PDF hash using Networkwalks Hash Calculator.
- Completed a dictionary attack using Networkwalks.
- Recovered the password `password1`.
- Captured the completion flags from the practical activities.

**6. Learning Outcomes**

Through this practical, I developed a better understanding of password hashing, PDF hash extraction and password-recovery techniques.

I gained hands-on experience using John the Ripper, Johnny GUI and Networkwalks tools. I also learned how dictionary attacks test common password combinations and why weak passwords can create security risks.

**7. Security and Ethical Considerations**

Password-cracking tools should only be used for authorised security testing, educational activities and legitimate password recovery.

Using these techniques without permission can violate privacy and security policies. Organisations and individuals should use strong, unique passwords and additional security measures, such as multi-factor authentication, to reduce the risk of unauthorised access.

**8. Conclusion**

This Week 3 practical provided hands-on experience with password-recovery and dictionary-attack techniques. By using John the Ripper, Johnny GUI and Networkwalks, I learned how password hashes can be tested and how weak passwords may be exposed.

The activities improved my practical cybersecurity knowledge and strengthened my understanding of the importance of password protection.
