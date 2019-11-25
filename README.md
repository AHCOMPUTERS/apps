# Azure Active Directory B2C app samples

The following tables provide links to samples for integrating Azure AD B2C as an identity provider.

## Secure REST API 

|Platform|OAuth2 library|Documentation|Source code|
|----|----|----|----|
|[.Net Core](https://docs.microsoft.com/en-us/aspnet/core/web-api/?view=aspnetcore-3.0)| [Microsoft.AspNetCore.Authentication.JwtBearer](https://www.nuget.org/packages/Microsoft.AspNetCore.Authentication.JwtBearer/)| [Documentation](apps/rest-api-dotnet-core)| |
|[.Net Framework](https://docs.microsoft.com/en-us/aspnet/web-api/)| [Microsoft.Owin.Security.Jwt](https://www.nuget.org/packages/Microsoft.Owin.Security.Jwt) |[Documentation](apps/rest-api-dotnet-fw-owin)| A combined [sample](https://github.com/Azure-Samples/active-directory-b2c-dotnet-webapp-and-webapi) for a .NET web application that calls a .NET Web API, both secured using Azure AD B2C.|
|[Node.JS](https://nodejs.org/en/), [express](https://www.npmjs.com/package/express)|[passport](https://www.npmjs.com/package/passport)|[Documentation](apps/rest-api-node-js)| A small node.js Web API [sample](https://github.com/Azure-Samples/active-directory-b2c-javascript-nodejs-webapi) for Azure AD B2C that shows how to protect your web api and accept B2C access tokens using passport.js.|
