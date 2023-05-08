Download Link: https://assignmentchef.com/product/solved-programming-assignment-1-password-checker
<br>
In this project you are going to write an assembly language program to check a user-supplied password for strength.  Most modern definitions of a strong password requires that the password has at least one character from each of the following sets:  a lower case character a-z; an uppercase character A-Z; a number 0-9; and a character from the set of special characters:  &lt;&gt;<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="18273958">[email protected]</a>#$%^&amp;*()+{}




In addition to the requirement that the password contain at least one character from each of the four groups, the password must be 8 to 20 characters in length.




Your program has the following requirements:

<ol>

 <li>Obtain a password from the user. As the user is typing the password, place a “*” on the screen for each character typed.</li>

 <li>Check the password to verify it meets the criteria as described above.</li>

 <li>If the password meets the criteria, output the message “password meets requirements” on the screen. If not, state the requirement that is not met: no lowercase character, no uppercase character, no lowercase character, no numeric character, no special character, too short, or too long. Note that it is possible for more than one criteria to not be met.</li>

 <li>Ask the user if they wish to run the program again (accept either a “Y” or “y” for a possitive response, “N” or “n” for a negative response). If yes, then loop back to step 1.  If not, exit.  If the user response is anything except “Y”, “y”, “N”, or “n”, ask the user again.</li>

</ol>




Example interaction would be:




Please enter a password:  *********




Your password is lacking a special character

Your password is lacking an uppercase character




Do you wish to try again (y/n)? Y

Please enter a password:  *********




Your password is successful!




Do you wish to try again (y/n)? n

(exit)




Deliverables:  submit a hard copy of your source code.  Email the code and screen shots showing successful assembly, linking, and execution of your program to your instructor.