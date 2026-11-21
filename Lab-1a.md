For this lesson I learned how to install Oracle VirtualBox 7.2.22 on my windows computer and created a virtual machine Ubuntu. Virtualbox allows Ubuntu to run as a guest operating system while I still retain windows as my host operating system. 
<img width="811" height="400" alt="Screenshot 2026-11-22 030520" src="https://github.com/user-attachments/assets/3c0d0f7f-c752-40d1-9ff3-7f9a54ccc7eb" />
I set up 8GB for memory, 4 virtual CPUs, and 40GB of virtual space, I also went through the interactive installer and created a local account and selected singapore as the time zone
I encountered and issue with virtualization which I will discuss later. I managed to succesfully set up the virtual machine, and learnt by process how to install Ubuntu using an ISO image and allocate hardware resources for it.
I also practiced using basic linux commands. I learnt to use whoami,hostname,lsb_release -a which showed my username,hostname and operating system
<img width="819" height="582" alt="Screenshot 2026-11-22 033913" src="https://github.com/user-attachments/assets/b340d55c-3381-4d48-b0dd-322fa7386576" />

I also learnt other commands like pwd, ls, ls -1,cd,cd.. , cd ~, mkdir ~p, touch practice.txt. Learning that pwd displays the full path of the current working directory, ls lists directory contents, ls -1 displays detailed lists of ownership and file size,
cd changes the current working directory, cd.. moves up one directory from the current location, cd ~ returns to my home directory, mkdir -p creates directories  and touch practice,txt creates an empty file when that filename does not exist.
Through these things i learned i also created a practice.txt and directory /home/jay/isea-labs/lab02
<img width="816" height="570" alt="Screenshot 2026-11-22 035151" src="https://github.com/user-attachments/assets/8c1bdcaf-944d-44ae-b143-d770a1c9870a" />
<img width="807" height="493" alt="Screenshot 2026-11-22 040121" src="https://github.com/user-attachments/assets/79a29642-0079-46bc-8748-550615257637" />

Also learnt about /home which contains users personal directories, /etc which contains system wide config files, /var which contains data that changes during system operation and also explored linux manual pages via man ls

I encountered a challenge while setting up my virtual machine
<img width="1276" height="746" alt="Screenshot 2026-11-22 030718" src="https://github.com/user-attachments/assets/4dfe7c2d-99af-4ff0-bfc2-eb18593ac32a" />
I had virtualization disabled upon inspecting my task manager and performance tab and looking at my cpu. I had to go in to the BIOS to enable SVM mode so I could install Ubuntu. I learnt that the hosts computer settings matters on whether a virtual machine can run

Overall, I still feel new to Ubuntu and running linux command and need more practice with them cause I have never touched any of this beforehand. I am not that confident so far as because these command names sometimes feel so dissociated with real words,it becomes
like a second language and having to learn that. But by doing this so far I also can see the implications that a virtual machine can help in industry specific scenarios particularly in cybersecurity where they can use these virtual machines without affecting their 
host computer and also allowing various operating system to run concurrently. If I were to set up another VM, I would ensure that I check if virtualization in the BIOS is enabled first before trying.




