Create by [StevenBlack/hosts](https://github.com/StevenBlack/hosts)
python3 UpdateHostsFile.py --auto --extensions fakenews gambling porn --output "/your/path/hosts/"

## HOSTS in Windows 7/8.x/10
1. Right mouse click on Notepad icon then click on `Run as administrator`
2. File → Open... then insert the path `C:\windows\system32\drivers\etc\hosts`
3. Add a new line and copy-paste the entire content of HOSTS.txt
4. Save
5. Reboot

### Using Windows PowerShell
1.  Open HOSTS.txt and add a newline to the beginning
2.  Save and close HOSTS.txt
3.  Open Windows PowerShell
4.  Run this command in Windows PowerShell: `Get-Content HOSTS.txt | Add-Content "C:\windows\system32\drivers\etc\hosts"`

### Using Cygwin
1. Open HOSTS.txt and add a newline to the beginning
2. Save and close HOSTS.txt
3. Right mouse click on Cygwin icon then click on 'Run as adminstrator`
4. `cd` to where HOSTS.txt lives
5. Run this command in Cygwin: `cat HOSTS.txt >> /cygdrive/c/Windows/System32/drivers/etc/hosts`
6. Reboot

The steps in Cygwin should be similar on in any POSIX compatible system running on Windows.

## HOSTS in Linux and macOS
1. Open the terminal
2. Type `sudo vim /etc/hosts`
3. Add a new line and copy-paste the entire content of HOSTS.txt
4. Save
5. Reboot

## HOSTS in Android=
1. Install [DNS66](https://github.com/julian-klode/dns66#installing)
2. Open [DNS66](https://github.com/julian-klode/dns66#installing)
3. Click on HOSTS button to select the "HOSTS" section of the APP
4. Click on the + floating button on the lower-right corner
5. Insert a title of your choice and the following url: https://raw.githubusercontent.com/harrypython/hosts/master/hosts
6. Save the filter you created by clicking the check mark on the top-right corner
7. Press the refresh button on the top-right corner
8. Go back to the "START" section of the APP and start it
9. You should notice a symbol indicating an active VPN on your Android system
