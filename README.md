# CVE-2024-1071 with Docker

🎯 Want to practice with the new WordPress CVE ? Follow the instructions

## Build the lab

1. Install Docker : https://docs.docker.com/get-docker/
2. Clone the project : `git clone https://github.com/Trackflaw/CVE-2024-1071-Docker.git`.
3. Go to the project : `cd CVE-2024-1071-Docker `
4. Launch the Docker Compose file : `docker compose up -d`.
5. Connect to `http://localhost` with `root:root` credentials.
6. Activate the plugin in http://localhost/wp-admin/plugins.php
7. Activate `Enable the use of a custom table for account metadata` option in http://localhost/wp-admin/admin.php?page=um_options&tab=misc

## PoC

https://github.com/Trackflaw/CVE-2024-1071-Docker/assets/78696986/e4c31c76-e7e2-415f-8142-15325c179f9b

## Automation

Many PoCs are available online to automate the exploitation of this vulnerability:

- https://github.com/gbrsh/CVE-2024-1071
