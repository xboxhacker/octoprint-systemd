BigTreeTech octoprint.service file:

`wget https://raw.githubusercontent.com/xboxhacker/octoprint-systemd/refs/heads/master/octoprint.service && sudo mv octoprint.service /etc/systemd/system/octoprint.service
ExecStart=/home/biqu/OctoPrint/venv/bin/octoprint
sudo systemctl enable octoprint.service`
