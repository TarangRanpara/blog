---
title: "About Me!"
date: 2024-03-10T17:46:19+05:30
draft: false
toc: true
---

## Summary

![Example image](/images/01_me.jpg)  

Hello World, Namaste! 🙏

I'm Tarang Ranpara, a Member Technical Staff (SE-2) with the MySQL Runtime team at Oracle, Bangalore, since Aug 2022. I currently contribute to the development of MySQL Server, one of the most popular relational database engines out there, working with systems programming technology stack (C/C++, Pthreads, Linux, CMake, Make). 

Being an inquisitive person, I believe in what Richard Feynman famously said "What I cannot create, I do not understand", and try to create minimal prototypes of things I'm trying to learn (mostly related to CS though). Some of the things (In no particular order) that interest me are Theoretical Computer Science, machine learning, Natural language processing, Physics, Businesses, (and somehow) Spirituality. 

I like to read a LOT of random stuff and talk to people from different walks of life. This blog is an attempt towards re-sharing the learnings that i've been fortunate to receive. 

Live long and prosper! 🖖

## Work Experience
--------
### Member Technical Staff @ [MySQL, Oracle](https://www.oracle.com/in/mysql/) 

- [Aug 2022 - Dec 2022] Oracle Tech Hub, Bengaluru
    - Worked with MySQL Runtime team on Control Plane and Data Plane of [MySQL Heatwave Service (or MHS)](https://www.oracle.com/in/mysql/features/), a fully managed `MySQL-as-a-service` offering on OCI. 
    - Worked as an Operator on-duty/on-call for MHS. 
    - Tech stack: Java

- [Jan 2023 - Now] Oracle Tech Hub, Bengaluru
    - Working with MySQL Runtime team and contribute to the development (features and bug fixes) of `MySQL Server`, one of the most popular relation database engines out there. 
    - Some of my note-worthy (and open-source) work is listed below: 
       - [WL#15369](https://github.com/mysql/mysql-server/commit/a0dd60dc022a74965f4f95fb1b21075f791ccfcd) : 
         - Identified the steps during MySQL Server initialization, startup and shutdown which can potentially take very long time to complete but are not reported in error-logs. Added logs for such steps. 
         - Notably, logs added as part of this work helps to identify infamous "stuck shutdown" problem of MySQL. 
       - [WL#15400](https://github.com/mysql/mysql-server/commit/d8ac701f3207494b8d46b6578fb37876d87db177) :
         - Added "externally visible" progress information during MySQL Server initialization, startup and shutdown which can potentially take very long time to complete or depend on user input (which makes their execution time unpredictible). 
         - Automated database management tools can initiate MySQL Server initialization, startup, or shutdown processes, and typically have defined timeouts for each workflow, which may be insufficient in certain cases. Access to granular progress notifications would be beneficial for these tools, enabling them to implement conditional logic based on the server's current execution stage.
         - This feature is actively used in MHS.
         - Blog post : https://blogs.oracle.com/mysql/post/enhancing-systemd-notifications-in-mysql
       - Other bug fixes and everything: https://github.com/mysql/mysql-server/commits?author=tranpara
    - Worked on performance benchmarking and regression issues to identify bottlenecks, and suggest potential improvements.
    - Worked on Customer POC where they were trying to migrate from competitor service to MHS (to find out optimal configurations, compute shape, etc based on their workload). 
    - Working as a SME (Subject Matter Expert) for MySQL Server and worked on issues filed by MHS customers.   
    - Working as an Operator on-duty/on-call for MHS. 
    - Tech stack: C/C++, Pthreads

### Researcher @ [IRLP Lab, DA-IICT](https://www.linkedin.com/company/daiict-irlp-lab/about/) 
[Jul 2021 - Jul 2022] DA-IICT, Gandhinagar
- Pursued a master's thesis titled "Finding Proxy For Human Evaluation: Re-evaluating the evaluation of news summarization" under the guidance of Prof. Prasenjit Majumder. 
- The thesis explores various evaluation metrics including the defacto metric, ROUGE, and various contextual similarity models like BERT ROBERTA, word2vec, etc. and it proves that the defacto evaluation metric ROUGE performs worse than various contextual similarity-based metrics. The idea is that a metric having a higher correlation with human evaluation is said to be a better proxy of it, and hence a better metric.

### SDE Summer Intern @ [OpsHub, Inc.](https://www.opshub.com/)
[May 2021 - Jul 2021] Ahmedabad
- Built a silent installation utility for OIM (OpsHub Installation Manager) which helps users install it using CLI. 
- Tech stack: Java

### Research Intern @ [Space Applications Centre, ISRO](https://www.sac.gov.in/Vyom/)
[Jan 2020 - May 2020] Ahmedabad
- Built a data processing tool for signal data. 
- Tech stack: 
   - NumPy stack: For math intensive parts
   - Numba: Mainly for parallelization, JIT compilation, CPU/GPU threading

## Education 
---------
### M.Tech (ICT) with specialization in Machine Learning
[Dhirubhai Ambani Institute of Information and communication technology (DA-IICT), Gandhinagar](https://www.daiict.ac.in/)

CGPA - 8.71/10

- Below are the courses I undertook as part of the curriculum: 
   - SC505 - Linear algebra
   - IT506 - Accelerated computing (CUDA C)
   - SC531 - Probability and Random variables
   - IT542 - Pattern Recognition Machine Learning 
   - IT507 - Advanced Image Processing
   - IT524 - Computer Vision 
   - IT550 - Information Retrieval
   - IT412 - Natural Language Processing


### B.E. Computer Science
[Gujarat Technological University (GTU), Gandhinagar](https://www.gtu.ac.in/)

CGPA - 9.28/10