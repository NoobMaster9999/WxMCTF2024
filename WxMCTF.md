# Misc 3: Firstgrep

In this challenge, we are provided with a folder, which contains 10 folders, each of these folders contain 10 more folders and each of these folders include 10 text files. Knowing that the challenge name is taking about "grep", we can assume that in one of these text files is the flag. We can use the command -

`grep -R "wxmctf{"`

Grep can search for patterns inside a file, or a directory based on the user agruments. `-R` is an argument which means recursive. That is, look in every single file from the current directory onwards. We use the format "wxmctf{" to tell grep what to look for.

And we get our output as:
`SJZIQZ/DJ9YIL/DLCTU6.txt:wxmctf{Wha7_W0uLD_w3_6e_w17HouT_Gr3P}` This means that the flag is in `SJZIQZ/DJ9YIL/DLCTU6.txt` and the flag is `wxmctf{Wha7_W0uLD_w3_6e_w17HouT_Gr3P}`.

# Flag: wxmctf{Wha7_W0uLD_w3_6e_w17HouT_Gr3P}
