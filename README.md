
Edge Sense Protocol Connector includes  EI-Agent, MQTT-BUS, Node-RED, SUSIControl, Modbus, and HDD-PMQ Services on x86_64 Ubuntun 16.04 Dokcer Image.

#Requirement
Arch: x86_64
OS: Ubuntu 14.04 x86_64
Docker Engine: 1.12.6
Docker Compose: 1.9.0

# Deploy
You can run deploy.sh to deploy the Edge Sense Protocol Connector

```go
Deploy SW Service: Pull and run all Edgse Sense Southbound services ( MQTT-BUS, SUSIControl, Modbus, HDD-PMQ )
$./deploy.sh

Pull all of Southbound images
$./deploy.sh pull

Start all of Southbound Container Services
$./deploy.sh start

Stop all of Southbound Container Services
$./deploy.sh stop

Stop and remove all of Southbound Container Services
$./deploy.sh down

Restart all of Southbound  Docker Container Services
$./deploy.sh restart

Remove all of Southbound Docker images
$./deploy.sh rmi

# Northbound Agent
Pull and Run 'EnSaaS'
$./deploy.sh connector EnSaaS





```

