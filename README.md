# Hello, Alexa!

This is the code project for the [Hello, Publish to AWS!](https://davidpallmann.hashnode.dev/hello-publish-to-aws) blog post. 

This episode: Publish to AWS and enhanced deployment from Visual Studio. In this Hello, Cloud blog series, we're covering the basics of AWS cloud services for newcomers who are .NET developers. If you love C# but are new to AWS, or to this particular service, this should give you a jumpstart.

In this post we'll introduce the Publish to AWS feature of the AWS Toolkit for Visual Studio and use it deploy a "Hello, Cloud" .NET web application to multiple cloud services. We'll do this step-by-step, making no assumptions other than familiarity with C# and Visual Studio. We're using Visual Studio 2022 and .NET 6.

## Our Hello, Publish Project

We will create an website with an Angular front end and an ASP .NET MVC back end. We'll use Publish to AWS to deploy the website to AWS Elastic Beanstalk. Then we'll publish the same app to Amazon ECS. Lastly, we'll publish the app to AWS App Runner. In each case, Publish to AWS will do all the work, including creating the AWS service and required artifacts such as IAM roles.

See the blog post for the tutorial to create this project and run it on AWS.

