##### MERN STACK IMPLEMENTATION
###### BACKEND CONFIGURATION
**Update of Ubuntu** "sudo apt update"

![sudo update](https://user-images.githubusercontent.com/90611657/193079892-2da2c8c6-d7f2-437b-bac3-87d3d23f072f.JPG)
**sudo apt upgrade** "sudo apt upgrade"

![sudo apt upgrade](https://user-images.githubusercontent.com/90611657/193080578-3d0b1c51-c0e7-4b72-bcad-a850519da0c3.JPG)

**locate of Node.js software from Ubuntu repositories**  "curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -"

**Install Node js** "sudo apt-get install -y nodejs" This command installs both nodejs and npm package manager. it is used to install Node modules & packages and to manage dependency conflicts

![install node js](https://user-images.githubusercontent.com/90611657/193082699-aeb7b453-d064-47f7-a55e-31a9230f3bca.JPG)
Use "node -v " and "npm -v" **to Verify the node installation with the command below**
![node v](https://user-images.githubusercontent.com/90611657/193272567-5f06c86a-d26a-405b-b91f-7b5324b4e8b3.JPG)

## Application Code Setup
**Create a new directory for the To-Do project**
"mkdir Todo"
**Run the "ls" command below to verify that the Todo directory is created**
ls
Now change current directory to the newly created Todo 
"cd Todo" and 
**use the command "npm init" to initialise your project, so that a new file named package.json will be created.**
"npm init"
![npm init](https://user-images.githubusercontent.com/90611657/193274584-f054ac5d-9b13-464e-87a6-843580311f10.JPG)
**Install ExpressJs and create the Routes directory**
"npm install express" **create the index.js file** "touch index.js" **and install the dotenv with**  "npm install dotenv"

![install express](https://user-images.githubusercontent.com/90611657/193277606-ed1f3230-0845-4095-9e54-71be16ca77d4.JPG)

**open index.js with the** " vi index.js" **and paste a sample code **

![vi index](https://user-images.githubusercontent.com/90611657/193290662-6ee92be2-1797-43c5-9bfe-7c7f51a17a2a.JPG)

**start our server to see if it works** "node index.js"

![node index](https://user-images.githubusercontent.com/90611657/193299226-e547b780-334d-4acb-a996-a0e08c8550bc.jpg)

 **output result accessing server’s Public IP followed by port 5000** http://13.41.73.242:5000
 
 ![express](https://user-images.githubusercontent.com/90611657/193300258-bb8a6477-d6ad-4dc7-9537-0d19ccd72a9a.JPG)
 
**There are three actions that the To-Do application needs to be able to do**

   **Create a new task**
   
   **Display list of all tasks**
   
   **Delete a completed task**
   
**Each task will be associated with some particular endpoint and will use different standard HTTP request methods: POST, GET, DELETE.

 **
 

