# flightjournal
Pilot logbook

Relatively simply logbook idea written in C++ and utilizing SQLite for storage. Primary target is Linux systems.

I know . . . why do we need ANOTHER pilot logbook program when there are already at least three major commercial applications in the wild? Answer: none work well (if at all) with Linux. Logbook Pro uses a non-industry standard databse backend and has no use for SQL. Don't know much more about LogTen or AeroLog, however.

Depends:
 - sqlite3 ... 3.27.2
 - qt 5.15 ... 5.15.1
 - tbd compression library (probably libbz2 as I am partial)
 - libtar (for . . . reasons)
 - other stuff I'm forgetting ...
