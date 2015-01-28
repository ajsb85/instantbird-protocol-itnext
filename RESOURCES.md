
#Resources
Enable chat outside Google Apps <br>
https://support.google.com/a/answer/34143 <br>
Getting started with Google Hangouts <br>
https://support.google.com/a/answer/3094760?hl=en  <br>
Hangouts Chat vs. Google Talk  <br>
https://support.google.com/a/answer/4564211?hl=en  <br>



Enable Hangouts chat
Hangouts chat combines previous Talk and new chat functionality


Enable the new Hangouts for messaging and video calls
	

Allow users in this organizational unit to opt-in to the new Hangouts, which combines previous Google Talk and Google+ Hangouts video calling functionality. After you opt-in this organizational unit, users will have the option to enable the new Hangouts.
Please note these current issues:

    Hangouts conversation history - Administrators can turn history on or off for all the new conversations. Regardless of the administrator setting, users can turn history on or off on a per-conversation basis.
    Google Apps Vault - Hangouts is not fully compatible with Google Apps Vault, and your organization's use of Google Apps Vault is subject to the Google Apps Enterprise Amendment: Hangouts & Vault
    Reverting to Talk - You can revert your users back to the Google Talk version of chat within their Gmail by disabling the new Hangouts for this organizational unit (from within Talk settings). Note: Conversations and history created while using Hangouts will still remain after reverting.

I have read and acknowledge the above.


## Resources for the new version

##Admin SDK

##Directory API: User Accounts
https://developers.google.com/admin-sdk/directory/v1/guides/manage-users

###Retrieve a user as a non-administrator

While user accounts can only be modified by administrators, any user on the domain can read user profiles. A non-admin user can make a users.get or users.list request with the viewType parameter equal to domain_public to retrieve a user's public profile. This permits a non-admin user to access a standard set of core fields. For a custom field, you can choose whether it should be public or private when defining the schema.
    Note: Any profiles with contact sharing disabled will not be shown to non-admin users.

##Search for users
https://developers.google.com/admin-sdk/directory/v1/guides/search-users

##Push Notifications
https://developers.google.com/admin-sdk/directory/v1/guides/push
