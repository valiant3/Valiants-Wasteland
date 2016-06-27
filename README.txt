A3W extDB2 MySQL instructions

1. Extract everything from this folder to your Arma 3 install dir
2. Run the a3wasteland db SQL script with your MySQL tool of choice
3. Open extdb-conf.ini and put your MySQL connection infos in the [A3W] section
4. Add -filePatching to your arma3server command line, and allowedFilePatching = 1; to your server.cfg
5. Try to start your server, and hope it doesn't blow in your face

That should do it!

If you want to create a MySQL user with restricted access just for extDB, the privileges needed are: SELECT, INSERT, UPDATE, DELETE

A3Wasteland v1.2b is currently compatible with extDB2 v49 and up.

Fow Windows, you need to install Visual C++ Redistributable Packages for Visual Studio 2013 (x86):
https://download.microsoft.com/download/2/E/6/2E61CFA4-993B-4DD4-91DA-3737CD5CD6E3/vcredist_x86.exe

For Linux, you need to install libtbb2:
https://github.com/Torndeco/extDB2/wiki/Setup:-Linux-Static-Build
