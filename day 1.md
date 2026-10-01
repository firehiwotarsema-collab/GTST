Linux is not an OS  its just a *Kerner *
Kerner is a code or a Programme used to meet your hardware  and your software
in 1969 Unix was created by ken thrompson and dennis ritchie  but it wasnt cheap and open source
then linus torvalds created LInux kerner 
then again richard stallman came up with GNU projecct so he cooporated with linus and created GNU Linux togather. GNU Linux is now operating system.


<h1> shell </h1>
is a command line interprater between karnel and user. karenel understands only binary number

<h1> types of shells </h1>
A. Sh    B. BASH    C. ZSH     D. FISH
( they differ by coloring  comand compition .....)

operating system contains
1. kernel
2. softwares
3. desktop environment
4. file extensions 
5. window manager
<H1> TYPES OF DESKTOP ENVIRONMENT ON LINUX</H1>
1.mate
2 . gnome
3 . KDE plasma ( looks like windows 10 )
4 .  XFCE  

why Linux
1, its fast 
2, most used ( many technologies  are based on Linux based operation )
 3 . over 600 active linux distors 
  4. most hacking tools run on linux 
  5. most secured os 
Linux distributions 
1 Linux kernel 
2 packages ( GNU )
3 package manager 
4  desktop UI 

the distros 
Debian kali linux 
        ubantu 
          parrot 
  Arch   black arch 
        
         garuda
 ferdora
 redhat
 gentoo
 android


<H1>DAY 5 </H2>
Oveerview of kali linux
linux shell
linux command basic
multiple command executions
text manipulation with linux


Overview of kali linux
preveously known as backtruck

your linux can have multiple desktop environments

option : additional settings they take
arguments: diffrent inputs to have output

command is small programs that do one task well


tilda is home directory
tree : lists file like a branch
ls : lists all the file
ls-l : extra information about the files.
ls-a : shows hidden files
ls-R : recurse. list but explore each folder
ls-foldername : shows detail about the folder.
you can run multiple options in a command 
cd ( change directory) : change directory 
cd / : root directory which our linux os needs to run (files)
cd : home directory
cd .. : back 1x
cd../.. : back 2x
cd " folder name " : if the folder has a space
pwd : to print the path



DAY 6 LINUX FOR USER 

echo : used to dispplay line of test/string that are passed as an argument

output redirecting 
you  can write output of anycommand into files 
todo this we will use > sign 
echo text >fie.text
echo text >> file.text : add new content to the exisiting file ( > erase the first outcome , >> append )

CAT : shows what s in the file 
LESS  :  same as cat but displays as another text editor( to go back press Q) 
HEAD / TAIL   : same as cat but displays only 10 lines of the file 
TAIL : starts from the bottom to the 10 up.
single clote ( file with a space on it)

CAT option (  -n ) shows the line 

TOUCH : create file without content in it
mkdir : make directory 
mkdir -p : create folde in a folder
ex. mkdir -
ppppppppppppppppppPpppmentaPabrsh/abigiya 



how to create file : echo 

clear : clear the mess not the work
cd home directory 
clear short cut : contol l 
rm( remove) : to delete file and folder
rm-r : delete the file in tthe folder
rm-i : for prompte 
rm-f : force the undelatable force.
cp : copy folder
move : 
example : cp my.txt dirl
examole : mv my.text dir2
have to use recurse to copy the folder with files. 
ex. c

astric : all folder


grep : 
wc : how many word , bite , character
exp wc grape.txt
wc-l : line
wc-c : bite
multiple command execution
using 3 methods 
and ( &&) : 2 command. run if both works only
or ( || ) : if one works it will run
piping ( | ): the output of the firist as the imput for the next one.

sed ( stream editor)
to replace  a teext
processses files line by line 
common use
     text subistitutions and replacement
      deleting or selecting specific line
      text maipulation
      info gathering or penetration testing
      
ex. 's/nathan/minte'
awk
pattern scanniing and data extraction in structured text.
features 
1. process line  by line 
2. allow field  based pattern matching
3. supports complex pattern matcing
4. 

awk pattern : cat awk.txt | awk -F " ," '/6/ ' { PRINT $2}
 grape atni


DAY 7 further on linux
total grade awk .  awk -F',' /science/  { total += $3 } END  {print   'total grade 'total }' 

linux file hierarchy
file system ... directory structure that the os uses
root directory is the operating file system for linux
cd/ : root directory

1. root directory
2. bin : command folder
3. /boot : boot lemareg mintekembet filoch
4. /dev : include terminal devices , usb or any device
5. /etc : configration requaired by all program. start up and shutdown.
6. /home directory : for all users to store their personal files
7. /lib : essential for binaries in /bin & /sbin
8. /media : all the removable devices file is saved in media
9. /mnt : to create temporary file or directory  ( only root user can do that by the way)
10. /opt : what you install softwares for your self is saved in opt
11. /sbin : commands but both the normal and root user cant run only the root user can run it
12. /tmp : like mnt but normal user can also run  it 
13. /usr : to give permission to share a file  and commands.
<h1> text editors </h1>
for text prossesing

1 . VIM used on unix ( vi is its old name ) ...its complex , very pawerfull
it has mainly modes. it runs on normal mode
 1.1. normal mode
 1.2 . insert mode ( i on keyboard)
  1.3 . command mode ( esc key ) : save , save and quit , force quit , force save , undp , execute bash commands
  (  : q + enter to quit  ) force ( : wq! + enter force = !)
undo { : undo + enter or :u }
bash command [ :%!]
1.4 visoual mode : to select and manipulate blocks of txt

2. nano : nano is always there.its gnu nano

