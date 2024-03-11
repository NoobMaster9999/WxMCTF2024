# Compiler

Description: Come check out this python compiler I made! Just don't look too far into it...

# Solution

Looking at the source code provided, the flag is definied in the Dockerfile like this:
`ENV FLAG=wxmctf{dummy_flag}`. 

We can read the Dockerfile on the server by using: `print(open("Dockerfile").read())` to get the flag!

# Flag: wxmctf{ok4Y_M4y8e_I_5K1mpED_@_bit}
