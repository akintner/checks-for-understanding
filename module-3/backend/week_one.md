## Week One - Module 3 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week (which is a TON!). 

Note: When you're done, submit a PR. 

1. What is `json` and why is it important? JSON stands for JavaScript Notational Object, and it's a data interchange format that is now widely used for APIs because it's both quickly machine and human readable.  
2. What's the difference between `joins` and `includes` in ActiveRecord? A `joins` allows you to specify which associated tables you want to use from a set of database tables. The `includes` method allows you to specify first which exact associations you want loaded without having to load all the associations (a.k.a. it is a way to speed up the load time for some queries by specifying in advance all the details you want to load instead of just loading everything).  
3. What's an API? It is an application program interface, which means that it's a way to set routines and protocols that help different systems and applications talk to each other and exchange small bits of data while keeping the actual database hidden inside the program.  
4. How do we test an internal API (in general)? We would want to use controller request tests.  
5. What are two different ways to customize your `json`? First you can tell the program to parse JSON, and then you can use a serializer that specifies how you want the JSON returned.  


