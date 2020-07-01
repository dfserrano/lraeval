# LRA Evaluation Dataset

The service-operation collection was extracted from real service offerings, in order to evaluate [Linked REST APIs](https://ieeexplore.ieee.org/document/8029755). The services represent the variety in terms of design patterns and resources found in real environments. We selected the domain of scholarly APIs, and used the list of APIs in the
[Scholarly Resources at University of Alberta](https://www.library.ualberta.ca/about-us/open-data/api), which is similar to the lists collected in other academic institutions. 

Then, guided by an expert in the area, the number of service providers was narrowed down to 13 (52 operations) based on the relevance of the resources offered and the quality of the documentation. The relevant service operations were selected, removing the input parameters used for control and authentication, such as pagination parameters and API keys, in order to help relevance judges by eliminating noise that may interfere with the comprehension of the functional specification. It is important to note that the LRA middleware deals with these issues, and supports service invocation and complete service-composition chain enactment. 


## File Organization

The folders are organized as follows:

* **html:** Contains the files that serve the website that hosts the data and results of our evaluation.  Available at http://ec2-34-221-52-138.us-west-2.compute.amazonaws.com/lraeval/.
* **lra-services**: Contains the service descriptions in OpenAPI, enhanced with LRA semantic annotations.
* **services**: Contains the service descriptions in OpenAPI, without LRA annotations.

## Contact

The authors of this dataset can be reached at:
* Diego Serrano: serranos@ualberta.ca
* Eleni Stroulia: stroulia@ualberta.ca
