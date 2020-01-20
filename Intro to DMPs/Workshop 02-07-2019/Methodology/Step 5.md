# Step 5 - Preservation and Publication

**Available time:** 15 minutes

### Description
In this final step, researchers need to identify which data will be shared and for how long will it be preserved. Any existing data reuse restrictions must also be identified, and an appropriate license should be chosen. 

Researchers should also characterize the appropriate data repositories to preserve and share their data. This characterization should also include technical details, such as its trustworthiness, versioning support, existence of automated citation, etc.

### Example
“The Endoscopic bioimaging dataset comprises solely of processed data. The ethics committee has reviewed the dataset and given its authorization for it to be shared and preserved.

During the storage and description process a Share-Alike Creative Commons License was thus applied. This licence requires that copies or adaptations of the work to be released under the same or similar licence as the original.

Data will be stored at the INESC-TEC research data repository that guarantees long-term preservation for all deposited datasets.”

### Information to collect
* **Distribution** - Information regarding the policies on how each dataset is to be distributed.
* **License** - A characterization of the licenses associated with each distribution policy.
* **Host** - A characterization of the data host.

### Notes
Fields marked with a * are mandatory.

### Distribution

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| title*      | Distribution title | Full resolution images |
| description*      | Distribution description     |   Best quality data before resizing |
| format*      | The media type, according to IANA    |   image/tiff, audio/mp4, text/csv, text/json, video/mp4, etc. |
| access_url      | Access URL     |   http://some.repo... |
| available_till*      | Indicates how long this distribution will be/ should be available     |   2030-06-30 |
| data_access*      | Indicates access mode for data.      |   Allowed values: open / shared / closed |
| byte_size      | Byte Size     |   690000 |
| download_url      | Download URL   |   http://some.repo.../download/... |

### Licence

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| licence_ref*      | Type of licence that is applied. | CC BY, CC BY-SA, CC BY-NC, CC BY-NC-ND, etc. |
| start_date*      | If date is set in the future, it indicates embargo period. | 2019-06-30 |

### Host

| **Field**        | **Description**           | **Example Value**  |
| ------------- |:-------------:| -----:|
| title* | Host title | Super Fancy Repository |
| description* | Host description     |   Repository hosted by the IGC at their Oeiras facilities |
| support_versioning* | Does it support versioning |   Allowed values: yes / no / unknown |
| pid_system* | Persistent Identifier System | ark, doi, hdl, purl, urn, other, none, etc. |
| availability | A percentage of availability. | 99.99 |
| backup_frequency | Backup Frequency | weekly, monthly, daily, etc. |
| certified_with | Repository certification standard | DIN3164437, DINI-Zertifikat38, DSA39, ISO1636340, ISO1691941, TRAC42. WDS43, CoreTrustSeal |
| geo_location | Physical location of the data expressed using ISO 3166-1 country code. | pt, en, fr, etc. |
