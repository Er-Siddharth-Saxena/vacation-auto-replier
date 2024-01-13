# vacation-auto-replier

This is a Node.js based app that is able to respond to emails sent to your Gmail mailbox while you’re out on a vacation.

working

The app checks for new emails in a given Gmail ID using gmail id.

The app sends replies to Emails that have no prior replies

💡 The app identify and isolate the email threads in which no prior email has been sent by you. This means that the app only reply to first time email threads sent by others to your mailbox.

The app adds a Label to the email and move the email to the label

💡 After sending the reply, the email gets tagged with a label in Gmail AutoVacationReply. If the label is not created already, it will create it.

The app repeats this sequence of steps 1-3 in random intervals of 45 to 120 seconds
