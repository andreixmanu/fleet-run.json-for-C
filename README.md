# Running C Files in JetBrains Fleet - Noob-Proof Guide
## Introduction
This guide provides step-by-step instructions on how to run C files using JetBrains Fleet, ensuring a seamless experience for beginners. The provided run.json configuration file simplifies the process and allows users to execute C programs effortlessly.

### Prerequisites
Before proceeding, make sure you have the following installed:

- JetBrains Fleet
- GCC (GNU Compiler Collection)

### Getting Started
1. Clone the Repository:
Clone the repository containing your C files using your preferred method.

2. Open Project in JetBrains Fleet:
Launch JetBrains Fleet and open your C project.

3. Configure run.json:
Open the run.json file in your project. This file contains configurations for running C programs. Follow the comments within the file for customization.

4. Update the "dependsOn" field in the "run" configuration to match the name of the command you want to execute (e.g., "main").
For each C file you want to run, create a separate configuration under "configurations" by copying the example command and updating the name and source file in the "args" field.
