# shebang1 | Points:125
# This challenge is simple.

1)Login with given credentials
> ssh shebang1@cyberyoddha.baycyber.net -p 1337
>
> password:CYCTF{w3ll_1_gu3$$_b@sh_1s_e@zy}

> Note: Password for this challenge is shebang0's flag

2) Type __ls__ to list the files

3)There is a file called __flag.txt__

4)First i used __cat__ command. But it is not useful

5)So next i used __grep__ command
> command: grep -r "CYCTF"*

> Note:grep is a command-line utility for searching plain-text data sets for lines that match a regular expression. 

6)wow!!! we found the flag
> Flag:CYCTF{w3ll_1_gu3$$_y0u_kn0w_h0w_t0_gr3p}
