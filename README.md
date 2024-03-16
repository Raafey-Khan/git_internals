1.`tree .git `: this will help us to see the .git folder in a tree like structure in the terminal

The moment you added README.md
git created a 40 digit hexadecimal shavan hash
the first two hash becomes the folder of 
which it contains the file the a directory in the 
object directory.

i just checkedout, that when i do git adds
it's stores in the object folder
and in the object folder the first 2 letter's 
are the KEY and the other id's are Value.

key:value
01: 2224423245232111221
⬆️           ⬆️ value is blob (binary object)
shawan
hash
--------------------------------------------------------
Total: 40 (character's)                                 |
first two key(directory)                                |
rest 38 are the binary large object jibrish value(blob) |
                                                        |
these becomes key:value pairs                           |
--------------------------------------------------------
for seeing these cause cat command will make visible
the blob that is not readable to humans
so git provides their own command for this

called git cat-file -p <two-digit-key> <38value>
git cat-file -p 7882f86e79f1b94eb350714b82ed5e1d83df64ea
<<<<<<< HEAD
========

commit's are unique because they comes in different
timestamp
so even if your writing the same commit -m 
it still assigns it to a different sha-1 hash


after a first commit whatever commit will be done
are also points to the parent commit and their parent id
that's how detailed-tree works.
>>>>>>> master
