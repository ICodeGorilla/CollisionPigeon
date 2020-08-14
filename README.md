# Collision Pigeon

The purpose of this technical assessment is to provide you with an opportunity to demonstrate how you implement a solution.  We will be assessing your overall approach to the implementation including, but not limited to, automated testing, design patterns and coding style.

Our team predominantly utilises C# .NET Core for our platform and this assessment will focus on delivering a simple .net core microservice.  You are welcome to use any coding resources, free packages or libraries that you feel are appropriate.

Requirement: 

Create a microservice for registering users on the platform using C# .NET Core, Swagger and Entity Framework Core.  You are encouraged to utilise the in-memory database feature of Entity Framework Core.

1.	Post /users
{
  username: “name”
}
Duplicate usernames are not allowed.  
Users should be assigned an incremental id.

2.	Get /users
[
  {
    userId: 0,
    username: “name”
  }
]
Collection should be ordered by user id.

3.	Put /users/{id}
{
  username: “name”
}

4.	Del /users/{id}
