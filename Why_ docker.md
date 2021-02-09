Why Docker?

Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly. With Docker, you can manage your infrastructure in the same ways you manage your applications.

Benefits of Docker

1. Reproducibility: Similar to a Java application, which will run exactly the same on any device capable of running a Java Virtual Machine, a Docker container is guaranteed to be identical on any system that can run Docker. The exact specifications of a container are stored in a Dockerfile. By distributing this file among team members, an organization can guarantee that all images built from the same Dockerfile will function identically. In addition, having an environment that is constant and well-documented makes it easier to keep track of your application and identify problems.

2. Isolation: Dependencies or settings within a container will not affect any installations or configurations on your computer, or on any other containers that may be running. By using separate containers for each component of an application (for example a web server, front end, and database for hosting a web site), you can avoid conflicting dependencies. You can also have multiple projects on a single server without worrying about creating conflicts on your system.

3. Security: With important caveats (discussed below), separating the different components of a large application into different containers can have security benefits: if one container is compromised the others remain unaffected.

4. Docker Hub: For common or simple use cases, such as a LAMP stack, the ability to save images and push them to Docker Hub means that there are already many well-maintained images available. Being able to quickly pull a premade image or build from an officially-maintained Dockerfile can make this kind of setup process extremely fast and simple.

5. Environment Management: Docker makes it easy to maintain different versions of, for example, a website using nginx. You can have a separate container for testing, development, and production on the same Linode and easily deploy to each one.

6. Continuous Integration: Docker works well as part of continuous integration pipelines with tools like Travis, Jenkins, and Wercker. Every time your source code is updated, these tools can save the new version as a Docker image, tag it with a version number and push to Docker Hub, then deploy it to production.
