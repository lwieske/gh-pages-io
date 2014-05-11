## Welcome to GitHub Pages

GitHub Pages are public webpages freely hosted and easily published through our site. Pages are served over HTTP, not HTTPS.

GitHub Pages allow you to document and organize your GitHub presence in terms of an anchor web page, a sets of web pages to document your breakdown of conceptual groupings, and finally linking to your repositories.

## User/Organization Pages

Create a new GitHub repository named username.github.io (username or organization name).

Create, edit and push an appropriate index.html into it. 

Fire up a browser and go to http://username.github.io.

## Project Pages

Project Pages are kept in the same repository as their project.

* The gh-pages branch is used to build and publish Project Pages sites.
* Project Pages sites are served under http://username.github.io/projectname.

## Conceptual Example

Think of the following conceptual and naming breakdown of someone interested in cloud / mobile / social / bigdata / devops and having a growing number of repositores following a consistent naming scheme.

* DevOps

* Big Data

* Cloud
  * Infrastructure-as-a-Service 
    * aws-* for Amazon Web Services
      * Repostory 1
      * ...
      * Repository X
    * ...
  * Platform-as-a-Service
    * cf-* for CloudFoundry
      * Repostory 1
      * ...
      * Repository Y
    * ...

* Mobile

* Social

This could be represented by the following breakdown structure in GitHub Pages (User + Projects)

### User Pages

    index.html
    groups/
    	devops.html
    	bigdata.html
    	cloud.html
    	mobile.html
    	social.html
    	devops/
    	bigdata/
    	cloud/
    		iaas.html
    	    iaas/
    	        aws.html (with links to Repositories 1..X)
    	        ...
    	    paas.html
    	    paas/
    	        cf.html (with links to Repositories 1..X)
    	mobile/
    	social/
    	
### Project Pages

    aws-repo-1 (gh-pages branch)
    ...
    aws-repo-X (gh-pages branch)

    cf-repo-1 (gh-pages branch)
    ...
    cf-repo-Y (gh-pages branch)
    	

