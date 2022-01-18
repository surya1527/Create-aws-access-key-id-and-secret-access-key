#Create-aws-access-key-id-and-secret-access-key


In order to copy files from one s3 bucket to another s3 bucket it is mandatory to create AWS ACCESS KEY ID AND SECRET ACCESS KEY and to install AWS CLI.


How to get aws access key id and secret access key?

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


Then in the third and fourth step if you want to add any keywords then add or else cntinue to the last step.

In the fifth step (Final Step) you can  can see your access key id and secret key id.
(Do not share you access key id  and secret key id to anyone and for a user it is his responsibility to remember his secret key id.)




![WhatsApp Image 2022-01-13 at 17 43 07](https://user-images.githubusercontent.com/58841159/149332793-1995b3ea-7c23-4496-9289-fab2609125bd.jpeg)


THEN OPEN YOUR AWS LAMBDA AND WRITE THE PROGRAM TO COPY FILES FROM ONE S3 BUCKEET TO ANOTHER S3 BUCKET AS SOON AS IT IS TRIGGERED IN THE LAUNGUAGE YOU ARE COMFORTABLE.
In my case it is python.
For python code refer to my [repository](https://github.com/surya1527/surya1527-Copy-files-from-one-s3-bucket-to-another-s3-bucket-immediately-by-AWS-LAMBDA)


