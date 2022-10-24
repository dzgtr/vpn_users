# VPN IPconfig script
Creates nftables-user.conf and user config files based on .ODS table

Requirements:
```
cpan Spreadsheet::Read
cpan Spreadsheet::ReadSXC
```

Destination folders have to exist:

```
my $userfile_path = "./users/";
my $nftablesfile_path = "./nftables/";
```
