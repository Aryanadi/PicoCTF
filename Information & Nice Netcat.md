# PicoCTF

Link https://youtu.be/oQnKQ5dH1ik

Information:

$ wget https://mercury.picoctf.net/static/e5825f58ef798fdd1af3f6013592a971/cat.jpg

$ ls

$ exiftool cat.jpg

$ exiftool cat.jpg | grep License | sed -e 's/.*: //'

$ exiftool cat.jpg | grep License | sed -e 's/.*: //' | base64 -d

Or you can use http://rumkin.com/tools/cipher/base64.php to compare and match the flag

You'll get the flag!

![Information   Nice NetCat](https://user-images.githubusercontent.com/67795345/155937483-9b6d80b6-d6a2-48b6-97e4-61b85383bfdc.jpeg)

![Information   Nice NetCat-2](https://user-images.githubusercontent.com/67795345/155937535-4a77033b-5d62-47d4-ad7e-108e5e5e826b.jpeg)




Nice Netcat:

$ nc mercury.picoctf.net 21135

You 'll get a bunch of ASCII numbers. Copy it and...

Paste the result at https://www.duplichecker.com/ascii-to-text.php

You'll get the Flag! 

![Information   Nice NetCat-1](https://user-images.githubusercontent.com/67795345/155938367-9d4c07ca-7c0e-4966-b330-4debe2fce140.jpeg)

Best luck!
