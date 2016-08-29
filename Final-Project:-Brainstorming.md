Here are some ideas suggested by our physician instructors. 

***

### Data sets

One broad idea is to look at various available data sets and figure out what computationally interesting questions could arise from them. To that end, here are a few such data sets.

* https://health.data.ny.gov/Health/Hospital-Inpatient-Discharges-SPARCS-De-Identified/u4ud-w55t
* https://health.data.ny.gov/
* http://www.dshs.state.tx.us/THCIC/Hospitals/Download.shtm
* https://github.com/ImagingInformatics/hackathon-dataset
* http://www.cancerimagingarchive.net/

We also have about 100 anonymized DICOM images available, see Professor Zabih or Dr. Shih if you are interested.

### Ideas

Below are a number of ideas suggested by Dr. Dorfman, Hentel and Shih.

***

Using any of the content from the talks (past or future), pick one disease / condition that was discussed and create a prototype of a mobile app to help either the doctor or patient (or both) treat or manage the disease.  This could be pretty broad and involve managing logistics of disease, etc. Here's an example of what a prototype might look like: https://projects.invisionapp.com/share/P33O728AR

Examples:

1.  Stroke management app: Help doctors manage patients with stroke, by outlining the stroke protocol algorithm (https://www.acls.net/acls-suspected-stroke-algorithm.htm) with integration with the EHR and PACS.  One might imagine using this where a small hospital does not have an onsite radiologist so integrating imaging in the app would be useful.
2.  Alzheimer's disease brain boosting app: Examples here - http://www.alzheimers.net/2014-01-13/akili-app-may-detect-alzheimers/
3.  Trauma 911 app:  Currently 911 is done over the phone.  How could a smartphone app improve the 911 interaction?

***

Creation of a medical calendar app that functions on the concept of a disease/condition plan. Students should choose one short term and 1 long term condition.
(e.g If we used something simple like pneumonia it could be a daily reminder to take medication for X days depending on Abx prescribed and then a reminder for follow-up MD appointment)
This idea requires them to take a concept from 1 of the lectures and translate into terms for the lay user.

***

Creation of a basic Dicom analytics tool (possible use cases below)
- first image to last image times based on specific imaging protocol
- individual series time(s) for specific series (etc)
- automatic detection of deviation from standard protocols

*** 

Creation of a novel medical search engine/algorithm: e.g. a search engine that could search pubmed based on a combination of CPT code and ICD-10 code (or ICD-9 code)
We can come up with a de-identified dataset. Example capabilities:
- display 3 most recent relevant articles
- display 3 most relevant review articles

***

Using the DICOM data set:

A)  Come up with an algorithm to sort the image datasets (not using the DICOM header) as to modality and anatomy (i.e., using feature recognition to determine MRI, CT, etc. and brain, head/neck, chest, abdomen, etc.).

B) For a subset of images find and determine volume of an organ or structure (e.g., brain - locate and determine the volume of the lateral ventricles; abdomen - locate and determine the volume of the liver or each kidney)

C) For a subset of images create an anatomy teaching tool that will name the organ when a cursor is placed in the organ

D) For a subset of images, in c/w a radiologist create a reporting tool that will highlight an abnormality (or normal measurement) as contained within the text of a report (e.g., the report states that the gallbladder has a certain measurement, when the reader hits the url in the report, the gallbladder is highlighted and the measurement appears on the image; the report states that there is hippocampal atrophy, the link in the report highlights the hippocampus and the hippocampal volume as predetermined is displayed on the image).
