# SQLiteCobol
SQLite database for OpenCobol with patches

# How to compile 
cobc -c ocshell.c

# How to compile with OpenCOBOL ?
cobc -x -lsqlite3 your_source_code.cbl ocshell.o
