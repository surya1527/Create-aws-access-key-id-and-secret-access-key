# copy-files-from-one-bucket-to-another-s3-in-python-3.


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



Then install the aws cli configure the aws cli by using the command: %   aws configure
then you would be asked to enter the access key id and secret key and continue for the region and output format.


