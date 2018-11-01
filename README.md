# Just-a-repo

OUTPUT1="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5)" ; echo $OUTPUT1 ; echo "is the character A ; alias $OUTPUT1="echo "a" >> file.txt"
OUTPUT2="$(</dev/urandom tr -dc 'A-Za-z0-9' | head -c 5)" ; echo $OUTPUT2 ; echo "is the character B" ; alias $OUTPUT2="echo "b" >> file.txt"
#To change the length of the characters generated, change the number in " head -c 5 "

#This is possible to use but does not funtion correctly yet
#</dev/urandom tr -dc 'A-Za-z0-9!"#$%&'\''()*+,-./:;<=>?@[\]^_`{|}~' | head -c 13  ; echo
