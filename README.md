# ISpotFishing-Tool

**Section 1: ISpotFishing Tool Information**

The ISpotFishing Tool is a newly designed tool, which is responsible for helping to detect phishing emails. It aims to extract, analyse, and present data from emails to help determine the risk or the likelihood of a phishing email. 

How to download the ISpotFishing Tool
1. Download the tool as the executable file (.exe) in this respitory. 
2. Allow the program to download.
3. Run the program

How to login to the ISpotFishing Tool

The ISpotFishing Tool only works currently with Outlook. This tool will not work against other email providers such as Gmail, Yahoo, etc. Please note that we also don’t support custom email domains e.g. university emails, or business emails. All emails used are to be personal and kept personal during the use of the tool.

1. Once you run the tool, you will be prompted to sign in to your Outlook account, as shown in the image below.
 
![ISpotFishingToolUI](https://i.gyazo.com/62bf77e4a9cf488b6da42ac66e8c5734.png)

2. Please enter your Outlook email address and password.
3. If you type in the incorrect login details, access to the tool will be denied.
4. If your login details match, then you will be granted access to the tool.

When launched for the first time, the tool will load the UI element of the program. 

![ISpotFishingToolMainUI](https://i.gyazo.com/f1be5ecab5cc17dd4e52c6727289d55c.png)



**Section 2: Methods in the ISpotFishing Tool**

The tool has three different methods of detecting phishing emails. These methods are the following:
- Email Header Extraction and Analysis
- Website (URL) Detection and Analysis
- Attachments Detection and Analysis

Email Header Extraction and Analysis

The Email Header Extraction and Analysis method automatically fetches and extracts the contents of an email header for analysis. When a student clicks on an email and unclicks it, the tool will retrieve the necessary email header data, and present this data for analysis. 

Website (URL) Detection and Analysis

The Website (URL) Detection and Analysis method scans an email and identifies any embedded URLs. URLs can be embedded through buttons or hyperlinks that can navigate students to websites once successfully clicked. The tool will detect these URLs, but it will also display a list of these URLs and scan them for analysis.

Attachments Detection and Analysis

The Attachments Detection and Analysis method detect any attachments attached to an email. Attachments can include files such as documents, spreadsheets, etc, or can consist of any software such as .exe files. The tool will detect these attachments, but it will also display a list of these attachments and scan them for analysis.

How to run these methods when viewing an email

Before viewing an email, you must ensure that you are logged in with the correct account on the tool. Otherwise, the tool will not be able to retrieve or fetch any data from the email you’re wishing to analyse. 

1. Click on the email you wish to analyse. Please note that this must be an unread (unseen) email. If you’re wishing to analyse a seen email, you must unsee it first.
2. Once the email has loaded, you can then click off the email that you have selected.
3. Wait for some time for the tool to collect the data.
4. The data should now be presented for analysis.

**PLEASE NOTE THAT THE METHODS IN THIS EMAIL ARE DESIGNED TO HELP ANALYSE EMAILS. THEREFORE, IT IS YOUR RESPONSIBILITY TO REVIEW ALL THE DATA IN FRONT OF YOU AND MAKE YOUR JUDGEMENT. ISPOTFISHING TOOL DOES NOT TAKE ANY RESPONSIBILITY FOR ANY LOSSES, OR DAMAGES AS A RESULT OF YOUR ACTIONS.**



**Section 3: Factors/Techniques in detecting phishing emails**

To detect phishing email attacks, you must ensure to have sufficient information on the techniques, and methods cybercriminals use to conduct phishing email attacks. When using the tool, please make sure to analyse the following data presented:
- The email address of the sender.
- A return path if one is provided - can help to cross-check the sender email address against the return-path email address.
- Attachments in the email.
- Domain names (if any).
- URLs provided in the email.

More information on how to detect a phishing email can be found here: https://www.itgovernance.co.uk/blog/5-ways-to-detect-a-phishing-email



**Section 4: Q&A**

**Q: Why does this tool only work against unseen emails?**

A: Due to limitations of the protocol used to retrieve the data, alongside the API used to collect the data, the tool will only work against unseen emails. However, if you unsee an email and then repeat the steps above, it will work.

**Q: Do I have to click off the email for the tool to retrieve the data?**

A: Yes. This is due to the limitations of the API as mentioned above. We cannot fix this ourselves.

**Q: How far back can emails be analysed?**

A: Due to limitations of the software, the tool can only handle 30 unread emails and lower. Anything more than 30 will not work against the email. If you want to analyse older emails, you will need to read some first until it is below the limit.

**Q: Why am I responsible for analysing the data and making my judgement?**

A: The job of the tool is to simply extract, and present specific and filtered data for analysis. This tool cannot tell you if it is a phishing email: it can help to analyse a phishing email, which can assess the likelihood of it being a phishing email. You are responsible for checking this yourself.  More information as mentioned above can be found here: https://www.itgovernance.co.uk/blog/5-ways-to-detect-a-phishing-email

**Q: Am I allowed to take the tool and distribute it as my own?**

A: No you can’t. The tool developed belongs to the Project Manager unless stated otherwise. All creations are protected under the Copyright, Designs, and Patents Act.

**Q: I have a suggestion I would like to add. Where can I report this?**

A: Please create an issue here: https://github.com/Joshua82188/ISpotFishing-Tool/issues. Please make sure to include as much information as you can. Please note that although we appreciate all feedback reported, this does not guarantee it will be implemented.

**Q: Why does this tool only work with Outlook?**

A: Every email provider stores and generates data differently. Because of this, it is difficult to expand it to different email providers with the restrictions in place of the project. Therefore, the decision was made to implement it only for Outlook for now.

**Q: Why do I have to log in to the tool before I start using it?**

A: This is so that the email server and the tool can communicate with each other. Don’t worry, all requests and data transmitted are secured with SSL Encryption. Your details are also encrypted when logged in. No one can view or steal your information or data.

**Q: Are there any plans in the future to continue the development of the tool?**

A: Unfortunately, the current answer is no. This project is only going to be active until May, in which afterward the project will be terminated (closed). The tool will be discontinued following project termination and will no longer be receiving any updates or support. There could be plans in the future to continue the development of the tool, but this is at the discretion of the Project Manager.

**Q: I have discovered a bug or issue with the tool. Where can I report this?**

A: Please read Section 4: Reporting Bugs, or Issues.

**Q: I would like to report my feedback on the prototype. Where can I do this?**

Please read Section 5: Prototype Questionnaire

**Q: I have another question that doesn’t have an answer. Who should I forward the question to?**

Please drop me an email: joshua@ispotfishing.net



**Section 5: Reporting Bugs, or Issues**

Please read the following information below before reporting any bugs or issues with the tool.

Bug or Issue Information:

- Please ensure that you’re on the latest version of the tool. The version number to date is: PROTOTYPE-fa24b0f

- Please document any steps or methods in replicating the bug or issue. The steps should ensure that the bug or issue can be replicated consistently for debugging purposes.

- Please include any images, photographs, or videos of the bug or issue if possible. This is to identify how the bug or issue is behaving in the tool.

Once you have read all the information above, please make sure to copy this template below, and create an issue here: https://github.com/Joshua82188/ISpotFishing-Tool/issues.

Questions with an asterisk (*) must have an answer.
```
(*) Description of bug or issue:
(*) Are you able to consistently replicate this bug or issue?:
(*) Please provide the steps to replicate here:
(*) Your Operating System, including Version: 
Image(s) of bug or issue:
Video(s) of bug or issue:
Additional Information:
```

Note:

Failure to fill in the questions may result in your report being denied or delayed. Therefore, please ensure to gather all the necessary information before submitting your report. 

All bugs or issues reported must have been done ethically. This means not using any additional software to modify the tool’s behaviour. Any reports involving unethical behaviour, or testing will be rejected.



**Final Section: Prototype Questionnaire**

The Project Manager would like to welcome you to participate in the Prototype Questionnaire. This is a chance for you to have your say on the tool developed, including what you like and dislike about the tool, and any feedback you would like to add. 

The Questionnaire can be completed here: https://forms.gle/NnW7xpgui8vk5KmWA 

All feedback received will be reviewed by the Project Manager. The Project Manager will be responsible for deciding changes for Version 1 of the tool. So what are you’re waiting for? Complete the questionnaire now!

Thank you for submitting your feedback, as well as for testing out the tool, and taking the time to provide your opinions and suggestions. If you have any questions, please do not hesitate to contact the project manager for further assistance: joshua@ispotfishing.net

Yours Faithfully

Joshua
Project Manager of the ISpotFishing Tool
