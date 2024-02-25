# Backend

PROBLEM STATEMENT – SOCIAL MEDIA APPLICATION
BACKEND:
 MongoDB, Node and Postman for Backend.
Database – 1
•	Collections – 2 (Posts details and User account details)
 ![first](https://github.com/HasikaB/Backend/assets/145472009/95a0e3ab-9ad3-4970-bb00-416a1dc9f3ff)

Postman 
•	Contains request for each functionality
![second](https://github.com/HasikaB/Backend/assets/145472009/f337ab87-6dea-4834-bb66-b29f193ca520)

 
1.)	REGISTER:
Using postman, the user details can be entered and can send request to add new user. The new user if registered successfully, the user details will be displayed below with STATUS:200 OK

![third](https://github.com/HasikaB/Backend/assets/145472009/9fd2750e-8b8f-4371-bd2c-46c81827506d)

In MongoDB the registered user details are stored and for security purpose the password is hashed without displaying the original password.

![fourth](https://github.com/HasikaB/Backend/assets/145472009/aceb7792-3465-4acb-997f-f8e6cf9f8a50)

2.)	LOGIN
-> If correct email and password are entered it displays the logged in user details with STATUS 200 OK

![five](https://github.com/HasikaB/Backend/assets/145472009/4c416625-b760-4d60-be7e-5c8850001af1)
 
-> If the email or password is incorrect will receive a message indicating Bad request.
PASSWORD INCORRECT:
![six](https://github.com/HasikaB/Backend/assets/145472009/03b21a5a-1a76-47f0-a4f8-e79044c47696)

EMAIL INCORRECT: 
![seven](https://github.com/HasikaB/Backend/assets/145472009/762efd89-e064-4a84-975c-ce7a38ebb345)

3.)	PROFILE UPDATE 
-> User can able to update profile and personal details.Also can delete user.
![eight](https://github.com/HasikaB/Backend/assets/145472009/483bd137-a199-4231-b6dc-569867872cf2)
![nine](https://github.com/HasikaB/Backend/assets/145472009/3066b172-fa53-431d-b8ec-4fee1a771174) 

4.)	Follow and Unfollow 
-> Users can follow other users, if they already follow them displays “Already following” message.

![ten](https://github.com/HasikaB/Backend/assets/145472009/9638f9dd-a02b-4690-a6bb-652148b55c13)
![11](https://github.com/HasikaB/Backend/assets/145472009/a9b6cbbf-0d58-4f4b-ae4e-db16a013d9de)
5.)	POST OPTIONS [create-upload file,update,like,dislike,timeline post]

i)	Create post
 ![12](https://github.com/HasikaB/Backend/assets/145472009/69c8dce8-65d0-49c6-89fa-4b8b10f5c417)
Added to database
![13](https://github.com/HasikaB/Backend/assets/145472009/dbc2486f-4bb5-43b1-9a09-ee8ef4884032)
 
ii)	Upload file for post it can be png,jpg,jpeg
 ![14](https://github.com/HasikaB/Backend/assets/145472009/0215d836-440e-4df3-9dfd-c95ace6148d4)
 
iii)	Update Post
![15](https://github.com/HasikaB/Backend/assets/145472009/9f50a241-11ae-4770-8c0e-5471bfb4dcf6)
 
iv)	Like/Dislike
![16](https://github.com/HasikaB/Backend/assets/145472009/d2269ba4-d2ae-494e-9a83-43a31daa584d)
![17](https://github.com/HasikaB/Backend/assets/145472009/37d0a35f-bd5a-4277-a3cf-772c1769ea30)
Likes stored in database
![18](https://github.com/HasikaB/Backend/assets/145472009/0d5f13ba-76bf-48bb-919f-1ad47839134a)
 
v)	Timeline post – indicates the posts shared by only the people who user follows in the feed with the time it has been posted.
![19](https://github.com/HasikaB/Backend/assets/145472009/6fc739af-8dae-4b8d-bed8-91bf1340b833)

6.)	SEARCH USER -Using userId
![20](https://github.com/HasikaB/Backend/assets/145472009/26b3f93c-f712-4365-8e5f-436a2693ff18)

 


