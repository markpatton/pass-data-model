# Publisher

A [journal](Journal.md) publisher

| Field  		| Type  		| Description |
| ------------- | ------------- | ------------- |
| __id*__ | String | Unique Publisher URI |
| name* | String | Name of publisher |
| journals | List[[Journal](Journal.md)] | Journals associated with publisher |
| pmcParticipation | Enum ([see list below](#pmc-participation-options)) | This field indicates whether a journal participates in the NIH Public Access Program by sending final published article to PMC. If so, whether it requires additional processing fee. |
| __created*__ | DateTime | Date the record was created |
| __lastModified*__ | DateTime | Date the record was last modified |

*required  
_autogenerated fields are in **bold** and are readonly_

## PMC Participation options

These are the possible submission methods relating to PMC deposits. A full description of these methods can be found on the [NIH public access website](https://publicaccess.nih.gov/submit_process.htm)

| Value  		| Description |
| ------------- | ------------- | 
| A | PMC deposit route A. Journals automatically post the paper to PMC |
| B | PMC deposit route B. Authors must make special arrangements for some journals and publishers to post the paper directly to PMC |
| C | PMC deposit route C. Authors or their designee must submit manuscripts to NIHMS |
| D | PMC deposit route D. Some publishers will submit manuscripts to NIHMS |