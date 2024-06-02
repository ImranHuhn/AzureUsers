<p align="center">
  <h1 align="center">Creating a user for least privilege</h1>
</p>

<h2>Links:</h2>

- [Google Doc](https://docs.google.com/document/d/1ZUGkgGCq0eHjSl91mGeFpZXTSQdBi8Wh08D9XJwco_Q/edit?usp=sharing)
- [Github Repo](https://github.com/ImranHuhn/AzureUsers)
- [Blog](http://www.techdeficient.com/2024/06/creating-user-for-least-privilege.html)

<h2>TLDR: Creating a new user</h2>

- <b>Introduction </b>
  - Guide for creating a new user in Azure to manage and limit user access.

- <b>Creating a new user </b>
  1. Go to the "User" section.
  2. Ensure you're in "All Users" view.
  3. Select "New User."

- <b>Identity for the user </b>
  1. Create a principal name (e.g., "labuser2").
  2. Create a display name (e.g., "labuser2").
  3. Copy the password; reset if needed.
  4. Click "Next: Properties."

- <b>Principal name </b>
  - Review and click "Create."

- <b>User creation completed </b>
  1. Click the bell icon for the right panel.
  2. Ensure it shows "Successfully created user."
  3. Verify in "All Users"; click "Refresh" if needed.
  4. Confirm "labuser2" is listed.

- <b>Conclusion </b>
  - Successfully created a new user in Azure.

<h2>How to read each section (in this order)</h2>

<b>Section-Intro</b> 
- <b>Title: </b>Name of the section.
- <b>Description: </b>Describe what the section entails. Some sections won’t have descriptions. 

<b>Image</b> 
- <b>Numbering: </b>Within the images are sequential numbers, with corresponding text explanations directly below each image.
- <b>Yellow highlights: </b>Yellow highlights are navigation aids to help identify your current section in the Azure portal.

<b>Text numbers</b> 
- <b>Numbers: </b>Each number provides a brief explanation of the image directly above it.

<b>Side notes</b> 
- <b>Notes: </b>Any extra details you should be aware of.

<h2>Introduction</h2>

&nbsp;&nbsp;&nbsp;&nbsp;Welcome to this guide on creating a new user in the Azure portal. This guide is organized to offer clear instructions and visual aids for easy understanding. Each section includes titles and descriptions, with some sections being straightforward enough to require no further explanation. The goal of creating a new user is to manage and limit their access privileges effectively.

Note:  If some screen images show missing sections, it indicates default settings; for a comprehensive overview, refer to the accompanying videos.

<h2>Creating a new user</h2>

<b>Description: </b>We will begin by accessing the "User" section within the Azure portal. Once we have navigated to this section, we will commence the procedure by selecting the option to add a new user. This step is crucial as it allows us to input the necessary details and configure the user's settings. 

![01_Capture](https://github.com/ImranHuhn/AzureUsers/assets/52342912/3cfe6990-ec44-4206-b62b-d11568503345)

0.  Go to the "User" section.
1.  Ensure that you are in the "All Users" view.
2.  Select "New User" from the options at the top.

<h2>Identity for the user</h2>

<b>Description: </b>Here, we will create a new user by assigning them a unique identity. This process involves providing essential details, including a name and a secure password. By doing so, we ensure that each user has distinct credentials for authentication. It is important to choose a strong password to enhance security and protect the user's account. 

![02_Capture](https://github.com/ImranHuhn/AzureUsers/assets/52342912/20f1ecda-9e93-4d44-a6a7-72b0ce09ddbf)

1.  Take notice that we are currently in the "Basic" section.
2.  Create a principal name, which you will use to sign into the account. For example, I used "labuser2."
3.  Create a display name, which will appear on the dashboard after you sign in. I entered "labuser2" for this purpose.
4.  Be sure to copy and paste the password into a document or notepad for future use. If you happen to lose the password, don't worry. I will demonstrate how to reset it later.
5.  Once you have completed this step, click on "Next: Properties."

<h2>Principal name</h2>

<b>Description: </b>Take a moment to review the fields you have entered, ensuring that all the information is accurate and meets your requirements. This thorough review helps prevent any errors or omissions that could affect the setup. If you are satisfied with your entries, you can proceed to the next step confidently. 

![03_Capture](https://github.com/ImranHuhn/AzureUsers/assets/52342912/d1e9f369-da67-418f-8b81-8cbd68f70b07)

1.  There is little to do in this section except for reviewing your entries. Once you have finished, click on "Create."

<h2>User creation completed</h2>

<b>Description: </b>We have successfully completed the creation of a new user. Now, the next step is to verify that the user has been created correctly. To do this, navigate to the "All Users" section and locate the newly added user in the list. Ensure that the user details match the information you entered during the setup process. 

![04_Capture](https://github.com/ImranHuhn/AzureUsers/assets/52342912/188c1426-b518-48ac-815e-c076682a8973)

1.  Click on the bell icon to display the right panel.
2.  Ensure the status shows as completed and that it states "Successfully created user."
3.  Now, let's verify if our user has been created. Ensure that you are in the "All Users" section.
4.  The new user (labuser2) should be visible in the center of the dashboard. If it does not appear, click "Refresh" to update the display.
5.  As you can see, labuser2 appears in the list.

<h2>Conclusion</h2>

&nbsp;&nbsp;&nbsp;&nbsp;By following this guide, you have successfully learned how to create a new user in the Azure portal. Each section has been designed to provide clear instructions and visual aids to ensure a smooth process. From accessing the "User" section and adding a new user to verifying the user's creation, every step is crucial for managing user access and privileges effectively. Remember to review the provided images and notes for additional details and insights.
