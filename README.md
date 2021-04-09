# Allstar

## Project Objective

Welcome to Allstar! Allstar are a new gym francise who have set up facilities in the Dublin City area. They require a new website that targets customers with attractive design and vivid imagery. 

The website design I have chosen is clear and concise, and provides sufficient information to satisfy the curiousity of prospective members. This information can be easily obtained due to the intuitive layout of the page. It utilises striking colors and appealing imagery to catch the users attention.

## UX

### Website Design Goals

- A striking landing page with design matching the business's brand
- A website that works seamlessly on mobile, tablet and desktop devices
- Vivid imagery to capture the imagination of website visitors
- Information regarding gym facilities, classes and trainers
- Smooth intuitive navigation elements to assist user experience
- Information regarding contact details, site locations and a contact form option
- Member testemonials
- Social media links

### User Stories

- As a user, I want to find out what these gyms have available at their facilities. 
- As a user, I want to know what kind of gym this is as well as the clientele I can expect to find here.
- As a user, I want to find information regarding classes as well as associated times. 
- As a user, I want to research pricing and policy information.
- As a user, I want to see images that show off the gyms interior and imagine myself there and how comfortable I may or may not feel.
- As a user, I want to be able to see testemonials from people who are already members.
- As a user, I want to find out if one of the gyms are near me.
- As a user, I want to be able to contact a member of staff using information available on the site.
- As a user, if I left something behind I will have piece of mind to know I can get in touch quickly and can avoid a phonecall.
- As a user, I want the website to motivate me to join and to start working out and better myself.
- As a user, I want to be able to intuitively move around the site.

### Site Owner Goals

- To advertise our presence within the Dublin area
- To attract new members
- To persuade customers to consider us over our competitors
- To stand out as a brand in peoples minds
- As a user, I want to have access to the gyms assoicated social media so I can be part of their community.

### User Requirements and Expectations

#### Requirements

- Striking and attractive overall design
- Easy to navigate using the navigation bar and other interactive elements
- Relevant information including everything a potential customer could be looking for
- Clear and concise information regarding pricing and policy
- Appropriate contact and location information including contact form 

#### Expectations

- I can quickly find the info I am looking for
- I wont be confused, distracted, or discouraged by the website layout
- I expect the navigation links to work and take me to where I need to go
- I expect the website to be responsive and intuitive on mobile, tablet, or desktop
- I expect the website to assist with the customers journey in joining up
- I want social media or any other expernal links on the page to open up a new tab in the browser

### Design Choices

I went with a design that aims to empower the potential gym user, to invoke strong emotions of confidence and inner strength. I want potential customer to view this website as a portal to becoming the best they can be. This requires a blend of strong dark colors blended with bright striking ones to add a visual flair. 

#### Fonts

For fonts I browsed [Google Fonts](https://fonts.google.com/?preview.text=Strong&preview.text_type=custom) for a good strong title and heading font as well as a font suited for detailed information. I chose [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue?preview.text=Strong&preview.text_type=custom#standard-styles) for my strong title font as I felt it gives headlines a punchy, standout look. This pairs well with [Roboto](https://fonts.google.com/specimen/Roboto?preview.text=Strong&preview.text_type=custom) which I used for all paragraph text. Roboto is easily legible and should aid with accessibility as it allows for a more natural reading rhythm.

#### Icons

I used some free icons available on [Font Awesome](https://fontawesome.com/icons?d=gallery&p=2) to enhance and draw attention to certain sections of the page. The appropriate icons coincide with the topic being discussed in the text, such as using a dumbell when talking about gym equipment. Soical media icons are used instead of urls for asthetic enhancement. These icons are also styled alongside all other elements of the page so they blend seemlessly without sticking out. The navigation is also designed to shrink into a hamburger button when the page is using mobile screen format.

#### Colors

For colors I went with a blend of light and dark colors. Lighter colors are primarily used for text and icon elements while the darker colors provide the background that allows the text elements to pop. I will go into greater detail, color by color, below the image.

![Allstar-color-pallete](https://github.com/JMuckian94/Allstar-Gyms-MS1/blob/master/AllstarColorPal.png "Allstar-Color-Pallete")

- #981F29 Ruby Red: This color will be used for 
- #090446 Midnight Blue: This color will be used for
- #4361EE Ultramarine Blue: This color will be used for
- #494947 Davys Grey: This color will be used for
- #FFFFFF: This color will be used for primarily text elements as it will stand out best on dark backgrounds.

Work in progress

#### Structure

I chose to utilise [Bootstrap](https://getbootstrap.com/docs/4.6/getting-started/introduction/) to create the overall structure of the website. It allowed me to have all my content in responsive row/column sections on the page. These sections can also adapt to various screen sizes. Bootstrap can also provide some basic CSS and Javascript functionality so it is a great way to assemble the skeleton of the page before custom styling begins.

## Wireframes

I used [Balsamiq](https://balsamiq.com/wireframes/?gclid=Cj0KCQjw9YWDBhDyARIsADt6sGbn1ZOXBiFtGYsZKhw_Vn14WS0VrUxu8nj3vnZ_2fwGqf4FdsBoB20aAosXEALw_wcB) to create my wireframe mockups. I used industry best practice to start my designs with mobile viewports before scaling up and fleshing out the website more on larger devices. For overall design, I went with a single page website as my skills are limited to static mobile designs at this point in my learning journey. As mentioned before, the nav bar will assist in quickly scrolling to the desired area of the page.

Here are the links to my wireframes:

### [Desktop Wireframe](https://github.com/JMuckian94/Allstar-Gyms-MS1/blob/master/Wireframes/Allstar%20Desktop%20Wireframe.png)

### [Tablet Wireframe](https://github.com/JMuckian94/Allstar-Gyms-MS1/blob/master/Wireframes/Allstar%20Tablet%20Wireframe.png)

### [Mobile Wireframe](https://github.com/JMuckian94/Allstar-Gyms-MS1/blob/master/Wireframes/Allstar%20Mobile%20Wireframe.png)

## Features

### Navigation

I used Bootstrap to create a responsive searchbar that will adapt to the platform the user is viewing the website from. Since this is a single page site design I have opted for a sticky navbar. This will give the user greater agility and help them identify the relevant information sooner. This navbar will convert to a hamburger icon on mobile devices to avoid crowding. I have also implemented the Bootstrap scroll spy feature, to remind the user where they are currently on the page, by highlighting the appropriate heading in the navbar.

### Hero Image Slideshow

The hero image slideshow will act as an initial impression maker for any first time visitors, adding some dynamism to an otherwise static website. This section will use a rotation of images to give users a quick taste of the gyms atmosphere. The slideshow is configured to occupy 100% screen width and to adjust height to the appropriate size for each viewing platform.

### Promotional Jumbotron

Here I have added a Bootstrap jumbotron to announce the current promotion on offer with Allstar Gyms. It will include the announcement message, some special pricing information, and a sign up button. All text will be centered and custom styled with CSS.

### Reviews

I have added a reviews section, positioning it using the Bootstrap grid system. On Desktop, I have aligned the first members image to the left the second to right while centering the review text. I wanted to minimise unused space in this area. On tablet,  both review images are aligned left with text aligned right. On mobile, the reviews section is configured to hide the images and only display the review text. This is to avoid crowding.

### FAQs

For this section, I went for the Bootstrap accordian feature to organise the FAQs, making them easier to use and navigate. The initial framework is constructed in HTML using Bootstrap and then styled further in CSS. "+" and "-" symbols provided by FontAwesome add addtional visual indicators to assist accessiblility.

### Gallery

The gallery section will have 3 columns on Desktop, 2 on tablet and 1 on mobile. The images selected will showcase the gyms interior, equipment and clientele. Each image is scaled appropriately for the column it occupies with mobile configured to have the image fill full screen width. I also reduced the number of images available on smaller devices to reduce user fatigue.

### Class Schedule

For this section I went with a dark background image of the gym facility which I then overlayed with column sections. These columns contain the class schedule information and everything is formatted to be easily legible to the user while adding an attractive, eye catching section to the page. 

### Contact Section

This section will contain the company's contact information as well as a contact form for if email or phone options arn't imediately available to the user. I aligned the contact information on the left and the contact form on the right. Below these elements will be the company's social media links

## Features to be Implemented

- Sign up modal for when the user clicks the sign up button on the jumbotron

## Technologies Used

### Languages

- HTML
- CSS
- Javascript

### Framworks & External Liberaries

- [Bootstrap 4.6.0](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
- [Font Awesome](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [Unsplash](https://unsplash.com/)
- [Stockvault](https://www.stockvault.net/)

### Tools

- [Git](https://github.com/)
- [Gitpod](https://gitpod.io/workspaces)
- [Balsamiq](https://balsamiq.com/)
- [W3C HTML & CSS Validation Service](https://validator.w3.org/)

## Testing of Interactive Elements

### Navigation
- Plan
I will create a navbar that will follow the user down the page. This suits the single page design and will help the user navigate to the desired sections with ease. I will also include a scrollspy feature to highlight what area of the page the user is currently looking at. The navbar will increase the number of items available from small to large screens. It will transition from a hamburger icon to a short list of items and then to the full list at large screen widths.

- Implementation
The navbar was created using Bootstrap components. This allowed for initial simple alignment, coloring and font options. I then overrided some of these elements using my own CSS styling. Bootstrap also made the transition from hamburger to full list of nav items simple using its intuitive display property classes.

- Test
I clicked each item in the live navbar to test that it takes me to the correct area of the page each time. I also opened the site and did this test again on Edge, Firefox, Chrome and Safari to make sure the experience was consistant and bug free. 

- Result
On tablet and mobile the nav elements reduced nicely and then finally converted to the hamburger icon without issues. The navigation also worked on all browsers tested without error. However, I am still adjusting the logo positioning on mobile as it currently wraps the hamburger icon giving an uneven look.

- Verdict
All nav elements and display properties work as intended. Some styling issues left to be resolved.

### Modals
- Plan
I plan to implement a modal that appears whenever the user clicks the Sign In/Sign Up navbar item or the Sign Up button on the jumbotron. This modal will contain a form to fill out with various personal information typically needed for a new user account. I also want to include a modal that pops up when a user has submitted info correctly in the contact section.

- Implementation
I utitilised Bootstrap's packaged Javascript elements to include this funtionality. The modal is centered on the page and uses similar styling to the rest of the site. The modal includes form elements that ask for full name, address, and email. Card information is ommited as in future I would include that in a more secure format via an encrypted external process. The user also has the option to exit the modal using an "X" symbol in the top right corner. The contact section modal just includes a message and does not ask for further input.

- Test
I have tested the sign up modal and it is functioning well on all browsers and device sizes. The form elements seek info when trying to submit by turning red. Currently nothing happends when info is provided. The modal simply closes. This is the same for the "X" symbol, the user will be returned to the main site.

- Result 
All the form elements are functioning as intended and the submit and "X" buttons function as intended for this project. Some styling elements clash and require adjustment.

- Verdict
All functionality working. Styling needs further work.

### Contact Form
- Plan
I plan to implement three form elements to the contact section, asking the user to provide full name, email address, and their query in seperate areas. There is then a submit button to click at the bottom for when the user is finished inputting their info. Once the submit button is clicked with the required fields filled a modal message should appear to inform the user that the query was sent successfully. 

- Implementation
I used grid and form components from Bootstrap to provide structure and positioning of the contact form. Bootstrap also made it easy to scale up and float the form, from underneath, to the right on larger screens so as to be adjacent to the business contact info. I then  styled the text elements using CSS to make it consistant with the rest of the site. I went with a label format instead of placeholders, as I have space to work with in that section and I felt it looked better.

- Test
All form elements are working correctly. However, the modal currently pops up regardless of whether the user has inputted information or not. This will be fixed for the final deployment. Currently, user data isn't being saved or sent anywhere. This functionality will be implemented once I aquire new abilities with Javascript and have the appropriate resources for data storage and encryption. All elements floated to desired positions on various screen widths.

- Result
Form elements functioning as intented. Submit button working as intended. Responsive elements working as intended. Modal requires extra Javascript elements to function as intended. Some styling elements looked a bit ugly.

- Verdict
Modal and styling requires further work. All other elements and their positioning in line with initial plan.

### Bugs

#### Hero Image Carousel
- Bug
Carousel was changing heights to suit image aspect ratio instead of remaining within its desired container.

- Fix
Applied CSS styling to set max-height to 500px. I also added a container-fluid Bootstrap class so that the carousel always took up 100% screen width.




