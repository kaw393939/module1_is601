# Module 1: Setting Up the Development Environment with GIT and Linux

## Module Overview
This module introduces students to essential tools for software development: GIT and Linux. Understanding and navigating the command line, using version control, and setting up a development environment are foundational skills for many roles in technology. By the end of this module, students will be able to install and configure WSL2, use basic Linux commands, edit text files with Vi, set up GIT for version control, and configure GitHub with SSH keys.

### Why GIT and Linux?
GIT and Linux were both developed by Linus Torvalds. Linux is an open-source operating system kernel, widely used for its robustness, security, and flexibility. GIT, a distributed version control system, allows multiple developers to work on the same codebase without conflicts. These tools are crucial in many fields, including data science, computer security, programming, and DevOps.

### The Importance of the Command Line
Proficiency in the command line is vital for various professional roles:
- **Data Science:** Automating data processing tasks, managing data files, and running scripts.
- **Computer Security:** Performing security audits, managing servers, and analyzing logs.
- **Programming:** Developing software, managing code versions, and automating development tasks.
- **DevOps:** Managing infrastructure, automating deployments, and ensuring system reliability.

### Background on GIT and Linux
GIT and Linux were both developed by Linus Torvalds. Linux is an open-source operating system kernel, while GIT is a distributed version control system. Both tools are widely used in software development and system administration, providing powerful capabilities for managing code and operating systems.

- **Linux:** Linux is known for its robustness, security, and flexibility. It is used in various environments, from servers to embedded systems. Basic commands such as `ls`, `cd`, `mkdir`, `rm`, and `cp` are essential for navigating and managing the Linux file system.
- **GIT:** GIT enables multiple developers to work on the same codebase without conflicts. Key commands include `git init`, `git clone`, `git add`, `git commit`, `git push`, `git pull`, `git branch`, and `git merge`. Understanding GIT flow methodology helps streamline the development process by organizing work into branches, merging changes, and maintaining a stable main branch.

## Learning Outcomes
- Install and configure WSL2 on a Windows machine.
- Understand and navigate the Linux command line.
- Use Vi to edit text files.
- Perform basic file system operations in Linux.
- Install and use GIT for version control.
- Set up and configure GitHub with SSH keys.
- Practice branching and merging in GIT.

## Module 1 Learning Pathway

### Recall

**Title:** Prior Experience with Linux and GIT  
**Grading Type:** Points  
**Instructions:** 
- Participate in a discussion forum to share your previous experiences with Linux and GIT.
- Discuss any challenges you faced and how you resolved them.
- This activity will help gauge your familiarity with Linux and GIT, and set the stage for the new material.

### Read

1. **Article: "Getting Started with WSL2"**
   - URL: [Getting Started with WSL2](https://learn.microsoft.com/en-us/windows/wsl/about)
   - Purpose: To guide you through the installation and configuration of WSL2 on Windows.

2. **Interactive Tutorial: "Introduction to Linux Commands"**
   - URL: [Introduction to Linux Commands](https://linuxsurvival.com/)
   - Purpose: To familiarize you with basic Linux commands and navigation.

3. **Video: Quick Introduction to VI**
   - URL: [Introduction to VIM](https://www.youtube.com/watch?v=-_DvfdgR-LA)
   - Purpose: A quick overview of Vi the Linux text editor

4. **Article: "Introduction to GIT"**
   - URL: [Introduction to GIT](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control)
   - Purpose: To introduce you to the basics of GIT and version control.

5. **Videos: Git Introduction**
   - URL: [GIT Intro Videos](https://git-scm.com/videos)
   - Purpose: Watch these 4 short videos for more detailed explanations of GIT

6. **Article: "Basic GIT Commands"**
   - URL: [Basic GIT Commands](https://www.atlassian.com/git/tutorials/setting-up-a-repository)
   - Purpose: To help you learn essential GIT commands and workflows.

### Watch

1. **Video: "Introduction to the Unit" (15 minutes)**
   - Purpose: To provide an overview of the unit, its objectives, and its importance.

2. **Video: "Basic Linux Commands" (15 minutes)**
   - Purpose: To demonstrate basic Linux commands and navigation.

3. **Video: "Getting Started with GIT" (15 minutes)**
   - Purpose: To provide a visual guide to setting up and using GIT.

4. **Video: "Setting Up SSH Keys for GitHub" (15 minutes)**
   - Purpose: To provide a visual guide to setting up SSH keys for secure communication with GitHub.

### Review

1. **Resource: Basic Linux Commands Cheat Sheet**
   - [Linux Command Cheat Sheet](https://www.geeksforgeeks.org/linux-commands-cheat-sheet/)
   - Purpose: To provide you with a quick reference to navigate the Linux command line.

2. **Resource: Vi Cheat Sheet**
   - [Vi Cheat Sheet](https://www.atmos.albany.edu/daes/atmclasses/atm350/vi_cheat_sheet.pdf)
   - Purpose: Various commands for Vi

3. **Resource: GIT Cheat Sheet**
   - URL: [GIT Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)
   - Purpose: To offer you a quick reference for essential GIT commands and workflows.

### Submit

**Activity Type:** Hands-on Assignment  

**Activity Title:** Linux and GIT Command Cheat Sheet  

**Grading Type:** Points  

**Submission Instructions**: Submit a link to your repository to Canvas

**Instructions:** 
- Create a cheat sheet for at least 15 Linux and GIT commands.
- The cheat sheet should be created using Vi or another text editor in the terminal.
- Practice branching and merging in GIT by maintaining your cheat sheet in a GIT repository.
- Set up GitHub with SSH keys and push your cheat sheet to a GitHub repository.

**Grading Expectations:** Completeness and accuracy of the cheat sheet, proper use of GIT commands, successful branching and merging, and correctly setting up GitHub with SSH keys to publish the assignment to GitHub.
  
**Alignment:** 
- Understand and navigate the Linux command line.
- Use Vi to edit text files.
- Perform basic file system operations in Linux.
- Install and use GIT for version control.
- Set up and configure GitHub with SSH keys.
- Practice branching and merging in GIT.

### Reflect

**Title:** Module 1 Reflection  
**Grading Type:** Points  
**Instructions:** 
- Write a brief reflection (150-200 words) on your experience setting up the development environment.
- Discuss how confident you feel using the tools and any areas where you need further clarification or support.
- This activity aims to encourage metacognition and connect new knowledge with prior experiences.

### Quiz

**Title:** Linux and GIT Basics Quiz  
**Grading Type:** Points  
**Instructions:** 
- Complete a quiz covering the key concepts and commands introduced in this module.
- The quiz will test your understanding of basic Linux commands, GIT commands, and the process of setting up SSH keys.
- Review the provided cheat sheets and tutorials before taking the quiz.

### Additional Information

#### Installing Homebrew on Mac
Mac users will need to install Homebrew to easily manage the installation of GIT and other software packages. Follow these steps:

1. **Install Homebrew:**
   - Open the Terminal application.
   - Paste the following command and press Enter:
     ```sh
     /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
     ```
   - Follow the on-screen instructions to complete the installation.

2. **Install GIT using Homebrew:**
   - In the Terminal, type the following command and press Enter:
     ```sh
     brew install git
     ```

3. **Verify the Installation:**
   - Type the following command and press Enter:
     ```sh
     git --version
     ```
   - You should see the installed version of GIT.
