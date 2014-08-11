## 15.1 Procedures

### 15.1.1 Computer Setup

1. From MS DOS mode, you will see **“C:\Windows>”**
2. Type **'cd..'** and **'cd CPT'**
3. At the CPT> prompt, type **'CPT'**
4. At the main screen, go to **Administration**
5. Select **Standard Practice** which will start 2 minute practice

### 15.1.2 Participant Practice

**Explain to the participant the following:**  _“This test is for 14 minutes straight and we can’t stop it so if you need to get a drink or use the bathroom now is the time to do it. This test shows letters, one at a time. You’re going to watch the computer screen and you will click the space bar quickly for any letter except for X. So, what will you do when you see the letter A? The letter T? The letter X?”_ (Confirm that the participant responds with ‘click the space bar for all letters except X)

_“Okay this is a two minute practice test. Press the spacebar whenever you’re ready to start."_

Press **Ctrl+End** after participant is finished with the test and the screen displays ‘Call the Tester’.

### 15.1.3 Test Administration

* 1. From the Administration menu, select **Start Test**
* 2. Enter on first and second line **First initial of last and first Name**
* 3. Click **F10** button
* 4. **Explain to the participant the following:** _“I can’t help you out once the test has started. Do you have any questions? (Respond to any questions, if any) I’ll tell you when you’re halfway done and when you have one minute left. If you ask me, ‘how much longer?’ I can’t tell you.”_
* 5. Prompt to **Start Test**. Test will begin.
* 6. When test is over, only two prompts are allowed (‘Attend to the Test’ and ‘Call Tester’).
* 7. Select **Ctrl+End** to exit this screen.
* 8. The screen will show **Initial RPT**
* 9. Type over it with the **Subject# RPT**.

 * Family Study will use a 5 then the 4-digit personi number when saving the file.
 * When a personi is three digits a “0” will be added to the beginning of the personi. (Ex. personi 400 would read 50400.)

* 10. Hit **F10** button to accept changes.
* 11. To Exit, select **Report > Y > N > Y > Initial #**

## 15.3.2 Data Import to SAS

* 1. Log on to a computer that has SAS on its hard drive and has access to the network folders for the Family study.
* 2. Run the SAS <u>cptcheck</u> program. This will update the data set and compare the CPT files to the patient files
* 3. Open the SAS <u>cptimport</u> program and make sure that the most recent .dat file is listed.  (You can look at the .dat files in the Family CPT Data folder.)
* 4. Run the SAS <u>cptimport</u> program. Write down the patient IDs from the output section (or print the output).
* 5. From the Family CPT Data folder, copy all patient files that were shown in the output to a floppy disk.
* 6. Setup the old gray Texas Instruments laptop.  You will need to watch the screen and press **F1** to Resume Setup.

* It might say, **“Operating system not found”**.  Turn the computer off and back on again.  Press **F1** to Resume Setup.  It will prompt you to ‘hit any key’.  It should start up.

* 7. You may need to brighten the screen, hit the **Fn** button and up arrow keys to do this
* 8. Transfer the files to the old gray Texas Instruments laptop computer.
* 9. Transfer files to the famcpt folder.
* 10. Restart the computer in MS-DOS, make sure the CPT floppy disk is in the a: drive
* 11. At the “C:/WINDOWS:>” prompt, type **‘cd desktop’**
* 12. Type **“CD CPT”**
* 13. Type **‘CPT’**
* 14. From the main window of the CPT program, select the **Patient/Subject** menu
* 15. Select **Export Data**
* 16. Verify that the path is C:/Famcpt
* 17. Name the file by adding an **F** to the front of the date of export (Ex. If you were to do this procedure on July 4, 2004 then the name of the file would be: f070404.DAT)
* 18. Select **Export**
* 19. In Explorer, verify that they have indeed been exported, and the file has been correctly named.
* 20. In Explorer, transfer the files, including the newly created .DAT file to the a:/ drive and to a floppy disk.
* 21. Put the floppy disk into the computer with SAS and transfer the .dat file to the network.
* 22. Update the line in the SAS <u>cptimport</u> program to reflect the new .dat file
* 23. Save the changes to the program


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/conners-performance-test/15-00-conners-performance-test-toc.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    Table of Contents
  </a>

  <a href=":pages_path:/manuals/conners-performance-test" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Conners Performance Test
  </a>

  <a href=":pages_path:/manuals/conners-performance-test/15-02-harvesting-cpt-data.md" class="btn btn-success">
    15.2 Harvesting CPT Data
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
