# Salesforce in Google Summer of Code 2019

> [Google Summer of Code](https://summerofcode.withgoogle.com/) is a global program focused on bringing more student developers into open source software development. Students work with an open source organization on a 3 month programming project during their break from school.

# Contact Information

You can contact the Salesforce GSoC team at oss-gsoc@salesforce.com or by opening an issue on this repository. The program administrator is Chris Kelly and can be contacted on GitHub or Twitter at @amateurhuman.

# Project Ideas

### TransmogrifAI – [salesforce/transmogrifai](https://github.com/salesforce/TransmogrifAI)
This project is open to original proposals from participants.

* **Model interpretability/explainability**
    * Insights into the functioning of machine learning models can foster greater trust and increased transparency around automated machine-learning driven decisions. In this task, we would like to enhance the algorithmic techniques that TransmogrifAI provides to peak into the black-box of machine learning models. Today, TransmogrifAI already comes with techniques such as LOCO and correlation-weighted feature importances to provide explainability at the level of individual automated decisions. We would like to enhance the set of techniques available for developers to use. Examples include Permutation Feature Importance or Shapley Additive Explanations.
    * How does one evaluate which of the techniques above provides the best insights and explainability into the workings of a machine learning model? A follow up task would be to prototype an evaluation metric for comparing feature importances across different interpretability techniques.

* **Hyperparameter optimization**
    * One of the most expensive parts of automated model training is searching the space of hyperparameters for the machine learning algorithms to find the best ones. We would like to enhance the TransmogrifAI model selector API to store and load the best hyperparameters based on previous model trainings on the same dataset so that the search can start off from a smarter starting point. We can also store the relative importances of each hyperparameter in previous model trainings, so that the future searches can focus more on the most impactful hyperparameters.
    * In addition, there are more sophisticated hyperparameter search strategies we want to investigate. Random search with configurable stopping criteria, intelligent search space pruning, or even a secondary model to predict good hyperparameters based on dataset metadata. These can be benchmarked against publicly available datasets like the OpenML 100.

* **Developer Experience**
    * Setup a Jupiter notebook for TransmogrifAI with Scala and Spark to simplify the on-boarding experience with our library and allow faster prototyping of ideas.
    * Enable import of TransmogrifAI models into Python or PySpark enabled environments to allow easier exploration and evaluation of our models against other machine learning libraries.

* **Aren't finding what you're interested in?** Look for more ideas at https://github.com/salesforce/TransmogrifAI/issues

### Design System React – [salesforce/design-system-react](https://github.com/salesforce/design-system-react)
Design System React is a set of accessible, localization-friendly, presentational React components that implement the [Salesforce Lightning Design System](https://www.lightningdesignsystem.com/). Both DSR and SLDS are owned by engineering teams within a user experience department. This project is open to original proposals from participants.

* **Additional Lightning Design System components** Be a part of creating some of the world’s best enterprise app experiences by building user-centered, re-usable, presentational components. Please review the [SLDS website](https://www.lightningdesignsystem.com/) for ideas. Components can be different sizes of complexity and may need to be scoped into small components. Creating an accessible UI can be a nascent skill even for front-end engineers that have been coding for years. This will expose the participant to program management, cross-company collaboration between user experience engineering and product engineering in an enterprise engineering organization. Components will be audited, reviewed, and added to the library and then be used by Salesforce products in production as well as by external consumers in the open-source community.

* **Iterate on the developer experience** Interested in developer operations? This task would focus on iterating and streamlining the contributor workflow to ensure a convenient and clear developer experience that scales and increases developer productivity. Technologies likely to be used include Webpack, Babel, Storybook, Jest and Mocha suites, Visual Regression Tests, and aXe accessibility automated testing. Please consider your own experience as a contributor as a guide. If you have any issues, you are probably not alone.

* **Lint component prop APIs in pull requests** `containerStyle` or `styleContainer`? Use react-docgen's output to lint prop names to conform to project architecture and create a consistent consuming developer experience. This will add additional checks to pull requests in order to provide more efficent reviews.

* **Add cross-component utility APIs** Increase component flexibility by adding a varity of render props, ARIA attribute, style/CSS class, and data-attributes props across many components.

* **Aren't finding what you're interested in?** Look for more ideas at https://github.com/salesforce/design-system-react/issues

* **Mentor(s):** Stephen James ([@interactivellama](https://github.com/interactivellama)), Lead UX Engineer; Dave Woodward ([@futuremint](https://github.com/futuremint)), UX Engineering Architect

#### Additional resources for brainstorming proposals to consider
* [Designing UX with Salesforce Engineering](https://www.youtube.com/watch?v=MKwQXfN-8Rk)
* [Interning as a UX Engineer](https://medium.com/salesforce-ux/interning-as-a-ux-engineer-290e9115a034)
* [Open Sourcing Design System React](https://engineering.salesforce.com/open-sourcing-design-system-react-9be45b8bb127) - Medium article
* [@SaleforceUX](https://twitter.com/salesforceux) - Twitter account
* [Creating an Enterprise CSS Framework: A Salesforce UX Case Study](https://www.slideshare.net/uxpin/creating-an-enterprise-css-framework-a-salesforce-ux-case-study) - This is not about this project, but the CSS framework used by Design System React

### oclif – [oclif/oclif](https://github.com/oclif/oclif)
This project is open to original proposals from participants.

* **Design an oclif linter.** Linters have become the go-to way of enforcing code styles. For this project, we're looking to build a linter for oclif developers to enforce better practices. The linter needs to be able to lint both Typescript and plain JS CLI's, should run via the command line and also integrate into various IDE's (ex: Atom, VS Code).

* **Aren't finding what you're interested in?** Look for more ideas at https://github.com/oclif/oclif/issues

# Code of Conduct

Participation in all Salesforce open source projects requires adherence to our [code of coduct](CODE_OF_CONDUCT.md).
