 Invoke-RestMethod -Uri "http://localhost:8080/api/auth/local/register" `
>>   -Method Post `
>>   -Headers @{
>>     "Content-Type" = "application/json";
>>     "Authorization" = "Bearer 42bef8658254fdf36b26de7e17b15f1f03a79b29aa45c7b53743acef29626b498d8b1bb4174db892f0805192f5b444a717569e1b7e593b56e5447daa5c9eea610614f4a6bc272f53477ca7a52061a40e8d4a548511cd1a0d69e1d2e1281500e4810f7df467162669e16f9b6a413a246a9c35bb3b4d18ccddbebb32c7a8f93925"
>>   } `
>>   -Body '{
>>     "username": "pronwisa",
>>     "email": "s6602041510041@email.kmutnb.ac.th",
>>     "password": "pronwisa0605"
>>   }'
