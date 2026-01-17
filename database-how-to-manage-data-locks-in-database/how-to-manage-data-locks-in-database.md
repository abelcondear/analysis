## How to manage data locks in database

We can proceed following the next alternatives:

- We may use the hint "with nolock" to let other users, use the same table when another process/user is modifying that table.
- We may have on one side, a copy of the transactional database and use it for reading. On the other side, there could be the transactional database for executing updating, inserting, or deleting.
- We may insert a Java code or .Net code to catch the database events when a table needs to be changed.
- We may use sp_who intrinsic stored procedure to know the current processes which are running and we can have an overview about the processes that are locking that table we want to modify.
