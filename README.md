
ll
Copyright (C) Microsoft Corporation. Alle Rechte vorbehalten.

Installieren Sie die neueste PowerShell für neue Funktionen und Verbesserungen! https://aka.ms/PSWindows

PS C:\Users\shakt> ls


    Verzeichnis: C:\Users\shakt


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11.01.2024     15:53                .anaconda
d-----        13.01.2024     23:35                .conda
d-----        11.01.2024     15:53                .continuum
d-----        11.01.2024     20:46                .ipython
d-----        11.01.2024     18:37                .jupyter
d-----        13.01.2024     19:16                .matplotlib
d-----        11.01.2024     15:35                .vscode
da----        11.01.2024     20:17                anaconda3
d-r---        11.01.2024     11:19                Contacts
d-r---        13.01.2024     18:57                Desktop
d-r---        11.01.2024     15:52                Documents
dar---        13.01.2024     20:17                Downloads
d-r---        11.01.2024     11:19                Favorites
d-----        13.01.2024     17:03                Ironshakti
d-----        13.01.2024     16:49                lab-bash-1
d-----        13.01.2024     16:54                lab-git
d-r---        11.01.2024     11:19                Links
d-r---        11.01.2024     11:19                Music
dar--l        11.01.2024     20:56                OneDrive
d-r---        11.01.2024     11:19                Pictures
d-r---        11.01.2024     11:19                Saved Games
d-r---        11.01.2024     11:36                Searches
d-r---        11.01.2024     19:11                Videos
-a----        11.01.2024     15:53             25 .condarc


PS C:\Users\shakt> cd Ironshakti
PS C:\Users\shakt\Ironshakti> touch about.txt
touch : Die Benennung "touch" wurde nicht als Name eines Cmdlet, einer Funktion, einer Skriptdatei oder eines
ausführbaren Programms erkannt. Überprüfen Sie die Schreibweise des Namens, oder ob der Pfad korrekt ist (sofern
enthalten), und wiederholen Sie den Vorgang.
In Zeile:1 Zeichen:1
+ touch about.txt
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (touch:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\shakt\Ironshakti> nano about.txt
nano : Die Benennung "nano" wurde nicht als Name eines Cmdlet, einer Funktion, einer Skriptdatei oder eines
ausführbaren Programms erkannt. Überprüfen Sie die Schreibweise des Namens, oder ob der Pfad korrekt ist (sofern
enthalten), und wiederholen Sie den Vorgang.
In Zeile:1 Zeichen:1
+ nano about.txt
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (nano:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\shakt\Ironshakti> mkdir about.txt


    Verzeichnis: C:\Users\shakt\Ironshakti


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        13.01.2024     23:39                about.txt


PS C:\Users\shakt\Ironshakti> ls


    Verzeichnis: C:\Users\shakt\Ironshakti


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        13.01.2024     23:39                about.txt
-a----        13.01.2024     17:03              0 Ironshakti.txt
-a----        13.01.2024     17:02             12 README.md


PS C:\Users\shakt\Ironshakti> touch about.txt
touch : Die Benennung "touch" wurde nicht als Name eines Cmdlet, einer Funktion, einer Skriptdatei oder eines
ausführbaren Programms erkannt. Überprüfen Sie die Schreibweise des Namens, oder ob der Pfad korrekt ist (sofern
enthalten), und wiederholen Sie den Vorgang.
In Zeile:1 Zeichen:1
+ touch about.txt
+ ~~~~~
    + CategoryInfo          : ObjectNotFound: (touch:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\shakt\Ironshakti> ls


    Verzeichnis: C:\Users\shakt\Ironshakti


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        13.01.2024     23:39                about.txt
-a----        13.01.2024     17:03              0 Ironshakti.txt
-a----        13.01.2024     17:02             12 README.md


PS C:\Users\shakt\Ironshakti> echo about.txt
about.txt
PS C:\Users\shakt\Ironshakti> echo Hallo my name is shakti, I am realy happy to join Ironhack. I always want to be a person to have every day to have lost of chalange, and every day become a new day. I realy seeing me as it.
Hallo
my
name
is
shakti
I
am
realy
happy
to
join
Ironhack.
I
always
want
to
be
a
person
to
have
every
day
to
have
lost
of
chalange
and
every
day
become
a
new
day.
I
realy
seeing
me
as
it.
PS C:\Users\shakt\Ironshakti> echo (Hello, my name is Shakti. I am really happy to join Ironhack. I always want to be a person who faces lots of challenges every day, and for whom every day becomes a new day. I really see myself as such.)
In Zeile:1 Zeichen:12
+ echo (Hello, my name is Shakti. I am really happy to join Ironhack. I ...
+            ~
Argument in der Parameterliste fehlt.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : MissingArgument

PS C:\Users\shakt\Ironshakti> cd about.txt
PS C:\Users\shakt\Ironshakti\about.txt> cd ../
PS C:\Users\shakt\Ironshakti> Git Bash about.txt
git: 'Bash' is not a git command. See 'git --help'.

The most similar command is
        stash
PS C:\Users\shakt\Ironshakti> stasch about.txt
stasch : Die Benennung "stasch" wurde nicht als Name eines Cmdlet, einer Funktion, einer
Skriptdatei oder eines ausführbaren Programms erkannt. Überprüfen Sie die Schreibweise des
Namens, oder ob der Pfad korrekt ist (sofern enthalten), und wiederholen Sie den Vorgang.
In Zeile:1 Zeichen:1
+ stasch about.txt
+ ~~~~~~
    + CategoryInfo          : ObjectNotFound: (stasch:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\shakt\Ironshakti> ls


    Verzeichnis: C:\Users\shakt\Ironshakti


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        13.01.2024     23:39                about.txt
-a----        13.01.2024     17:03              0 Ironshakti.txt
-a----        13.01.2024     17:02             12 README.md


PS C:\Users\shakt\Ironshakti> cd ../
PS C:\Users\shakt> ls


    Verzeichnis: C:\Users\shakt


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        11.01.2024     15:53                .anaconda
d-----        13.01.2024     23:57                .conda
d-----        11.01.2024     15:53                .continuum
d-----        11.01.2024     20:46                .ipython
d-----        11.01.2024     18:37                .jupyter
d-----        13.01.2024     19:16                .matplotlib
d-----        11.01.2024     15:35                .vscode
da----        11.01.2024     20:17                anaconda3
d-r---        11.01.2024     11:19                Contacts
d-r---        13.01.2024     18:57                Desktop
d-r---        11.01.2024     15:52                Documents
dar---        13.01.2024     20:17                Downloads
d-r---        11.01.2024     11:19                Favorites
d-----        13.01.2024     23:39                Ironshakti
d-----        13.01.2024     16:49                lab-bash-1
d-----        13.01.2024     16:54                lab-git
d-r---        11.01.2024     11:19                Links
d-r---        11.01.2024     11:19                Music
dar--l        11.01.2024     20:56                OneDrive
d-r---        11.01.2024     11:19                Pictures
d-r---        11.01.2024     11:19                Saved Games
d-r---        11.01.2024     11:36                Searches
d-r---        11.01.2024     19:11                Videos
-a----        11.01.2024     15:53             25 .condarc


PS C:\Users\shakt> git clone https://github.com/ironhack-labs/lab-git.git
fatal: destination path 'lab-git' already exists and is not an empty directory.
PS C:\Users\shakt> cd  lab-git
PS C:\Users\shakt\lab-git> mkdir abot.txt


    Verzeichnis: C:\Users\shakt\lab-git


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        13.01.2024     23:59                abot.txt


PS C:\Users\shakt\lab-git> mkdir about.txt


    Verzeichnis: C:\Users\shakt\lab-git


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        14.01.2024     00:00                about.txt


PS C:\Users\shakt\lab-git> echo about.txt
about.txt
PS C:\Users\shakt\lab-git> echo my name is shakti
my
name
is
shakti
PS C:\Users\shakt\lab-git> echo ('my name is shakti')
my name is shakti
PS C:\Users\shakt\lab-git>
PS C:\Users\shakt\lab-git>  echo(' Hello my name is Shakti .I am really happy to join Ironhack. I always want to be a person who faces lots of challenges every day and for whom every day becomes a new day will always exited' )
 Hello my name is Shakti .I am really happy to join Ironhack. I always want to be a person who faces lots of challenges every day and for whom every day becomes a new day will always exited
PS C:\Users\shakt\lab-git> git commit -m "a txt file added"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'shakt@OmGamGanapatiNa.(none)')
PS C:\Users\shakt\lab-git> push
push : Die Benennung "push" wurde nicht als Name eines Cmdlet, einer Funktion, einer
Skriptdatei oder eines ausführbaren Programms erkannt. Überprüfen Sie die Schreibweise des
Namens, oder ob der Pfad korrekt ist (sofern enthalten), und wiederholen Sie den Vorgang.
In Zeile:1 Zeichen:1
+ push
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (push:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\shakt\lab-git> push shakti
push : Die Benennung "push" wurde nicht als Name eines Cmdlet, einer Funktion, einer
Skriptdatei oder eines ausführbaren Programms erkannt. Überprüfen Sie die Schreibweise des
Namens, oder ob der Pfad korrekt ist (sofern enthalten), und wiederholen Sie den Vorgang.
In Zeile:1 Zeichen:1
+ push shakti
+ ~~~~
    + CategoryInfo          : ObjectNotFound: (push:String) [], CommandNotFoundException
    + FullyQualifiedErrorId : CommandNotFoundException

PS C:\Users\shakt\lab-git> ls


    Verzeichnis: C:\Users\shakt\lab-git


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        13.01.2024     16:54                .github
d-----        13.01.2024     23:59                abot.txt
d-----        14.01.2024     00:00                about.txt
-a----        13.01.2024     16:54           2445 readme.md


PS C:\Users\shakt\lab-git>
PS C:\Users\shakt\lab-git> git commit -m "Add new file"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'shakt@OmGamGanapatiNa.(none)')
PS C:\Users\shakt\lab-git> git config --global user.email "shakti.pandit00@gmail.com"
PS C:\Users\shakt\lab-git> git config --global user.name "Ironshakti"
PS C:\Users\shakt\lab-git> git push origin master
fatal: User cancelled dialog.
Username for 'https://github.com':
Password for 'https://github.com':
remote: No anonymous write access.
fatal: Authentication failed for 'https://github.com/shaktipandit001/lab-git.git/'
PS C:\Users\shakt\lab-git> ls
