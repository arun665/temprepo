#All the code files for backend and its API

API 1 - 

REQUEST BODY - 
name, email, message, contactno

Process - 
Saved To Database

Return -
JSON 
{
    status:boolean,
    saved_to_db:boolean,
    mail_sent:boolean
}

Status - InProcess
Endpoint - /submitQuery

API 2 - To fetch All the entries saved in Database

Request body :
{
    offset : int,
    total: int
}
But will be checked the origin of Request

Return - List of {total} entries, starting from {offset} index 

Status - In Process
Endpoint - /fetchQueries