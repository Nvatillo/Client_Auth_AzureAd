# Client_Auth_AzureAd
es un proyecto basico donde uso Azure Active Directory para autentificacion por token.  

para conseguir el access token se debe ingresar 

https://login.microsoftonline.com/TentantId/oauth2/authorize?
client_id=ClientId
&response_type=token
&redirect_uri=http%3A%2F%2Flocalhost%3A5000%2F
&resource=ClientId
&response_mode=fragment
&state=12345
&nonce=678910


esto devolvera un token por Url y despues lo pegaremos en postam de la siguiente manera 

![image](https://user-images.githubusercontent.com/66400630/158605691-70b4ecda-20fb-4f2f-9f30-98a7cb73222a.png)
