#DAYZSP

----------

_A **DAY-Z** server package meant to be played as a single-player game._

----------

##CORE FEATURES

- **Building**
- **Complex AI**
- **Character Progression**

##SCRIPTS
- **DZAI** - AI
- **SARGE** - AI
- **DZMS** - AI/Missions
- **Snap Build** - Better Building

##REQUIREMENTS
- **MYSQL Database Access** - Can host on your own PC or separate PC or try **[FreeMYSQLHosting.net](http://www.freemysqlhosting.net/)** or **[db4free.net](http://www.db4free.net/)**
- A computer powerful enough to run both DAYZ and the DAYZ server (or a separate computer to run the DAYZ server)

##INSTALLATION
1. Install the **Day-Z Epoch** client files through **[DayZ Commander](http://dayzcommander.com/)** or **[PlayWithSix](http://play.withsix.com)**
2. Copy the contents ARMA 2 Install folder (typically **C:\Program Files (x86)\Bohemia Interactive\ArmA 2** or in your **SteamApps\Common** folder)  to a new directory (for example **E:\DAYZ_SERVER**). This is where the server will run from.
3. Install the **Day-Z Epoch 1.0.4.2** server files by following the instructions on the **[Day-Z Epoch Server Installation Page](http://epochmod.com/wiki/index.php/Server_Installation_Instructions)**. Don't forget to run the SQL code on your MYSQL server.
4. Navigate to [**SERVER INSTALL PATH**]\Config-Examples\instance\_11\_Chernarus\ and edit the following files to fit your setup:
	* config.cfg
	* HiveExt.ini
5. Copy **DayZ\_Epoch\_instance\_11\_Chernarus.bat** and **instance\_11\_Chernarus** (directory) from the **[SERVER INSTALL PATH]\Config-Examples** to root of [**SERVER INSTALL PATH**]. The bat file will not launch the files from the proper directory otherwise.
6. Now would be a good time to test your server to make sure it works. Run **[SERVER INSTALL PATH]\DayZ\_Epoch\_instance\_11\_Chernarus.bat** and try to connect to your server (IP 127.0.0.1 by default). If it doesn't work, make sure you followed steps 1-5 properly.
7. If all goes as planned, download the modded server files from this site by clicking the **[Download ZIP](https://github.com/mudzereli/DayzEpochChernarus/archive/DAYZSP.zip)** button on the right (or use the link).
8. Navigate to **[SERVER INSTALL PATH]\MPMissions\DayZ\_Epoch\_11.Chernarus** and delete the contents of this folder.
9. Open the downloaded ZIP file and copy the contents of  the **dayz_mission** directory to the **[SERVER INSTALL PATH]\MPMissions\DayZ\_Epoch\_11.Chernarus** directory that you just deleted the contents of.
10. Navigate to **[SERVER INSTALL PATH]\@DayZ\_Epoch\_Server\addons** and delete the contents of this folder.
11. Open the downloaded ZIP file and copy the entire **dayz_server** directory (including the directory) to the **[SERVER INSTALL PATH]\@DayZ\_Epoch\_Server\addons** directory.
12. If you have **[INFISTAR](http://dayzantihack.com/)** then copy it into the **[SERVER INSTALL PATH]\@DayZ\_Epoch\_Server\addons\dayz\_server\addons\antihack** folder
13. Use your favorite **[PBO Manager](http://www.armaholic.com/page.php?id=16369)** to pack the entire **dayz_server** folder that you just extracted.