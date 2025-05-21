# OverTheWire
Online based Linux War CTF

OverTheWire Commands 
- man <command> (to know the purpose of the command) press q to quit.
- help <X> command (help cd)

    * USERNAMES are somegame0, somegame1, ...
    * Most LEVELS are stored in /somegame/.
    * PASSWORDS for each level are stored in /etc/somegame_pass/.

New Commands:
ls -alps
find . -type f | xargs file
find . -type f size 1033c ! -executable

login id :
ssh bandit_@bandit.labs.overthewire.org -p 2220

****
- Lvl 0   : bandit0
- Lvl 1   : ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
- Lvl 2   : 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
- Lvl 3   : MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
- Lvl 4   : 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ  - find . -type f | xargs file
- Lvl 5   : 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw  - find . -type f size 1033c ! -executable
- Lvl 6   : HWasnPhtq9AVKe0dmk45nxy20cvUa6EG  - find / -type f -user bandit7 -group bandit6 -size 33c
- Lvl 7   : morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj  - grep "milimoth" data.txt
- Lvl 8   : dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc  - sort data.txt | uniq -u
- Lvl 9   : 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM  - strings data.txt | grep -oP '=+\K[^=]+' | sort | uniq -u
- Lvl 10  : FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey  - base64 -d data.txt
- Lvl 11  : dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr  - cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
- Lvl 12  : 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4  - 
