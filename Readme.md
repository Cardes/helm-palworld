# Helm Chart Using modified steamcmd image for Openshift

## Usage Example

### Requirements
Please complete the steps mentioned inside the [Palworld Openshift Readme](https://github.com/Cardes/docker-palworld-dedicated-server/blob/develop/openshift/README.md)

### Installation
- Clone this Repository
- Copy values.yaml to mypals.yaml
- Adjust values inside mypals.yaml to your needs
- Install Helm Chart
  > helm install mypals . -f mypals.yaml
- If you changed values, just upgrade the helmchart
  > helm upgrade mypals . -f mypals.yaml

> [!TIP] 
> If you did not change the default passwords, your <appname> Pod will crash with an errormessage :)