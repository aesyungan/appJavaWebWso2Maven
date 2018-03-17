# appJavaWebWso2Maven
ejemplo de una aplicación web en java 
# configuracion <Proyecto>/src/main/resources/travelocity.properties
### A unique identifier for this SAML 2.0 Service Provider application
SAML2.SPEntityId=travelocity.com
### The URL of the SAML 2.0 Assertion Consumer
SAML2.AssertionConsumerURL=http://wso2is.local:8084/travelocity.com/home.jsp
### The URL of the SAML 2.0 Identity Provider
SAML2.IdPURL=https://ayungan.me:9443/samlsso
### OAuth2 token endpoint URL
OAuth2.TokenURL=https://ayungan.me:9443/oauth2/token
### OpenId Provider Url
OpenId.ProviderURL=https://ayungan.me:9443/openid/
### openid.return_to parameter
OpenId.ReturnToURL=http://wso2is.local:8084/travelocity.com/home.jsp

## estas configuraciones se realizaron para el WSO2 Identity Server 5.5.0 - RC2
servidor: https://ayungan.me:9443
app cliente :http://wso2is.local:8084/travelocity.com
#### es necesario crear un dominio para la aplicacion del cliente para q  funcione correctamente las cookies en: linux sudo nano /etc/hosts en windows C:\Windows\System32\drivers\etc\hosts  ejemplo 127.0.0.1  wso2is.local 

### para mas informacion https://docs.wso2.com/display/IS550/Configuring+Single+Sign-On
