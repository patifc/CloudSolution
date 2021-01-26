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
