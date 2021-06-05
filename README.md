# Project Title
Legal-tech for GDPR consent phrasings

## Summary
Under the Europen General Data Protection Regulation (GDPR), individuals can be asked for consent to have their data processed, e.g. in cookie banners.
However, there are rules for how consent must be phrased, i.e. easy to understand, and include information on how to withdraw consent.
This project aims at analysing user-input consent phrasings and give users tips on how to improve it to better comply with GDPR.

## Background
Organisations often struggle to comply with GDPR due to complex legal requirements.

An issue often encountered in the wild are consent forms, be it for cookies, newsletters or for research.
Organisations focused on their main aim do want to protect their users' data and comply with the requirements mappe dout by the GDPR.

Whilst formulating declarations of consent, there are lots of little details to consider:
* Is the phrasing clear and transparent? Does it include the purpose and data involved, and the duration of consent?
* Is the declaration not too long and thus hard to understand?
* Does the declaration include an information on how to withdraw consent, if wished?

The solution to this problem often involves expensive privacy lawyers. 
A simpler self-service AI solution could do the trick: Get organisations to focus on their aim whilst protecting their users data.

## How is it used?
The solution would offer an easy-to-use web interface. 
Users, mostly non-privacy professionals who want to ask individuals for permission to process their data for a given purpose, will find tips on how to properly formulate a declaration of consent. 
Below, they will be able to input their proposed formulation, and have it checked by the service.
The output would include concrete tips on how to improve the formulation.

## Data sources and AI methods
The data source for training would have to be collected compiled manually, as there is no repository of GDPR consent declaration forms.
It would have to be classified manually.

Input data from users would come from the input field in web interface.
Both inputs should be in English-language to begin with.

The AI method would have to be supervised learning to get the legalese right.
First, text would have to be converted to numerical represenations with, second, features to be detected.
Then, a model would have to predict whether all features can be found and what to improve.
Based on the Building AI course, probably a recurrent neural network could be of help.

## Challenges
The project is limited to the formulation of declarations of consent, but does not check how the personal data will actually be processed.
It does not evaluate whether the purpose is lawful, ethical, or anything - it checks for phrasings and gives hints on how to improve the wording.
That being said, the solution cannot assess whether the processing is legal or not, it is limited to the correct phrasing of consent.

## What next?
The project could take more aspects of GDPR compliance into account, and slowly offer more and more GDPR self-service compliance modules.
Moreover, it could be expanded from English to the other European languages.
To realise this idea, a thorough understanding of frontend and backend development would be necessary, along with IT operations.

## Acknowledgments
Thanks to Reaktor and the University of Helsinki for the AI courses
