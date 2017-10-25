# Backup & Restore MySQL Database Using VB.Net

## Description
Simple Backup and Restore Application Using VB.Net for XAMPP or WAMP MySQL Database.

## Download Link
Link: [Download Here](http://bit.ly/BackRestVBNet)

## What You Need to Know
**Backup Code default format:**
```
Process.Start("[MySQL Dump File Location]", "-u [USERNAME] -p [YOUR PASSWORD] [DATABASE THAT YOU WANT TO BACKUP] -r ""[OUTPUT LOCATION INCLUDE .SQL EXTENSION]""").
```

**Restore Code default format:**
```
myStreamerWriter.WriteLine("mysql -u [USERNAME] -p [PASSWORD] [YOUR DATABASE NAME] < [DATABASE THAT YOU ALREADY BACKUP FILE PATH]")
```

## How to Use
Change this File Location based on what application you used, WAMP or XAMPP to find MySQLDump.exe and MySQL Bin Folder
### On Backup Section (Sub Backup)
* WAMP User: C:\wamp64\bin\mysql\mysql5.7.14\bin\mysqldump.exe
* XAMPP USer: C:\xampp\mysql\bin\mysqldump.exe

### On Restore Section (Sub Restore)
* WAMP User: C:\wamp64\bin\mysql\mysql5.7.14\bin"
* XAMPP User: C:\xampp\mysql\bin\"

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details

## Last But Not Least
For more info you can contact me on my social media. Visit [My Website](https://ericliputra.xyz/) for more information about this project. Thank You!