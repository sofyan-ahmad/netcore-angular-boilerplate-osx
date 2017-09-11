# Introduction

This is a template to create **.NET Core API and Angular for OSX and linux with MySQL DB**, based startup projects for [ASP.NET Boilerplate](https://aspnetboilerplate.com/Pages/Documents).
 
User Interface is based on [BSB Admin theme](https://github.com/gurayyarar/AdminBSBMaterialDesign).
 
# Up and Running
### Baceknd
- git clone https://github.com/sofyanhadia/netcore-angular-boilerplate-osx.git 
- cd aspnet-core/src/AbpCompanyName.AbpProjectName.EntityFrameworkCore
- dotent restore
- Configure mysql server in:
    ```
    AbpCompanyName.AbpProjectName.Migrator/appsettings.json
    AbpCompanyName.AbpProjectName.Web.Mvc/appsettings.json
    AbpCompanyName.AbpProjectName.Web.Host/appsettings.json
    ```
- dotnet ef database update
- cd ../AbpCompanyName.AbpProjectName.Web.Host
- dotnet run

### Frontend
- cd angular
- npm install
- npm start

# Download

Create & download your project from https://aspnetboilerplate.com/Templates

# Screenshots

#### Sample Dashboard Page
![](_screenshots/module-zero-core-template-ui-home.png)

#### User Creation Modal
![](_screenshots/module-zero-core-template-ui-user-create-modal.png)

#### Login Page

![](_screenshots/module-zero-core-template-ui-login.png)

# Documentation

* [ASP.NET Core MVC & jQuery version.](https://aspnetboilerplate.com/Pages/Documents/Zero/Startup-Template-Core)
* [ASP.NET Core & Angular  version.](https://aspnetboilerplate.com/Pages/Documents/Zero/Startup-Template-Angular)

# License

[MIT](LICENSE).