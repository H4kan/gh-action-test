# Github repo setup
 To ensure CI is properly working check if your project contains:
- scripts: 
    - test - which starts tests
    - build - which creates/refresh directory "build" in your repo with build of your app included in it
- Github secrets: 
    - GH_TOKEN - containinig your private Github token
    - AWS_PRIVATE_KEY - containing AWS private key of your AWS EC2 instance
    - AWS_USER - containing username of AWS EC2 user
    - AWS_REMOTE - containing remote url of your AWS EC2 instance
    - AWS_BUILD_PATH - containing your desired path on AWS EC2 instance to build of your project to be sent, path is relative to AWS_USER home directory



