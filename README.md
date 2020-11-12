# Udagram
Deploy a High-Availability Web App using CloudFormation
To spin up a new stack run the create.sh followed by a stack name, like -
> ./create.sh <Stack_name> udagram1.yml udacity-parameters.json 

Diagram for the whole infrastructure is provided [here](/udagram.png)

Output URl for the website is [Udagram](http://udagr-WebAp-15ZY4Q2OOMAWA-606931153.us-east-2.elb.amazonaws.com/Udagram-website)

## Note
Replace the address of the static website with the s3 address of your own static website to the WebAppLaunchConfig section in the [cloudformation file](/udagram1.yml) (Lines 275-277).