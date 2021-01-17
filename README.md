# aws-devops-elasticbeanstalk
eb create dev-env --single
eb config save dev-env --cfg dev-env-configuration
eb create dev-env --cfg dev-env-configuration
# Links
https://dev.to/gigincg/deploy-jar-file-to-elastic-beanstalk-using-eb-cli-4f46
https://developer.okta.com/blog/2019/08/07/deploy-a-spring-boot-app-with-aws-elastic-beanstalk
https://github.com/saibalghosh1980/aws-devops/blob/main/code/elastic-beanstalk/0-EB.md