# PythonPasswordChecker
This code allows you to check your password whether it has been hacked before!

On your terminal || bash write the following after git clone:

python checkmypass.py your_password_here

**REPLACE your password on your_password_here

# How it works?!
To avoid we really put our REAL PASSWORD online to check the safeness 

(** we dont know how many computers our password will be passed through before it really gets checked)

The code will turn your password to the hash - sha1 format and only send the first 5 characters to the API 

Later on, the matched results will all be rendered back to our machine and 

further does the matching process with the tail ( the rest of the hash sha1 code of your password )

# The API used

https://haveibeenpwned.com/
