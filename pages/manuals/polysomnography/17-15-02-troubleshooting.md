## 17.15.2 Troubleshooting

<u>When Outlier Program Reports Problems or Outliers</u>

If during checking, any changes or corrections need to be done, they can be done without exiting program (or closing DOS window).  Just let the program wait (window can be minimized) and make the necessary changes. Continue checking by typing **“c”** in the DOS window and entering the Participant ID again.

<u>When Outlier Program Cannot Open Study</u>

* Check if Participant ID was typed correctly.  If not, in the DOS window type **"C"** and retype Participant ID.
* Make sure, that study is located in the root directory of the C: drive.  If it is not, move study to the root directory C: drive. In the DOS window, type **"C"** and retype participant ID.
* Check name of the folder with the study.  If name is wrong, the folder has to be renamed.
* Check name of the SAS report.  Name has to start from the letter "S" followed by Participant ID and be saved as a text file (.txt).
* If SAS report is missing, run report (in Replay) and save it.
* If SAS report is saved as a RTF file, it does not have to be run again.  Double click on it and save again as a text file.

<u>Typed Participant ID and First Field of the Report are Not Matching</u>

1. Open SAS report (double click on it) and see what's in it.  First number has to be Participant ID and nothing else.
2. If it is something else, open study in Profusion program.
3. In the Patient Information window, erase what's in the First Name box (this box has to be empty).
4. Click **OK**.
5. Run SAS report again.

<u>Scorer ID Is Not Correct</u>

1. Open SAS report (double click on it) and see what's in it on the second place (usually it's Scorer ID missing and in the second place is date of the study).
2. To correct Scorer ID, open study in Profusion program.
3. In the Patient Information window, enter correct Scorer ID in the Martial Status box.
4. Click **OK**.
5. Run SAS report again.

<u>First (Or Last Line of the Report) Has String '30 Sec'</u>

1. Open SAS report
2. Find string "30sec" and replace it with **“00:01”**
3. Save report.  **<u>NOTE</u>:** This has to be done every time after SAS report is run.

<u>Minimum Respiratory Event Length <10 Sec</u>

This outlier needs to be corrected in the study, a new SAS report created, and checked again for the presence of the outliers.

**<u>NOTE</u>:** Due to the rounding error some respiratory events lengths (9.5-9.9 sec) can be difficult to find.  They will appear as a 10 sec long in the list of the respiratory events on the screen and 9 sec in the report.  In this case, they can be left.  On QS form, for Question 29e (outliers - other), check box "yes" and place note in the Notes section (ex. Outlier 9 sec hypopnea).

<u>0% Of Any Sleep Stages, >90% Of Any Sleep Stages</u>

There are two possible sources of this outlier:

1. Study is scored Sleep – Wake only.  In this case, nothing needs to be done with the study. On the QS form, for Question 29a (Scored Sleep Wake only), Box “yes” should be checked.
2. Unusual staging.  In this case, the study has to be checked with the other scorer. If there are different opinions, it will be reviewed during QA meeting.  If after revision, outliers remain:

* On the QS form, for Question 29b (Unusual staging), check box "yes".
* In the Box Initials/Date, write initials of Reviewing Physician (or ‘Group’ if it was group review).
* In the Notes section, enter short note with the explanation (ex. Outlier: REM=0 - real)

<u>RDI=0</u>

If outlier is real, it does not have to be reviewed.  On The QS form, for Question 29c (RDI=0 real), check box "yes”.

<u>Maximum Length of Resp. Event >150 Sec</u>

Check with another scorer.  If outlier is real, on the QS form for Question 29d (Max length of resp. event > 150s real), check box "yes".


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/polysomnography/17-15-01-checking-outliers-procedure.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    17.15.1 Checking Outliers Procedure
  </a>

  <a href=":pages_path:/manuals/polysomnography" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Polysomnography
  </a>

  <a href=":pages_path:/manuals/polysomnography/17-16-01-electrode-overview.md" class="btn btn-success">
    17.16 PSG Equipment Care and Maintenance
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
