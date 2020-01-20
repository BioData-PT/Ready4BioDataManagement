# Step 3 - DMP Document

**Available time:** 15 minutes

### Description
This step focuses on gathering information on two classes.

For the first class (DMP Information), researchers are asked to provide general information about the DMP. This information is useful to characterize the DMP.

### Example
"The project will manage several types of data, most of which has ethics or legal issues. 

The RAW data created during the project belongs to the Instituto de Financiamento da Agricultura e Pescas (IFAP), and can not be preserved and/or shared under any circumstances. Moreover, all RAW data must be destroyed at the end of the project. 

All processed data, based on RAW data should be anonymized, encoded and cleared by the Ethics Committee for publishing and preservation. All other biological data collected during the project does not have any restrictions or any ethics or legal issues.  As such, it can be published in the research data repository with the appropriate license”.

For the second class (Cost), researchers should provide information related to all associated costs. Researchers need to consider the following types of questions:
* Where should data be stored and preserved?
* What data should be stored and preserved? 
* What type of storage will be used?
* What type of access with the storage have?
* Who should be performing the tasks?
* What resources are required? 
* Etc.

The DMP should be a live document, and reflect any changes made throughout the project. As such multiple versions of the DMP will be created and deprecated during its life-cycle.

### Example
"In a project focusing on breast cancer histology, all created images comprise of up to 5GB of RAW data. This data is to be preserved in an institutional datacenter. 

The servers hosting the data, must be fitted with a redundant array of independent disks (RAID) 5 configuration, comprising of 4 hard disks. The datacenter should, as a minimum requirement,  have weekly maintenance checks. Only the datacenter technical staff and project supervisors are to be allowed access to the data".


### Information to collect
* **DMP Characterization** - General information about the DMP document.
* **Cost** - Information of the associated costs of the DMP.

### Notes
Fields marked with a * are mandatory.

### DMP Characterization

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| title*      | DMP title | DMP for our new project |
| description*      | DMP description     |   This DMP aims to describe our data management policies... |
| created*      | Date and time of the first version of a DMP.     |   2019-03-13 13:13 |
| modified*      | Must be set each time DMP is modified. Indicates DMP version     |   2020-03-14 10:53 |
| language*      | Language of the DMP expressed using ISO 6391-1 two letter country code.     |   en |
| ethical_issues_exist*      | Are there ethical issues related to data that this DMP describes.     |   Allowed values: yes / no / unknown |
| ethical_issues_description*      | To describe ethical issues directly in a DMP     |   There are ethical issues, because... |
| ethical_issues_report*      | An indication of where a protocol from a meeting with an ethical committee can be found   |   http://report.location |

### Cost

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| title*      | Cost title | Storage and backup |
| description*      | Cost description     |   Costs for maintaining.... |
| currency_code      | Allowed values defined by ISO 4217.     |   EUR |
| value      | The value associated to the cost    |   1000 |
