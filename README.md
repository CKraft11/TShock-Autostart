# TShock-Autostart
## TShock Terraria Autostart Service for Linux
#### Swap out the nessisary paths in the command on line ```10``` and then put the ```terraria.service``` file in ```/etc/systemd/system/``` run the following commands

```systemctl daemon-reload```

```systemctl enable terraria.service```

```systemctl start terraria.service```

Optionaly you can check the status of your new service with:

```systemctl status terraria.service```

Reference this guide if you need any help with the initial server setup:
https://stackoverflow.com/questions/54709898/how-to-install-terraria-tshock-server-on-ubuntu-server
