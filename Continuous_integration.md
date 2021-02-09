Continuous Integration

Continuous Integration works by pushing small code chunks to your application's codebase hosted in a Git repository, and to every push, run a pipeline of scripts to build, test, and validate the code changes before merging them into the main branch.

The continuous methodologies of software development are based on automating the execution of scripts to minimize the chance of introducing errors while developing applications. They require less human intervention or even no intervention at all, from the development of new code until its deployment.

It involves continuously building, testing, and deploying code changes at every small iteration, reducing the chance of developing new code based on bugged or failed previous versions.



Why Continuous Integration?

There are three main approaches to this methodology, each of them to be applied according to what best suits your strategy.

Continuous Integration
Consider an application that has its code stored in a Git repository in GitLab. Developers push code changes every day, multiple times a day. For every push to the repository, you can create a set of scripts to build and test your application automatically, decreasing the chance of introducing errors to your app.

This practice is known as Continuous Integration; for every change submitted to an application - even to development branches - it’s built and tested automatically and continuously, ensuring the introduced changes pass all tests, guidelines, and code compliance standards you established for your app.

GitLab itself is an example of using Continuous Integration as a software development method. For every push to the project, there’s a set of scripts the code is checked against.

Continuous Delivery
Continuous Delivery is a step beyond Continuous Integration. Your application is not only built and tested at every code change pushed to the codebase, but, as an additional step, it’s also deployed continuously, though the deployments are triggered manually.

This method ensures the code is checked automatically but requires human intervention to manually and strategically trigger the deployment of the changes.

Continuous Deployment
Continuous Deployment is also a further step beyond Continuous Integration, similar to Continuous Delivery. The difference is that instead of deploying your application manually, you set it to be deployed automatically. It does not require human intervention at all to have your application deployed.
