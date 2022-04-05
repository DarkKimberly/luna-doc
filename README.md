# Verification
| Slash Command | Description | Usage | Example | Required? | Default |
|---|---|---|---|---|---|
| /verification-panel | Creates a panel for the verification system. | /verification-panel /verification-panel [Target Channel] | /verification-panel channel:#get-verified | True | Disabled |
| /verification-type | Sets if the verification system should be an age verification or a normal verification. | /verification-type [True/False] | /verification-type age:true | False | Normal Verification |
| /verification-gatekeeper | Sets the role to remove after verifying a user. | /verification-gatekeeper [Target Role] | /verification-gatekeeper role:@New User | True | Role is not set |
| /verification-member | Sets the member role to be given after verifying a user. | /verification-member [Target Role] | /verification-member role:@Member | True | Role is not set |
| /verification-under18 | Sets the under 18 role to be given after verifying a user. **Only required if verification type is set to age verification!** | /verification-under18 [Target Role] | /verification-under18 role:@Under 18 | True | Role is not set |
| /verification-over18 | Sets the over 18 role to be given after verifying a user. **Only required if verification type is set to age verification!** | /verification-over18 [Target Role] | /verification-over18 role:@Over 18 | True | Role is not set |
| /verification-moderator | Sets the moderator role that will give access to moderation panel. | /verification-moderator [Target Role] | /verification-moderator role:@Moderator | True | Role is not set |
| /verification-admin | Sets the admin role that will be given access to the verification administration panel. | /verification-admin [Target Role] | /verification-admin role:@Admin | True | Role is not set |
| /verification-welcometype | Sets if the welcome message should be an embedded message or a normal message. | /verification-welcometype [True/False] | /verification-welcometype embed:True | False | Embed Message |
| /verification-welcomerole | Sets the welcome role to mention outside the embed welcome message when a user is verified. **Only required if welcome type is set to embed!** | /verification-welcomerole [Target Role] | /verification-welcomerole role:@Welcome Ping | False | Role is not set |
