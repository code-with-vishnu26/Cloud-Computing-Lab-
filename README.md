# Cloud-Computing-Lab

This repository contains the lab work performed for a Cloud Computing course, submitted by J. Vishnu (UG ID: 22WU010101129, CSE B) under the supervision of Prof. Vaishali Thakur at Woxsen University.

## Table of Contents

The lab record covers the following experiments:

1.  **Install Virtualbox with different flavors of Linux or Windows OS on top of Windows 7 or 8.**
    * Installation of Oracle Virtualbox.
    * Installation of Ubuntu Linux ISO file.
    * Installation of Linux OS on Virtualbox.

2.  **Install a Python compiler in the virtual machine created using Virtualbox and execute Simple Programs.**
    * Installing `build-essential` package in Ubuntu.
    * Upgrading installed packages.
    * Installing `Gedit` text editor.
    * Creating a text file using `touch`.
    * Opening a file with `Gedit`.
    * Writing and saving Python code.
    * Viewing file content using `cat`.
    * Executing Python code using `python3`.
    * Changing file permissions with `chmod`.
    * Opening a file with `nano` editor.

3.  **Install Google App Engine. Create "hello world" app and other simple web applications using Python/Java.**
    * Installation of Google App Engine.
    * Adding Python path in App Engine preferences.
    * Adding App Engine files.
    * Creating a new application folder and setting the port.

4.  **Use GAE Launcher to launch the web applications.**
    * Launching web applications using GAE Launcher.
    * Creating and Browse a new application on localhost.
    * Viewing logs.
    * Accessing `localhost:8080` in a browser.

5.  **Simulate a cloud scenario using CloudSim and run a scheduling algorithm that is not present in CloudSim.**
    * Downloading JAVA.
    * Downloading CloudSim 3.0.3.
    * Downloading Common Math 3.
    * Placing Common Math JAR file in the CloudSim folder.
    * Accessing the CloudSim folder as a Java project in Eclipse IDE.
    * Selecting Common Math JAR file while creating the Java project.
    * Running an example program in CloudSim.

6.  **Find a procedure to transfer files from one virtual machine to another virtual machine.**
    * Adding a shared folder in Virtual Machine settings.
    * Installing `build-essential` and `linux-headers` in the Linux VM.
    * Installing Guest Additions.
    * Adding user to `vboxsf` group.
    * Restarting the VM to access the shared folder.

7.  **Find a procedure to launch a virtual machine using TryStack (Online OpenStack Demo Version).**
    * Understanding OpenStack and TryStack.
    * Registering and logging into TryStack.org.
    * Creating a private network.
    * Creating an OpenStack instance (virtual machine).
    * Creating a router for internet connectivity.
    * Configuring Floating IP Address for public access.
    * Configuring Access & Security (firewall rules like ICMP, HTTP, SSH).
    * SSH access to the launched instance.

8.  **Install Hadoop single node cluster and run simple applications like wordcount.**
    * Downloading and extracting Java 8.
    * Downloading and extracting Hadoop 2.7.3.
    * Adding Hadoop and Java paths to `.bashrc`.
    * Editing Hadoop configuration files: `core-site.xml`, `hdfs-site.xml`, `mapred-site.xml`, `yarn-site.xml`, `hadoop-env.sh`.
    * Formatting the NameNode.
    * Starting Hadoop daemons (`start-all.sh` or individually: NameNode, DataNode, ResourceManager, NodeManager, JobHistoryServer).
    * Verifying running daemons using `jps`.
    * Checking NameNode interface via browser.
