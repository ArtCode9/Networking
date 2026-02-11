What do you call a cryptographic method or product considered bogus or fraudulent?

Snake oil

What is the name of the command replacing netstat in Linux systems?

ss

----------------------------
Let’s consider the search operators supported by Google.

   - ```"exact phrase"```: Double quotes indicate that you are looking for pages with the exact word or phrase. For example, one might search for ```"passive reconnaissance"``` to get pages with this exact phrase.

   - ```site:```: This operator lets you specify the domain name to which you want to limit your search. For example, we can search for success stories on TryHackMe using ```site:tryhackme.com success stories```.

   - ```-```: The minus sign allows you to omit search results that contain a particular word or phrase. For example, you might be interested in learning about the pyramids, but you don’t want to view tourism websites; one approach is to search for ```pyramids -tourism``` or ```-tourism pyramids```.

   - ```filetype:```: This search operator is indispensable for finding files instead of web pages. Some of the file types you can search for using Google are Portable Document Format (PDF), Microsoft Word Document (DOC), Microsoft Excel Spreadsheet (XLS), and Microsoft PowerPoint Presentation (PPT). For example, to find cyber security presentations, try searching for ```filetype:ppt cyber security```.

You can check more advanced controls in various search engines in this advanced search operators list; however, the above provides a good starting point. Check your favourite search engine for the supported search operators.

https://github.com/cipher387/Advanced-search-operators-list

--------------------------
What phrase does the Linux command ss stand for?

socket statistics

How would you limit your Google search to PDF files containing the terms cyber warfare report?

filetype:pdf cyber warfare report

------------------------------
You are familiar with Internet search engines; however, how much are you familiar with specialized search engines? By that, we refer to search engines used to find specific types of results.

Shodan

Let’s start with Shodan, a search engine for devices connected to the Internet. It allows you to search for specific types and versions of servers, networking equipment, industrial control systems, and IoT devices. You may want to see how many servers are still running Apache 2.4.1 and the distribution across countries. To find the answer, we can search for apache 2.4.1, which will return the list of servers with the string “apache 2.4.1” in their headers.

Consider visiting Shodan Search Query Examples for more examples. Furthermore, you can check Shodan trends for historical insights if you have a subscription.

------------------------
Censys

At first glance, Censys appears similar to Shodan. However, Shodan focuses on Internet-connected devices and systems, such as servers, routers, webcams, and IoT devices. Censys, on the other hand, focuses on Internet-connected hosts, websites, certificates, and other Internet assets. Some of its use cases include enumerating domains in use, auditing open ports and services, and discovering rogue assets within a network. You might want to check Censys Introductory Use Cases.

-----------------
VirusTotal

VirusTotal is an online website that provides a virus-scanning service for files using multiple antivirus engines. It allows users to upload files or provide URLs to scan them against numerous antivirus engines and website scanners in a single operation. They can even input file hashes to check the results of previously uploaded files.

--------------------------------
Have I Been Pwned


Have I Been Pwned (HIBP) does one thing; it tells you if an email address has appeared in a leaked data breach. Finding one’s email within leaked data indicates leaked private information and, more importantly, passwords. Many users use the same password across multiple platforms, if one platform is breached, their password on other platforms is also exposed. Indeed, passwords are usually stored in encrypted format; however, many passwords are not that complex and can be recovered using a variety of attacks.

--------------------------------
CVE

We can think of the Common Vulnerabilities and Exposures (CVE) program as a dictionary of vulnerabilities. It provides a standardized identifier for vulnerabilities and security issues in software and hardware products. Each vulnerability is assigned a CVE ID with a standardized format like CVE-2024-29988. This unique identifier (CVE ID) ensures that everyone from security researchers to vendors and IT professionals is referring to the same vulnerability, CVE-2024-29988 in this case.

The MITRE Corporation maintains the CVE system. For more information and to search for existing CVEs, visit the CVE Program website. Alternatively, visit the National Vulnerability Database (NVD) website. The screenshot below shows CVE-2014-0160, also known as Heartbleed.

--------------------
Exploit Database

There are many reasons why you would want to exploit a vulnerable application; one would be assessing a company’s security as part of its red team. Needless to say, we should not try to exploit a vulnerable system unless we are given permission, usually via a legally binding agreement.

Now that we have permission to exploit a vulnerable system, we might need to find a working exploit code. One resource is the Exploit Database. The Exploit Database lists exploit codes from various authors; some of these exploit codes are tested and marked as verified.

GitHub, a web-based platform for software development, can contain many tools related to CVEs, along with proof-of-concept (PoC) and exploit codes. To demonstrate this idea, check the screenshot below of search results on GitHub that are related to the Heartbleed vulnerability.


What utility does CVE-2024-3094 refer to?
 
 xz

 ---------------------------------

One vital skill to acquire is to look up official documentation. We will cover a few examples of official documentation pages.

Linux Manual Pages

Long before the Internet was everywhere, how would you get help using a command in a Linux or Unix-like system? The answer would be checking the manual page, man page for short. On Linux and every Unix-like system, each command is expected to have a man page. In fact, man pages also exist for system calls, library functions, and even configuration files.

Let’s say we want to check the manual page for the command ip. We issue the command man ip. The screenshot below shows the page we received. You might want to start the AttackBox and run man ip on the terminal. Press q to quit.

If you prefer to read the man page of ip in your web browser, just type man ip in your favourite search engine. This page might be at the top of the results.


The AttackBox is a Linux system accessible from your browser. Clicking on the Start AttackBox button will display the AttackBox in a split screen, making it convenient to read the task text and apply the instructions within the same browser window. If you hide the AttackBox window, you can show it again by clicking the blue Show Split View button at the top. In this task, you can start the AttackBox and use it to try Linux commands such as man.

Microsoft Windows

Microsoft provides an official Technical Documentation page for its products. The screenshot below shows the search results for the command ipconfig.

Product Documentation

Every popular product is expected to have well-organized documentation. This documentation provides an official and reliable source of information about the product features and functions. Examples include Snort Official Documentation, Apache HTTP Server Documentation, PHP Documentation, and Node.js Documentation.

It is always rewarding to check the official documentation as it is the most up-to-date and offers the most complete product information.

What does the Linux command cat stand for?

concatenate

What is the netstat parameter in MS Windows that displays the executable associated with each active connection and listening port?

-b

------------------------------
There are billions of users registered on social media platforms such as Facebook, Twitter, and LinkedIn. We expect you to be familiar with popular platforms. However, if you are aware of any platform you are not familiar with, we recommend that you check it out and learn about it. Ideally, one would want to explore a platform without creating an account; however, this severely limits your experience. Instead, one recommendation is to use a temporary email address to discover these platforms without linking them to your real email addresses; once done, you can terminate the accounts and associated email addresses. One reason for not using your primary account is that you don’t want your contacts to start connecting with you there when you are only temporarily exploring a platform.

The power of social media is that it allows you to connect with companies and people you are interested in. Furthermore, social media offers a wealth of information for cyber security professionals, whether they are searching for people or technical information. Why is searching for people important, you ask?

When protecting a company, you should ensure that the people you protect are not oversharing on social media. For instance, their social media might give away the answer to their secret questions, such as, “Which school did you go to as a child?”. Such information might allow adversaries to reset their passwords and take over their accounts effortlessly.

Furthermore, as a cyber security professional, you want to stay updated with new cyber security trends, technologies, and products. Following the proper channels and groups can provide a suitable environment for growing your technical expertise.

Besides staying updated via social media channels and groups, we should mention news outlets. Hundreds of news websites would offer valuable cyber-security-related news. Try different ones and stick with the ones you like most.

This lesson focused on the most common sources of information for cyber security professionals. There are plenty more. As the information landscape keeps changing, it is impossible to cover all the sources. However, by subscribing to relevant cyber security groups, one can stay ahead and be aware whenever new interesting sources arise.

---------------------------------------------
Linux Fundamentals Part 1

Where is Linux Used?

It's fair to say that Linux is a lot more intimidating to approach than Operating System's (OSs) such as Windows. Both variants have their own advantages and disadvantages. For example, Linux is considerably much more lightweight and you'd be surprised to know that there's a good chance you've used Linux in some form or another every day! Linux powers things such as:

Websites that you visit

Car entertainment/control panels

Point of Sale (PoS) systems such as checkout tills and registers in shops

Critical infrastructures such as traffic light controllers or industrial sensors

-----------------------------------------------
Flavours of Linux

The name "Linux" is actually an umbrella term for multiple OS's that are based on UNIX (another operating system). Thanks to Linux being open-source, variants of Linux come in all shapes and sizes - suited best for what the system is being used for.


For example, Ubuntu & Debian are some of the more commonplace distributions of Linux because it is so extensible. I.e. you can run Ubuntu as a server (such as websites & web applications) or as a fully-fledged desktop. For this series, we're going to be using Ubuntu.

Note: Ubuntu Server can run on systems with only 512MB of RAM!

Similar to how you have different versions Windows (7, 8 and 10), there are many different versions/distributions of Linux.

As we previously discussed, a large selling point of using OSs such as Ubuntu is how lightweight they can be. This, of course, doesn't come without its disadvantages, where for example, often there is no GUI (Graphical User Interface) or what is also known as a desktop environment that we can use to interact with the machine (unless it has been installed). A large part of interacting with these systems is using the "Terminal".


The "Terminal" is purely text-based and is intimidating at first. However, if we break down some of the commands, after some time, you quickly become familiar with using the terminal!

We need to be able to do basic functions like navigate to files, output their contents and make files! The commands to do so are self-explanatory (once you know what they are of course...)

--------------------------------
The find command is fantastic in the sense that it can be used both very simply or rather complex depending upon what it is you want to do exactly. However, let's stick to the fundamentals first.

Now, of course, directories can contain even more directories within themselves. It becomes a headache when we're having to look through every single one just to try and look for specific files. We can use find to do just this for us!


Let's start simple and assume that we already know the name of the file we're looking for — but can't remember where it is exactly! In this case, we're looking for "passwords.txt"

If we remember the filename, we can simply use find -name passwords.txt where the command will look through every folder in our current directory for that specific file like so:

"Find" has managed to find the file — it turns out it is located in folder1/passwords.txt — sweet. But let's say that we don't know the name of the file, or want to search for every file that has an extension such as ".txt". Find let's us do that too!

We can simply use what's known as a wildcard (*) to search for anything that has .txt at the end. In our case, we want to find every .txt file that's in our current directory. We will construct a command such as find -name *.txt . Where "Find" has been able to find every .txt file and has then given us the location of each one:

------------------------
Another great utility that is a great one to learn about is the use of grep. The grep command allows us to search the contents of files for specific values that we are looking for.

Using a command like cat isn't going to cut it too well here. Let's say for example if we wanted to search this log file to see the things that a certain user/IP address visited? Looking through 244 entries isn't all that efficient considering we want to find a specific value.

We can use grep to search the entire contents of this file for any entries of the value that we are searching for. Going with the example of a web server's access log, we want to see everything that the IP address "81.143.211.90" has visited (note that this is fictional)

"Grep" has searched through this file and has shown us any entries of what we've provided and that is contained within this log file for the IP.

--------------------------
Searching Recursively with grep

Sometimes, the information we are looking for is spread across multiple files inside a directory. Instead of checking each file individually, we can tell grep to search recursively through all files and subdirectories.

To do this, we use the -R (recursive) option.

For example, to search for a variable across all files in the current directory and its subfolders, we can run:

``` grep -R "PRETTY_NAME" /etc/```

>This will:
   - Search every file in the current directory
   - Search all subdirectories
   - Show where the PRETTY_NAME appears

------------------------------------

```&```  -> This operator allows you to run commands in the background of your terminal.

```&&``` -> This operator allows you to combine multiple commands together in one line of your terminal.

```>```  -> This operator is a redirector - meaning that we can take the output from a command (such as using cat to output a file) and direct it elsewhere.

```>>``` -> This operator does the same function of the > operator but appends the output rather than replacing (meaning nothing is overwritten).


-----------------------------------------------
Operator "&"

This operator allows us to execute commands in the background. For example, let's say we want to copy a large file. This will obviously take quite a long time and will leave us unable to do anything else until the file successfully copies.

The "&" shell operator allows us to execute a command and have it run in the background (such as this file copy) allowing us to do other things!


Operator "&&"

This shell operator is a bit misleading in the sense of how familiar is to its partner "&". Unlike the "&" operator, we can use "&&" to make a list of commands to run for example command1 && command2. However, it's worth noting that command2 will only run if command1 was successful.

Operator ">"


This operator is what's known as an output redirector. What this essentially means is that we take the output from a command we run and send that output to somewhere else.

A great example of this is redirecting the output of the echo command that we learned in Task 4. Of course, running something such as echo howdy will return "howdy" back to our terminal — that isn't super useful. What we can do instead, is redirect "howdy" to something such as a new file!

Let's say we wanted to create a file named "welcome" with the message "hey". We can run echo hey > welcome where we want the file created with the contents "hey" like so:

Note: If the file i.e. "welcome" already exists, the contents will be overwritten!

Operator ">>"

This operator is also an output redirector like in the previous operator (>) we discussed. However, what makes this operator different is that rather than overwriting any contents within a file, for example, it instead just puts the output at the end.

Following on with our previous example where we have the file "welcome" that has the contents of "hey". If were to use echo to add "hello" to the file using the > operator, the file will now only have "hello" and not "hey".

The >> operator allows to append the output to the bottom of the file — rather than replacing the contents like so:




