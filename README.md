<h1>Create-aws-access-key-id-and-secret-access-key</h1>




In order connect our system to aws account we need to install AWS CLI. </br>
In case if you have aws access key id and secret access key <a href="#aws_Configure">click here</a> to directly move the configuration step.</br>

How to get aws access key id and secret access key?</br>

=> In order to get aws access key id and secret key we need to create user in the IAM(Identity and Access Management).

<img width="1411" alt="Screenshot 2022-01-13 at 15 22 18" src="https://user-images.githubusercontent.com/58841159/149307445-7f783fb8-a539-4d9d-9c2e-ad6ae1e2700f.png">

=>Then go to users and click on Add user
=>As soon as you click on add user then we can see the a blank box for to write a user name


![WhatsApp Image 2022-01-13 at 17 43 21](https://user-images.githubusercontent.com/58841159/149330024-9da478ef-b981-4988-88f4-f938e581c410.jpeg)


Then in the second step you can see three options 

1) Add user to group
2) copy permissions from existing user
3) Attach existing policies directly

In my case click on the third option (Attach existing policies directly)



![WhatsApp Image 2022-01-13 at 17 44 53](https://user-images.githubusercontent.com/58841159/149330846-818e2277-cda7-4056-8c1f-5e438dac0f7a.jpeg)



Then under policies search for "s3" and under s3 click on AMAZONS3FULLACCESS




![WhatsApp Image 2022-01-13 at 17 44 13](https://user-images.githubusercontent.com/58841159/149331241-1252ea1e-494a-4044-8809-b71e8193fb25.jpeg)


Then in the third and fourth step if you want to add any keywords then add or else cntinue to the last step.</br>

In the fifth step (Final Step) you can  can see your access key id and secret key id.
(Do not share you access key id  and secret key id to anyone and for a user it is his responsibility to remember his secret key id.)




![WhatsApp Image 2022-01-13 at 17 43 07](https://user-images.githubusercontent.com/58841159/149332793-1995b3ea-7c23-4496-9289-fab2609125bd.jpeg)</br>

<div> id = "aws_configure" </div>

To configure your aws account open terminal (or command prompt in windows) and type <strong>aws configure</strong> as shown in the image and click enter.Then type you AWS Access Key ID and click enter. Then type your AWS Secret Access Key and so on type your region and your output format.</br> 
For reference see the image below</br>



<img width="601" alt="Screenshot 2022-03-04 at 23 43 42" src="https://user-images.githubusercontent.com/58841159/156819605-92128009-5edb-43e4-a2b0-75ae91edb613.png">



This is Continuous to another project <strong> Dynamo Db</strong> and <strong>Copy-files-from-one-s3-bucket-to-another-s3-bucket-immediately-by-AWS-LAMBDA Project.</strong></br>

For (Copy-files-from-one-s3-bucket-to-another-s3-bucket-immediately-by-AWS-LAMBDA Project) python code refer [here](https://github.com/surya1527/surya1527-Copy-files-from-one-s3-bucket-to-another-s3-bucket-immediately-by-AWS-LAMBDA) </br>

For (dynamo db operations) python code refer [here](https://github.com/surya1527/Curd-operations-in-dynamodb)</br>
