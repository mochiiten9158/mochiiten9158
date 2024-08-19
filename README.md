# About
I am a first year PhD student at UIC under the mentorship of Dr. Zhiling Lan.
I am passionate about High-Performance Computing (HPC) and am exploring the creation of systems that combine Agent-Based Modeling and DES, along with the creation of a Digital Twin within the ALCF project SEEr-Polaris. I also plan on focusing on current problems related to energy use in the creation and management of supercomputers, and developing new algorithms to address these issues.

# Projects
* **HawkPhish**
    * I, along with my team consisting of John Deifel, Kaleb Austgen, Verica Karanakova, Alyssa Cao, Na'im Mohammed, Mohammed Trigui, Harrison Le, Emmanuel Gonzalez, Ricky Madrid Quiles, Katherine Prush, Kathleen Monahan, Lucas Costa-Wang, Jiachen Wang and Rodney Fears under the guidance of Dr. Rahul Patel created a cybersecurity solution that works as a chrome extension that scans malicious links and stores them in an Azure SQL database. I worked in creation and management of databases and performing analytics/statistics on real world data. I contributed to establishing end-to-end connection between frontend and backend, and contributed towards encryption of data and garbage collection.
    * We constructed backend for a cybersecurity chrome extension to scan malicious links by building the Azure SQL database (V1.0) and AWS db (V2.0) and created end-to-end connection between frontend and backend by deploying REST functions to connect to database to store approximately 1000 entries used to perform data analyses. I led data encryption and garbage collection by writing functions to clean data directly at frontend before storage to ensure efficiency and rapid bidirectional communication between frontend and backend, speedup of 10 ms
* **Automated Sudoku and Tic-Tac-Toe AI Solver**
   * Designed and executed an AI Sudoku and Tic-Tac-Toe solver using the Backtracking, GBFS and MRV heuristics algorithm to reduce runtime for problem to less than 1 minute, speedup by nearly 80% and efficient node traversal in decision tree
* **Lottery Scheduler, Multi-Level Paging, Threading and System Calls**
    * I modified a research OS in xv6 to enable new and customized system calls and implement multilevel paging, threading and scheduling. I created an OS CPU Scheduler in C that assigns each running process with a specific resource time of the processor directly proportional to the number of tickets it has. Event scheduling is random based on a linear congruential generator algorithm (LCG) where a linear equation is used to determine which event “wins” the lottery to be assigned processor time.
    * I also enhanced xv6 research by introducing over 20 new and customized system calls, performing multilevel paging, threading, and scheduling, improving runtime to 10.0 seconds across 10 to 20 test workloads files
Designed a C-based OS CPU Scheduler with random event scheduling deploying the LCG algorithm, enhanced runtime efficiency and achieved a speedup of approximately 5.0 seconds across 20 test workloads
* **Python TUI Bank Application**
    * I constructed a TUI Bank app with Python and PostgreSQL for frontend and backend, implemented deposit, withdrawal, and transfer functions, along with security measures including data encryption and password protection and optimized the database for 500 entries to maintain runtime efficiency catered towards small-scale banking applications
* **Android Weather App and Android News App**
     * I created a Weather App in Android Studio that utilizes real time weather information from an external API source to display real time weather for any part of the world, along with weather icons imported using a local library. The Weather App I built displayed weather information for not only the same day but also up to the next 15 days, with display options in the metric as well as other systems. The News app displayed all news sources from an external API that allowed users to choose news articles from a specific source for a specific topic. The titles and articles itself are stored and displayed using an Adapter and View Holder, while the list of available sources and topics are accessed using Hash Maps that are used to navigate between articles.
     * Built full-stack Android app to fetch real-time weather data from an external API, integrates personalized features using a local library, and displays dynamic weather information for next 15 days, utilized Agile
     * Constructed full-stack Android app to display news sources utilizing an external API by implementing Hash Maps with more than 1000 entries to allow smooth browsing based on intuitive frontend design principles, utilized Agile
* **Java Game: Race Between Two Campuses**
     * I, along with a team of students (Ryan Ciminski, Olivia Debenedictis, Matthew Horowitz) created a game map similar to chutes and ladders, coded for a three-class project with application of concepts like exception handling, object oriented programming and inheritance.

# Work Experience
* **Graduate RA at University of Illinois at Chicago and Argonne Leadership Computing Facility**
   * Jun ’24 - Aug ’24
   * Optimized DES software for batch scheduling called CQSim to run capability and capacity jobs from Theta and Cori systems and analyzed graphical representations of utilization and scheduling delay
   * Conducted literature survey on ABM versus DES and explored Digital Twin and HTCondor to design and implement systems with inter-agent communication for facility wide resource management and meta-scheduling
* **Undergraduate RA at Illinois Institute of Technology**
   * Jan ’23 - May ’24
   * Analyzed and studied discrete event simulation framework CODES (primarily in C and OpenMPI) and cluster scheduling simulator CQSim (predominantly in Python), instrumental in supporting development of production batch scheduler Cobalt
   * Studied and constructed event scheduling simulation by analyzing two DUMPI trace files and creating five trace workload files, resulting in refined event scheduler and batch scheduler performance
   * Conducted research under supervision and guidance of Dr. Zhiling Lan during Spring 23 CS497 course, gained valuable insights in High Performance and Scientific Computing
* **CRA Intern at FIGmd**
   * May ’22 - Aug ’22
   * Assessed medical practitioners and systems with 10,000+ entries with measures from CMS.gov, enhanced database efficiency and accuracy, collaborating with a team of 20 members to build HTML files and Excel/SQL databases
   * Utilized proprietary technologies MAT and VSAT, endorsed by CMS.gov, SQL and advanced Excel functions
* **Project Consultant and Teaching Assistant at JP Morgan Chase and Co., P33 Chicago, Illinois Tech**
   * Jan ’22 - May ’24
   * Mentored and managed full-cycle development of 4 banking applications, including frontend and backend, by introducing technologies (MySQL, Wordpress, Android Studio, Eclipse) and debugging with a total of ~30-40 students
   * Solved problems related to frontend design, backend efficiency and functionality through mentoring teams of 6 students and brainstorming solutions through market/technical research and interviews of experts at JPMC

# Interests and Future Goals
In my free time, I rather enjoy reading academic papers on various topics. I am currently trying to read more papers regarding HPCs in order to gain more knowledge about them. Apart from papers, I enjoy playing video games and listening to classical music!
<!--
**mochiiten9158/mochiiten9158** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
