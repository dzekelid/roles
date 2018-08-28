{
  "info": {
    "name": "AWS Cognito API Get Identity Pool Roles",
    "_postman_id": "a3b873b9-429f-426d-858c-c386d09468d2",
    "description": "Gets the roles for an identity pool.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Identity Pool Roles",
      "item": [
        {
          "id": "87bc3118-50f0-4d0c-8fe5-11a215e235bd",
          "name": "getIdentityPoolRoles",
          "request": {
            "url": "http://example.com/api/?Action=GetIdentityPoolRoles?IdentityPoolId=IdentityPoolId",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Gets the roles for an identity pool."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5667491e-847b-48d4-863d-d4766ad1a288"
            }
          ]
        }
      ]
    }
  ]
}