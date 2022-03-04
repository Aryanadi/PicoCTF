# PicoCTF

Link https://youtu.be/Qw4xgNYxsAo

Download the file in Matryoshka doll challenge and use StegSpy tool to detect the hiding flag

![Ethical Hacker Lab 111 PicoCTF Forensics | Matryoshka doll (using StegSpy V2 1 to detect) FINAL](https://user-images.githubusercontent.com/67795345/156733896-c00e5d4c-ece4-4008-89e9-8ee9c7f34019.jpeg)

Go to picoCTF WebShell

$ wget [copy and paste the link the downloaded file from Matryoshka doll]

$ ls 

$ binwalk -e dolls.jpg

ls

$ cd _doll.jpg.extracted ; ls

$ cd base_images ; ls

$ binwalk -e 2_c.jpg 

$ ls

$ cd _2_c.jpg.extracted ; ls

$ cd base_images ; ls

$ binwalk -e 3_c.jpg

$ ls

$ cd _3_c.jpg.extracted 

$ cd base_images ; ls

$ binwalk -e 4_c.jpg

$ ls

$ cd _4_c.jpg.extracted ; ls

$ cat flag.txt 

You'll see the flag! 

![Ethical Hacker Lab 111 PicoCTF Forensics | Matryoshka doll (using StegSpy V2 1 to detect) FINAL-1](https://user-images.githubusercontent.com/67795345/156736385-dad6d985-c352-42c4-b49b-1ada48a75dc3.jpeg)


Best luck! 













