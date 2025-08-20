## Digital Forensics Investigation
# Description
I was tasked with using Autopsy to investigate a rouge insider threat who attempted to steal and share 
intellectual property and trade secrets. This information will be displayed in a step by step format 
with a photo provide of each step taken.

# Tools
- Autopsy

# Project Details
  

Oil Co. Forensics Report 
Case Number: 009389963
Jeff Blanchard



# Key Terms

<p>•	Autopsy - a open-source user friendly digital forensics tool that has the capability to recover deleted files. (Easttom,2022)</p>
<p>•	Hash – A function that is nonreversible, takes variable-length input, produces fixed-length output of random characters, and has few or no collisions. (Easttom,2022)</p>
<p>•	Metadata – Data about the data, including information about when a file or directory was created, when it was last modified and so forth. (Eastom,2022)</p>
<p>•	Steganography – the art and science of writing hidden messages. Typically using some form of image to hide data. (Eastom,2022)</p>
<p>•	MD5 hash – hash calculated using the MD5 Hashing Algorithm.</p>
<p>•	Acceptable Use Policy (AUP)- Policy outlining rules for employees using and accessing corporately owned resources.</p>





# A1. Creating A Case File in Autopsy
<p>1.	To Begin the process, I opened the Forensics software known as Autopsy, version 4.19.1.</p>
   <img width="685" height="406" alt="image" src="https://github.com/user-attachments/assets/7ab18655-b953-41d7-91fe-c53a5ff4610c" />

<p>2.	In this step I start the process of opening a new case file inside of Autopsy.</p>

   <img width="685" height="394" alt="image" src="https://github.com/user-attachments/assets/e7d8721b-b04b-4967-ba81-efb3c58ae9b2" />

<p>3.	Step 3 Covers the initial step in creating a case file which gives the case a title, also known as the case name. The case name of this investigation is Oil Co.</p>

   <img width="685" height="409" alt="image" src="https://github.com/user-attachments/assets/0f231c83-a458-46b2-9e72-e152105a6c3f" />

<p>4.	Here I click browse and open the C:/ drive to begin selecting the base directory. I will be clicking on the Users folder to continue the process.</p>

   <img width="685" height="410" alt="image" src="https://github.com/user-attachments/assets/7d3c9acc-e187-4390-924f-2b9473e65d32" />

<p>5.	This is a view of the Users folder where I will be clicking on the LabUser folder to continue the process.</p>

   <img width="685" height="409" alt="image" src="https://github.com/user-attachments/assets/f62368fb-0563-40f5-ab38-c8c9498c4f02" />

<p>6.  Here is a view of the inside of the LabUser Folder where I will be clicking on the Desktop folder to continue the process.</p>

   <img width="685" height="422" alt="image" src="https://github.com/user-attachments/assets/dccc9d3c-8e8a-4c5d-bab7-7695f8af8f02" />

<p>7.	Here is a view of the inside of the Desktop folder where I will wrap up the process by selecting Evidence Files and clicking select.</p>
                       
   <img width="685" height="424" alt="image" src="https://github.com/user-attachments/assets/65633dda-107d-4285-a738-9b420744a808" />

<p>8.	Now you can see the full path of the base directory listed in the form next to Base Directory: on the case information page. 
  I click next to bring me to the next page.</p>
  
   <img width="685" height="403" alt="image" src="https://github.com/user-attachments/assets/29df4535-15ba-454d-8e2e-0d73448ab5c6" />

<p>9.	This is the screen where I will create the case name and enter the examiner name.</p>

   <img width="685" height="377" alt="image" src="https://github.com/user-attachments/assets/fed4957b-a768-411b-96da-b486b5ac8adb" />

<p>10.	This is where I Enter the case number 009389963, which will help identify the case in numerical format if another file is added later.</p>

   <img width="685" height="403" alt="image" src="https://github.com/user-attachments/assets/79b09002-360d-491c-95cf-c619cacb461f" />

<p>11.	Here I enter in the examiner name to help maintain accountability in the chain of custody process.</p>

   <img width="685" height="406" alt="image" src="https://github.com/user-attachments/assets/1ccc2028-79e4-422c-8686-e1804272bc3a" />

<p>12.	I clicked finish which caused the system to begin loading the next stage in the casefile set up process.</p>

   <img width="685" height="397" alt="image" src="https://github.com/user-attachments/assets/080fd9a5-fb33-4dfa-a70b-0c0b4c5dabb1" />

<p>13. This section is where I select the host. In this case I left the default option “Generate new host name based on data source name” 
checked and clicked Next to move on to the next step in the process.</p>

   <img width="685" height="386" alt="image" src="https://github.com/user-attachments/assets/49100f9f-e842-4f84-97e0-7a2bec3e15ed" />

<p>14. This step involves selecting the data source type which for this case will be the Disk Image or Vm File option.</p>

   <img width="685" height="397" alt="image" src="https://github.com/user-attachments/assets/87486245-814e-4f73-a069-7e3d828b2c0d" />

<p>15. I clicked next which brings me to the Select Data Source screen.</p>

   <img width="685" height="390" alt="image" src="https://github.com/user-attachments/assets/cd3bee52-83e6-4e67-8f3e-9d88110b1f31" />

<p>16.	I clicked the browse button which brought me to the This PC directory where I will open the Local C Drive.</p>

   <img width="685" height="391" alt="image" src="https://github.com/user-attachments/assets/50aff081-e635-42a1-8a92-cdf62a4c0246" />

<p>17. This is a view of the Local C drive directory where I will find and open the Users folder which is the next folder in the source path
to our target file.</p>

   <img width="685" height="398" alt="image" src="https://github.com/user-attachments/assets/8a4d9495-c4d9-447f-9f9b-3d600a53da3d" />

<p>18. This is a view of the Users folder. Next, I will select the Users folder where I find the LabUser folder which is the next folder in
the source to our target file.</p>

   <img width="685" height="399" alt="image" src="https://github.com/user-attachments/assets/9a97fd73-1672-4714-81f9-1992bc2a6f13" />

<p>19. This is a view of the LabUser folder. Next, I will select the Desktop folder</p>

   <img width="685" height="400" alt="image" src="https://github.com/user-attachments/assets/fdaee95e-fecb-4129-a650-447cd0b695da" />

<p>20. This is a view into the Desktop Directory, where I will then select the Evidence Files folder.</p>

   <img width="685" height="391" alt="image" src="https://github.com/user-attachments/assets/b34e4949-9c3e-447b-8253-2d809ffb5549" />

<p>21. This is a view into the Evidence Files folder where I will be selecting the JSmith_Q1.001 file which will be the final file selection.</p>

   <img width="685" height="390" alt="image" src="https://github.com/user-attachments/assets/93080fbd-313a-44cd-9d5e-b342041f1e38" />

<p>22. Now you can see the Data Source Path is listed as C:\Users\LabUser\Desktop\Evidence Files\JSmith_Q1.001.</p>

   <img width="685" height="386" alt="image" src="https://github.com/user-attachments/assets/47426879-549b-4386-9c2f-127917285aeb" />

<p>23. I click next, leaving  the time zone set and sector size to the default setting as the default time zone actively reflects the local
time zone where the alleged act occurred.</p>

   <img width="685" height="393" alt="image" src="https://github.com/user-attachments/assets/ae74c2fc-e1ee-4cbf-aff1-73c34f8ac75c" />

<p>24. This is the next screen known as the Configure Ingest screen, all the default sections are checked which contains all the options
needed to effectively conduct the investigation.</p>

   <img width="685" height="400" alt="image" src="https://github.com/user-attachments/assets/62f97c5f-c30b-463d-be4c-69f491428a0c" />

<p>25. This shows the adding data source portion in action.</p>

   <img width="685" height="396" alt="image" src="https://github.com/user-attachments/assets/e206c299-8171-4106-b578-15a8a171e0ff" />

<p>26. Now the case file creation process is complete so I will click finish to officialy complete the process.</p>

   <img width="685" height="393" alt="image" src="https://github.com/user-attachments/assets/20e9516c-6c65-4191-8c96-91e76ae1b1e3" />

<p>27. We are now at the primary screen where I can begin the investigation process.</p>

   <img width="685" height="387" alt="image" src="https://github.com/user-attachments/assets/caa9b855-c318-4c8c-90b1-a00527bd3c3e" />

# A2. Identifying Evidence Process                                                                                         

<p>1. Starting at the main screen we can see the first initial J and the last name Smith in the file listed in the main window on the right.
 Also visible on the left side of the photo are all the different folders available to me that I can leverage to conduct my investigation.</p>

   <img width="685" height="432" alt="image" src="https://github.com/user-attachments/assets/6b13298d-839f-4c9e-b263-e0539faba928" />

<p>2. Here I click the plus sign next to Data Sources option in the left side menu to view its contents. Contents shown is the
JSmith_Q1.001_1host option.</p></p>

  <img width="685" height="391" alt="image" src="https://github.com/user-attachments/assets/a3ace63b-f468-44e0-a28c-6b4727abfb12" />

<p>3. Next I click the plus sign next to the JSmith_Q1.001_1host option, which reveals the JSmith_Q1.001 drive.

   <img width="686" height="415" alt="image" src="https://github.com/user-attachments/assets/4d57d039-886b-47a3-922d-096dec412db1" />

<p>4. In this step I click the plus sign next to JSmith_Q1.001 drive which opens 11 files some of which appear to have been deleted indicated 
by the red “x”. Some of these files have very suspicious names indicating business strategies, methodologies, and a few files about using
bitcoin in a conspicuous manner.</p>

   <img width="685" height="406" alt="image" src="https://github.com/user-attachments/assets/c652a0fe-8892-49ff-b619-f62b7dc4ad88" />

<p>5. I decide to click on one of the deleted files titled Business_Strategy.pdf(17) to investigate a bit further.</p>

   <img width="685" height="387" alt="image" src="https://github.com/user-attachments/assets/5e2826cf-de46-49d5-9563-259225e52048" />

<p>6. I scroll to the right to view the hashes and find MD5 Hash of 06c53c92480c829c126dd9b0ff2dc8e3 repeated 4 times on 4 different image files.
Regarding a hash, different inputs or images in this case should produce a different hash output. This finding could indicate that some form
of steganography was conducted.</p>

   <img width="685" height="413" alt="image" src="https://github.com/user-attachments/assets/c5affa4f-23de-494f-8ead-9690840bd0d8" />

<p>7. Next, I Click on the Deleted Files folder which reveals a File Sytems(6) folder and an All(12) folder.</p>

   <img width="685" height="361" alt="image" src="https://github.com/user-attachments/assets/bd6fe5e4-f082-4671-98e0-9cfd4aecfcbb" />

<p>8.  I choose to click the All(12) folder as it will contain all deleted files that were recovered that could be relevant to my investigation.
As you can see the Business_Strategy.pdf file I inspected earlier is present along with some other interesting files.</p>

   <img width="685" height="387" alt="image" src="https://github.com/user-attachments/assets/90e60c11-fa84-4f74-b678-9114bde309a0" />

<p>9. Here I click on the file in the top window to open it and then the file is displayed in the form of a document in the bottom window.
You can see the document is titled Oil Company, with the words CONFIDENTIAL and Restricted underneath in red. Also note Business Strategies
2021 in the title section as well.</p>

   <img width="685" height="403" alt="image" src="https://github.com/user-attachments/assets/74b67c96-c172-43fc-9fea-fc87d6e01760" />

<p>10. I decided to look at the File Metadata tab to do further analysis. Here you that the file contains both the document name as well
as JSmith_Q1.001 which helps link the person in question to the document itself.</p>

   <img width="685" height="398" alt="image" src="https://github.com/user-attachments/assets/8e141223-c6f7-4849-91cd-a84802417786" />

<p>11. Given the information I have obtained while examining this file I decided to extract it to use as evidence for my case. I right
clicked the file and selected Extract File in the drop-down menu to begin the extraction process.</p>

   <img width="685" height="367" alt="image" src="https://github.com/user-attachments/assets/96093309-9523-4da0-b049-4feb9ec814a4" />

<p>12. After clicking the Extract File option in the drop-down menu, I am now in the Local Disk (C:) Drive where I will be selecting
the Users folder.</p>

   <img width="685" height="378" alt="image" src="https://github.com/user-attachments/assets/445569be-7577-4acb-b2b8-1391ba0d8a3b" />

<p>13. Now am in the Users folder and will be selecting the LabUser Folder.</p>

   <img width="685" height="375" alt="image" src="https://github.com/user-attachments/assets/abfcdcdc-6ef2-428d-9dca-d604713604f3" />

<p>14. Here I am in the LabUser folder and will be selecting the Desktop folder.</p>

   <img width="685" height="371" alt="image" src="https://github.com/user-attachments/assets/2ee3d96a-b523-4125-956d-87a2037245b2" />

<p>15. Here I am in the Desktop folder and will select the Evidence Files.</p>

   <img width="685" height="365" alt="image" src="https://github.com/user-attachments/assets/06245ba4-da85-49ca-8481-aab32aeba33a" />

<p>16. Here I am in the Evidence Files folder where I will be Selecting the Oil Co folder.</p>

  <img width="685" height="377" alt="image" src="https://github.com/user-attachments/assets/fb922df1-2be8-4684-9c11-8bba5a05bc54" />

<p>17. Here I am in the Oil Co folder and will be extracting the file to the export folder.</p>

   <img width="685" height="372" alt="image" src="https://github.com/user-attachments/assets/761e2d88-e7e4-4d75-94ee-27b185be98e5" />

<p>18. Here you can see the file was extracted.</p>

   <img width="685" height="383" alt="image" src="https://github.com/user-attachments/assets/d216668d-579f-43ba-bc14-74ba4e55185d" />

<p>19. This image shows the contents of the next deleted file of interest which is the Drilling  Methodology.pdf, as you can see from the
photo the report picture in the bottom right window is clearly labeled as CONFIDENTIAL and Restricted. The accused was not authorized
to access documents with this kind of classification.</p>

   <img width="685" height="373" alt="image" src="https://github.com/user-attachments/assets/9f26986c-ca15-432a-871f-fd353badf9c6" />

<p>20. In this image I have selected the File Metadata tab with the results displayed in the bottom right window. You can see in the name
field that the file path contains JSmith_q1.001 like the previous file.</p>

   <img width="685" height="369" alt="image" src="https://github.com/user-attachments/assets/1853ad95-428e-4844-9ba6-be5a781dce53" />

<p>21. Given the information I have obtained while examining this file I decided to extract it to use as evidence for my case. I right
clicked the file and selected Extract File in the drop-down menu to begin the extraction process.</p>

   <img width="685" height="386" alt="image" src="https://github.com/user-attachments/assets/e438845c-b224-480a-8088-9cdc812abacb" />

<p>22. After clicking the Extract File option in the drop-down menu, I am now in the Local Disk (C:) Drive where I will be selecting the
Users folder.</p>

   <img width="685" height="370" alt="image" src="https://github.com/user-attachments/assets/7b3d096b-0c53-4ed9-9a14-1a62d58ce48e" />

<p>23. I am now located in the Users folder, where I will be selecting the LabUser folder.</p>

   <img width="685" height="381" alt="image" src="https://github.com/user-attachments/assets/1234d37e-2079-4bee-ad43-be77bc57b358" />

<p>24. This image shows me in the LabUser folder, where I will be selecting the Desktop folder.</p>

   <img width="685" height="369" alt="image" src="https://github.com/user-attachments/assets/483925b1-df7d-40fd-8ba7-d597fc8f0f6f" />

<p>25. This Image shows me in the Desktop folder, where I will select the Evidence Files folder.</p>

   <img width="685" height="366" alt="image" src="https://github.com/user-attachments/assets/3d3b53b5-3807-4b5a-b388-010d6449daa7" />

<p>26. This image shows me in the Evidence Files folder, where I will select the Oil Co folder.</p>

   <img width="685" height="364" alt="image" src="https://github.com/user-attachments/assets/c7293af2-0b85-439a-871e-cda7d211850c" />

<p>27. This image shows me in the Oil co folder where I will select the Export folder.</p>

   <img width="685" height="359" alt="image" src="https://github.com/user-attachments/assets/fe1726bc-f4e5-46a0-9419-4a43c77cd615" />

<p>28. Here I am saving the Drilling Methodology.pdf in the Export folder alongside the Business_stratagey.pdf.</p>

   <img width="685" height="360" alt="image" src="https://github.com/user-attachments/assets/d089b1f2-6fa6-43a7-acfa-eca042a61e03" />

<p>29. Here you can see the File was successfully extracted.</p>

   <img width="685" height="382" alt="image" src="https://github.com/user-attachments/assets/2b222776-bd4f-4307-9038-b79421d82683" />

<p>30. Now that I have extracted my files, I can open them up for further analysis. I will start by minimizing the Autopsy window.</p>

   <img width="685" height="406" alt="image" src="https://github.com/user-attachments/assets/c5981ec8-a70a-4ddb-a800-8eea48d5c4a9" />

<p>31. I open the Evidence Files folder located on the desktop where I will be opening the Oil Co folder.</p>

   <img width="685" height="403" alt="image" src="https://github.com/user-attachments/assets/35a3d342-3a0a-4796-b4e3-9cc65061144b" />

<p>32. This Image shows inside the Oil Co folder where I will be selecting the Export folder.</p>

   <img width="685" height="411" alt="image" src="https://github.com/user-attachments/assets/43edf3df-f72f-4908-9896-772f07cb7646" />

<p>33. In this image you can see the contents of the Export folder which includes the files I extracted from Autopsy. First, I will
select the Business_Strategy.Pdf file.</p>

   <img width="685" height="471" alt="image" src="https://github.com/user-attachments/assets/e6abc756-d4b3-4465-b3c7-ea691144434e" />

<p>34. Here we see the document's title and a part of the watermark that says confidential across the page.</p>

   <img width="685" height="401" alt="image" src="https://github.com/user-attachments/assets/8fa74224-2082-473f-83f0-59fbe282687a" />

<p>35. As I scroll down the .pdf document the watermark becomes clearer and you cansee it in its entirety.</p>

   <img width="685" height="386" alt="image" src="https://github.com/user-attachments/assets/01b2383b-82f0-431e-ab84-fa61315d14ea" />

<p>36. I close out of that document and return to the Export folder containing the other suspicious file. I will next be examining the
Drilling Methodology.pdf file.</p>

   <img width="685" height="402" alt="image" src="https://github.com/user-attachments/assets/72f76a47-b296-4be0-8996-b4a692ea10fd" />

<p>37. Here you can see that the information contained in the Drilling Methodology.pdf is also marked as confidential.</p>

   <img width="685" height="408" alt="image" src="https://github.com/user-attachments/assets/b086f3d1-f2b8-4eaf-a509-293f7878a695" />

<p>38. After the analysis I closed the pdf window. Bringing me back to the Export folder.</p>

   <img width="685" height="402" alt="image" src="https://github.com/user-attachments/assets/e593f5bf-2c61-4064-b277-6ef9f08a3fe0" />

<p>39. I then close out of the File Explorer window. Which brings me back to the desktop. This concludes my investigation.</p>

  <img width="685" height="405" alt="image" src="https://github.com/user-attachments/assets/d0114ce4-cb4d-4b2f-950d-93781ed218f5" />

# A3. Summary of the Investigation   

<p>  Throughout my investigation I was able to identify multiple confidential files which the accused John Smith had obtained. According 
to the company's Acceptable Use Policy (AUP) Mr. Smith was not supposed to have access to files of this classification. The images 
below will show the two primary files in question along with metadata that links the files to Mr. Smith.
The first photo Shows the File Metadata of the Drilling Methodology.pdf file. You can see JSmith_Q1.001 listed in the file path 
in the name section which indicated that at some point the file was in the possession of Mr. Smith. </p>

   <img width="685" height="368" alt="image" src="https://github.com/user-attachments/assets/1a75c0cb-9243-4884-84b9-890dac593a4a" />

<p>  This image was taken during the analysis of the pdf document itself. It clearly shows that the information contained within 
  the document is of a classified nature which would mean that for Mr. Smith to have possession of such a file would be a direct violation 
  of the company’s AUP.</p>

   <img width="685" height="416" alt="image" src="https://github.com/user-attachments/assets/aba4802e-f654-4bac-be69-4c50ddc6a12c" />

<p>  A similar instance can be seen in the next image. This image is regarding the Business_Strategy.pdf which is yet another
  file containing confidential information. The image with the metadata will show JSmith_q1.001 in the file whereas the second photo 
  shows the actual pdf with a watermark that states confidential.</p>

   <img width="685" height="397" alt="image" src="https://github.com/user-attachments/assets/dc8942d1-6e4c-4633-87f5-f9efb4118f55" />

   <img width="685" height="431" alt="image" src="https://github.com/user-attachments/assets/c9309fef-cdc6-4d3d-a6fe-02a22f4e9ba2" />


<p>  Throughout my investigation I was unable to Identify if John Smith sent this information to anyone. However, I can prove he 
  had classified documents to which he was not authorized access. It is my professional opinion through the examination of the evidence
  I obtained through my investigation, that he is guilty of violating Oil Co’s Acceptable Use Policy.</p>

# References
<p>Easttom, C. (2022).  Digital Forensics, Investigation, and Response (4th  Edition). Jones and Bartlett Learning, LLC</p>











 





























 






    
