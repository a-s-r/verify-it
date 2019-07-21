# verify-it

INTRODUCTION

Nowadays the world moving towards digitalization, therefore everything is available over the web via internet. Everybody from a Household person to an enterprise wants to do everything online whether its applying for a passport, transactions, making complaints. All wants to save their time and do the process as fast as possible and for every country it is essential that they provide anything to their citizens readily so that everything is accessible to them. So basically the purpose to do this is saving time, cost, efficiency, productivity, make life easier, and happier. 
In order to do this I have various plans in mind to simply the consumer life.
To start with, I want to introduce a project named “Verify It”.

VISION

To make consumer life easier, no matter if he is an individual or organization and doing it via UIPATH platform is to save the manual time.
 
Where we implement it?

There are several websites where the user or the concerned person (individual/organization etc. it would be anyone) wants to apply for any kind of document online whether its applying their pan card, identify proofs, passports or whether its any kind of recruitment registration where there is form submission and along with that document uploading, this process at the initial stage before submitting it to the authorities will check it and inform accordingly to the person that he filing the right information or not by checking his/her documents. This interface will check the documents and check whether the information is as per the document uploaded or not. So that the user has not to face any future notification/rejection that the documents are mismatched and they have to upload everything again, which is quite a frustrating thing for the person. So, the initial check is beneficial for both the user and further for the authorities. 

Let’s suppose the user is filling a pan card application online, in order to do this, the user fills the application form with the required documents and the process would take almost one month. If there is any problem occurred due to a mismatch of documents with the data filled, user is intimated and asked to fill it again to give relevant document as per the information filled, it's quite annoying for the user if he needs a relevant document in hand on a very urgent basis like he has to apply for overseas study, or applying for a job.
Also from the provider perspective they will also take 5-10 days to manually check the document and do the further process of issuing a document, if any kind of interface check it at the initial stage it will simplify the things at both ends. 
The conclusion is that if the manual process will be converted to automation then the response time is absolutely nothing i.e. like 5-10 minutes.
 
How it works?

I build a dummy web page where user filling the application form and submit required documents. As you know the documents are confidential therefore I created some sample documents for this application. When user submits the application simultaneously the request adds in queues and the bots will pick one by one and verify the application form and the documents. It creates both responses. First, create verified ID; if it corrects then bot will assign one verified ID which is required to submit when the final submission. Secondly, if there is some issues then it will update status as invalid and what needs to be rectified. In both scenarios bot will intimate via mail or update on specific website where user will navigate easily. Therefore it saves users time, increased provider productivity and efficiency and many more benefits which is directly related to both parties. Also send stats to admin in the end of day.
It will implement everywhere where there is any kind of communication related to application and respective documents.
 
Assumptions

Build dummy web page for creating the solution.
Documents are sample documents not real.
When I got chance to implement in real then it will modify accordingly.