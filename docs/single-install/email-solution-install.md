# Email Solution Installation

## Build Version
[iRedMail](https://www.iredmail.org) v1.3.2 + Patches

## Preparation

* Create a jail and then continue with the steps bellow.
* [Follow the preparation steps till the download](https://docs.iredmail.org/install.iredmail.on.freebsd.html)

**[Optional] Backup Strategy**

* Create a TrueNAS dataset to backup emails.
* Mount the dataset path to the jail path /mnt/data
* Implement a backup strategy for the mail dataset to another instance of instance of TrueNAS CORE or any other *nix based OS with `zfs` and `openssh-server` installed

## Installation

Run this shell command
```bash
git clone https://github.com/iredmail/iRedMail.git | bash ./iRedMail/iRedMail.sh
```

**Keypoints**
* Don't use any passwords that contains any special characters otherwise the password may be misinterpreted which may break the script.


## Original Guide
https://docs.iredmail.org/install.iredmail.on.freebsd.html
