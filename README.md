# Google Summer of Code Contributor Application  

## About Me  
My name is Abdelrahman Khalifa. I am in my final year of Computer Engineering, experienced in C/C++, Linux, MCUs, Python, and Qt. I am interested in embedded systems, RTOS system design, and open-source software. My preferred method of communication is via email at abdelrahman.kahlifa.gad@gmail.com. You can also reach me via Telegram (@Abd0o02) or Discord (.abd002).


## My Coding Skills 
- **Platform and Tools:** Using Ubuntu 22.04 as a platform, GCC, VS Code, and Qt Creator as tools.  
- **Programming Experience:**  
  - **C/C++:** Proficient in systems programming and Qt (used in GUI projects).
  - **Competitive Programming:** I have a lot of experience in problem-solving and have demonstrated these skills in Codeforces and LeetCode contests.    
  - **Embedded C, Linux Administration, RTOS, Linux Kernel Development, and Bash Scripting for Test Automation.**  

- **Relevant Knowledge:**  
  Familiar with D-Bus, CUPS, and Qt and have been exploring how CPDB abstracts backend/frontend communication.  


## Me and OpenPrinting

- **Past Contributions to OpenPrinting:**  
  I haven't contributed to any OpenPrinting project before.

- **Other Open Source Experience:**  
  I have contributed to another group related to Linux (Zephyr RTOS), where I implemented support for IPv4 Multicast Loop and refactored some code.  

- **Why This Idea:**  
  It allows me to practice C in a highly abstracted environment (Frontend-Backend) and work with D-Bus as the communication interface.  
  I enjoy building bridges between backend logic and user interfaces.  


## **Title:** Error Response Pop-Up Support for Common Print Dialog Backends (CPDB)  

- ### **What I Want to Achieve:**  
  I want to improve the user experience by adding a feature that displays appropriate error messages and possible resolution actions. If there is time, I would like to help with improving signal handling in the D-Bus interface.

- ### **Why This Idea:**  
  It allows me to practice C in a highly abstracted environment (Frontend-Backend) and work with D-Bus as the communication interface.  

- ### **Why Me:**  
  I have strong experience in C/C++ and Qt and have already explored `cpdb-libs` and `cpdb-backend-cups` repositories, as well as D-Bus APIs. My problem-solving experience will help me complete this task efficiently.  

- ### **Time Commitment:**  
  - **Before GSoC:** 10+ hours/week to familiarize myself with the codebase and architecture and communicate with mentors.  
  - **During GSoC:** 40 hours/week except during my final exams.  
    - **Final exams:** From **June 9 to June 23**; reduced availability (~10 hours/week).  
  - **After GSoC:** I want to continue contributing to the project, help others, and possibly become a mentor.  


### **Expected Timeline:**  

| **Period** | **Plan** |  
|------------|----------|  
| **Community Bonding** | Familiarize myself with the codebase and architecture, communicate with mentors, discuss project goals, and understand how to test the output of this work. |  
| **Week 1–2** | Implement D-Bus signals and methods  |  
| **Week 3–4** | Modify `cpdb-backend-cups` to detect certificate mismatch errors and emit the error signal. |  
| **Week 5–6** | Implement error handlers in the backend to reset the CUPS certificate state. |  
| **Week 7–8** | Add a new frontend API to `libcpdb-frontend` for receiving errors and sending actions. |  
| **Week 9–10** | Create a CLI example in the text frontend and integrate it with a print dialog (GTK/Qt). |  
| **Week 11** | Test the end-to-end error resolution flow and handle edge cases. |  
| **Week 12** | Write documentation and submit the final blog post. |  

- ## **Note** 
    I believe I may be able to achieve my goals in this project in a duration shorter than the standard 12 weeks. If so, I would like to help with improving signal handling in the D-Bus interface.
