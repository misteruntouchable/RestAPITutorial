# RestAPITutorial

### [Pictoral Walkthrough Demonstration]

   <h> </h>
    For this Lab we are going to be coding our own Rest API using Node JS and Express. To make things simple, we are going to use the example 
    of a student going to a University and requesting academic records. The API will have four main functions. The first is going to allow 
    students to request copies of their academic records. Another fuction will be to allow people to come in and register as new students. A 
    third function will be to allow students to come in and update their information like their names (first and last). And lastly, it will 
    allow students to delete their academic records.  </b>

  <h2>Languages and Utilities Used</h2>

- <b>Node JS</b> 
- <b>Postman</b>
- <b>Visual Studio Code </b>

<h2>Program walk-through:</h2>
<p align="center">
   Visual Studio Code <br/>
<img src="https://imgur.com/35F0z1d.png" height="80%" width="80%" "/>
<p align="center"> Before going into VSCode create an empty folderon your local laptop name "RestAPI", then download and open Visual 
                  Studio Code. Go to open folder and click on the empty folder you created named RestAPI then select foldr in VScode you 
                   should see this image. At the top of the browser hit the ellipsis and open and new terminal. We are going to use it 
                   to initialize our project and then install our modules. In the terminal section type npm init<br/>
 
<br />

<p align="center">
   Visual Studio Code (Terminal -->Node Package Manager <br/>
<img src="https://imgur.com/g1UNARa.png" height="80%" width="80%" "/>
<p align="center"> NPM stands for Node Package Manager and init stands for initialize. This will set up your project for you so accept all the defaults then in will install a JSON file called package.json. Next we are going to install our modules.   <br/>
 
<br />


<br />

<p align="center">
   Module installation using Express <br/>
<img src="https://imgur.com/WcHZ3vG.png" height="80%" width="80%" "/>
<p align="center"> Express is used to make our API easily accept web requests. So type npm install express in the Terminal section.
                   After it is install you should see in our package.json  dependecies and the express was installed. Then will will 
                   install a few more modules body-parser, which is used to parse the body of API requests. And lastly we want to 
                  install nodemon. Nodemon will automatically restart your server for you every time you save the file that you are 
                  working on.<br/>
 
                  <br />


