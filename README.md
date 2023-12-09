

<img align='center' alt='coding' src='https://media.licdn.com/dms/image/D5616AQFG60xaS3kYMg/profile-displaybackgroundimage-shrink_350_1400/0/1702117946762?e=1707350400&v=beta&t=_ZuxcmPFqD_EVK-mvvLjKdZDqQ0O_LGsI-5T6HW8uL0'>

<img align="right" src="https://komarev.com/ghpvc/?username=samirsadek&label=Profile%20views&color=0e75b6&style=flat" alt="samirsadek" />
<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Samir+Sadek!;" />
</h1>

<h3 align="center">A passionate Front-End Developer from 🇧🇩</h3>

<br/>

<div align="center">
 
 🔭 Eager to dive into the world of **MERN stack development** and unleash its creative potential.
 
 🌱 I’m currently learning **Redux, Next.js**

💬 Ask me about **Javascript, React, Firebase, Express, Mongodb**

🌍 Dhaka, Bangladesh.

 </div>

<div align="center"> 
  <a href="mailto:samirsadek1009@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://www.linkedin.com/in/samir-sadek-9487a6132" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="https://github.com/SamirSadek" target="_blank">
     <img src="https://img.shields.io/badge/github-FF5722?style=for-the-badge&logo=github&logoColor=white" target="_blank" /> <!-- sqlite, safari, google-chrome are other good icon options -->
  </a>
</div>
    

 <hr/>

<h2 align="center">⚒️ Languages-Frameworks-Tools ⚒️</h2>

<br/>
<div align="center">
    <img src="https://skillicons.dev/icons?i=react,html,css,vscode,github,figma,tailwind,git" /><br>
    <img src="https://skillicons.dev/icons?i=nodejs,python,javascript,express,firebase,mongodb,c" /><br>
</div>

<hr/>

<h2 align="center">📊 GitHub Stats 📊</h2>
<br>
<div align=center>
<img  src="https://github-readme-stats.vercel.app/api/top-langs?username=samirsadek&show_icons=true&locale=en&layout=compact" alt="samirsadek" />  <img src="https://github-readme-stats.vercel.app/api?username=samirsadek&show_icons=true&locale=en" alt="samirsadek" />
  <br/>
  <img  src="https://github-readme-streak-stats.herokuapp.com/?user=samirsadek&" alt="samirsadek" />
</div>

<br/><br/>

<hr/>

<h2 align="center">💻 Projects 💻</h2>
<br/>


## SURVO (Online Survey Website)

* **Role-Based Access Control:** User roles (user, surveyor, admin, pro-user) with distinct permissions.Admin control over user roles, including elevating roles to admin/surveyor.

* **Survey Management:** Creation and update of surveys with various question types from the Surveyor Dashboard.Surveys with titles, descriptions, options, like/dislike counters, and categories.

* **User Engagement:** Participation in surveys limited to logged-in users.Like/dislike functionality for surveys.Report functionality for inappropriate survey content

* **Feedback Handling:** Surveyors can view feedback for individual surveys given by users 

* **Security and Authentication::** User authentication via email/password and social media.JWT token generation and storage for secure authentication.
* **Used Technology:**  <div align="center">
    <img src="https://skillicons.dev/icons?i=react,html,css,vscode,github,tailwind,git" /><br>
    <img src="https://skillicons.dev/icons?i=nodejs,javascript,express,firebase,mongodb,jwt" /><br>
</div>
<br/>

## JOBCONNECT (Online Marketplace Website)
* **Navigation and Layout:** Consistent Navbar and Footer on all pages, excluding the 404 page.Meaningful footer with website logo, copyright notice, contact information, social media links, and address.

* **Registration and Login:** Login Page with email and password login options.Google Sign-in functionality for user convenience. Link to the Registration Page for new users.Registration Page includes fields for name, email, password, and photo URL.

* **Home Page:** Banner section featuring a carousel with relevant images.Tab-based system for browsing jobs with categories like web development, digital marketing, and graphic design.Each tab displays job cards with information: job title, deadline, price range, short description, and a "Bid now" button.Job data is fetched from a MongoDB database, and users can add job data via the Add Job page.

* **Add Product Page:** A private/protected route where users can add a new product to the database.The form includes fields for image, name, brand name, type, price, short description, rating, and an "Add" button.

* **Job Details Page:** Users are redirected to this page after clicking the "Bid now" button on a job card.Displays job information, including name, deadline, price range, and description.A "Place your bid" form allows users to enter their bidding amount and deadline.User's email (read-only) and job owner's email (read-only) are displayed.The "Bid on the project" button is disabled for the job owner.Data is stored in a MongoDB database when the button is clicked, and a toast notification is shown to the user.Users are then redirected to the My Bids page.


* **Add Jobs:** Users can post job listings on the Add Jobs page.The form includes fields for the employer's email (read-only), job title, deadline, description, category (selectable from available categories), minimum price, maximum price, and an "Add job" button.Data is stored in a MongoDB database when the button is clicked, and a toast notification is displayed.Users are redirected to the My Posted Jobs page.

* **My Posted Jobs Page:** Logged-in users can view their posted jobs on the My Posted Jobs page.Each job card allows users to update or delete the job listing.Updating allows users to modify job details, and a toast notification is displayed upon completion.Deletion requests are confirmed to avoid accidental removal.Users can only update and delete their own job listings.

* **My Bids:** The My Bids page displays bid information that users have added from job details pages.Information includes job title, email, deadline, status, and a "Complete" button (conditionally enabled).Initially, the status is set to "Pending." If a bid is accepted, the status becomes "In Progress," enabling the "Complete" button.Clicking the "Complete" button updates the status to "Complete."

* **Bid Requests:** Job owners can manage bid requests made by users on their posted jobs.The Bid Requests page displays job title, bidder's email, deadline, price, and status.Job owners can accept or reject bid requests.After clicking the "Reject" button, the status changes to "Rejected," and the buttons disappear.A progress bar is displayed for jobs in progress, with optional dynamic updating.
* **Used Technology:**  <div align="center">
    <img src="https://skillicons.dev/icons?i=react,html,css,vscode,github,tailwind,git" /><br>
    <img src="https://skillicons.dev/icons?i=nodejs,javascript,express,firebase,mongodb,jwt" /><br>
</div>
<br/>


  






