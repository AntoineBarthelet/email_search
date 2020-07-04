# email_search
Goal is to read through entire email set looking for specific headers. In this particular example, we are sorting through spam mails

To reiterate, I want the tool to do a number of things:
•	Find emails with these domains in the headers
•	Export each email to a .pdf
•	Put the following information into a spreadsheet:
o	recipient email address (yours initially)
o	date email was received
o	"from name" (i.e. the name that shows up on the left when you view an email in your inbox)
o	subject line
o	the domain name of the sending address
•	Remove the "spam" tag from the email, therefore moving it out of google's spam folder, which deletes emails automatically after 30 days. These emails must not be automatically deleted
•	Optional: move the email into a separate folder so that it isn't stuck in the recipient's (yours initially) main inbox.
So the two outputs would be
•	a folder with pdfs
•	a spreadsheet with the above information, and
•	removal from the spam folder to avoid automatic deletion
