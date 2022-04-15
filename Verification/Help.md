# Verification
| Slash Command                | Description                                                                                                                      | Usage                                      | Example                                                                                               | Required? | Default                             |
|------------------------------|----------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------|-------------------------------------------------------------------------------------------------------|-----------|-------------------------------------|
| /verification-type           | Sets if the verification system should be an age verification or a normal verification.                                          | /verification-type [True/False]            | /verification-type age:true                                                                           | False     | Normal Verification                 |
| /verification-welcometype    | Sets if the welcome message should be an embedded message or a normal message.                                                   | /verification-welcometype [True/False]     | /verification-welcometype embed:True                                                                  | False     | Embed Message                       |
| /verification-welcomemessage | Sets the welcome message to send to your main channel. **Welcome messages for embed type will be sent in an embed description!** | /verification-welcomemessage [Description] | /verification-welcomemessage description:Welcome to the server {user.mention}! Please get some roles. | False     | Welcome to the server @Salem💗#3327! |
| /verification-requirement    | Sets the server requirements that users need to follow in order to enter the server.                                             | /verification-requirement [Description]    | /verification-requirement description:Please make sure to follow Discord's TOS!                       | False     | No requirement is set               |
| /verify                      | Verify the mention user. **Only works in a verification channel!**                                                               | /verify [Target User]                      | /verify user:Salem💗#3327                                                                              | True      | Not Verified                        |

# Message Help

When setting up a message, you will probably want something to mention a user in it. Under this message will be a set of tags you can use in a message.

## Tags

- {user.mention} | Mentions the user. **E.g** • @Salem💗#3327
- {user.tag} | Sends the username and tag of the user. **E.g** • Salem💗#3327
- {user.id} | Sends the id of the user. **E.g** • 515989471645401088
- {user.name} | Sends the username of a user. **E.g** • Salem💗

# Setting up channels

When setting up your channel you have to use `/set-channel`. For verification to work you need to setup your main channel & panel.

# Setting up roles

When setting up roles, you can use `/set-role`. This will allow you to setup the target role for the server. Verification requires the following:
- Gatekeeper
- Moderator
- Admin
- Member
If you use the age verification this is what is required:
- Under 18
- Over 18
