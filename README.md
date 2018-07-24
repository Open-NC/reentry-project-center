# Reentry Resources Project Center
This is the central repository for information about and links to all the component repositories.

## Purpose

Accessible, accurate and safe information on resources for those returning to the community after a period of incarceration or suffering the consequences of a criminal conviction on their record can be very hard to come by. Not only is the information dispersed across many different sites, but there is a tremendous amount of inaccurate, outdated information out there and a lot of places that are looking to exploit the vulnerable. The challenge is there not only for those contending with the issue, but also for those trying to help them: defense lawyers, parole officers, prison counselors, etc.

We built the [Buncombe Reentry Resources Hub](http://www.buncombereentryhub.org/) to provide up-to-date, accurate and safe links to national, state and local information and resources. The site is in use by the defense bar, DA's office, prison officials and reentering individuals. Now we are working to scale this resource to every county in North Carolina.

## Approach

We are in the process of re-developing the state-wide version of the reentry hub based on the [Open Referral standard](https://openreferral.readthedocs.io/en/latest/). There are 3 phases to this work:

### Phase I: Implement Open Referral Database and GraphQL API

The City of Asheville is building a GraphQL API and database to implement the Open Referral standard [here](https://github.com/cityofasheville/open-referral-gql-api). The implementation is designed to be shared across different projects that might use 211-like resources. We expect this implementation to be available shortly. No help is needed here.

### Phase II: Extend Phase I API and Database for Reentry, Update Front End to Use

In this phase, we will extend the Open Referral base to support the additional information needed for the reentry site (such as descriptive text on each topic) and deploy it on Amazon RDS. We will also modify the front end code to use the new API. This phase should be relatively quick. We can use front-end help here, although it's not critical.

The front-end code will remain in the [current reentry project](https://github.com/Open-NC/reentry-resources-hub). The back-end code will be in a new not-yet-created repository.

### Phase III: Deploy the Public Site & Improve

Once Phase II is done, we need to actually deploy the public site (probably on AWS). Would love to have help here, both in AWS deployment and, longer-term, in improving the usability of the site.

### Phase IV: Build an Administrative Interface to Maintain the Site

The information on the site must be simple to maintain for non-technical domain experts. Here Melanie Mazanec will lead the project to design and implement a front end for updating the Open Referral database plus extensions for applications like reentry. This is a great place for front-end design, development, and user-testing help.


## Want to Help?

If you have any questions or want to help, please reach out to [Eric Jackson](https://github.com/ejaxon) for Phases I-III, to [Melanie Mazanec](https://github.com/orgs/cityofasheville/people/mmazanec22) for Phase IV.


### Prepare to Contribute

Interested, but not ready to commit code yet? - Here are some resources to prepare

#### Git
  * [Main Page](https://git-scm.com/)
  * [Download/Install](https://git-scm.com/downloads)
  * [Docs](https://git-scm.com/doc)
  * [Tutorial](https://www.codeschool.com/courses/try-git)
  
#### GitHub
  * [Main Page](https://github.com/)
  * [Create Account](https://github.com/join)
  * [Tutorial](http://lifehacker.com/5983680/how-the-heck-do-i-use-github)
  
#### JavaScript
  * [Main Page](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
  * [Tutorial](https://www.codecademy.com/learn/javascript)

#### React
  * [Main Page](https://facebook.github.io/react/)
  * [Docs](https://facebook.github.io/react/docs/installation.html)
  * [Tutorial](https://facebook.github.io/react/tutorial/tutorial.html)
  
#### GraphQL
  * [Main Page](http://graphql.org/)
  * [Docs](http://graphql.org/learn/)
  * [Tutorial](http://graphql.org/graphql-js/)
 
#### Node
  * [Main Page](https://nodejs.org/en/)
  * [Download/Install](https://nodejs.org/en/download/)
  * [Docs](https://nodejs.org/en/docs/)
  * [Tutorial](https://github.com/maxogden/art-of-node/#the-art-of-node)
  * [Resources](https://stackoverflow.com/questions/2353818/how-do-i-get-started-with-node-js)
  
#### Express
  * [Main Page](https://expressjs.com/)
  * [Docs](https://expressjs.com/en/4x/api.html)
  * [Tutorial](https://code.tutsplus.com/tutorials/introduction-to-express--net-33367)
  
  
  
  
