---
layout: page
title: Jaethem8 Server + Database
description: Spring Boot based blog web application
img: assets/img/12.jpg
importance: 999
category: work
related_publications: false
---

**THis Project is deprecated and no longer in service**
**Tech Stack:** TypesScript, React, Nest.JS, Serverless Framework, AWS
**Overview**
This website was created was created in order to serve as one-stop reference for Economics Data Science Research group at Drake University, specifically for API and DB development team.

> API and DB development team is sub-group of Economics Data Science Research group. Our task is to optimizing data storing and gathering, developing the interface to access the data. Currently there are over 50GB of bank audit data stored in database. If you are interested in our research, please check research section of blog. If you are interested in our API, please check the post on Bank API.
> <a href="https://github.com/Jaethem8y/research-blog-frontend">Fronted Source Code on Github</a> > <a href="https://github.com/Jaethem8y/registration-serverless">Backend Source Code on Github</a>

**Overall Architecture**

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/12.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

**Frontend**

The frontend of this application was built using TypeScript and Vanilla React. The interface was designed as simple as possible, as it was designed to be used by internally.

**Backend**

The backend of this application was created using TypeScript, Nest js, and Serverless Framework. The database was hosted on MySQL RDS. The structure of the database was very similar to Jaethem8's database. Where Post and Content had one-to-many relationships.

> The backend of this application was created using TypeScript, Nest js, and Serverless Framework. The database was hosted on MySQL RDS. The structure of the database was very similar to Jaethem8's database. Where Post and Content had one-to-many relationships.

**Serverless Related**

It was interesting to note that how similar Spring Boot and Nest js was. Usage of Injectable annotations for dependency injections and TypeORM's implementation compared to Spring Data JPA reminded me a lot of resemblance. Originally the Prisma was chosen as ORM for version 0, however, the complication that it created during the deployment with Serverless Framework led to change to TypeORM. The Serverless Framework dramatically decrease the complexity on deployment using serverless architecture.
