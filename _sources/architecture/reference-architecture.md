# 参考架构

## 认证

Identity and Access Management (IAM) 解决方案

认证

- Amazon Cognito
    - Cognito User Pool

单点登录 SSO 解决方案

## 前台

前台

- S3
- CloudFront (CDN)

## 基本架构EC2

- 前台
    - S3
    - CloudFront (CDN)
- 后台
    - Application Load Balancer (ALB)
    - EC2 (2台或扩展组)

## 基本架构Serverless

- 前台
    - S3
    - CloudFront (CDN)
- 后台
    - API Gateway
    - Lambda

## 可观测性

- 可观测性
    - ELK
        - ElasticSearch
        - Logstach
        - Kibana
    - Splunk
    - Datadog
    - Grafana
    - Graydog
    - Sumo

## 数据缓存

- 缓存
    - ElasiCache for Redis

## 数据库

- 数据库
    - DynamoDB
    - RDS for PostgreSQL

## CI/CD

共享组件服务

- AWS CodeArtifact

CI/CD管道

- AWS CodeCommit
- AWS CodeBuild
- AWS CodeDeploy

![](ci-cd.png)