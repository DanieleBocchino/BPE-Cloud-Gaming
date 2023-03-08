#  Cloud Gaming Platform Project
#### _This project was completed for a course in Business Process Engineering at the University of Milan_
[![AWS](https://img.shields.io/badge/AWS-100000?style=flat&logo=amazon&logoColor=white&labelColor=525252&color=FFC000)](https://aws.amazon.com/) [![Bizagi](https://img.shields.io/badge/Bizagi-8BF400?style=flat&logo=binance&logoColor=white&labelColor=525252)](https://www.bizagi.com/en) [![e3Value](https://img.shields.io/badge/e3Value-100000?style=flat&logo=e3&logoColor=white&labelColor=525252&color=029EFF)](https://research.e3value.com/)




## Introduction
This project is a theoretical implementation of a cloud gaming solution. The aim of this project is to provide a viable alternative to traditional gaming for users who do not need very high performance with some small sacrifice. This project includes a business analysis of cloud gaming platforms and a possible architecture with AWS.

## Business Analysis
The users are the primary actors in this business, and the cloud gaming platform was created for them. To use the service, users must register and pay a monthly subscription. Users can use the service on the web browser or on a dedicated application. After logging in, users can choose the game they want and start it. If the user wishes, they can stop the subscription at any time and reactivate it whenever they want. The project also includes a way for the user to report inefficiencies or functional bugs within the games or platform.

The cloud computing company is responsible for developing a service to allow users to play a large number of games. The company includes different types of workers, such as financial and management teams, and employees employed in maintaining the hardware and software of the cloud computing service. The video game company creates video games and interfaces with the cloud computing company to make its products available on the cloud game library.
## BPMN 2.0
In this project, I have created BPMN 2.0 diagram with Bizagi The BPMN diagram provides a visual representation of the business process.
![Alt Text](https://github.com/DanieleBocchino/BPE-Cloud-Gaming/blob/master/img/BPMN.png?raw=true)

## Evalue Model:
In this project, I have created an e3value model. E3value model defines the value exchanges among the different actors involved in the project.
![Alt Text](https://github.com/DanieleBocchino/BPE-Cloud-Gaming/blob/master/img/value_model.png?raw=true)

## Business Evaluation:
We have conducted a business evaluation with possible CSF (Critical Success Factors), KGI (Key Goal Indicators), and KPI (Key Performance Indicators) to ensure the success of the project.
![Alt Text](https://github.com/DanieleBocchino/BPE-Cloud-Gaming/blob/master/img/KPI.png?raw=true)

# AWS Architecture:
In the end, we have implemented a possible architecture with AWS, which includes AWS Cognito for user registration and login, Route 53 and CloudFront for DNS linking and request balancing, S3 for providing access to the game library, API Gateway and Lambda for creating a REST API, Step Functions for orchestration, Gamelift for managing all aspects of the game, and CloudWatch for monitoring any issues and displaying information on a dashboard for the company.
![Alt Text](https://github.com/DanieleBocchino/BPE-Cloud-Gaming/blob/master/img/AWS_BPMN.png?raw=true)

#### AWS Services

## Conclusion
This project demonstrates that a cloud gaming platform is a viable alternative to traditional gaming. The business analysis, BPMN 2.0 diagram, e3value model, business evaluation, and AWS architecture provide a comprehensive understanding of the project and ensure its success.

## Tools
The following tools were used in this project:

| Tools | Description |
| ------ | ------ |
| [Bizagi](https://www.bizagi.com/en) |Bizagi is a business process management (BPM) software that allows users to model, automate, execute, and improve business processes.|
| [e3Value](https://research.e3value.com/)|E3value is a methodology and software tool used for modeling and analyzing e-business models, services, and value networks. It provides a graphical notation for modeling, simulation, and analysis of business models and value networks. |
| [AWS](https://aws.amazon.com/it/?nc2=h_lg)|AWS (Amazon Web Services) is a cloud computing platform provided by Amazon that offers a wide range of cloud-based computing services, including computing power, storage, and databases, as well as other functionality to help organizations scale and grow. |

# Author
I'm [Daniele Bocchino](https://danielebocchino.github.io/) a MSc student in Computer Science at Unimi and a Cloud & Data Enthusiast. I enjoy working with AWS and have a deep interest in Machine Learning."

