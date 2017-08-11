# Cloudify Fortigate TOSCA Example on Openstack

This blueprint deploys a fortigate server in an Openstack environment, with three different network interfaces.
Based on the [cloudify-hello-world-example](https://github.com/cloudify-examples/cloudify-hello-world-example).

## prerequisites

You will need a *Cloudify Manager* running in Openstack.

If you have not already, set up the [example Cloudify environment](https://github.com/cloudify-examples/cloudify-environment-setup). Installing that blueprint and following all of the configuration instructions will ensure you have all of the prerequisites, including keys, plugins, and secrets.

You will also need a [Fortigate image with a valid licence](https://support.fortinet.com/Download/FirmwareImages.aspx).


## Installation

### Step 1: In Openstack: 
Install the Fortigate image

### Step 2: In Cloudify GUI: 
* Upload the blueprint located in this repository (blueprint.yaml)
* Deploy the blueprint (change values of parameters accordingly)
* Install the deployment