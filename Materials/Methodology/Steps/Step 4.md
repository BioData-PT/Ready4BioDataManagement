# Step 4 - Datasets

**Available time:** 15 minutes

### Description
In this step, researchers need to characterize each dataset that will be creating during the project and/or after it conclusion. The title, keywords, description, authors, language and metadata standards are the most common descriptors used for this purpose. 

If personal or sensitive data is present in the datasets, this fact should signaled in the dataset characterization. Additionally, standards can be applied during data processing (e.g. General Data Protection Regulation (GDPR)). Researchers might find it necessary to clarify which tools or methodology is to be used for data quality assurance. Researchers must also provide information regarding the policies and methods applied with regards to Security and Privacy.  

### Example
“Researchers should offer descriptions on the software used during the project, its updates, any antivirus software installed, network configurations, and list any existing risks that related to unsafe connections, finally they should also list any possible technical failures.”

Additionally, researchers should also detail any technical resources that were required during the project (e.g. software, hardware, measurement sensors, plots, etc.). All information provided in this step should be verified with the help of the project’s technical staff.

### Example
“In the Biodata.pt compute platform, researchers resort to a datacenter that contains x blade servers running a Linux OS. All these servers are monitored remotely and controlled through a custom version of Openstack, thus allowing for the allocation of virtual machines as required”

Metadata standards are commonly used for the description of the digital objects, such as Dublin Core or personalized metadata schema based on INSPIRE for example, or Darwin Core that used for facilitating the sharing of information about biological diversity. Researchers must declare any metadata standards that are used within the project.

### Information to collect
* **Datasets** - General information about all datasets created in the context of a project.
* **Security and Privacy** - A characterization of any security and privacy policies associated with each of the identified datasets.
* **Technical Resource** - A characterization of any technical resources associated to each of the identified datasets.
* **Metadata** - A characterization of metadata associated to each of the identified datasets.

### Notes
Fields marked with a * are mandatory.

### Datasets

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| title*      | Dataset title | Benfica’s transfers |
| description*      | Dataset description     |   A spreadsheet containing all of Benfica’s summer transfers. |
| issued      | Issued     |   2019-06-30 |
| keyword*      | Keyword     |   Benfica, Money, Players |
| language*      | Language of the DMP expressed using ISO 6391-1 two letter country code.     |   en, pt, fr, etc. |
| type*      | A controlled vocabulary describing the resource type     |   website, image, software, sound, book, paper, patent, report, thesis, etc. |
| personal_data*      | Is there personal data in the dataset     |  Allowed values: yes / no / unknown |
| sensitive_data*      | Is there sensitive data in the dataset   |   Allowed values: yes / no / unknown |
| preservation_statement      | Preservation Statement   |   Must be preserved to enable future boards to track the money.  |
| data_quality_assurance      | Data Quality Assurance   |   We use file naming convention xyz |

### Security and Privacy

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| title*      | Security and Privacy title | Physical access control |
| description*      | Security and Privacy policy description     |   Server with data must be kept in a locked room |

### Technical Resource

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| description*      | Technical resource description     |   Device needed to collect field data... |


### Metadata

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| description*      | Cost description     |   Costs for maintaining.... |
| language*      | Language of the DMP expressed using ISO 6391-1 two letter country code.     |   en, pt, fr, etc. |
