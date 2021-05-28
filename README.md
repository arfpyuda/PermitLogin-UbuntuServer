# PermitLogin-UbuntuServer
Jika mengalami permission denied ubuntu server

## Merubah PermitRootLogin

- sudo nano /etc/ssh/sshd_config

## Ubah dan tambahkan seperti yang di beri tanda "*" dibawah ini

#LoginGraceTime 2m

*PermitRootLogin yes

*PermitRootLogin prohibit-password

#StrictModes yes

#MaxAuthTries 6

#MaxSessions 10
