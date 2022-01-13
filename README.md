# Jupyter Threat

Jupyter Threat is a threat modelling framework that is a hybrid of conventional threat modelling and threat modelling as code. It uses Jupyter notebooks to visualise and store the threat model. The threat model is formed of the theoretical part - in Markdown syntax and the diagram - with Wardley Maps to complement the output. 

## The Threat Modelling Process

1. Trigger the threat modelling process within the design phase of the Software Development Lifecycle (SDLC)
2. Clone this repo into a repo where the Threat Model will live. Other options are to have a threat modelling repo for all the threat models or to create a threat model folder in the source code repo. 
3. Communicate with developers / architects / product managers to work on the threat modelling questionnaire / template. The output should be in a report format, not Q&A. The output should be inserted in the Jupyter Notebook that will later be used during the threat modelling session. 
4. Review architectural diagrams and in collaboration with the engineering team create the data flow diagram as code
5. Trigger a threat modelling session. On the threat modelling session:
    - confirm the flows
    - identify the threats
    - translate the threats into risks
    - identify the controls
    - create a Wardley Map to create a remediation strategy

## How to Use

1. Install Anaconda on your local environment from https://www.anaconda.com/products/individual

2. Clone this repo to your local machine

3. Create an Anaconda environment with the environment.yml file and activate it

4. Run the Jupyter notebook from the folder where you cloned the repository

5. Create a Develop branch on the repo and ask the developers to work on the Develop branch (see the section above). Use other branching strategies if the threat model is in the source code repo. An option is to create a threat-model branch then. 

6. Once the initial assessment is completed proceed to create a diagram as code using Diagrams https://diagrams.mingrammer.com/

7. To create a Wardley map as code use https://github.com/anjackson/ipywardley

WARNING: Use only on your local machine 

## Getting involved
Please contribute by creating a PR. If you have questions, concerns, bug reports, etc, please file an issue in this repository's Issue Tracker.

More Threat Modelling as Code Frameworks:

- Threatspec
https://github.com/threatspec/threatspec
- Pytm 
https://github.com/izar/pytm



To do:

- [ ] Improve README
- [ ] Review Dependencies
- [ ] Optimise Code






