# primera_bd

Como conectar a base de ejemplo de SQLite

La base de datos de ejemplo esta en formato ZIP, por lo tanto, es necesario extraerlo a un directorio, por ejemplo, C:\sqlite\. 
El nombre del archivo es chinook.db

Primero, abre la terminal en Windows y navega al directorio donde sqlite3.exe este ubicado.

Segundo, usa el siguiente commando para conectar a la base de datos chinook ubicada en el mismo directorio.

-------------------------
|						|
|	sqlite3 chinook.db	|
|						|
-------------------------

Va a mostrar algo asi:

-------------------------------------------------
|												|
|	SQLite version 3.36.0 2021-06-18 18:36:39	|
|	Enter ".help" for usage hints.				|
|	sqlite>										|
|												|
-------------------------------------------------


Third, show all tables in the Chinook database using the .tables command:

Tercero, muestra todas las tablas en la bd chinook usando el comando .tables

-----------------
|				|
|	.tables		|
|				|
-----------------

La salida debe ser:

-----------------------------------------------------------------
|																|
|	albums          employees       invoices        playlists	|
|	artists         genres          media_types     tracks		|
|	customers       invoice_items   playlist_track				|
|																|
-----------------------------------------------------------------

Finalmente, con el comando .exit puedes salir de la herramienta sqlite3.
