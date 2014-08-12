## 17.14 Scoring Procedures

For more details on scoring rules, please refer to the <u>Family Reading Center PSG Manual</u>.

Setup of the screen used for scoring should be the same on all scorers’ computers.  The setup used for staging and scoring arousals is saved in the polygraph <u>Family Staging.pol</u>.  The setup used for scoring respiratory events is saved in the polygraph <u>Family Respi.pol</u>.

* 1. <u>Sleep stages assigned and arousals scored</u> according to the rules below.  This is done using polygraph Family Staging.
* 2. <u>Edited lights set</u>.  This is done on the Summary screen based on the information from recorded lights and sleep stages and rules outlined below.
* 3. <u>Respiratory events scored</u> according to the rules below. Respiratory events are scored using layout called Family Respi.  Also during this pass, SaO2 signal should be screened for artifacts and all artifacts marked.
* 4. <u>PLMs (Periodic Leg Movements) scored</u>. Legs can be scored during respiratory or a second pass can be made.
* 5. <u>Entered date study was scored</u> in Patient Information window in the Date of Birth box and Scorer ID in the Martial Status box.  Also, check if box Patient Surname has Participant ID only and First Name box is empty.
* 6. <u>Participant Feedback report created</u>.  For the Family study use “Family Feedback2”.  Print copy and attach to the rest of the papers.  Save in the study folder as Rich Text Format document (.rtf).  Name of this document is Participant ID preceded with an ‘F’. Participant ID is always 3-digit Familyi and 4-digit personi.  If personi is 3 digits, precede the number with a zero.

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    Different studies have reports with the different names.
  </p>
</div>

<div class="bs-callout bs-callout-info">
  <p>
    <strong>7. Note:</strong>
    If study meets criteria for Medical Alert, e-mail needs to be sent to Dr. Redline and it has to be reviewed by PI (Dr. Redline or assigned MD) before proceeding.
  </p>
</div>

* 8. <u>SAS report created</u>. Run the <u>sas_pro5</u> program from the Profusion report option to create a SAS report. Save in the folder containing study. Name of the report should be Participant ID proceeded by letter ‘SF’ and saved as a text file (.txt)
* 9. <u>Outliers checked and removed if applicable</u>.

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    If outliers were removed, a new SAS report has to be created and outliers checked again. Delete the original SAS report and create a new SAS report as stated in Step 8.
  </p>
</div>

* 10. Copy of the SAS report placed in the SAS Reports folder and then saved as a text file in the Family SAS folder.
* 11. <u>QS form completed</u>.
* 12. <u>Scored study backup</u>.  A copy of the folder with the scored study is placed in Family Scored Files folder.  A second copy of the folder with the scored files (without Rawdata.slp file) placed on the file server (Drive N on scorers’ computer).  Then save a copy to a CD. Once the study is saved to a CD, it may be deleted.

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    Verify that the CD is working and can be read BEFORE deleting the study from the hard drive.
  </p>
</div>

* 13. <u>Scored study deleted from the hard drive</u>.

### 17.14.1 Sleep Staging and Arousals

* For staging and arousals the following tracings are displayed (from the top to the bottom of the screen):  EOG(L), EOG(R), EMG, EEG, EEG(sec) and ECG.  Timebase: (Top) 30 sec.
* As a default for scoring sleep stages and arousals, zoom for both EEGs should be x5 (full scale 125 mV).  In some cases, (alpha intrusion) scoring, use zoom x8 (full scale 250 mV).
* No tracing with the respiratory signals should be visible during this phase of scoring.

MISSING_IMAGE

### 17.14.2 Setting Lights

1. Open window by selecting **View/Summary** from the menu or clicking on the button with the blue sign **E**.
2. Lights recorded during study are on the top of the screen. Lights set up are on the bottom of this screen (called Stage Lights).  They can be changed manually by placing the cursor on the epoch and pressing **F8** key to set them ON and pressing **F9** to set them OFF.

### 17.14.3 Respiratory Events

For scoring respiratory events, the following tracings are displayed (from the top to the bottom of the screen): L Leg, R Leg, Nasal Pressure, Airflow, Thoracic, Abdomen, SaO2 and SaO2 status.  No other signals should be visible during scoring respiratory events. As a default, Timebase: 5 min/page is used.

MISSING_IMAGE

### 17.14.4 Patient Information Window

Patient Information window can be opened from menu by clicking on **View/Patient Information** or by clicking on the icon with the letter ‘I’ in the blue circle on the toolbar.  Changes made in this window are saved when the **OK** button is pressed.


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/polysomnography/17-13-06-creating-sas-reports.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    17.13.6 Creating SAS Reports
  </a>

  <a href=":pages_path:/manuals/polysomnography" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Polysomnography
  </a>

  <a href=":pages_path:/manuals/polysomnography/17-15-00-checking-outliers.md" class="btn btn-success">
    17.15 Checking Outliers After Scoring
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
