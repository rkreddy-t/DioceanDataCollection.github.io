# DioceanDataCollection Application

## Introduction
This application development process is a part of capstone course, where our team had developed an application to meet the needs of our client "Diocese of Bridgeport".

## About our client
The Diocese of Bridgeport is a Latin Church ecclesiastical jurisdiction or diocese of the Catholic Church located in the southwestern part of the state of Connecticut in the United States. It is a suffragan diocese in the ecclesiastical province of the metropolitan Archdiocese of Hartford.

The Diocese of Bridgeport includes all of Fairfield County, Connecticut and oversees 84 parishes located across 26 cities.


## Need for an application

The Diocese of Bridgeport collects data on the operations of all its parishes. This includes financial data, attendances, activities at the
different parishes and historical data. There are several datasets that need to be periodically collected. Some are available through third-party
services and housed on different platforms. All these differences make it difficult to extract, process, and create custom reports of the data. The goal of this project is twofold: developing an application that collects and maintains all the information in a data warehouse and providing a user interface to easily generate reports and visualizations.


This application developed on Appian, comes in use by collecting data using REST base API's, Webforms and Historic data uploads. The collected data is stored on a centralized data base and this data is used to generate visulizations using tableau which helps in examing the parish performances.


## what is Appian? 
Appian is an industry-leading, modern ‘low-code’ platform that helps businesses manage their processes, cases, and customers more effectively.  
For more information please checkout the ([https://appian.com/about/explore/overview.html](url))


## Architecture used 
We had used layered architecture for application developement and it comprises on mainly 3 layers. 

* User layer
- Processing layer
+ Data layer

