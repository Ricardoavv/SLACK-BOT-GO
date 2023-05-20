# SLACK-BOT-GO
Prerequisite, install go

In order to run the project, you first need to create a module to be able to use the slack API

- go mod init <Module Name>
-go get -u github.com/slack-go/slack

==================================================== ==================================================== ===============

Create a slack account and perform the following steps:

     1. We create a workspace
     2. In the upper left corner is the name of the created workspace, we click on it
     3. We look for the "settings and administration" option, we put the cursor on that option
     4. We look for the option that says "Manage applications" and click
     5. In the upper corner it says "compile", we click
     6. We create an application, we select the option from scratch, we choose the place of work and the
         the name of the application.
     7. A new page is displayed, among the first options offered we select "bot"
     8. Once the above is done, we go to the upper right corner and click on "your apps"
     9. In the "your apps" section, we click on the "generate token" part, select the workplace
     10. We are going to copy and paste the generated token where it says TOKEN
     11. With all steps completed, we go to the chat we created and look in the chat url for the last series of
             characters, in this example it would be: C04S8H5CU7J
         https://app.slack.com/client/T04asdfasdS/C04S8H5CU7J
     12. We paste these characters in the code where it says "CHAT"
     13. In this way the code would be ready, it would only be necessary to run the program and pass the parameters
     14. go run jenkins-notification.go http://localhost SUCCESS 10 test
     15. After running this command with the necessary variables you should send a message in your slack chat
==================================================== ==================================================== ===============

Documentation:

https://pkg.go.dev/github.com/slack-go/slack@v0.12.1#section-readme
