**Instagram mobile aplication**

**Test Case 1:** Uploading Reel Video with Maximum Allowed Duration from Phone Gallery (Boundary Value Analysis)  
**Priority:** high  
**Preconditions:** 
* The user must have an active Instagram account and be logged into the app.  
* Ensure the Instagram app is up to date on a compatible device.  
* The  user's device’s media library contains a video file in MP4 format with a duration of exactly 60 seconds.

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | On the main page tap on the icon ⊞ in the bottom of the screen |  | The New Post page opens, displaying options: Post, Story, Reel, and Live. |
| 2\. | Tap on the “REEL” |  | The New Reel page opens, and the media library appears, displaying available video files. |
| 3\. | From media library select video | Video format mp4 duration of 60 seconds | Video is accepted and loads in the preview screen with edit options. |
| 4\. | Tap “Next” button |  | A new page opens with tagging and location settings for the reel. |
| 5\. | Tap the “Share” button |  | The reel is successfully uploaded and appears in the user’s feed. |

__________________________________________________________________________________________________________________________________________________________
**Test Case 2 :** Editing Profile with Minimum Characters in Instagram Edit Profile Form  
**Priority:** high  
**Preconditions:** 
* The user must have an active Instagram account and be logged into the app.  
* The app is updated to the latest version and is open to the user’s profile page.

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | Tap on the profile icon on the main page. |  | Profile page is opened |
| 2\. | Tap on the “Edit profile” button |  | Edit profile page is opened |
| 3\. | Tap on the “Name” field and fill it with data. | single(one) alphabetic character | Field accepts and displays entered data.  |
| 4\. | Tap on the green checkmark to accept changes. |  | User is returned to the user edit profile form, change is accepted  and in the field “Name” is displayed the entered value. |
| 5\. | Tap on the “Username” field and fill with data | single(one) alphabetic character | Field accepts and displays entered data. |
| 6\. | Tap on the green checkmark to accept changes. |  | User is returned to the user edit profile form, change is accepted  and in the field “Name” is displayed the entered value. |
| 7\. | Tap on the back arrow on the left top corner of the page Edit Profile page. |  | New user name is shown on the profile page. |



 Telegram  mobile aplication 
________________________________________________________________________________________________________________________________________________________________________________________
**Test Case 3 :**  Verify Sending a Message with an Emoji in Telegram Mobile App  
**Priority:** high  
**Preconditions:**
*  User is logged into the Telegram app.  
*  User has at least one contact in the contact list who also uses Telegram.

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | Select a contact from the contact list. | Contact from the list | The chat window with the selected contact opens. |
| 2\. | Tap on the message input field at the bottom of the screen. |  | The keyboard appears, and the message input field becomes active. |
| 3\. | Type a message into the input field. | Emojis (e.g., 😊🎉🔥) | The emojis are displayed correctly in the message input field. |
| 4\. | Tap the button arrow icon to send a message. |  | The message status updates to "Sent" immediately after sending, and to "Delivered" once the recipient receives the message. |
|  |  |  |  |

__________________________________________________________________________________________________________________________________________________________________________________________
**Test Case 4 :** Verify error message when attempting to send a valid format file Mp4 exceeding the 2GB limit (2.01GB)  
**Priority:** high  
**Preconditions:**  
*  User is logged into the Telegram app.  
*  User has at least one contact in the contact list who also uses Telegram.  
* The  user's device’s media library contains file 2.01GB

| Steps | Test Steps | Test Data | Expected Results |
| :---: | ----- | ----- | ----- |
| 1\. | Select a contact from the contact list. | Contact from the list | The chat window with the selected contact opens. |
| 2\. | Tap on the attachment icon in the chat window. |  | The device directory opens to choose a file to upload. |
| 3\. | Select a file from device directory | File format Mp4  of 2.01GB | The file is selected and displayed in the attachment preview area. |
| 4\. | Press the "send" button |  | An error message is displayed, stating that the file size exceeds the 2GB limit. |
|  |  |  |  |



