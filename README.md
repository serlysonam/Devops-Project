# Devops-Project
End to end Devops project


<img width="662" alt="image" src="https://github.com/serlysonam/Devops-Project/assets/47883763/ba69371b-5cf3-4929-9f95-8c6bbdbf3a23">

<img width="684" alt="image" src="https://github.com/serlysonam/Devops-Project/assets/47883763/f99e5652-432d-41ec-812a-6785b87bba15">

<img width="696" alt="image" src="https://github.com/serlysonam/Devops-Project/assets/47883763/a3e8dbc8-7692-46e8-817f-f9cc57de5ce6">

launch EC2 instance:
setup jenkins server:
ssh -i **keypair** **user**@public_ip
ssh -i Devops_project_key.pem ec2-user@54.90.235.238
sudo su-
--jenkins redhat packages
sudo wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
sudo rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io-2023.key
amazon-linux-extras install epel
amazon-linux-extras install java-openjdk11

