To clone and open up the project on a local IDE, use the command:
>git clone https://github.com/annexyz/SignUp.git

As project has .gitignore file containing node_modules to avoid unncessary data redundancy, dependenies have to be rebuilt using: 
>npm install

To serve the project:
>ng serv

Additionally, disable Samesite setting on web browser as the CORB feature prevents cross-site file reading and the image (logo) cannot be loaded from an insecure foreign source. 

Application serves single page containing Sign Up panel for a sample company website. This application is created using Angular 9 and uses HTML5 and CSS. No other frameworks are used so as to keep it simple. Frontend resembles the requested image as much as possible. As requested features are small, they are all contained in one component, the AppComponent. The header contains a sample logo from public domain. The sign up panel a form for taking input for signup details. It must be added that it also contains dummy buttons for social media login as I experienced problems while implementing JavaScript SDK for Facebook for Angluar and was unable to replace them with the Facebook button as the sdk was not properly installed. 
