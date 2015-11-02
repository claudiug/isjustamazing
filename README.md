
###### API
> models:
 * user
 * template
 * versions
 * place_holder
 * connector
 
> relationship between models:
 * *user* has_many *templates*
 * *template* belongs_to *user*
 * *template* has_many *versions*
 * *user* has_many *place_holder*
 * *template* has_many *place_holders*
 * *user* has_many *connectors*
 
> endpoints
 * *GET* /v1/status
 * *GET* /v1/templates
 * *GET* /v1/templates/:id
 * *POST* /v1/templates
 * *GET*  /v1/templates/
 * *GET* /v1/templates/:id/edit
 * *PUT*  /v1/templates/:id
 * *DELETE*  /v1/templates/:id
 * *GET* /v1/users
 * *GET* /v1/users/:id
 * *POST* /v1/users
 * *GET*  /v1/users/
 * *GET* /v1/users/:id/edit
 * *PUT*  /v1/users/:id
 * *DELETE*  /v1/users/:id


 


###### Rails App

###### ruby library
