# Microservices Hands-on Workshop

## Step:1 Pre-requisites(Please install the applications mentioned below).
### Laptop with access to the Internet
### Install Intellij or your choice of IDE to build a java based microservice. Link to download IntelliJ for your machine.
    Windows: https://www.jetbrains.com/idea/download/#section=windows
    Linux: https://www.jetbrains.com/idea/download/#section=linux
    Mac: https://www.jetbrains.com/idea/download/#section=mac
### Install Docker Desktop. Please select the binary to install based on type of machine(windows/linux/mac) that you use.
    https://www.docker.com/products/docker-desktop
https://docs.microsoft.com/en-us/virtualization/windowscontainers/quick-start/set-up-environment?tabs=Windows-10-and-11#install-docker
### Java JDK 1.8 or the latest for building the microservice.
### Install git 
    https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
### Install Postman or similar API Tool. Link to install postman.
    https://www.postman.com/downloads/
### Install nodeJs
    https://nodejs.org/ru/blog/release/v14.5.0/
### Install npm 
    npm install -g npm
### Install yarn
    https://classic.yarnpkg.com/lang/en/docs/install/#mac-stable
### Add axios
    yarn add axios
### Install Vue JS
    npm install vue
### add nuxt    
    yarn add nuxt
### Install AWS Cli
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html

After Installing AWS Cli, create test creds for DynamoDB by running "aws configure" in terminal(powershell/comnand prompt).
  
       Please use below values when asked. 
       
        AWS Access Key ID [None]: testid
        AWS Secret Access Key [None]: testSecret
        Default region name [None]: us-east-1
        Default output format [None]: json

### Install Visual Studio code
https://code.visualstudio.com/download

### Download dynamodb docker for testing by running in the commandline.
docker pull amazon/dynamodb-local:latest
