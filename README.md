# PoshZabbixTools PowerShell Module

[![Build status](https://ci.appveyor.com/api/projects/status/github/twillin912/poshzabbixtools?branch=stable&passingText=stable%20-%20OK&svg=true)](https://ci.appveyor.com/project/twillin912/poshzabbixtools/branch/stable)
[![Build status](https://ci.appveyor.com/api/projects/status/github/twillin912/poshzabbixtools?branch=develop&passingText=develop%20-%20OK&svg=true)](https://ci.appveyor.com/project/twillin912/poshzabbixtools/branch/develop)
[![Documentation Status](http://readthedocs.org/projects/poshzabbixtools/badge/?version=stable)](http://poshzabbixtools.readthedocs.io/en/stable/?badge=stable)
[![Documentation Status](http://readthedocs.org/projects/poshzabbixtools/badge/?version=develop)](http://poshzabbixtools.readthedocs.io/en/develop/?badge=develop)

A set of PowerShell tools to interact with the Zabbix API.

## Installation

Install from PSGallery

```powershell
PS> Install-Module -Name PoshZabbixTools
```

## Getting Started

Connect to the Zabbix server using the Connect-ZabbixServer command

```powershell
PS> Connect-ZabbixServer -Server 'ServerName' -Secure -Credential (Get-Credential)
```

Get a list of available commands

```powershell
PS> Get-Command -Module PoshZabbixTools
```

## Documentation

* Full documentation is available in [ReadTheDocs](http://poshzabbixtools.readthedocs.io/en/latest/) format.

## Links

- Github - [Trent Willingham](https://github.com/twillin912)


## License

[MIT](LICENSE)


## Notes

Thanks go to:
* [Simon Morand](https://github.com/simnyc) started this idea with his [zabbixPoshAPI](https://github.com/simnyc/zabbixPoshAPI).


