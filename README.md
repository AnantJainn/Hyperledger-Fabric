HLF Design & Setup - Fabric 2.x
===========
Version Log
===========
July         2020            v2.1-1.1
Minor Release:  
* Added docker/raft for RAFT samples
* Added docker/tls for TLS samples
* Updated multiple scripts under the docker subfolders
* Updated setup scripts to address minor issues

Upgrade from v2.1-1.0:
* Overwrite your existing project source folder - this way you may use your existing VM setup


July         2020             v2.1-1.0
Major release
* Updated VM to Ubuntu 18.x 
* All of the Fabric binaries | samples updated to Fabric 2.1
* All of the scripts updated to reflect the "Chaincode Lifecycle" enhancements in Fabric 2.x
* Introduced the "Virtual Box Express Install"
* New sections on chaincode lifecycle management (enhanced in 2.x)

PS: To upgrade you MUST create a new VM and setup the environment as the OS is now Ubunto 18.04, where as the earlier version used Ubunto 16.04


Dec          15, 2019         v1.4-3.2
Minor release

* setup/fabric-install.sh    Shim installation changes (Now it takes LONGER - please be patient)
* Updated GoLang to version 1.2.14
* Removed '-o' from cloud/bins/peer/launch.sh

Oct          22, 2019         v1.4-3.1
Minor release
* Updated the scripts to execute with bash  (some students reported permission issues)
* Updated the Kafka version to 2.12-2.1
* Added a script for environment validation    setup/validate.sh
* Updated the cleaner script

July         25, 2019         v1.4-3

* Updated the docker-compose install script
* Updated the peer/simple-two-org/README.md 
* Added the project folder k8s (Kubernetes)

Feburary     20,2019          v1.4-2

* Addition of a new project folder for docker setup
* Some of the YAML files fixed for unsupported v1.4 LogLevel/LogFormat parameters

Feburary     10, 2019         v1.4-1
MAJOR Update requires the creation of a new VM.
Follow the setup steps in the setup/README.md file

December     11th, 2018       v1.3-3
* Minor bug fixes etc.

November     4th, 2018        v1.3-2
* Changed the scripts to address the permissions issue

November     8th, 2018        v1.3-1

PLEASE REFER to note below for upgrading from lower version to this version

- fixed the solution to exercise "  Exercise-Setup a new Channel Profile with 2 Orgs"
- Updated the setup scripts to take care of the caserver.sh setup issue
- Fixed minor issues

To upgrade you MUST create a new VM as the binaries will be switched to version 1.3
Do not forget to destroy the VM for v1.2
PS: If your earlier VM is running then the VM for v1.3 will fail to launch 

October      5, 2018        v1.2
September    26, 2018       v1.0
