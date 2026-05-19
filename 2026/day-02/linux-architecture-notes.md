**The core components of Linux**
**Linux Architecture**
    Application-
        This is the top tier where the user and the software reside and operate. The boundary between the Kernel Space and User Space is strictly enforced by the CPU to guarantee system stability.
        Applications: Software programs (browsers, text editors, servers, databases) that interact indirectly with the hardware via kernel requests.
    Shell-
        A command-line interpreter (e.g., Bash or Zsh) that takes human-readable commands from the user and translates them into execution instructions for the underlying OS.
    Kernel-
        Kernel is the core component of the Linux OS that sits between the hardware and user space, managing system resources and ensuring smooth communication between software and hardware. It controls how processes are executed, scheduled, and isolated to maintain system stability and security.
   
    
**init/systemd**
    init stands for initializes
        Systemd Running as the first Process (PID 1),it initializes the operating system, aggressively parallelizes the boot process, manages background services, logs events, and handles device management.
    Why systemd was important?
        it replaced slow, manual scripts with parallel processing, dynamic resource management, and unified system control, which are essential for modern servers and computers

**Linix Commands Basic Commands**
    16 Practice Basic Commands list with one line
        ls - List directory contents
        pwd - Show current directory path
        cd - Change directory
        mkdir - Create a directory
        rmdir - Remove an empty directory
        cp - Copy files or directories
        mv - Move or rename files
        touch - Create an empty file
        file - Show file type
        cat - Display file content
        head - Show first lines of a file
        tail - Show last lines of a file
        du - Show directory size
        whoami - Show current user
        top - Display running processes
        htop - Interactive process viewer
Process Topic Was Remaning


**Linkedin Post**
🚀 Day 02 of 90 Days of DevOps

Today was all about Linux fundamentals — the backbone of every DevOps Engineer.

🔹 Learned how:
✅ The Linux OS works
✅ Kernel, Shell & User Space interact
✅ Core components of Linux
✅ systemd, why it matters, and the role of PID 1

🔹 Practiced essential Linux commands: ls, pwd, cd, mkdir, rmdir, cp, mv, touch, file, cat, head, tail, du, whoami, top, htop, vim df -h, free -h.
💡 As I Practice Linux more and more it's make me More Confidence and Clear - Strong Basic = Strong DevOps Skills. 
🙏 Thanks to Utho & Shubham Londhe for the guidance.
#90DaysOfDevOps #TrainWithShubham  #LearningInPublic #Linux #DevOpsJourney #Systemd