# DRASync

Allows organizations to register/unregister printers for Document Routing Agents via the D365 user interface rather than needing to do so via each individual DRA application.

# Demo

Registered printers within each DRA are visible in the D365 application.

<img width="858" height="238" alt="image" src="https://github.com/user-attachments/assets/cde5de5d-9728-447a-8ad2-5c7f5fd386bc" />

<img width="975" height="531" alt="image" src="https://github.com/user-attachments/assets/7b804265-9d81-4826-ba0e-95b2654a430c" />


Via the D365 application, one can deregister the printers assigned to a given DRA.

<img width="975" height="539" alt="image" src="https://github.com/user-attachments/assets/4ad43d37-4723-435e-a0bd-800e9a3638ab" />

<img width="975" height="194" alt="image" src="https://github.com/user-attachments/assets/b3dc105a-a28c-4903-9249-4b66c4d78c52" />


As well as add back printers as needed via the D365 application. 

<img width="975" height="502" alt="image" src="https://github.com/user-attachments/assets/21c1646f-b6b5-4ba7-886d-89544fdf5154" />

<img width="814" height="278" alt="image" src="https://github.com/user-attachments/assets/3388b3fa-3ace-4843-a986-eafbddd7bb85" />


# Logic

An assumption is that the DRA/printer association is stored within the DRA application itself.  However, the relationship is actually stored in D365 itself, and the DRA makes API calls to retrieve and update this data.  
All this feature does is access that relation and update as needed.  

<img width="542" height="531" alt="image" src="https://github.com/user-attachments/assets/9d1e5f77-8ca6-4581-a367-bfb8ccaeddf3" />

<img width="786" height="447" alt="image" src="https://github.com/user-attachments/assets/e8192af2-af6c-42c5-927e-c62924d4a9d4" />

