# FILE_LOCKS<br />
**Created Date:** 10/12/2010<br />
**Last Updated:** 12/10/2013<br />
**Description:** This program uses the chklock utility to determine which record is locked
in a Synergy Isam file. The program displays the User PID, isam key,
filename, username, terminal name and terminal number.<br />
**Platforms:** Windows; Unix<br />
**Products:** Synergy DBL<br />
**Minimum Version:** 6<br />
**Author:** William Hawkins
<hr>

**Additional Information:**
The file RECORD_LOCKED.DBL is not used by FILE_LOCKS.DBL, but contains two
subroutines; ISAM_READS which can be used to replace a READS statement, and
can return the key that is locked, and ISAM_READS_LOCKED which can be called,
after a READS statement has returned a record locked error, to get the key
of the record that was locked. Updated for compatibility with Synergy 9.5
