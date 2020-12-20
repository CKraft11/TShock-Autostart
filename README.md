# TShock-Autostart
## TShock Terraria Autostart Service for Linux
#### Swap out the nessisary paths in the command on line ```10``` and then put the ```terraria.service``` file in ```/etc/systemd/system/``` run the following commands

```systemctl daemon-reload```

```systemctl enable terraria.service```

```systemctl start terraria.service```

Optionally you can check the status of your new service with:

```systemctl status terraria.service```

To fully confirm that your service is working simply reboot the machine you server is running on and the server should start 30 seconds after the machine boots up

Reference this guide if you need any help with the initial server setup:
https://stackoverflow.com/questions/54709898/how-to-install-terraria-tshock-server-on-ubuntu-server
