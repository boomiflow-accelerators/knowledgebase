# Provision a custom tenant



Using the API Tool within flow or simply Postman hit the following endpoint with a POST

`https://flow.manywho.com/api/admin/1/provisioning`



With the following JSON:

```
{
  "firstName":"William",
  "lastName":"Eccles",
  "password":"password",
  "email":"william.eccles@manywho.com",
  "tenantName":"elavon-production"
}
```



