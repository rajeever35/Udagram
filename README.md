# **_Udagram_**
Deploy a High-Availability Web App using CloudFormation
To spin up a new stack run the create.sh followed by a stack name, like -
'./create.sh <Stack_name> udagram.yml udacity-parameters.json' 

Diagram for the whole infrastructure is provided [here](/udagram.png)

Output URl for the website is [Udagram](http://udagr-WebAp-15ZY4Q2OOMAWA-606931153.us-east-2.elb.amazonaws.com/Udagram-website)

## **To use it for own Static website**
* Fork the repository.
* Update the *LaunchConfiguration*.
    * Change s3 address to the s3 address of your website.zip. (Line 275 in the file [udagram.yml](/udagram.yml))
    * Also update the Udagram.zip with your website's zip file.
##### _NOTE_: You can use index.html file instead of zip file.

### **Deploying your website**
Run the following command to the terminal
> ./create.sh stack_name udagram.yml udacity-parameters.json 

To send updates
> ./update.sh stack_name udagram.yml udacity-parameters.json 

