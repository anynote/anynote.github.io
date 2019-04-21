---
title:  "SQL or Stored procedure"
tags: database SQL stored-procedure
---

## Stored procedure

- cannot be debugged
- dont' provide much feedback when things go wrong
- can't pass objects
- hide business logic


## But stored procedure

- improve performance because the database can optimize the data access plan used by the procedure and cache it for subsequence reuse
- can be individually secured within the database
- easier maintenance, easier to modify, compare to hard-coded SQL when deploy
- add an extra level of abstraction from the underlying database schema.
The client of the stored procedure is isolated from the implementation details of the stored procedure and from the underlying schema.
- can reduce network traffic, because SQL statements can be executed in batches rather than sending multiple requests from the client.

BUT: none of these things are true in practice

## Reference

- [CODING HORROR Blog](https://blog.codinghorror.com/who-needs-stored-procedures-anyways/)