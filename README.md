# Salesforce in Google Summer of Code 2019

> [Google Summer of Code](https://summerofcode.withgoogle.com/) is a global program focused on bringing more student developers into open source software development. Students work with an open source organization on a 3 month programming project during their break from school.

# Contact Information

You can contact the Salesforce GSoC team at oss-gsoc@salesforce.com or by opening an issue on this repository. The program administrator is Chris Kelly and can be contacted on GitHub or Twitter at @amateurhuman.

# Project Ideas 

**Deadline for project submissions is February 6 at 12:00 PST**

### TransmogrifAI – [salesforce/transmogrifai](https://github.com/salesforce/TransmogrifAI)

* **Model interpretability/explainability**
    * Insights into the functioning of machine learning models can foster greater trust and increased transparency around automated machine-learning driven decisions. In this task, we would like to enhance the algorithmic techniques that TransmogrifAI provides to peak into the black-box of machine learning models. Today, TransmogrifAI already comes with techniques such as LOCO and correlation-weighted feature importances to provide explainability at the level of individual automated decisions. We would like to enhance the set of techniques available for developers to use. Examples include Permutation Feature Importance or Shapley Additive Explanations.
    * How does one evaluate which of the techniques above provides the best insights and explainability into the workings of a machine learning model? A follow up task would be to prototype an evaluation metric for comparing feature importances across different interpretability techniques.

* **Hyperparameter optimization**
    * One of the most expensive parts of automated model training is searching the space of hyperparameters for the machine learning algorithms to find the best ones. We would like to enhance the TransmogrifAI model selector API to store and load the best hyperparameters based on previous model trainings on the same dataset so that the search can start off from a smarter starting point. We can also store the relative importances of each hyperparameter in previous model trainings, so that the future searches can focus more on the most impactful hyperparameters.
    * In addition, there are more sophisticated hyperparameter search strategies we want to investigate. Random search with configurable stopping criteria, intelligent search space pruning, or even a secondary model to predict good hyperparameters based on dataset metadata. These can be benchmarked against publicly available datasets like the OpenML 100.

* **Developer Experience**
    * Setup a Jupiter notebook for TransmogrifAI with Scala and Spark to simplify the on-boarding experience with our library and allow faster prototyping of ideas.
    * Enable import of TransmogrifAI models into Python or PySpark enabled environments to allow easier exploration and evaluation of our models against other machine learning libraries.

* **Aren't finding what you like?** Look for more issues/ideas here - https://github.com/salesforce/TransmogrifAI/issues

### Design System React – [salesforce/design-system-react](https://github.com/salesforce/design-system-react)
This project is open to original proposals from participants.

#### Proposal Suggestions
* **Re-architect and open-source project website.** Keeping documentation resources up-to-date and meeting developer needs can make or break a library's reputation. This task would allow the participant to showcase a deliverable that a developer manager would like to see and share their commitment to building a quality engineering culture at scale through quality documentation. It would focus on re-engineering and open-sourcing the documentation site (https://react.lightningdesignsystem.com/) and increasing alignment with the Lightning Design System website. Technologies likely to be used include Redux, React, react-docgen, Express, Webpack, and more.

* **Create 3 or more Lightning Design System components.** Be a part of creating some of the world’s best enterprise app experiences by building user-centered, re-usable, presentational components. Creating an accessible UI can be a nascent skill even for front-end engineers that have been coding for years. This will expose the participant to program management, cross-company collaboration between user experience engineering and product engineering in an enterprise engineering organization. Components will be audited, reviewed, and added to the library and then be used by Salesforce products in production.

* **Iterate on developer experience:** Geared toward a participant interested in developer operations, this task would focus on iterating and streamlining the contributor workflow to ensure a convenient and clear developer experience that scales and increases developer productivity. Technologies likely to be used include Webpack, Babel, Storybook, Jest and Mocha suites, Visual Regression Tests, and aXe accessibility automated testing.


### oclif – [oclif/oclif](https://github.com/oclif/oclif)
* **Design an oclif linter.** Linters have become the go-to way of enforcing code styles. For this project, we're looking to build a linter for oclif developers to enforce better practices. The linter needs to be able to lint both Typescript and plain JS CLI's, should run via the command line and also integrate into various IDE's (ex: Atom, VS Code).

# Code of Conduct

Participation in all Salesforce open source projects requires adherence to our [code of coduct](CODE_OF_CONDUCT.md).
