<h1>Digital Forensics</h1>
In this week's assignment, you will continue working with your group to finalize the case report that you began in class. The instructions are included here again for reference.
<h2>Lab Environnement</h2>
This Challenge will use the Digital Forensics - Autopsy lab in Kali Linux.

<h2>Activity File</h2>
Use the following resource to help guide your work: <a href="https://docs.google.com/document/d/1MN4aTz8qsPh1SayR9LWKVNIGndLcSVrg1SPHj4NtVLs/edit" target="_blank"> iPhone Forensics - Important Files and Databases </a>

<h2>Instructions</h2>

You've examined and documented quite a bit of information from the iPhone image file. Now, you will use that documentation to build a final report.
<ul>
    <li>Before you complete your report, there is still some additional evidence to analyze. Since the internal investigators knew that Peter was close with Rosie, they collected Rosie's phone for your to analyze to determine if she in fact a co-conspirator.</li>
    <li>WIthin Autopsy, on the top left, select the option "Add Data Source" .</li>
    <li>Add Rosie's iphone image using the same process as Peter.</li>
    <li>Analyze the following evidence on Rosie's phone.</li>
    <li>View sms messages</li>
    <ul>
        <li>Are there any additional sms messages which correlate Rosie to the crime?</li>
    </ul>
    <li>Export Attachments on sms messages</li>
     <ul>
        <li>Expand the attachments folder under sms until you find a .HEIC file and a .MOV file</li>
        <li>Export those 2 files</li>
     </ul>
    <li>Analyze the .MOV file</li>
    <ul>
        <li>Access the .MOV file from your terminal, and run the following command xdg-open <filename>.MOV</li>
        <li>Did this file contain any evidence?</li>
    </ul>
    <li>Determine Geographic Data on the HEIC file</li>
    <ul>
        <li>Note: HEIC is Apple’s proprietary file type for photos</li>
        <li>Open a webbrowser within your Kali Terminal</li>
        <li>Browse to https://onlineexifviewer.com/ and upload the .HEIC file</li>
        <li>Analyze the data and determine the location where the photo was taken.</li>
    </ul>
</ul>

<h2>Bonus - Determining the Ring Leader of the Operation</h2>
Throughout the week, there were mentions that there was a ring leader secretly behind the operations of this crime. Additionally there are rumors this person is called Mr X. Can you determine who is Mr X?
<ul>
    <li>Hint - You may have to listen to this evidence on your local computer as Kali doesn't always play sound.</li>
    <li>Hint 2 - Look for this evidence you want to listen to, on Peter's phone.</li>
</ul>
