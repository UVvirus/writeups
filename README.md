supa secure

225 points

This time it’s a little tricker to crack the password: 19d14c463333a41a1538dbf9eb76aadf

You might also need this for something: cyctf

Are you up for the challenge?

-----------------------------------------------------------------------------------------------------------
1)First step is to identify the type of hash. For that i used this website
https://www.tunnelsup.com/hash-analyzer/

From this website i found that this is an MD5 hash.

Now our goal is to decrypt this hash. To decrypt this hash i used
https://www.md5online.org/md5-decrypt.html

Paste the hash inside the box and hit the Decrypt button.

You'll be greeted with this:cyctfilovesalt

Enclose this value within the curly braces. That is the flag.


Flag: cyctf{ilovesalt}

Happy Hacking!!😇
