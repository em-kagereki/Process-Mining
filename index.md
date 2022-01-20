## Predictive modeling of  acute coronary syndromes using Celonis.

* *Date Created*: 01 06 2022
* *Last Modification Date*: 06 06 2022

## Author:

*[Edwin Kagereki](Kagereki@dal.ca)*

Cardiovascular diseases (CVDs), principally ischemic heart disease (IHD) and cardiac stroke, are the leading cause of mortality globally and are often associated with poor survival[(Roth 2020)](https://doi.org/10.1016/j.jacc.2020.11.010). Acute Coronary Syndrome (ACS) is a term given to diverse presentations related to cardiac myopathies of quick onset. 


The chances of a patient to have good outcomes are usually high if substantive medical attention is given within  the first hour of the event, often called the "golden hour". It is therefore important to accurately estimate the risk for untoward outcomes after a suspected onset of an ACS and thereafter chose the type and intensity of therapy. For example, patients predicted to be at higher risk may receive more aggressive surveillance and/or treatment, while patients predicted to be at lower risk may be managed less aggressively.


In this project, I  considered a similar prediction problem. Interpreting events of an 
event log as outcomes of decisions, our goal is to build a predictive analytics model 
that accounts for the sequential nature of decision making in business processes. 
Provided with a partial sequence of events from an unfinished process instance, the 
model's task is quantifying the likelihood of the instance ending with certain future 
sequences. The model should be trained solemnly by means of event log data.

Such a predictive model could be useful in variety of situations. For instance, early 
warning systems could be built. Decision makers could be provided with a list of 
running process instances in which undesirable events will likely be observed in the 
future. A predictive model could also be used to estimate how many running instances 
will require a certain resource, again to warn decision makers if capacities will be 
exceeded. Moreover, anomaly detection approaches could be built to identify highly 
unlikely process instances. They could help pointing business analysts to unusual 
instances. It is also conceivable to use a predictive model to support other process 
mining endeavors, for instance by imputing missing values in incomplete event logs


## Context

The context in which an operational business process is executed is 
acknowledged as having a significant effect on the predictive power of a predictive 
process model.


The context in which an operational business process is executed is 
acknowledged as having a significant effect on the predictive power of a predictive 
process model.


### Markdown



Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/em-kagereki/Process-Mining/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


## References

Roth, et al, Gregory A. 2020. "Global Burden of Cardiovascular Diseases and Risk Factors, 1990-2019: Update from the GBD 2019 Study." Journal of the American College of Cardiology 76 (25): 2982-3021. https://doi.org/10.1016/j.jacc.2020.11.010.
