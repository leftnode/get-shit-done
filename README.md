# get-shit-done
get-shit-done is an easy to use command line program that blocks websites known to distract us from our work.

After cloning this repository, put it in your $PATH and ensure it is executable.

Execute it as root because it modifies your hosts file and restarts your network daemon.

## To get-shit-done
`sudo get-shit-done work`

## To no longer get-shit-done
`sudo get-shit-done play`

### $siteList
Add or remove elements of this array for sites to block or unblock.

### ~/.get-shit-done.ini
As an alternative to above, add lines in format
sites[] = www.blah.com
to this file

### $restartNetworkingCommand
Update this variable with the path to your network daemon along with any parameters needed to restart it.

### $hostsFile
Update this variable to point to the location of your hosts file. Make sure it is an absolute path.

