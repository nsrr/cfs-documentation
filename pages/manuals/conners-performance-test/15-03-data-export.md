## 15.3 Data Export

### 15.3.1 Data Export from CPT Computer

On (or near) the last day of the month, export a CPT ASCII file from computer.

1. Start the CPT program in MS DOS mode
2. Go to **Patient/Subject** Menu
3. Select the **Export Data**
4. Save to c:\cpt.
5. Press **F10** to complete the export.
6. Put file on a floppy or zip disk, whichever is necessary
7. Transfer the ASCII file from floppy/zip disk to the Family CPT folder on the NT server.
8. CPT data will then be imported from Family CPT folder into a SAS dataset, using the program <u>CPT_IMP</u>.  The files will be cumulative updates that will be merged into the Family master file.

### 15.3.2 Data Import to SAS

1. Log on to a computer that has SAS on its hard drive and has access to the network folders for the Family study.
2. Run the SAS <u>cptcheck</u> program. This will update the data set and compare the CPT files to the patient files
3. Open the SAS <u>cptimport</u> program and make sure that the most recent .dat file is listed.  (You can look at the .dat files in the Family CPT Data folder.)
4. Run the SAS <u>cptimport</u> program. Write down the patient IDs from the output section (or print the output).
5. From the Family CPT Data folder, copy all patient files that were shown in the output to a floppy disk.
6. Setup the old gray Texas Instruments laptop.  You will need to watch the screen and press **F1** to Resume Setup.
  * It might say, **“Operating system not found”**.  Turn the computer off and back on again.  Press **F1** to Resume Setup.  It will prompt you to ‘hit any key’.  It should start up.
7. You may need to brighten the screen, hit the **Fn** button and up arrow keys to do this
8. Transfer the files to the old gray Texas Instruments laptop computer.
9. Transfer files to the famcpt folder.
10. Restart the computer in MS-DOS, make sure the CPT floppy disk is in the a: drive
11. At the “C:/WINDOWS:>” prompt, type **‘cd desktop’**
12. Type **“CD CPT”**
13. Type **‘CPT’**
14. From the main window of the CPT program, select the **Patient/Subject** menu
15. Select **Export Data**
16. Verify that the path is C:/Famcpt
17. Name the file by adding an **F** to the front of the date of export (Ex. If you were to do this procedure on July 4, 2004 then the name of the file would be: f070404.DAT)
18. Select **Export**
19. In Explorer, verify that they have indeed been exported, and the file has been correctly named.
20. In Explorer, transfer the files, including the newly created .DAT file to the a:/ drive and to a floppy disk.
21. Put the floppy disk into the computer with SAS and transfer the .dat file to the network.
22. Update the line in the SAS <u>cptimport</u> program to reflect the new .dat file
23. Save the changes to the program


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/conners-performance-test/15-02-harvesting-cpt-data.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    15.2 Harvesting CPT Data
  </a>

  <a href=":pages_path:/manuals/conners-performance-test" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Conners Performance Test
  </a>
</div>
</div>
