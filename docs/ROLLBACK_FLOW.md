# Askutty Rollback Flow

Rollback means returning to the last known working state.

## Before Any Patch

1. Save current file state.
2. Save current git status.
3. Write what will change.
4. Apply patch only after approval.

## If Patch Fails

1. Stop the changed process.
2. Restore previous files.
3. Run doctor check again.
4. Report what failed.
5. Wait for Aslam approval before retry.

## Small Version

For now this file is a process guide.

Later it can become a real rollback script.
