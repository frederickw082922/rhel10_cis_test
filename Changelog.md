# Changes to rhel10CIS


## 0.1.3
Aligned with public RHEL9 fixes
5.4.2.5 - Enhancement for none existing directories thanks to @DianaMariaDDM
6.3.4.5 - fixed audit file permissions inline thanks to @DianaMariaDDM
6.3.3.5 - added missing locations for audit
Added fix for yescrypt and root password check thanks to miso321

## 0.1.2
Update to audit_only to allow fetching results
resolved false warning for fetch auditq
Improved documentation and variable compilation for crypto policies

## 0.1.1 RHEL10 - updates
Thanks to @polski-g several issues and improvements added
Improved testing for 50-redhat.conf for ssh
5.1.x regexp improvements
Improved root password check
egrep command changed to grep -E

## 0.1 RHEL10BETA - expected CIS benchmark
