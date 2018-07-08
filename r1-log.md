# #100DaysOfCode Log - Round 1 - RGD

The log of my #100DaysOfCode challenge. Started on [01.07.2018].

## Log

### R1D1 

####React

Start learning ReactJS. Build first test site based on [tutorial](https://reactjs.org/tutorial/tutorial.html).

React appears to very very easy if you know JS. It should be really handy when working with complex UI, like Dashboards or admin Panels, since you can create components, which you can handle separately and are kind of "isolated" from each other. Along with other stacks could be really easy to build interactive & dinamic UIs for the web. 

### R1D2

#### Static File Generators

Learned about Hugo and Jekyll and created first Test sites along examples

* Jekyll
* Hugo

Hugo appears to be more easy to start with, since you only need Hugo in your machine. If you already have a Ruby dev env or are a Ruby dev, maybe Jekyll is more for you. Both are not really different in what they do. Jekyll ships with a theme, but Hugo does not.

### R1D3

#### Flat File CMS

Learned about **Grav**, **Bolt** and **Pico**.

Buil first Test Grav on Azure.

**Grav** appears to be the most mature and the way to go for complex, stable scenarios.

### R1D4

### ASP.NET MVC

Continue learning about ASP.NET MVC. Done tutorial at [see](https://docs.microsoft.com/en-us/aspnet/mvc/overview/getting-started/introduction/getting-started). 

### R1D5

#### MultiMess

Worked on my measurement app. Starting to implemente dependency injection and mapping. Learning about DI. Try to implement with AutoFac. Mapping done with AutoMapper.
It looks like Mappers can be really handy in some situations (model-DTO-conversion etc).
About DI it is a very broad thema & I just getting started. The main concept is to pass dependent objects to a class and not declare them in the class. This give us some separation and keep things losely coupled.
There are then the DI Containers, what I need to learn about.

### R1D6

#### Versioning Assemblies

Readed about best practices when versioning assemblies in .NET. Implemented what learned in my MultiMess app. 
It looks like there should be a `SharedAssemblyInfo` for all projects in a solution declaring "common" assembly attributes.
The file should be `Added as a Link` in VS, so it get compiled in all projects.

#### WebSite Crawling

Learned about Crawling. Research libs for .Net. Tested to crawl a few sites. It seems to be a **very powerful** method to fetch data from **ANY** website.

### R1D7

#### Entity Framework

Refactor my T4 data library to C#. Fixed some relations and added some entities. 
Again I see how clean C# is for me in front of VB. 
Research about EF Core and the option to use it along .NET Framework. It appears to be possible, since Core is based on .NET Standard, which can be used with all .NET Stacks.

### R1D8

#### WebSite PanojaFilms

Updated Website to desire of customer. Learned some CSS classes.

#### MultiMess

Working on DDD Design. Refactoring my code to implement some DDD patterns. Every time I learn sth new, but to be honest, every time my code looks better, more robust, more stable. I start to see the **AWESOME** power of DDD when working with No-Devs. 
There are still a lot of questions about this and I'm at the very beginning, but I start to see its advantages.
Need to understand better about differences between entities and value objects, and how to set the boundaries in my contexts. 
I suppose those are a thing of experience. Only experienced coders will be close to nail a good design at start. Every time I go through my code I see a lot of improvements, what makes things slow, but it brings a lot of valuable knowledge for me, since I **CAN SEE** why things are not working, or how they could work better if done different.
