# PicoCTF

Link https://youtu.be/pa7kIB51iRw

Wireshark doo doo doo:

Download shark1.pcapng file.

Copy link shark1.pcapng file and paste it to:
$ wget <shark1.pcapng file>

![wget](https://user-images.githubusercontent.com/67795345/156183199-7d4c91e2-071b-47c7-81a5-e24ff1bcfecf.jpeg)

$ ls

Open shark1.pcapng file in Wireshark.

Input http in the filter box of Wireshark and find GET under the Info column. Select it and go to Follow - HTTP Stream that is under Analyze menu.

![http stream](https://user-images.githubusercontent.com/67795345/156183385-c17beef7-8621-49b8-bc20-de1ed2ba9ba3.jpeg)

In HTTP Stream dialog box, copy the phrase Gur synt vf…{ .. } and paste it in ROT13 box, then click ROT13 button. You'll get the flag!

![http stream 2](https://user-images.githubusercontent.com/67795345/156185350-c3688920-ca53-446f-b1c5-73560814e03a.jpeg)

![rot13](https://user-images.githubusercontent.com/67795345/156183731-09a2b3fb-511c-4e86-8993-8e1a458f439e.jpeg)

![flag dududu](https://user-images.githubusercontent.com/67795345/156183931-2e5a6fd0-c9bb-409d-b3a7-7984cccc1130.jpeg)






Wireshark twoo twoo twoo:

Download shark2.pcapng file.

Copy link shark2.pcapng file and paste it to picoCTF WebShell:
$ wget <shark2.pcapng file>

![wget 2](https://user-images.githubusercontent.com/67795345/156183780-321e9d68-75b3-450c-b2f5-b1c635853997.jpeg)

$ ls

$ tshark -nr shark2.pcapng -Y 'dns'

$ tshark -nr shark2.pcapng -Y 'dns' | grep -v '8.8.8.8'

$ tshark -nr shark2.pcapng -Y 'dns' | grep -v '8.8.8.8' | grep -v response

$ tshark -nr shark2.pcapng -Y 'dns' | grep -v '8.8.8.8' | grep -v response | grep local

$ tshark -nr shark2.pcapng -Y 'dns' | grep -v '8.8.8.8' | grep -v response | grep local | awk -e '{print $12}'

$ tshark -nr shark2.pcapng -Y 'dns' | grep -v '8.8.8.8' | grep -v response | grep local | awk -e '{print $12}' | sed -e 's/\'..*//'

$ tshark -nr shark2.pcapng -Y 'dns' | grep -v '8.8.8.8' | grep -v response | grep local | awk -e '{print $12}' | sed -e 's/\'..*//' | base64 -d

![flag tootoo](https://user-images.githubusercontent.com/67795345/156184097-9a907650-3fad-4496-9b45-9499aee9315a.jpeg)

You'll get the flag! 






Glory of Garden:

Download garden file

Open garden file using Hexed.it

![garden hexedit](https://user-images.githubusercontent.com/67795345/156184186-9468b870-89ca-44a7-9347-0fc7a3cbe931.jpeg)

Scroll down to the very bottom and you'll see the flag! 

![flag garden](https://user-images.githubusercontent.com/67795345/156184445-188d27c4-928d-4c56-bacd-ed4de63daa96.jpeg)

Best luck! 
