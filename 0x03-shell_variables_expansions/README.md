<0> : alias ls="rm *" ==> Creates ann alias with both the name = ls and the value = rm *<==








1. echo "hello $USER" ==> Prints hello user, where user is the current Linux user.










2. export PATH=$PATH:/action ==>Adds /action to the PATH <==






3. echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) ==> Counts the number of directories in the PATH<==





4. printenv ==> Lists environment variables <==




5. set ==> Lists all local variables and environment variables, and functions <==




6. BEST="School" ==> Creates a new local variable <==




7. export BEST="School" ==> Creates a new global variable <==




8. echo $(($TRUEKNOWLEDGE + 128)) ==> Prints the result of the addition of 128 with the value stored in the environment variable TRUEKNOWLEDGE. <==




9. echo $(($POWER/DIVIDE)) ==> Prints the result of POWER divided by DIVIDE. <==




10. echo $(($BREATH**LOVE)) ==> Displays the result of BREATH to the power LOVE. <==





11. echo "$((2#$BINARY))" ==> Converts a number from base 2 to base 10. <==





12. echo {a..z}{a..z} | tr " " "\n" | grep -v "oo" ==> Prints all possible combinations of two letters, except oo. <==





13. printf "%.2f" $NUM | sort ==> Prints a number with two decimal places. <==





14. printf "%x\n" $DECIMAL ==> Converts a number from base 10 to base 16. <==





15. tr "a-zA-Z" "n-za-mN-ZA-M" ==> Encodes and decodes text using the rot13 encryption. <==





16. cat -n | grep [13579][[:space:]] | tr -s ' ' | cut -f2 ==> Prints every other line from the input, starting with the first line. <==






17. echo $(printf %o $(($((5#$(echo $WATER | tr 'water' '01234'))) + $((5#$(echo $STIR | tr 'stir.' '01234'))))) | tr '01234567' 'bestchol') ==> Adds the two numbers stored in the environment variables WATER and STIR and prints the result. <==





