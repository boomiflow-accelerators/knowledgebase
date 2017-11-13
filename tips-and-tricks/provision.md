# Provision a custom tenant

Using the API Tool within flow or simply Postman hit the following endpoint with a POST

`https://flow.manywho.com/api/admin/1/provisioning`

With the following JSON:

```
{
  "firstName":"John",
  "lastName":"Smith",
  "password":"password",
  "email":"john.smith@somthing.com",
  "tenantName":"my-tenant-name"
}
```



