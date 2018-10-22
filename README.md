# AWS Initiation

The following ReadMe displays the information required to spin up your very own virtual cloud machine using AWS(Amazon Web Services). AWS is one of the big names in regards to cloud services, along with Microsoft Azure and Google. Follow the following steps to create your own virtual machine platform using AWS.

# Step One

First of all, you will need to make an account with Amazon Web Services - Please note, AWS and Amazon are different sectors of the same company and do not relate directly. [Click Here](https://aws.amazon.com/premiumsupport/knowledge-center/sign-in-console/) to sign up. 

# Step Two

Once logged in you will have a variety of tools to available at your disposal. To access all of these features, navigate to the navbar at the top of the page and select **'services'**. Here a drop down list will display all the features you have available for being an AWS user. The option we will be focusing on is the **EC2** in the **compute** section, select on this option. 

# Step Three 
## 1

A page will be displayed from which the top section will display your journey in creating the cloud based environment allowing you to navigate back if any details need to be amended. 

'Step 1' displays the selection of the AMI(Amazon Machine Image). This image provides a selection of various template system software to use as a platform to support functionality within the environment, these include Ubuntu, Red Hat, Linux and Windows etc. with many version types i.e. windows 7, 8, 10.

## 2

The Second step involves in the components you require your machine to have. For small projects, a huge CPU and GB machine is not required. However, in the instace of a huge application transitioning into the virtual machine, a suitable machine would be required. **Please Note..** Specific machines cost accordingly.

## 3

The third step involves the configuration of instances. These are preset and generally do not need to be amended.

## 4

The fourth step contains the storage section allowing you to increase storage through attaching additional EBS(*Elastic Block Store*). If not required, continue to the next step.

## 5

The next step allows you to add tags in accordance to key:value pairs making it easier to visualise and differentiate the different machines/instances through words in appose to id's/serial numbers. An example would be *Name:Joe Bloggs* or *Owner:DB Admin*. 
**Note..** The key tags are case sensitive.


## 6

The Sixth step supports the implication of security providing a variety of preset security groups for example; SSH and HTTPS. This also allows you to provide a firewall to control traffic in any instance making it more real-life based.
  
## 7

The final step provides an overview of the tailored specifications selected to ensure that everything is correct before launching the AMI. If the user is pleased with the configuration, select launch and the system will boot up!
Hoooowever, before it does boot up, a pop up will display on the screen providing the optionality to select the key pair for your private and public key so that connection can be fired up. **NOTE..** Be warned on selecting the right keys. **Public keys can be shared but private keys cannot**.

From this, you will be able to see instances created followed by their ID's, Types, Zonal Availabilities, Instance States and various other information per variant.

