# Angular-4

# Angular-5 to Angular-4
Now , latest angular version is 5, when we install angular cli or create angular project then default it take latest version i.e. 5. But we need stable version which is version 4. So, below is the command we need to install .

**On Linux/Mac:**

npm install @angular/{common,compiler,compiler-cli,core,forms,http,platform-browser,platform-browser-dynamic,platform-server,router,animations}@4.4.6 typescript@latest --save

**On Windows:**

npm install @angular/common@4.4.6 @angular/compiler@4.4.6 @angular/compiler-cli@4.4.6 @angular/language-service@4.4.6 @angular/core@4.4.6 @angular/forms@4.4.6 @angular/http@4.4.6 @angular/platform-browser@4.4.6 @angular/platform-browser-dynamic@4.4.6 @angular/platform-server@4.4.6 @angular/router@4.4.6 @angular/animations@4.4.6 typescript@latest --save

**Install Bootstrap 4**

Step- 1

npm install bootstrap@4.0.0-beta --save

Step -2

2) after inside angular-cli.json (inside project root folder) find styles and add a bootstrap css like this:

"styles": 

"../node_modules/bootstrap/dist/css/bootstrap.min.css",

 "styles.css" 
 
],
