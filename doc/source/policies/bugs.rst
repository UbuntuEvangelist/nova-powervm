Nova-PowerVM Bugs
=================

Nova-PowerVM maintains all of its bugs in `Launchpad <https://bugs.launchpad.net/nova-powervm>`_.
All of the current open Nova-PowerVM bugs can be found in that link.

Bug Triage Process
------------------

The process of bug triaging consists of the following steps:

1. Check if a bug was filed for a correct component (project). If not, either change the project
   or mark it as "Invalid".
2. Add appropriate tags. Even if the bug is not valid or is a duplicate of another one, it still
   may help bug submitters and corresponding sub-teams.
3. Check if a similar bug was filed before. If so, mark it as a duplicate of the previous bug.
4. Check if the bug description is consistent, e.g. it has enough information for developers to
   reproduce it. If it's not consistent, ask submitter to provide more info and mark a bug as
   "Incomplete".
5. Depending on ease of reproduction (or if the issue can be spotted in the code), mark it as
   "Confirmed".
6. Assign the importance. Bugs that obviously break core and widely used functionality should get
   assigned as "High" or "Critical" importance. The same applies to bugs that were filed for gate
   failures.
7. (Optional). Add comments explaining the issue and possible strategy of fixing/working around
   the bug.
