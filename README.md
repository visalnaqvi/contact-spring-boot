## Available Endpoint:

Method:GET
Endpoint:/api/contacts
Responsse: List of All Available Contacts
[{"name":"new contact","address":"new address","phoneNumber":"123456789","email":"newemail@emai.com"}]

-----------------

Method: POST
Endpoint:/api/contacts/new
Request body:
{
    "name":"new contact",
    "address":"new address",
    "phoneNumber":8920152023,
    "email":"newemail@emai.com"
}


-----------------


Method: DELETE
Endpoint: /api/contacts/{id}   
Note:id = phone number


-----------------


Install Maven dependencies from pom.xml


