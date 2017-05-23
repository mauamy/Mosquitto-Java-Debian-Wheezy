# Mosquitto-Java-Debian-Wheezy

## Install Mosquitto
```
$ sudo chmod +x mosquitto_installer.sh
$ sudo ./mosquitto_installer.sh
```
This will install the following packages:
- mosquitto
- mosquitto-clients
- mosquitto-dev

Usually the installation of these packages should automatically start the mosquitto service.
In case it does not, you can do it manually by typing this command:
```
$ sudo service mosquitto start
```

## Sample Code

The sample code already includes the required mosquitto jar-library (Version 1.1.1).
If you want to build it from source uncomment the corresponding lines in mosquitto_installer.sh

### Build 
```
$ cd SampleSrc/
$ make build
```
### Run
```
make run_sub
```

```
make run_pub
```

