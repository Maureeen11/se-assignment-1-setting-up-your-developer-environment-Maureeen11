[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15270226&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
 First, back up all your crucial data on drive C: to an external hard drive or cloud storage. Installing Windows 11 will erase everything on this drive.

Next, verify your PC meets Windows 11's minimum requirements using the official Microsoft PC Health Check app. Download the Windows 11 Installation Assistant tool from the Microsoft website and create a bootable USB drive with at least 8GB of free space.

Now we move on to the installation process itself. Restart your PC and press the designated key to enter the boot menu (typically Esc, F2, F10, or Del - depending on your motherboard). Use the arrow keys to choose the USB drive you created and press Enter to boot from it.

During Windows Setup, select your language, time zone, and keyboard layout. Click "Install Now" and enter your product key (if you have a retail copy). Otherwise, select "I don't have a product key" if upgrading from a previous qualified Windows version. Agree to the license terms and choose the "Custom" installation type (advanced).

When selecting the installation type, you'll see available drives. Unless you have a specific reason to modify partitions, it's recommended to select the default option that includes formatting drive C:. Click "Next" to begin the installation process.

The installation will take some time and your PC may restart several times. Once complete, you'll go through the Out-of-Box Experience (OOBE) process. This involves setting up your region, language, keyboard layout, connecting to Wi-Fi, and creating or signing in with a Microsoft account. You can personalize your settings during this stage. Follow the on-screen instructions to complete the OOBE and arrive at the Windows 11 desktop.

Finally, after installation, you can change your PC name if desired by going to Settings > System > About and clicking "Rename this PC". Windows 11 should automatically install most drivers, but you might need to check the manufacturer's website for any specific ones not included.

![alt text](<Step 2.png>) ![alt text](<Step 3.png>) ![alt text](<Step 4.png>) ![alt text](<Step 1-1.png>)


2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   There are two main categories of coding software: text editors and Integrated Development Environments (IDEs). Text editors are lightweight programs focused on writing and editing code. They offer basic features like syntax highlighting, which colorizes code based on its function, and code folding, which allows you to collapse sections of code for better organization. These features make text editors ideal for beginners or those who prefer a simpler environment.

IDEs, on the other hand, are more comprehensive suites that go beyond just editing. They offer functionalities like debugging, which helps identify and fix errors in your code, build automation, which streamlines the process of compiling and running your code, and project management tools to keep your projects organized. These additional features make IDEs ideal for larger projects or developers who need the extra functionality.

Choosing the Right Fit:

When selecting your software, consider these factors:

Programming Languages: Make sure the editor/IDE supports the languages you plan to use.
Features: Identify which functionalities are important to your workflow, such as debugging or version control (tracking changes made to your code).
Complexity: Decide if a full-fledged IDE is necessary for your projects, or if a simpler text editor would suffice.

Downloading VS Code:

First, head over to the official VS Code download page: https://code.visualstudio.com/download. There, you'll find the appropriate version for your operating system, whether it's Windows, macOS, or Linux. Simply select the version that matches your system and click the download button.

Installing VS Code:

Once the download is complete, double-click the installer file and follow the on-screen instructions. The installation process is typically straightforward and shouldn't take long.

VS Code Customization (Optional):

While VS Code is powerful on its own, it also offers a vast marketplace of extensions. These extensions allow you to personalize your coding experience. You can explore the VS Code Marketplace to add features like support for specific programming languages, customize themes for a unique look, and install productivity tools to streamline your workflow.
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com


Head over to the official Git downloads page: https://www.git-scm.com/downloads and download the installer that matches your operating system (Windows, macOS, or Linux). Once downloaded, follow the on-screen instructions to complete the installation process
Before using Git, let's configure it with your information. Open your command prompt (Windows) or terminal (macOS/Linux). Here, run the following commands, replacing <your_username> and <your_email> with your actual information:

git config --global user.name "<your_username>"
git config --global user.email "<your_email>"

Now that Git is installed and configured, you'll need a place to host your project's version control information. Head to GitHub: [https://github.com/] and create a free account if you haven't already. A GitHub account allows you to create remote repositories to store your project's code and collaborate with others.

Navigate to your project directory using the cd command in your command prompt/terminal. Once there, run the command git init to initialize a Git repository within your current directory. This creates a hidden folder named .git that stores version control information for your project.

Now that you have a Git repository, it's time to capture the initial state of your project. Use the git add command followed by the file names or paths to add files to your initial commit. For example, git add main.py adds a file named main.py, or git add . adds all files in the current directory.

Once your files are staged for commit, run the command git commit -m "<commit message>" to create a commit with a descriptive message. Replace <commit message> with a brief explanation of the changes you're committing (e.g., "Initial commit of project files"). This creates a snapshot of your project at this point in time.

4. Install Necessary Programming Languages and Runtimes: Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

The first step is identifying the programming languages your project requires. Research different languages if you're unsure which ones are best suited for your needs. Always download languages from their official websites to ensure you have the latest stable version and avoid security risks.
Once you've downloaded the installer for your chosen language, follow the on-screen instructions carefully. These typically involve accepting license agreements, selecting installation paths, and choosing optional components.

After installation, open your command prompt (Windows) or terminal (macOS/Linux). To verify successful installation, type the appropriate command to check the installed version. For example, with Python, you can type python --version (or python3 for Python 3 on some systems). If the command displays the installed version number, you're good to go!

Some languages might require additional runtimes, like the Java Runtime Environment (JRE) for Java.  Consult the language's documentation to determine if any extra runtimes are necessary for your project. If needed, download and install these runtimes from their respective official sources.

For some languages like Python, package managers like pip help you install and manage additional libraries and frameworks that enhance your coding capabilities. Refer to the language's documentation for instructions on using package managers effectively.

5.Install Package Managers: If applicable, install package managers like pip (Python).

First, let's verify if pip is already installed. Open your command prompt (Windows) or terminal (macOS/Linux) and type python -m pip --version followed by Enter. If pip is present, the command will display its version.

However, if you see an error message indicating pip is not found, proceed with the installation steps Download get-pip.py: Head over to the official Python Packaging User Guide (https://packaging.python.org/tutorials/installing-packages/) and download the get-pip.py script.
Run the script: Navigate to the folder where you downloaded the script using the cd command (e.g., cd Downloads if it's in your Downloads folder). Then, type python get-pip.py and press Enter.

6.Configure a Database (MySQL): Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

After downloading the appropriate MySQL installer from the official website find the downloaded MySQL installer file (e.g., mysql-installer-web-community.msi or mysql-installer-community.msi). It's usually located in your Downloads folder unless you specified a different location during download.
Double-click on the downloaded installer file. This will launch the MySQL Installer Wizard, which will guide you through the installation process.Double-click on the downloaded installer file. This will launch the MySQL Installer Wizard, which will guide you through the installation process.
The wizard greets you. Simply click "Next" to proceed.
Take a moment to carefully review the license agreement. If you agree to the terms, select "I accept the license agreement" and click "Next."Choose the type of installation you want. Selecting "Developer Machine" is a good option for development environments. Click "Next" to continue.This screen allows you to pick the MySQL components you'll install. The default selections typically cover essential components, but you can review the options and adjust them if needed. Once you're satisfied, click "Next."Then the data directory location and choosing a character set. The official MySQL documentation provides detailed explanations for each option if you need clarification. After making your selections, click "Next" to proceed.You have the option to configure MySQL as a Windows service. This allows it to start automatically when your system boots up. Choose the desired option and click "Next."This is a critical step! Here, you'll set a strong root password for the MySQL administrator account. Remember this password as you'll need it to access and manage the MySQL server. Click "Next" to continue.Review the summary of your installation choices. If everything looks good, click "Install" to begin the installation process.The wizard will display the installation progress, which might take a few minutes depending on your system configuration.
![alt text](<mysql 1.png>)

7. Set Up Development Environments and Virtualization (Optional):
   Consider using : Once the installation is complete, you'll see a completion screen. Click "Finish" to exit the wizard.Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
While the core development tools might be similar across machines, managing project dependencies and ensuring consistent environments can be a challenge. This section explores using virtualization tools like Docker or virtual machines (VMs) to address these concerns.Popular options include Docker (lightweight containers) and VMs (complete virtual machines). Docker excels at packaging and deploying applications, while VMs provide more isolation and are suitable for entire development environments or legacy applications.

8. Explore Extensions and Plugins:Virtualization lets you create isolated environments on your machine, each running its own operating system and applications.Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Syntax highlighting extensions paint your code with color, making it easier to differentiate keywords, functions, variables, and comments. This visual distinction significantly improves code readability and helps you grasp the structure of your program at a glance. Popular options include themes like Solarized or One Dark Pro, along with language-specific extensions like Python for VS Code or C++ Intellisense for Visual Studio.

Code completion extensions come to the rescue, suggesting relevant code snippets, function calls, and variable names based on your code context. This feature speeds up development and reduces errors. Examples include IntelliSense (Visual Studio), TabNine (various editors), and Kite (various editors).

Linters -  They scan your code for potential errors, stylistic inconsistencies, and bad practices. By identifying these issues early on, linters help you maintain clean, maintainable, and bug-free code. ESLint is a popular linter with various language configurations, while Stylelint focuses on enforcing consistent coding styles.

 Formatters automatically adjust your code's indentation, spacing, and line breaks based on the chosen style. Popular options include Prettier (various editors), Beautify (various editors), and YAPF (Python).

 Git or other version control systems (VCS) into your editor's interface. This allows you to commit changes, view version history, and collaborate with others directly within your coding environment. GitLens (VS Code) and GitHub for Visual Studio are excellent examples that enhance your Git workflow.Examples:
 Debuggers: Extensions like the Python debugger for VS Code or the C++ Debugger for Visual Studio allow you to step through your code line by line, inspecting variables and identifying issues during the debugging process.

![alt text](<Debugger 1.0.png>)



9. Document Your Setup:Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process.

To code editing, I rely on Visual Studio Code (VS Code).  VS Code offers a lightweight, customizable interface that integrates well with various programming languages through extensions.Visual Studio Code (VS Code) is my code editor of choice. It offers a lightweight, customizable interface, and extensive support for various programming languages through extensions.

 VS Code Extensions: I installed various extensions to enhance VS Code's functionality for specific programming languages and frameworks I frequently use (e.g., Python, C++, Node.js).
Themes and Settings: I customized VS Code's theme and settings for a more optimized and visually appealing coding experience. These customizations are personal preferences and can be adjusted as needed.
ssential Tools and Package Installation

Package Manager: I utilize the default package manager for my chosen Linux distribution (apt in Ubuntu's case) to install essential tools.
Terminal: The terminal serves as the primary interface for interacting with the system and managing development workflows.
Git: Git, a version control system (VCS), is crucial for managing code versions and collaboration. I followed the official Git installation guide for my Linux distribution.
  IDE Configuration and Customization

VS Code Extensions: I installed various extensions to enhance VS Code's functionality for specific programming languages and frameworks I frequently use (e.g., Python, C++, Node.js).
Themes and Settings: I customized VS Code's theme and settings for a more optimized and visually appealing coding experience. These customizations are personal preferences and can be adjusted as needed.
  Troubleshooting

Dependency Issues: During the installation of some development tools, dependency conflicts arose. These were resolved by using the package manager's features to identify and install missing dependencies.
Version Incompatibilities: Occasionally, specific tools or extensions required specific versions of system libraries. This required using the package manager to install the required version or finding alternative tools with compatible dependencies.
  Additional Considerations

Text Editor: While VS Code is my primary editor, I also have a lightweight text editor installed for quick edits or working on remote servers where a full IDE might not be available.
Development Workflow Tools: Depending on the project requirements, additional tools like task runners (e.g., Grunt, Gulp) or build automation tools (e.g., Make, Maven) might be installed and configured for streamlining development processes.
  Version Control System Integration

I configured VS Code to seamlessly integrate with Git for version control functionalities. This allows me to manage code changes, collaborate with others, and track the project's history effectively.
  Regular Maintenance

It's important to stay updated with the latest versions of tools and libraries to benefit from bug fixes, security improvements, and new features. I leverage the package manager to keep my system and development tools up-to-date.
 Customization is Key

This guide serves as a general framework. The specific tools, configurations, and customizations will vary depending on individual preferences, project requirements, and programming languages used.

The development landscape constantly evolves. Staying updated with new tools, technologies, and best practices is essential for maintaining an efficient and effective development environment.


#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
