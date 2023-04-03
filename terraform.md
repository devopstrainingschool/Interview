## 1- How to check terraform version?
```
terraform --version
```
## 2- what is a terraform resource?
#### It is an object manage by terraform
## 3- What are examples of resources?
#### VPC, EC2, Subnets, ...
## 4- What is terraform language?
#### HCL ( Harshicorp configuration language)
## 5- What is terraform hcl syntax?
#### block  paramaters {
####  key1=value1
####  key2= vlaue2
####  ..........
####  keyn=valuen
####  }
## 6- What are the types of blocks?
#### resources, data, modules, output , variables, ...
## 7- What are arguments?
#### they are key pair values.
##### On this picture the key are left of the equal sign and the value are in right
![image](https://user-images.githubusercontent.com/107158398/229578989-a5db0c21-e4f2-418b-bc87-2b4e7c198d88.png)
## 8- What does terraform init do?
#### It initialize the root directroy by installing plugins, initializing the backend, and the child modules
