## 17.15.1 Checking Outliers Procedure

1. Double click on the <u>Outlier.exe</u> icon placed on the desktop.  DOS window will open and program will prompt for Participant ID.
2. Enter Participant ID and press **Enter**. Program will check the following:
 
 * <u>Typed participant ID, name of the folder containing final report, and name of the report (text file) are matching.</u>  If not error message will appear and program will stop.
 * <u>Typed participant ID and first field of the report (which should be participant ID) are matching.</u>  If they are not error message appears (program will not stop).
 * <u>Scorer ID is correct.  Program is checking, if second field of the SAS report is three-digit number starting from 9.</u>  If it's something else error message (scorer ID out of range) appears.
 * <u>First and last lines of the report do not have string "30sec".</u>  When this string is found message: "30sec found in the first (or last) line of the report" appears.
 * <u>Presence of the outliers in the final report.</u> If any outlier is detected message appears on the screen with the description of outlier and actual value of outlier. If no outliers are detected message "No Outliers Found” appears. The following values will be considered outliers:

     * 0% of Stage 1, Stage 2 or Stage REM
     * 90 % of any stage of sleep (Stage 1, Stage 2, Deep Sleep, Stage REM)
     * Arousal Index < 3
     * Min O2sat < 40 %
     * Min duration of respiratory event < 10 sec.
     * Max duration of resp. event  > 150 sec

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    Duration of respiratory event should be at least 10 sec, but due to the rounding error (length of events is rounded on the computer screen and truncated at the reports) some events length 9 sec will be left in the report.
  </p>
</div>

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    Program will also return outliers in the Heart Rate.  These messages should be ignored.
  </p>
</div>

<div class="bs-callout bs-callout-info">
  <p>
    <strong>Note:</strong>
    When edited lights are set to one epoch before sleep onset in the report, sleep latency (seventh number in the first line) will be reported as “30sec”.  Programs dealing with outliers are not set to pick this one. It will be ignored.  It will cause errors in reading the report to SAS.   To correct this, the report has to be open and the string “30sec” has to be manually replaced with **“00:00”**. Save report.
  </p>
</div>


<div class="center">
<div class="btn-group">
  <a href=":pages_path:/manuals/polysomnography/17-15-00-checking-outliers.md" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-left"></span>
    17.15 Checking Outliers After Scoring
  </a>

  <a href=":pages_path:/manuals/polysomnography" class="btn btn-default">
    <span class="glyphicon glyphicon-chevron-up"></span>
    Polysomnography
  </a>

  <a href=":pages_path:/manuals/polysomnography/17-15-02-troubleshooting.md" class="btn btn-success">
    17.15.2 Troubleshooting
    <span class="glyphicon glyphicon-chevron-right"></span>
  </a>
</div>
</div>
