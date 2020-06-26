# Fibonacci-calculator
Multi container deployment using docker

Multi-container setup
1. Push code to github master branch
2. Travis automatically pulls the repository
3. Travis builds a test image and tests the code
4. Travis pushes the build production images to Docker hub
5. Traivs pushes the project to AWS ElasticBeanStalk
6. Elastic BeanStalk pulls the image from Docker hub and deploys the code.

Tools used:
1. Travis CI 
2. Docker
3. Docker Hub
4. AWS ElasticBeanStalk
5. AWS Relational Database service 

Language used: 
1. React
2. Node/Express
