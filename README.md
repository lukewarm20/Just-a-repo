# Just-a-repo

#This is the funtioning code but be careful. As the script has to remove all aliases as the aliases given for each character is random.
#One liner
alias -a ; OUTPUT1="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5 )" ; echo $OUTPUT1 ; echo "is the character a" ; alias $OUTPUT1="echo "a" >> file.txt" alias -a ; OUTPUT2="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5 )" ; echo $OUTPUT2 ; echo "is the character b" ; alias $OUTPUT2="echo "b" >> file.txt"
#One liner
alias -a ; OUTPUT1="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5 )" ; echo $OUTPUT1 ; echo "is the character a" ; alias $OUTPUT1="echo "a" >> file.txt"
alias -a ; OUTPUT2="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5 )" ; echo $OUTPUT2 ; echo "is the character b" ; alias $OUTPUT2="echo "b" >> file.txt"

OUTPUT1="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5)" ; echo $OUTPUT1 ; echo "is the character A ; alias $OUTPUT1="echo "a" >> file.txt"
OUTPUT2="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5)" ; echo $OUTPUT2 ; echo "is the character B" ; alias $OUTPUT2="echo "b" >> file.txt"
#To change the length of the characters generated, change the number in " head -c 5 "

#This is possible to use but does not funtion correctly yet
#</dev/urandom tr -dc 'A-Za-z0-9!"#$%&'\''()*+,-./:;<=>?@[\]^_`{|}~' | head -c 13  ; echo



unalias -a ; OUTPUT1="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5 )" ; echo $OUTPUT1 ; echo "is the character a" ; alias $OUTPUT1="echo "a" >> file.txt" ; OUTPUT2="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5 )" ; echo $OUTPUT2 ; echo "is the character b" ; alias $OUTPUT2="echo "b" >> file.txt" 


unalias -a ; OUTPUT1="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5 )" ; echo $OUTPUT1 ; echo "is the character a" ; alias $OUTPUT1="echo "a" >> file.txt" ; OUTPUT2="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5 )" ; echo $OUTPUT2 ; echo "is the character b" ; alias $OUTPUT2="echo "b" >> file.txt"



#Run this command for randomized input numbers for characters 
unalias -a ; alias $RANDOM="echo "{a..z}" >> text.txt"
#Run alias to see the numbers associated with the characters

$Full command
unalias -a ; alias $RANDOM="echo "{a..z}" >> text.txt" ; alias $RANDOM="echo "{A..Z}" >> text.txt" ; alias $RANDOM="echo "{0..9}" >> text.txt
