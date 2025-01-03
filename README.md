### Project: Scheduled Backup Script

#### Project Summary
This project involved automating the backup process for encrypted password files that were updated in the last 24 hours.

#### Accomplishments
1. **Automated Backup Script**:
   - Developed `backup.sh` to identify and back up encrypted password files updated within the past 24 hours.
   - Ensured the script created a timestamped archive (e.g., `backup-[TIMESTAMP].tar.gz`).

2. **Daily Scheduling**:
   - Configured the script to run daily using `crontab`.
   - Verified the scheduled task to ensure reliable execution.

3. **Executable Permissions**:
   - Set proper executable permissions for `backup.sh`.

4. **Testing and Validation**:
   - Conducted extensive testing to ensure the script functions as intended.
   - Captured evidence of successful execution, including:
     - Screenshots of the code.
     - Output demonstrating correct functionality.

#### Tools and Technologies Used
- Shell scripting
- Linux command-line utilities
- Crontab for scheduling
