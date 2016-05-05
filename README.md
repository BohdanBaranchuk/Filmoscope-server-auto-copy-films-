# Filmoscope-server-auto-copy-films-
The program moves films between directories and adds essential xml file.
Put it in a startup, select TMP1 directory,select TMP2 directory,select directory with ready films and essential xml file. 
After these actions click "Run". 

The algorithm of the program:
In each film's directories in TMP1 copies one xml file, after this all films moves in TMP2.
The program waits until each of films in TMP2 contain filmoscope.upd and folder.jpg, after this films move in Moves directory.
