# Auto-Mailer
 Link to the Demo :- https://drive.google.com/file/d/1gwPpOK0vcHQ3CSvKmINRhU3qRVsOT1KQ/view?usp=drive_link
## Introduction
<h4>
   This a Node.js based app that is able to respond to emails sent to your Gmail mailbox while you don't have an access to your email or you are unavailable to respond.
</h4>
<h2>Method</h2>
To build this application I had to use express library along with googleapis and gaooglecloud localauth modules and built it and deployed it using node.js. With the help of Gmail API provided by google cloud console I was able to get the access to the editing and reading rights of any mail id who avail the service of the app. I then had to generate oAuth2 credentials and with the help of that credentials I was able to make the API call. Once that was done we just had to seperate the undread mail after reading mailbox and tagging them into a different label and reply to all the senders.

<h2>Key Features</h2>
- The app identifies and isolate the email threads in which no prior email has been sent by you.
- It then sends appropriate reply to the sender that can be decided by us.
- After sending the reply, the email is tagged with a label in Gmail.

## 📲 To run this project

- Clone(fork) this repository
- Open the Project Directory in a code editor preferably VsCode.
- Enter the below commands one by one
- npm install (to install any missed dependency)
- npm install express
- npm install googleapis
- npm install @google-cloud/local-auth
- npm install nodemon
- npm run dev (To finally run the project)
- Wait for few seconds, it will start running on your local machine.
