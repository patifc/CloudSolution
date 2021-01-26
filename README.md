# CloudSolution
Assignment Introduction

Introduction
‘Medi-Advice’ is a SME Medical Company start up based out of Dublin, Ireland that have hired
you to architect an infrastructure in AWS to meet their application needs.
Medi-Advice have built an online medical diagnosis assistance application for users in Ireland
and also in North America. They have been in business for 2 years.
The application connects patients and doctors to allow online appointments, remote
consultation, remote diagnosis, electronic prescription transfer and payment services.
The application allows patients to upload documents and images. Text is extracted from
documents, and images are converted into multiple formats. This is currently a manual
process but would like recommendations to help automate some of these processes.
Medi-Advice have a small technical services team that support their infrastructure and
application. Currently, there are two web application servers that connect to two application
servers connecting to a database server (as shown in Figure 1). However, if the database
server goes down, the application servers are useless because they can't connect and retrieve
data. As the application has recently been launched publicly, they have had some major
outages with the infrastructure whereby patients and doctors have not been able to access
patient records on the database.
Another issue that that Medi-Advice have highlighted to you is at present, they are very slow
to respond to changes with their resource needs. E.g. If there is a demand in traffic, a technical
services member will need to manually boot a machine and add it to it’s fleet of web servers.
They would like recommendations on best practices on how to ensure their architecture can
handle changes in demand in the future.
There is also a big demand for the application both in Ireland and in the US. Doctors and
patients in the US have complained of slow access speeds and ‘slow loading times’.
Finally, Medi-Advice have informed you they require the system to have five nines availability.

References:

Amazon Web Services, Inc.. 2021. MedStar Health Case Study. [ONLINE] Available at: https://aws.amazon.com/solutions/case-studies/medstar-health/?did=cr_card&trk=cr_card. [Accessed 15 December 2021].
Amazon Web Services, Inc.. 2021. Amazon CloudWatch - Application and Infrastructure Monitoring. [ONLINE] Available at: https://aws.amazon.com/cloudwatch/. [Accessed 15 December 2021].
Amazon Web Services, Inc.. 2021. Amazon S3 Batch Operations - AWS. [ONLINE] Available at: https://aws.amazon.com/s3/features/batch-operations/. [Accessed 05 January 2021].
What is Identity and Access Management and Why is it a Vital IT Security Layer | BeyondTrust. 2021. What is Identity and Access Management and Why is it a Vital IT Security Layer | BeyondTrust. [ONLINE] Available at: https://www.beyondtrust.com/blog/entry/what-is-identity-and-access-management-and-why-is-it-a-vital-it-security-layer. [Accessed 05 January 2021].
South, G., 2020. Designing and Implementing A Proof-of-Concept Cloud Solution Based On A Client’s Needs. [pdf] Dublin: Greg South. Available at: <https://moodle.cct.ie/> [Accessed 5 January 2021].
Figure 2: 2021. Multi-Region Failover With Amazon Route 53. [image] Available at: <https://awsacademy.instructure.com/courses/1325/modules/items/135995> [Accessed 6 January 2021].
Amazon Web Services, Inc. 2021. Amazon CloudWatch - Application and Infrastructure Monitoring. [ONLINE] Available at: https://aws.amazon.com/cloudwatch/. [Accessed 05 January 2021].
Amazon Web Services. 2021. Achieving “Five Nines” In The Cloud For Justice And Public Safety | Amazon Web Services. [online] Available at: <https://aws.amazon.com/blogs/publicsector/achieving-five-nines-cloud-justice-publicsafety/#:~:text=It%20also%20uses%20multiple%20availability,based%20routing%20of%20client%20traffic.&text=To%20connect%20with%20an%20AWS,reality%2C%20visit%20AWS%20for%20government.> [Accessed 6 January 2021].
Docs.aws.amazon.com. 2021. Best Practices For Amazon RDS - Amazon Relational Database Service. [online] Available at: <https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/CHAP_BestPractices.html> [Accessed 7 January 2021].
2018. Architecting For The Cloud. [e-book] Amazon Web Services, Inc. or its affiliates, pp.20, 21, 27. Available at: <https://d1.awsstatic.com/whitepapers/AWS_Cloud_Best_Practices.pdf> [Accessed 7 January 2021].
2016. Cost Optimization With AWS Architecture, Tools, And Best Practices. [e-book] Amazon Web Services, Inc. or its affiliates, pp.12, 15, 17. Available at: <https://d0.awsstatic.com/whitepapers/Cost_Optimization_with_AWS.pdf> [Accessed 7 January 2021].





