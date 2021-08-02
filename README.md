<h1 align='center'>MainLogix grandeurSmart PWA Documentation</h1>

![1](https://user-images.githubusercontent.com/64613243/127857570-c6c6f3c9-f4b4-43fa-b8f6-6b5a2e0e541a.png)

The MainLogix grandeurSmart PWA is a progressive web application that was developed to control smart-devices and help improve the smart home experience to users of smart-home appliances produced by <a href='https://mainlogix.org/'>Mainlogix LTD</a> that could be installed from thier browsers on the home-screens of thier iOs, Android or desktop devices that allow PWA installability.

grandeurSmart consist's of many feautures which includes but are not limited to:

<ul>
  <li>User Login and Sign Up</li>
  <li>User Dashboard</li>
  <li>Weather Display</li>
  <li>Temprature, Wind, Force and Pressure Display</li>
  <li>Grouping - for categorization of Smart Devices into Rooms</li>
  <li>Editing - for renaming Smart Devices, Rooms, Persons, etc.</li>
  <li>Notifications</li>
  <li>Profile Page</li>
  <li>Profile Settings</li>
  <li>Integrations - for integrating services available from the backend</li>
  <li>People - for creating sub-user account to access the smart-home</li>
  <li>Light Mode and Dark Mode</li>
  <li>Installable</li>
  <li>e.t.c</li>
</ul>

<h1 align='center'>My Design Principles</h1>

I was tasked to come up with a product design for a website interface that will serve both it's mobile and desktop users, in my design research process and after having a clear communication with the team, I was given refrences and had to come up with my own ideas on how to improve these refrences to better suit our ultimate design goal. 

**• Mobile and Web Responsive**: first, the website had to be responsive due to persistent increase in users accessing the internet through their mobile phones over desktops or laptops devices, so this website had to be responsive which enables it to be accessible on any type screen size or device, the website is able to switch on having a sidebar on desktops or large screens to having a native-app-like footer navigation on mobile or smaller screens.

**• User-oriented interface**: the product was built to be user focused as to make it's users feel at home when utilizing the website and knowing that they are in full control of their smart-home and devices, this user name is displayed on logging in into the website, thier dashboard is filled with usefull weather informations such as Current Weather, Wind force, Temprature and Pressure.

It also show the available devices paired and detected by the grandeurSmart system, it displays rooms where those devices belong on the user dashboard to help in easily navigating areas where these devices have been categorized to. 

**• CRUD (Create, Read, Delete, Update)**: One of my design principles was to make the user interface very interactive by addind CRUD feautures to the front-end, on the grandeurSmart platform user can **Create** rooms and persons (sub-accounts), can **Update** the created rooms, smart-device names, persons, change passwords, update profile, e.t.c, and also **Delete** the rooms and person available on the application.

**• Light and Dark Mode**: One other suggestions and requirements from the team was to make sure users had the option to swicth between light mode and dark mode as growing concerns towards eye health damage from the blue-light emitted from mobile and desktop screens, so this feauture was included into the application where users can go to thier account settings and toggle if they want thier devices to access grandeurSmart using any of the screen modes.

**• Installability (iOs, Android or Desktop)**: The most interesting feature of it all is the website is installable!, due to the advancement in web technologies we created a PWA which has the ability to be installed from the browser and added to the home-screen of the device. Using the manifest.json and service-workers we set-up the web app to be installed on users devices by showing a install prompt which checks if the app already installed, and the app favicon and splash-screens all setup. 

The app being installable really reinforces the companines design and usability principles, where it allows users of it's tech products to easily access thier smart-homes whether on web or mobile at the tip of thier finger.


<h1 align='center'>How it works</h1>

grandeurSmart as a PWA is a website you can access on your browser by typing it's URL into the browser url bar, then you can access it locally by connecting to the network on gateway system provided, only then can you fully have access to the website full functionalities.

After you create an account or login into the application and pair in your smart-devices, you will be able to control your devices, categorize them into rooms, create accounts for other family members, add integrations and do so much more.

Below are only some of the User Inerface designs and images.

<h1 >• Login and Sign Up (Desktop View)</h1>

![Screenshot from 2021-07-22 16-09-27](https://user-images.githubusercontent.com/64613243/127873079-6a636d0d-0b35-4605-a496-23956e3b5819.png)
![Screenshot from 2021-07-23 07-35-43](https://user-images.githubusercontent.com/64613243/127873093-0afbd521-82ce-4af1-8373-11403e584f03.png)


<h1 >• User Dashboard (Mobile View)</h1>

![localhost_3000_dashboard(Pixel 2 XL) (1)](https://user-images.githubusercontent.com/64613243/127873191-b8961ae3-ca53-490f-a32b-9d2c176d025c.png)

<h1 >• Notifications (Desktop View)</h1>
![Screenshot from 2021-07-29 23-38-49](https://user-images.githubusercontent.com/64613243/127873572-af3a8071-1d02-4cb7-ba6f-845794b82b08.png)

<h1 >• Rooms (Mobile and Desktop View)</h1>

![localhost_3000_settings_people(Pixel 2 XL) (4)](https://user-images.githubusercontent.com/64613243/127873926-7f972c54-a33b-474b-b838-2faf8bb92000.png)
![localhost_3000_settings_rooms(Pixel 2 XL)](https://user-images.githubusercontent.com/64613243/127874228-571f7c41-f999-4c99-a808-49dbcb6e7eee.png)

![Screenshot from 2021-07-29 23-42-29](https://user-images.githubusercontent.com/64613243/127874025-4ddbd016-5019-4fc7-9541-b6549a753e79.png)
![Screenshot from 2021-07-29 23-42-41](https://user-images.githubusercontent.com/64613243/127874250-69950a8c-7a4c-46a1-8762-988bbe60727b.png)

<h1 >• People (Mobile View)</h1>
![localhost_3000_settings_people(Pixel 2 XL) (3)](https://user-images.githubusercontent.com/64613243/127874178-931ab145-2396-428f-911d-fc1a21f32d1c.png)
![localhost_3000_settings_people(Pixel 2 XL) (2)](https://user-images.githubusercontent.com/64613243/127874297-ed26c082-7844-41f9-a541-0d2882d60c52.png)

<h1 >• Integration</h1>
![localhost_3000_settings_integrations(Pixel 2 XL) (1)](https://user-images.githubusercontent.com/64613243/127874309-3ec6796b-2613-4195-a8a1-aec7fdee974d.png)

<h1 >• User Profile</h1>
![localhost_3000_dashboard(Pixel 2 XL) (4)](https://user-images.githubusercontent.com/64613243/127874540-94954f52-f62e-4be3-acc1-9969121c735f.png)

<h1 >• Settings (Mobile View)</h1>
![localhost_3000_dashboard(Pixel 2 XL) (3)](https://user-images.githubusercontent.com/64613243/127873293-8f4f970b-f144-4f9d-aa0d-ed2aeb29add0.png)


<h1 align='center'>About the project</h1>

grandeurSmart was built using **React**, a web browser javascript library from facebook, and other libraries including Tailwind CSS, Redux-toolkit, AntD Components, etc. The project was developed to improve the utility chain of <a href='https://mainlogix.org/'>Mainlogix LTD</a> and its smart-home products and services it offers.

The project was inspired by home automation and a burining desire to improve and simplify living through technology.

Great contributions from <a href='https://github.com/timothyakinyelu'>Tim Akinyelu</a> (Back-end Developer)

Many Thanks to **Tim Akinyelu** for the many contributions & guidance, and **Josiah Akinloye** and the entire MainLogix family for thier support.
