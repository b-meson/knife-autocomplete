# Knife block

A collection of bash autocomplete functions to quickly manage Cloudstack hosts and virtual machines.

## Installation

By default the tool should be in /etc/bash_complete.d/block your admin servers. If it is failing, this is because one of the requirements is that the files are populated by cron and Chef recipes, which are not being displayed in this guide.  

## Dependencies

Block requires a bash-compatible terminal. That means if you are crazy and run something like zsh, this *should* would for you if you are importing /etc/bash_complete.d/*.

## Usage

By default a Chef recipe will run cron jobs every morning at 02:00 and populate a list of all the known hosts and VMs in Cloudstack and populate the environment variables.
To use block, all you have to do is hit [TAB] in your terminal after sourcing the file (see README.md) 

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

