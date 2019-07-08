# Grep-Command-To-Extract-Emails
https://rietta.com/blog/2013/10/11/grep-extract-e-mail-addresses-from-a-text-file/

`grep -o '[[:alnum:]+\.\_\-]*@[[:alnum:]+\.\_\-]*' EMAIL_SAMPLES.TXT | sort | uniq -i`

(Recursive)

`grep -ro '[[:alnum:]+\.\_\-]*@[[:alnum:]+\.\_\-]*' EMAIL_SAMPLES.TXT | sort | uniq -i`

(Hide file name)

`grep -rho '[[:alnum:]+\.\_\-]*@[[:alnum:]+\.\_\-]*' EMAIL_SAMPLES.TXT | sort | uniq -i`
