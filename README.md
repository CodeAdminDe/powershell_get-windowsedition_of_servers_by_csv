# powershell_get-windowsedition_of_servers_by_csv

Simple Script to get the running windows edition (e.g. for clients: Home, Professional, etc... // e.g. for servers: ServerDatacenter, etc...). 
Systems need to be accessable via PowerShell. 

## Usage

Just put a list of windows systems into a file called `hosts.csv`. Make shure that the first entry is `hosts`.
See `hosts.csv_SAMPLE` as example. ;-)

Than run the script via powershell `./get-windowsedition.ps1`.

## License
    powershell_get-windowsedition_of_servers_by_csv
    Copyright (C) 2020  Frederic Habich <frederic.habich@codeadmin.de>

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see https://www.gnu.org/licenses/.
