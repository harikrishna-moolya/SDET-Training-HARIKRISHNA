CAUSE

I first edited hk.txt in the main branch and pushed the changes.

Later, I switched to the develop branch and made another update in the same file.

Both branches had changes on the same part of hk.txt.

When I raised a Pull Request (develop → main), GitHub detected that the two versions couldn’t be merged automatically.

Because of these overlapping edits, a merge conflict occurred.

RESOLUTION STEPS

I checked out the main branch, edited hk.txt, committed, and pushed the update.

Then I switched to the develop branch and added the new line (“HELLO FROM DEVELOPER”) in the same file.

I committed and pushed the develop changes to GitHub.

When I created the Pull Request, GitHub showed “Can’t automatically merge” due to the conflict.

I clicked Resolve conflicts inside GitHub.

I manually removed the conflict markers and kept only the correct content I wanted.

I clicked Mark as resolved and committed the fix.

GitHub updated the PR to “No conflicts” after the correction.

I clicked Merge Pull Request to complete the merge.

RESULT

The merge conflict in hk.txt was successfully resolved in GitHub using the Pull Request workflow.

The final version of hk.txt now contains the correct content without any conflict markers.

Both main and develop branches are updated and synchronized
