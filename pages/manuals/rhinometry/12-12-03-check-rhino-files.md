## 12.12.3 Check Rhinometry Files

* 1. Verify the number of Rhinometry files existing in the network Rhinometry directory.  This will be the number of files you will expect to be read in by the SAS program.
* 2. Open the SAS System for Windows, and open the program <u>Rhino Check.sas</u> from the study’s SAS folder.

 * Family: <u>\\Dcefilesrv01\DCE Share Root\DCE Projects\Family Study\SAS\ Rhinometry\Rhino Check.sas</u>

* 3. Submit the program by clicking the Run button from the toolbar.
* 4. When the program has completed running, check the Log by clicking on **Log** at the bottom of the screen.
* 5. Check the log. At the very end of the log, check that the number of records written to the userfile match the number of files you expected.
* 6. Page up through the rest of the log and check that there are no red or green ERROR messages.  If you find errors, contact a data manager for troubleshooting.
* 7. Check that you do not see details of a data file printed in the log.  This may happen if a file is corrupted or has too few or too many lines in it.  The program cannot read it in properly and you will see errors like the following:

 MISSING_IMAGE

 * If this occurs, check the file that was the last one read in (PT3514 in the example above) to verify that it has the correct number of lines and otherwise appears to be in the correct format.  Rhinometry files should contain 214 lines.

* 8. Print the Output. In addition to reading in the Rhinometry data and creating an updated userfile for the ORAL software, the Rhino Check program also creates some data checking reports. When the program has run without errors, go to the output by clicking on Output at the bottom of the screen.
* 9. Print the output and give to the study Coordinator,  Note in the output those studies listed under “Percent difference in the two measurements exceeds 10%.”  These will be used in scoring curves.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/rhinometry/12-12-02-upload-backup-data.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    12.12.2 Upload and Backup of Data
  </a>

  <a href=":pages_path:/manuals/rhinometry" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Rhinometry
  </a>

  <a href=":pages_path:/manuals/rhinometry/12-13-01-00-rhino-printout.md" class="btn btn-success">
    12.13 Score Rhinometry Curves and Print Reports
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
