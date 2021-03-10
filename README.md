# Welcome
My name is Kitty. I'm currently a student with AWS re/Start learning Cloud Computing. I'm also a former IT administrator, ITIL certified, first line help desk support and freelance copy editor.

I love to learn and am always looking for a role I can develop into.

## AWS Re/Start
I've been so happy to study Cloud Computing with AWS. It's really comprehensive and so far I've learned and experienced a lot of different technologies. I had a background in IT but this has let me get into the minutiae of how systems work. Some are systems I've worked with for years that I now understand more fully.

### Linux
The Bash challenge: Automatically generating twenty five numbered files. We learned all the details of the distros and I created and modified the directories and containing files.

![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/linux%200.png) 

![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/linux%201.png)

![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/linux%203.png)

The code itself was simple.

```
#!/bin/bash

#creating 25 empty files with naming convention [name]1 [name]2 [name]3 and so on

touch Kitty{1..25}.txt
```
![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/linux%204.png)

Originally the brief said that each time we run the script it should automatically create the next 25 files in sequence so I've been working on that as a side project.

### Python

Starting to code has always been something I'm interested in. My previous role was involved in the internal development of company software and tools so I have some experience tangential to development environments.

I first pseudo coded the following to separate out the character strings and print them to seperate files. Then wrote the code itself. 

```
#Print and count stripInsulin
stripInsulin="malwmrllpllallalwgpdpaaafvnqhlcgshlvealylvcgergffytpktrreaedlqvgqvelgggpgagslqplalegslqkrgiveqcctsicslyqlenycn"
print(stripInsulin)

#Count the number of characters
length=len(stripInsulin)
print(length)

#extract first 24 characters
lsinsulin_seq=stripInsulin[:24]
print(lsinsulin_seq)
length_lins=len(lsinsulin_seq)
print(length_lins)

#extract character 25-54
binsulin_seq=stripInsulin[24:54]
print(binsulin_seq)
length_bins=len(binsulin_seq)
print(length_bins)

#extract character 55-89
cinsulin_seq=stripInsulin[54:89]
print(cinsulin_seq)
length_cins=len(cinsulin_seq)
print(length_cins)

#extract character 90-110
ainsulin_seq=stripInsulin[89:110]
print(ainsulin_seq)
length_ains=len(ainsulin_seq)
print(length_ains)

#print lsinsulin_seq to txt
with open("lsinsulin_seq_clean.txt", "w") as text_file:
    print(f"{lsinsulin_seq}", file=text_file)
    
#print binsulin_seq to txt
with open("binsulin_seq_clean.txt", "w") as text_file:
    print(f"{binsulin_seq}", file=text_file)
    
#print cinsulin_seq to txt
with open("cinsulin_seq_clean.txt", "w") as text_file:
    print(f"{cinsulin_seq}", file=text_file)
    
#print ainsulin_seq to txt
with open("ainsulin_seq_clean.txt", "w") as text_file:
    print(f"{ainsulin_seq}", file=text_file)
    
```

### Security and Social Engineering

Part of my previous role was also training and guarding against social engineering attacks and working with password policies using Windows Azure and AD. I was very interested in the security group training and the ease with which you can gather information. I'd be interesting in expanding my knowledge in this area.

### Networking

I have experience with networking that I've expanded on in this course. I've helped to maintain and troubleshoot networks at multiple office locations. 

### Databases

I'd be very interested to advancing my relational and nonrelational database knowledge. Prior to this I'd worked with CSVs updating databases within internal systems, but it was using a UI. This has given me information on the minutae. I'm happy to have expanded my experience using CSV files and learning how to read and write them using Python.

![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/reading%20and%20writing%20CSV%20files.PNG)

[Review Quiz Results](https://realpython.com/quizzes/python-csv/results/?t=eyJjIjo3LCJuIjo3LCJxIjozNCwic2lnIjoid2FsYWpfKDY4OzZKK3hQJnZYM3Y-YGZPcXdeOXdiMX1YIUZWODxSeSIsInQiOjI5NywidiI6M30=)

### Web Design

I am still very interested in learning HTML and CSS for the purpose of web design. I have used basic commands before on personal webpages but would like to gather more in depth experience in order to build more sophisticated pages and build my own portfolio. You can see some of my knowledge in play in the [Online-CV](https://kit-tea.github.io/online-cv/)

# Experience

## IT Administrator at Ian Williams Ltd. Jul 2017-Oct 2020

- I am a former helpdesk operator and ITIL certified. I ran an internal helpdesk in my most recent position with Ian Williams. We dealt with all of the first line trouble-shooting as well as hardware estate management and networking tools and equipment management. Clear communication with end users was always maintained.
- Departmental billing was my responsibility, I managed the registered report and the invoicing for IT. I pursued outstanding credits and corrected invoices, requesting corrections where necessary.
-   Auditing experience maintaining internal accounts and looking for gaps in data. Digitizing information that had only been hardcopy.
-   Managing root users via CSV exports
-   Minuting and running Change Advisory Board meetings for our internal software development team. 
-   Reviewing and approving RFCs for implementation.

## Administrative Temp Oct 2016-Jul 2017

- Mostly reception roles and front of house. I was able to further develop my communication and professional interpersonal skills.
- Developed a familiarity with various intranet services and other mainstream programs like Office suites. 
- Developed flexible, transferrable administrative and communication skills; temping of any sort demands adaptability, a willingness to learn, and the ability to take on individual company procedures, whilst maintaining excellent team and customer service skills.

## Freelance Copy Editor Oct 2016-Jul 2017

- For a short period I completed copyediting work for individual clients. It is a great way to develop literary comprehension skills and a keen eye for detail.
- I proofread content for spelling and grammar errors.
- Freelancing also provided opportunities to self-motivate and manage my own time.

## Education

![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/swansea-university-2017.en.png) ![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/restart%20image.jpg)

- Amazon Re/Start Cloud Computing 			          		   TechTalent Bristol Cohort
- 2014-2016: MA, English Literature                      Swansea University
- 2010-2013: BA, English Literature & Creative Writing   Swansea University

## Skills

-	ITIL Foundation qualification
-	Holder of a full, clean drivers license 
-	Customer Service
-	Team / Collaborative Working 
-	Communication - Written & Verbal
-	Organisation - Personal & Event-Based
-	Social Media Management 

## Contact
![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/iconmonstr-github-1-48.png) [GitHub](https://github.com/Kit-tea)

![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/iconmonstr-linkedin-2-48.png) [LinkedIn](https://www.linkedin.com/in/kitty-nicholas-3290821b7/)

![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/UpdatestoREADME/img/iconmonstr-download-2-48.png) [Online CV](https://kit-tea.github.io/online-cv/)

![Image](https://raw.githubusercontent.com/Kit-tea/kit-tea.github.io/ead34605076404ea87e9932af8b6bba8f3a2f8bf/img/iconmonstr-cv-3-48.png) [CV Download](url)

