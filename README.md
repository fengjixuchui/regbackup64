# regbackup64
Registry Backup Tool Which Addresses the Shortcomings of "ERUNT"

Goal of the regbackup64 project is to enable users to create on-the-fly backups of the entire registry on demand, and to restore the backup even while in Windows recovery mode.

Motivation:
If you really screwed your registry neither safe mode nor system restore will work.
However, you will still be able to access the Windows 10 Recovery Environment whether from your installation or from installation media.
While you can use the "ERUNT" registry backup tool to perform a registry backup you cannot use it to restore the backup
while running in the RE since it lacks the WoW64 runtime and thus does not support execution of the 32-bits "ERUNT".
