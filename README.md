# powerline daemon with systemd

This is a systemd service file to start up powerline daemon on a per user basis on boot (headless).

* Place the powerline@.service file into /etc/systemd/system
* Reload the daemons: systemctl daemon-reload
* Enable the service for users: systemctl enable powerline@username
* Start service: systemctl start powerline@username
