## 12.12 Data Procedure

### 12.12.1 Testing and Raw Data Download

Testing should be administered according to study protocol.  After completion of the test, raw data files are saved on a floppy disk, using the following general naming conventions:

RF1234__.000
RF1234ns.000

* R to identify it as a rhinometry file
* F to identify Family Study
* 1234 – 4-digit Participant ID
* __  – 2 underscores
* Ns identifies test after nasal drops

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    There should be two files for each ID, one before and one after administration of nasal drops.  Raw data disks are returned to the Research Center for processing.
  </p>
</div>

### 12.12.2 Upload and Backup of Data

Upon receipt at the Research Center by a designated research assistant responsible for Rhinometry data, data is uploaded to the network file server and backed up on floppy disk.  In order to carry out the data procedures a computer needs the following specifications (typically DCEPC109 is used):

* Windows 2000 or higher, with connections to DCE network
* Floppy drive
* Oral_scoring.bat batch file installed (found in the Family Data Procedures folder)
* Network drive N:\ mapped to Family Study folder
* SAS for Windows V9.1x installed
* Rhinometry scoring software (ORAL 5.03) installed

#### 12.12.2.1 Upload Data to Network

Copy files from floppy disk to the Rhino transfer folder and to the appropriate folder on the study’s network drive.

#### 12.12.2.2 Backup Files on Disc

Insert a backup floppy disk and copy files from the Rhino transfer folder to the backup disk. The files in the transfer folder can then be deleted.

### 12.12.3 Check Rhinometry Files

1. Verify the number of Rhinometry files existing in the network Rhinometry directory.  This will be the number of files you will expect to be read in by the SAS program.
2. Open the SAS System for Windows, and open the program <u>Rhino Check.sas</u> from the study’s SAS folder.
3. Submit the program by clicking the Run button from the toolbar.
4. When the program has completed running, check the Log by clicking on **Log** at the bottom of the screen.
5. Check the log. At the very end of the log, check that the number of records written to the userfile match the number of files you expected.
6. Page up through the rest of the log and check that there are no red or green ERROR messages.  If you find errors, contact a data manager for troubleshooting.
7. Check that you do not see details of a data file printed in the log.  This may happen if a file is corrupted or has too few or too many lines in it.  The program cannot read it in properly and you will see errors like the following:
<div class="center">
  <img src=":images_path:/12.12 Data Procedure.png">
</div>
 * If this occurs, check the file that was the last one read in (PT3514 in the example above) to verify that it has the correct number of lines and otherwise appears to be in the correct format.  Rhinometry files should contain 214 lines.
8. Print the Output. In addition to reading in the Rhinometry data and creating an updated userfile for the ORAL software, the Rhino Check program also creates some data checking reports. When the program has run without errors, go to the output by clicking on Output at the bottom of the screen.
9. Print the output and give to the study Coordinator. Note in the output those studies listed under “Percent difference in the two measurements exceeds 10%.”  These will be used in scoring curves.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/rhinometry/12-11-equipment-maintenance.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    12.11 Equipment Maintenance
  </a>

  <a href=":pages_path:/manuals/rhinometry" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Rhinometry
  </a>

  <a href=":pages_path:/manuals/rhinometry/12-13-score-rhino-print-reports.md" class="btn btn-success">
    12.13 Score Rhinometry Curves and Print Reports
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
