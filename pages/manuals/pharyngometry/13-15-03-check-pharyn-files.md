## 13.15.3 Check Pharyngometry Files

* 1. Verify the number of Pharyngometry files existing in the network Pharynnew directory. This will be the number of files you will expect to be read in by the SAS program.
* 2. Open the SAS System for Windows, and open the program Pharyn Check.sas from the study’s SAS folder.
* 3. Submit the program by clicking the **Run** button from the toolbar.
* 4. When the program has completed running, check the **Log** by clicking on Log at the bottom of the screen.
* 5. Check the log.  At the very end of the log, check that the number of records written to the userfile match the number of files you expected.
* 6. Page up through the rest of the log and check that there are no red or green ERROR messages.  If you find errors, contact a data manager for troubleshooting.
* 7. Check that you do not see details of a data file printed in the log.  This may happen if a file is corrupted or has too few or too many lines in it.  The program cannot read it in properly and you will see errors like the following:

<div class="center">
  <img src=":images_path:/13.5.3 Check Pharyngometry Files-7.png">
</div>

 * If this occurs, check the file that was the last one read in (PT3514 in the example above) to verify that it has the correct number of lines and otherwise appears to be in the correct format.  Pharyngometry files should contain 151 lines.

* 8. Print the Output. In addition to reading in the Pharyngometry data and creating an updated userfile for the ORAL software, the <u>Pharyn Check</u> program also creates data checking reports. When the program has run without errors, go to the output by clicking on Output at the bottom of the screen.
* 9. Give output reports to the Study Coordinator.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/pharyngometry/13-15-02-upload-backup-data.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    13.15.2.1 Backup Files on Disc
  </a>

  <a href=":pages_path:/manuals/pharyngometry" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Pharyngometry
  </a>

  <a href=":pages_path:/manuals/pharyngometry/13-16-01-pharyn-printout.md" class="btn btn-success">
    13.16 Score Pharyngometry Curves and Print Reports
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
