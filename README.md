# Salesforce in Google Summer of Code 2021 #
> [Google Summer of Code](https://summerofcode.withgoogle.com/) is a global program focused on bringing more student developers into open source software development. Students work with an open source organization on a 3 month programming project during their break from school.

# Contact Information #
You can contact the Salesforce GSoC team at oss-gsoc@salesforce.com or by opening an issue on this repository. The program administrator is Alyssa Arvin and can be contacted on GitHub or Twitter at @AlyssaArvin.

# Project Ideas #
### Cloudsplaining – [salesforce/cloudsplaining](https://github.com/salesforce/cloudsplaining) ###
This project is open to original proposals from participants.

* **Build a web app that identifies excessive privileges in AWS**: 
    * Cloudsplaining can scan an AWS account or a single AWS IAM Policy - but it currently does so on command line. We’d like to turn this into a web app so developers can copy/paste their IAM policies, or upload their authorization details file, and see the results in the web app.
    * This will significantly lower the barrier to entry for identifying excessive privileges in AWS because developers will not have to learn a command-line tool - they will be able to use a web app instead.
    * This can be developed with a JavaScript framework of choice (React, Vue, Svelte, etc.). 
    * This web app will be available to the public so anyone can use it. It will not just help Salesforce, it will help the larger security community around the world.

* **Enhance a REST API that provides Cloudsplaining’s IAM scanning capabilities**
    * Cloudsplaining’s IAM scanning capabilities are currently hosted on a REST API. Enhancing this REST API will allow the web app to be more effective and responsive.
    * Tech stack includes Python, FastAPI, and AWS Lambda functions. If you are comfortable with Python but not with the rest, the rest can be learned.

* **Build IAM Security scans into CI/CD pipelines for Infrastructure as Code**
    * Cloudsplaining is currently available as a command-line tool. This opportunity would include building automation using GitHub Actions to scan policies defined in Terraform and return the results on Pull Requests in GitHub.


* **Aren't finding what you're interested in?** Look for more ideas at https://github.com/salesforce/cloudsplaining/issues

* **Mentor:** Kinnaird McQuade ([@kmcquade](https://github.com/kmcquade))

### JARM – [salesforce/jarm](https://github.com/salesforce/jarm) ###
This project is open to original proposals from participants.

* Build a JARM fingerprint to server application database* with confidence levels to be utilized by the community.

* Build features into JARM that will allow it to further identify, with high confidence, the server application. This can be done with further server application fingerprinting that has yet to be identified/invented such as deeper application probing. The student would be involved in the investigation, feasibility, and invention of these additional capabilities.

* **Aren't finding what you're interested in?** Look for more ideas at https://github.com/salesforce/jarm/issues

* **Mentor:** John Althouse ([@jalthouse-sfdc](https://github.com/jalthouse-sfdc))

