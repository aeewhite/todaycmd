# todaycmd

This is basically just a wrapper around exectuting multiple scripts in a directory. 


## Usage

Just execute the `todaycmd.sh` script. That script will run each of the "modules" in the modules directory in alphabetical order. You can disable a script by putting a `#` in it's filename.

## Built-in Modules

`agenda.sh` - This calls `todayview`, a program I wrote to print the events from OS X's system calendar. Can be found [here](https://github.com/aeewhite/todayview)

`weather.sh` - Executes a request to [wttr.in](http://wttr.in/) and truncates the weather report to just the current day

`fortune.sh` - Just makes a call to `fortune (6)`

Feel free to add or remove modules to your liking. They can be any exectuable file that can be run with `./filename`
