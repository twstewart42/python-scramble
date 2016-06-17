# python-scramble

This uses a very simply cipher list to translate each letter of a text file into a list of numbers, and is also able to de-scramable the cipher to translate back to English. If you understand that arrays start at 0, it is a very simply cipher, where the number at the index of the character matched within the array is used as the key for each character in the return file.

<pre>
&gt;dir
README.txt scramble.py
&gt;python scramble.py
Do you want to [S]cramble or [D]escramble? S
name of file to scramble: README.txt
Try to crack the very simple code without using the descrambler - scramble.py. Have fun!
['T', 'r', 'y', ' ', 't', 'o', ' ', 'c', 'r', 'a', 'c', 'k', ' ', 't', 'h', 'e', ' ', 'v', 'e', 'r', 'y', ' ', 's', 'i', 'm', 'p', 'l', 'e', ' ', 'c', 'o', 'd', 'e', ' ', 'w', 'i', 't', 'h', 'o', 'u', 't', ' ', 'u', 's', 'i', 'n', 'g', ' ', 't', 'h', 'e', ' ', 'd', 'e', 's', 'c', 'r', 'a', 'm', 'b', 'l', 'e', 'r', ' ', '-', ' ', 's', 'c', 'r', 'a', 'm', 'b', 'l', 'e', '.', 'p', 'y', '.', ' ', 'H', 'a', 'v', 'e', ' ', 'f', 'u', 'n', '!']
59 17 24 36 19 14 36 2 17 0 2 10 36 19 7 4 36 21 4 17 24 36 18 8 12 15 11 4 36 2 14 3 4 36 22 8 19 7 14 20 19 36 20 18 8 13 6 36 19 7 4 36 3 4 18 2 17 0 12 1 11 4 17 36 65 36 18 2 17 0 12 1 11 4 38 15 24 38 36 47 0 21 4 36 5 20 13 66
&gt;dir
(scrambled)README.txt README.txt scramble.py
&gt;cat (scrambled)README.txt
59 17 24 36 19 14 36 2 17 0 2 10 36 19 7 4 36 21 4 17 24 36 18 8 12 15 11 4 36 2 14 3 4 36 22 8 19 7 14 20 19 36 20 18 8 13 6 36 19 7 4 36 3 4 18 2 17 0 12 1 11 4 17 36 65 36 18 2 17 0 12 1 11 4 38 15 24 38 36 47 0 21 4 36 5 20 13 66
&gt;python scramble.py
Do you want to [S]cramble or [D]escramble? D
name of the file to descramble: (scrambled)README.txt
secret code: 59 17 24 36 19 14 36 2 17 0 2 10 36 19 7 4 36 21 4 17 24 36 18 8 12 15 11 4 36 2 14 3 4 36 22 8 19 7 14 20 19 36 20 18 8 13 6 36 19 7 4 36 3 4 18 2 17 0 12 1 11 4 17 36 65 36 18 2 17 0 12 1 11 4 38 15 24 38 36 47 0 21 4 36 5 20 13 66
Try to crack the very simple code without using the descrambler - scramble.py. Have fun!

</pre>
