<0> : alias ls="rm *" ==> Creates ann alias with both the name = ls and the value = rm *<==








1. echo "hello $USER" ==> Prints hello user, where user is the current Linux user.










2. export PATH=$PATH:/action ==>Adds /action to the PATH <==






3. echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1)) ==> Counts the number of directories in the PATH<==





4. printenv ==> Lists environment variables <==
