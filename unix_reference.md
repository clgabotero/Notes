##Unix Reference
* General structure: (command) (operator) (argument)
* Token Reference
. = location for current working directory
.. = location home directory (next directory up)
~ = location for home directory
^c = sends interrupt signal to current process
^d = send end-of-file character
^z = send sleep signal to current process
& = send command to background
| = pipes output of one command to another; connects two or more commands together
">" = redirects output to file

* Command Reference
bg = send a sleeping process to background
cat

  cat > file = creates file and waits for keyboard; to end process, use ^d
  cat file = streams file contents to STDOUT (terminal)
  cat a b c > all = concatenate files a, b, c to single file all while maintaining original files new file will have the contents of the files it is made up of

cd = changes directory; must specify path
chmod = change file permissions
cp = make a copy of a file

  cp file1 file2 = copies file1 and changes name o file2 (in current directory)
  cp file Directory/Subdirectory = copies file from current directory to designated directory
grep

  grep = processes text line by line and prints any line that match; grep option "pattern" file
  grep -c "pattern" file = finds, counts and prints the count for the lines with the matching pattern in the designated file
gzip = compresses a file
gunzip = uncompresses file
head

  head file = displays first ten lines of a file
  head -# file = displays first designated number of lines from file
history = displays recent commands you typed
kill = kills process with designated id number
less = lets you page through a file
ls

  ls = lists current directory
  ls -l = lists file with details
  ls -lta = sort listed files by time instead of name
  ls -ltaF = above and list file type symbols
manual = manual for designated command
mkdir = creates directory with designated file name
mv

  mv file1 file2 = _renames_ file1 to file2
  mv file1 Directory = _moves_ file1 to Directory
nano = opens nano text file editor (alternatively, use vim)
passwd = changes password for pc
pwd = prints working directory
ps = shows current processes
rm = removes file (be careful when using)
rmdir = removes designated directory
sort

  sort file = sorts file numerically by first column
  sort -n file = sorts file numerically by first column
  sort -k file # = sorts file alphabetically by column (denoted number)
tail = displays last ten lines of a file
tar

  tar -cf = create a compressed tar-ball (-z to compress)
  tar -xf = decompress a tar-ball
top = displays all processes running on your system
wc

  wc = counts the lines, words, and characters in a file; wc (option) file
  readout: numberoflines numberofwords numberofcharacters
  wc -l = prints the new line counts
