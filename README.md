# api-posts

## REST API with express / mongodb / netlify / serverless 

# GET
https://api-posts-jeric.netlify.app/.netlify/functions/api

# POST
https://api-posts-jeric.netlify.app/.netlify/functions/api
PAYLOAD:
{    
    "username": "johndoe",
    "email": "johndoe@gmail.com",
    "password": "abc123"
}

# GET:id
https://api-posts-jeric.netlify.app/.netlify/functions/api/63102dea2f72af4e9629e40a

# PUT:id
https://api-posts-jeric.netlify.app/.netlify/functions/api/63102dea2f72af4e9629e40a
PAYLOAD:
{    
    "username": "newjohndoe",
    "email": "newjohndoe@gmail.com",
    "password": "newabc123"
}

# DELETE:id
https://api-posts-jeric.netlify.app/.netlify/functions/api/63102dea2f72af4e9629e40a
