yubico-pam-binddn-patch
=======================

Patch for version 2.13 of yubico-pam module.

C patch for the yubico-pam module to allow two-factor authentication on LDAP that doesn't allow anonymous binds.

git clone https://github.com/Yubico/yubico-pam.git

cd yubico-pam

patch -i path_to_patch/pam_yubico.patch

