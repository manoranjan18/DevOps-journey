k8s configuration and security 
---------------------------------------------------------------
config maps:
--------------------------------------------
  
config maps allows you to store key value pairs which is non-confidential
and also it allows you to decouple your containerized image and allow you to run on different environments 

secrets:
--------------------------------

it is a way in which you can able to  store some confidential data inside it 
like password username etc

security :
-------------------------------
there is generally 3A's inside the kubernetes access control

1.Authentication

2.Authorization 

3.Admission 

authentication is the one in which when ever the request comes n it will check whether the 
credentials are valid 

authorization is the one in which authenticate user have the right to operate or perform some 
tasks .if not means then it will reject the authorization

admission is the one in which which checks it does not violate any of the defined policies 

In kubernetes there is different kind of authorization present 

1.RBAC

role based access contorl in this you will create seperate users with seperate functionalities and
roles and you will bind them into them 

2.Webhook  authorization
 
it is an external service which is based on simple HTTP callback functions and it will be only 
allowing whether the request should be allowed or not 


