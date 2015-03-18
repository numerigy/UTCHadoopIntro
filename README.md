# UTC - Intro to Hadoop

Course:
- Advanced Queries & Business Reports
- Dr. Beni Asllani
- Presented by
  - Joe France
  - @joefrance

Lesson Plan

The lesson will cover two technologies:
  - Hadoop 5:45 PM to 7:15 PM - with break(s)
  - GitHub 7:15 PM to 7:45 PM

Intro to Hadoop

- High Level Description of Hadoop Ecosystem
  - Created by Doug Cutting
  - Named for his son's toy elephant
  - Scalable, batch processing with reliable, redundant storage.
  - Built on two fundamental components
    - HDFS (Hadoop Distributed File System)
      - Based on concepts from Google’s GFS paper:
        - <a href="http://static.googleusercontent.com/media/research.google.com/en/us/archive/gfs-sosp2003.pdf">The Google File System</a>
    - MapReduce framework
      - Based on 2004 paper from Google on MapReduce:
        - <a href="http://static.googleusercontent.com/media/research.google.com/en/us/archive/mapreduce-osdi04.pdf">MapReduce: Simplified Data Processing on Large Clusters</a>
      - Java-based (starting with v1)
      - Streaming, allows non-Java coding (starting with MRv2/YARN)
- Examples of previous work and planned work
  - Baseball streaming - listener stats
  - Handyman service
    - Error log analysis
    - Job and Craftsman skills match
    - Potential for marketing/zip code analysis
  - Ceiling fan manufacturer
    - Failure analysis

Discussion

- HDFS
  - Default of 3 copies of data
  - Deep storage
  - Schema-on-read
- MapReduce
  - Java/JVM based paradigm
  - MRv2/YARN - Streaming, can use ruby, other languages
  - This structure brings the code to the data

MapReduce Example

- Review WordCount Java code
- Run WordCount example
  - Point out Map/Reduce percentage as job runs
- Discuss WordCount example
- Q & A about WordCount exampe

Overview of Hive and Pig

- Hive
  - High-level query atop MapReduce
  - Similar to SQL
  - HiveQL compatible with many SQL flavors
  - Compiles queries to MapReduce
  - Can see MapReduce progress on longer queries
  - Run Hive examples

- Pig
  - High-level "scripting" atop MapReduce
  - Run Pig examples
  - Can see MapReduce progress on longer queries

Local Big Data User Groups
- CHadoop
  - http://meetup.com/CHadoop
  - https://github.com/CHadoop
- Chattanooga Data Science R Users and Machine Learning
  - http://www.meetup.com/Chattanooga-Data-Science-R-Users-and-Machine-Learning

Installing Hadoop for Yourself

- Installing Hadoop on MS Windows, Mac OS X, and Ubuntu
- Download instructions and installation files from:
  - <a href="https://github.com/CHadoop/InstallationGuide">CHad

Intro to GitHub

- Brief history
  - Git is a source control system
  - Used by Linux creator Linus Torvalds and the kernel team
  - GitHub is a popular website frontend
  - Can create and share code in repositories (repo)
- Creating an account
- Installation
  - Mac
    - https://mac.github.com/
  - Windows
    - https://windows.github.com/
- Adding a repo
  - The README.md file
