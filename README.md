# VISA-Approval
## Overview
My project aims to predict the outcome of H1-B visa applications that are filled by
many high-skilled foreign nationals every year. It makes use of Machine learning's
classification algorithms to predict the outcome. The model takes input as certain
parameters which are the attributes of the applicant. Based upon the parameters, the
model predicts the outcome. The model has an accuracy of 0.97 and predicts the
outcome with utmost accuracy.

## Purpose
H-1B is a type of non-immigrant visa in the United States that allows foreign nationals
to work in occupations that require specialized knowledge and a bachelor’s degree or
higher in the specific specialty. This visa requires the applicant to have a job offer from
an employer in the US before they can file an application to the US immigration service
(USCIS). USCIS grants 85,000 H-1B visas every year, even though the number of
applicants far exceed that number. The selection process is claimed to be based on a
lottery, hence how the attributes of the applicants affect the final outcome is unclear.
So by building this model, we will be able to help future H1-B visa applicants and the
employers who are considering to sponsor them. The approved Labor Condition
Application (LCA) petition is submitted as part of the Petition for a Non-immigrant
Worker application for work authorizations for H-1B visa status. We want to uncover
insights that can help employers understand the process of getting their LCA approved.

## Proposed Solution
The solution to the above mentioned problem is to build a machine learning model
which can learn the pattern, analyze it and predict the outcome accurately so that it
would benefit the future H1-B visa applicants and the employers who are considering
to sponsor them. To determine the output, we made use of the attributes of the
applicant.

## Algorithm Used
Decision Tree was used to build the ML model. It is a Supervised Machine Learning
where the data is continuously split according to certain parameters. For classification
problems, Decision Tree can be used and since in practice, it gave highest accuracy
(0.97413) therefore it was used.

## Result
The machine learning model predicted the outcome of different scenarios
accurately. With the accuracy of 0.97413, the model proves that it learnt the
features well. The dataset had 528132 records and had a variety in them
which allowed the model to learn different behaviors. The model was
deployed using Flask. The webpage is the front end which takes the input
from the users and passes it for prediction. Also it is where the output is
being displayed. With increase in number of records, the time required to
train the model will also increase.

## Future Scope
- Some of the features were removed from the model. In the future,
these features could be in some other algorithm to provide even better
accuracy and less loss.
- Adding new data every year and training it to the model will help it to
learn the patterns even better.
- The application can be improved and made official so that it can help
millions of applicants.
