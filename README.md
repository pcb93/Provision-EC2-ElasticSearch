# Provision-EC2-ElasticSearch

Elasticsearch is the distributed search and analytics engine at the heart of the Elastic Stack. 
Elasticsearch is where the indexing, search, and analysis magic happens.
Elasticsearch provides near real-time search and analytics for all types of data. Whether you have structured or unstructured text, numerical data, or geospatial data, Elasticsearch can efficiently store and index it in a way that supports fast searches

# Elasticsearch Installation using Ansible on AWS Instance, configuring Elasticsearch, install nginx and configure SSL. 

 Step1 : Create an EC2 instance using Ansible, Insert your keypair name, instance type, security group, AMI image, and instance count
 Step2 : Add the newly created host to deploy group to connect
 Step4 : Connect ec2 instance and exchange ssh key pair
 Step5 : Install OpenJDK 8, set JAVA HOME, install nginx and Elasticsearch installation using ansible.
 Step6 : Making configuration in Elasticsearch and add SSL certificates


# Resources, if any, that you consulted to arrive at the final solution


For ssh connection
https://www.digitalocean.com/community/questions/error-permission-denied-publickey-when-i-try-to-ssh

Ansible Documentation : For Roles Creation
https://galaxy.ansible.com/elastic/elasticsearch

