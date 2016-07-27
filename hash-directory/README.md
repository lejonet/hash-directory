Usage
=====
`hash-directory.py <directory to scan for files to hash> <where to create directory that will hold the hashes>`

Example
=====
./hash-directory.py /tmp /home/tmp

It will enumerate all the files, recursively, in /tmp and replicate the directory hierarchy in /home/tmp and place a file with the name `_<filename>` at the same place in the hierarchy as it finds it, but the content will be the hash of the first 4MB of the file