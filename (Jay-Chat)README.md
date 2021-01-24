To solve this challenge we have to change the magic number headers of the guven .jpg file.
The given file cannot be opened so we use ghex tool on linux

To install ghex we can use sudo apt install ghex

With the help of ghex we can open the .jpg and file and notice a difference in the magic number headers of the given file and the magic number headers given on wikipedia.

There is difference with respect to "FF D9 FF E0"

We change the D9 TO D8 save the changes and reopen it.We will be able to view the flag

<img width="312" alt="amazing" src="https://user-images.githubusercontent.com/76178081/105620113-71bad980-5e1f-11eb-91ce-4c302e094ba3.PNG">


