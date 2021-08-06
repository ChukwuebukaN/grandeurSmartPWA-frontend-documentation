<h1 align='center'>MainLogix grandeurSmart PWA Documentation</h1>

![1](https://user-images.githubusercontent.com/64613243/127857570-c6c6f3c9-f4b4-43fa-b8f6-6b5a2e0e541a.png)

The MainLogix grandeurSmart app is a progressive web application that was developed to control smart-devices and help improve the smart home experience to users of smart-home appliances produced by <a href='https://mainlogix.org/'>Mainlogix LTD</a> that could be installed from their browsers on the home-screens of their iOS, Android or desktop devices that allow PWA installability.

grandeurSmart consists of many features which includes but are not limited to:

<ul>
  <li>User Login and Sign Up</li>
  <li>User Dashboard</li>
  <li>Weather Display</li>
  <li>Temperature, Wind, Force and Pressure Display</li>
  <li>Grouping - for categorization of Smart Devices into Rooms</li>
  <li>Updating - for renaming Smart Devices, Rooms, Persons, etc.</li>
  <li>Notifications</li>
  <li>Profile Page</li>
  <li>Settings</li>
  <li>Integrations - for integrating services available from the backend</li>
  <li>People - for creating sub-user account to access your home</li>
  <li>Light Mode and Dark Mode</li>
  <li>Installable</li>
  <li>e.t.c</li>
</ul>

<h1 align='center'>Our Design Principles</h1>

I was tasked to come up with a product design for a website interface that will serve both it's mobile and desktop users, I carried out my design research, with refrences from the development team and I also had to come up with new ideas on how to improve these references to better suit the businesses ultimate design goal.

Some if the design principles includes...

**• Mobile and Web Responsive**: first, the website had to be responsive due to persistent increase in users accessing the internet through their mobile phones over desktops or laptops devices, so this website had to be responsive which enables it to be accessible on any type of screen sizes or devices, the website is able to resize from having a sidebar on desktops or large screens to having a native-app-like footer navigation on mobile or smaller screens.

**• User-oriented interface**: the product was built to be user focused as to make it's users feel at home when utilizing the website and knowing that they are in full control of their smart-home and devices, the current users name is displayed on logging in into the website, also it shows the available devices paired and detected by the grandeurSmart system and furthermore the dashboard is presented with useful weather informations such as Current Weather, Wind force, Temperature and Pressure, also included are easy navigation, easily readable fonts, etc.


**• CRUD (Create, Read, Delete, Update)**: One of my design principles was to make the user interface very interactive by adding CRUD features to the front-end, on the grandeurSmart platform user can **Create** rooms and persons (sub-accounts), can **Update** the created rooms, smart-device names, persons, change passwords, update profile, e.t.c, and also **Delete** the rooms and persons available on the application. Also it displays rooms where available devices belong on the user dashboard to help in easily navigating areas where these devices have been categorized to.

**• Light and Dark Mode**: One other suggestions and requirements from the team was to make sure users had the option to switch between light mode and dark mode, this feature was included into the application where users can go to their account settings page and toggle if they want their devices to access grandeurSmart using any of the screen modes.

**• Installability (iOS, Android or Desktop)**: The most interesting feature of it all is that the website is installable! We created a PWA which has the ability to be installed from the browser and added to the home-screen of the device using the manifest.json and service-workers, we set-up the web app to be installed on users' devices with an install prompt which checks if the app is already installed, the app favicons and splash-screens were also set up.

The app being installable really reinforces the companies design and usability principles, which it allows users of it's products and services to easily access their smart-homes on desktop or mobile at the tip of their fingers.

<h1 align='center'>Getting started</h1>

- [x] Recommended: `Node.js 14+` and `npm 6+`
- [x] Install dependencies: `npm install` or `yarn`
- [x] Start the server: `npm run start` or `yarn start`

<h1>API </h1>

`grandeurSmartPWA/src/api/`

**login.js**

 // Send a GET request
 
        SendFlowId: async function(email, password, flow_id) {
            // console.log(email, password)
            let data = {
                username: email,
                password: password,
                client_id: 'http://localhost:3000'
            }
            return await localApi.post(`/auth/login_flow/${flow_id}`, data)
        },
        
  // Send a POST request
  
        GetFlowId: async function() {
            let data = {
                client_id: "http://localhost:3000",
                handler: ["homeassistant", null],
                redirect_uri: "http://localhost:3000",
                type: "authorize"
            }
            return await localApi.post('/auth/login_flow', data);
        }



<h1 align='center'>How it works</h1>

grandeurSmart as a PWA is a website you can access on your browser by typing it's URL into the browser url bar, you can access the app locally by connecting to the network on the gateway system provided by MainLogix, only then can you have full access to all it's functionalities.

After you create an account and login to the application, you pair in your smart-devices, Then on arriving at your dashboard will be able to see and control all your devices, categorize them into rooms, create sub-accounts for other family members, add integrations and do so much more.

Below are some of the User Interface designs and images.

<h1 >• Login and Sign Up</h1>

![Screenshot from 2021-07-22 16-09-27](https://user-images.githubusercontent.com/64613243/127873079-6a636d0d-0b35-4605-a496-23956e3b5819.png)
![Screenshot from 2021-07-23 07-35-43](https://user-images.githubusercontent.com/64613243/127873093-0afbd521-82ce-4af1-8373-11403e584f03.png)


<h1 >• User Dashboard</h1>

![Screenshot from 2021-07-29 23-37-15](https://user-images.githubusercontent.com/64613243/127876971-d55e39c8-4355-4e73-9047-64bb329ed589.png)


<h1 >• Notifications</h1>

![Screenshot from 2021-07-29 23-38-49](https://user-images.githubusercontent.com/64613243/127873572-af3a8071-1d02-4cb7-ba6f-845794b82b08.png)

<h1 >• Rooms</h1>

![Screenshot from 2021-07-29 23-42-29](https://user-images.githubusercontent.com/64613243/127874025-4ddbd016-5019-4fc7-9541-b6549a753e79.png)
![Screenshot from 2021-07-29 23-42-41](https://user-images.githubusercontent.com/64613243/127874250-69950a8c-7a4c-46a1-8762-988bbe60727b.png)

<h1 >• People</h1>

![Screenshot from 2021-07-29 23-42-01](https://user-images.githubusercontent.com/64613243/127878950-f77a4863-461b-4d9f-80d6-725814e6da11.png)


<h1 >• Integration</h1>

![Screenshot from 2021-07-29 23-43-33](https://user-images.githubusercontent.com/64613243/127878981-12faf44b-b525-4322-9c5d-f8c3c6f070f2.png)


<h1 >• Settings</h1>

![Screenshot from 2021-07-29 23-38-56](https://user-images.githubusercontent.com/64613243/127879065-b23232f0-818d-41c2-97b5-8ea02fff728f.png)


<h1 >• MOBILE VIEW</h1>

![Mainlogix grandeurSmart Mobile Views](https://user-images.githubusercontent.com/64613243/128128749-d70697f5-a0e9-4402-9f51-3585cb497fbe.png)

![Mainlogix grandeurSmart Mobile Views2](https://user-images.githubusercontent.com/64613243/128128765-59919e64-c44a-48d2-aec2-3a226b215f57.png)

![Mainlogix grandeurSmart Mobile Views3](https://user-images.githubusercontent.com/64613243/128128777-0794c523-1e4d-4e40-8629-161040bf2ad3.png)



<h1 align='center'>About the project</h1>

grandeurSmart PWA was built using **React**, a javascript library from facebook, and other libraries including Tailwind CSS, Redux-toolkit, AntD Components, etc. 

The project was developed to improve the utility chain of <a href='https://mainlogix.org/'>Mainlogix LTD</a> and its smart-home products and services offered.

Distributed under the MIT License. See LICENSE for more information.

Contact - Email Us: **support@mainlogix.org**

The project was inspired by home automation and a burning desire to improve and simplify life through technology.
