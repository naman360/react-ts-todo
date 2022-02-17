# React Typescript Todo
A basic todo application made using React and Typescript. It contains drag and drop feature to set task as completed and vice versa. 
 
## Setup 
### Setup on local machine
1. Clone the project. <br>
2. Run `npm install` in the cloned directory. <br>
3. Start the server using `npm start` and view it on `localhost:3000` 

### Setup using Docker
1. Clone the project. <br>
2. In the cloned directory, run `docker build . -t <IMAGE NAME OF YOUR CHOICE>`.<br>
3. After execution, image will be created which can be viewed using `docker images`, it will contain the image name which you entered previously.<br>
4. Start the container using `docker run <IMAGE NAME>`.<br>
5. After execution it will contain the link to view the application.<br>
<b>Note:</b> You will not be able to view the application on `localhost:3000`.<br>
For viewing it on your localhost, you need to forward the port using `docker run -p <PORT NUMBBER>:3000 <IMAGE NAME>`.
