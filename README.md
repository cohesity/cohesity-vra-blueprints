
# Cohesity - vRA Blueprints
Pre built blueprints (XASS & Resource Actions) for vRealize Automation to orchestrate [Cohesity vRO workflows.](https://github.com/cohesity/cohesity-vro-plugin)

## Pre-requisites

 - vRealize Automation and vRealize Orchestrator
 - [Cohesity vRO Plugin](https://github.com/cohesity/cohesity-vro-plugin) - Built & installed in vRealize Orchestrator.
 - [Cloud Client](https://code.vmware.com/web/tool/4.7.0/cloudclient) - vRealize command line utility to import pre built blueprints and use cases in vRA.

## Importing Blueprints

 - Download the pre-built zip archive from [here](https://github.com/cohesity/cohesity-vra-blueprints/tree/master/build).
 
 - Launch Cloud Client instance on your local system. 
 ```
 bin/cloudclient.bat (for windows) or bin/cloudclient.sh for OSX / Linux
 ```

 -  Login to the vRA appliance and vRA infrastructure server.
 ```
 vra login userspass --user <userName> --tenant <tenantName> --server <vRA appliance server>
 ```
 
 - Import the package using
 ```
 vra content import --path <path-to-zip-file> --resolution OVERWRITE
 ```

## Documentation
Please refer to the resources [here](https://github.com/cohesity/cohesity-vro-plugin/tree/master/docs) for further guidance.
