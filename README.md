# SSH-login-brute-forcing

-This script is an example of how one could automate the process of guessing an SSH server's password.
-The script uses a list of commonly used passwords stored in a text file named "ssh-common-passwords.txt"
-The script attempts to connect to the SSH server running on the localhost with the specified username and each of the passwords in the list, one by one.
-If the script is able to successfully connect to the SSH server, it prints the successful password and exits the loop.
-If the script is unable to connect to the server with a certain password, it moves on to the next password in the list.
-The script uses the 'paramiko' library to handle the SSH connection and the 'pwn' library for additional functionality
-The variable 'attempts' keeps track of the number of attempts made.
-It is important to note that such script should not be used for illegal activities as hacking is illegal and punishable by law.
-Instead, use this script to test your own SSH server's security and make sure your own password is not on that list!
-Who knows, you might even find your own password in the list and be able to change it to something more secure.
