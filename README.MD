# Free Ledgers - Eureka
Eureka server serves as the registration server for the Free Ledgers project(https://github.com/paris0120/freeledgers). This server must be online first before other client servers can start. The default values are:
1. username: user
2. password: password
3. port: 1111

The username and password are used by other client servers to connect to this server. If you changed the setting here you need to change the settings in your client servers accordingly.

All settings are available in src/resources/eureka-server.yml.