# Assignment-2
shell script to read in all lines of the attached email_address.txt file, identify the invalid email address and print out all valid email-address and invalid email-address.

Rules:
1. Only letters (a-z), number(0-9) and periods(.) is allowed
2.Username cannot contain consecutive periods (.)
3. Username 8 or more characters and must contain one alphabetic character
4. No whitespaces are allowed
5. The last letter of your username should be ascii letter(a-z) or number(0-9)
6. Capital letters are not allowed


Content from email_address.txt

WWrite a temail@example.com
firstname.lastname@example.com
email@subdomain.example.com
firstname+lastname@example.com
email@123.123.123.123
email@[123.123.123.123]
"email"@example.com
1234567890@example.com
email@example-one.com
_______@example.com
email@example.name
email@example.museum
email@example.co.jp
firstname-lastname@example.com
much.”more\ unusual”@example.com
very.unusual.”@”.unusual.com@example.com
very.”(),:;<>[]”.VERY.”very@\\ "very”.unusual@strange.example.com
plainaddress
#@%^%#$@#$@#.com
@example.com
Joe Smith <email@example.com>
email.example.com
email@example@example.com
.email@example.com
email.@example.com
email..email@example.com
あいうえお@example.com
email@example.com (Joe Smith)
email@example
email@-example.com
email@example.web
email@111.222.333.44444
email@example..com
Abc..123@example.com
”(),:;<>[\]@example.com
just”not”right@example.com
this\ is"really"not\allowed@example.com
