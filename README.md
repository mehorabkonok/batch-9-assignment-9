*** Main requirements: *** 
1. Include a minimum of 10 notable Github commits. (2 done)
2. Add a meaningfull readme.md file (done)
3. Add a name and live site URL (pending)
4. Include a minimum of five bullet points features and characteristics of your     website (pending)
5. Add the npm package name which you have used for the challenges task (pending)
6. Make the site responsible for mobile, tablet, laptop , desctop view.
7. Use environment variable for firebase configuration (pending)
8. Make sure your design is unique can take idea from theme forest but the design should not be simillar to any of then nor previous assignment's design (pending)
9. The name of the website will show in the title (pending)
10. The homepage should have these sections: 
    i.   Navbar, (pending)
    ii.  Slider, (pending)
    iii. Estates, (pending)
    iv.  Footer , (pending)
    v.   two extra sections. (pending)

11. Navbar: The homepage will have a navbar and implement active routes on the Navbar. The Navbar will contain;
    i.  Website name (pend)
    ii. Home (pend)
    iii.Update Profile (challange requirements-3) (pend)
    iv. User Profile (pend)

** But the user profile is conditional, If a user is logged in, the user
   image will show on the Navbar and When you hover over the user
   image it will show the user name. (pending)
** If the user is not logged in it will show a login button. (pend)
** So if a user is logged in you will show the user image and a logout
   button. If you click on the logout button make sure you have logged
   out. (pend)

12. Login: When you click the login button on the navbar it redirects to
    the login page. You have to use a password and email-based
    authentication to Login. (pend)
    The login page will have- (all pending)
    i.  Email
    ii. Password
    iii.Google login
    iv. Github login
    v.  A link that will redirect to the registration page

**  If there's error, show it using toast or sweet alert. (pend)

13. Register Page: You have to use a password and email-based
    authentication to register.(pend)
    The Register page will have the following - (all pend)
    i.   Name
    ii.  Email
    iii. PhotoURL
    iv.  password
    v.   Link for login redirection 

**  For password varification you need to follow this-
    i.  Must have an Uppercase letter in the password (pend)
    ii. Must have a Lowercase letter in the password (pend)
    iii.Length must be atleast 6 character (pend)

**  If any of this isn't fulfilled it will show an error/toast. (pend)
**  After successful login or Register you need to show toast/sweet alert. (pend)

14. Banner: Add a slider (Daisy UI slider or Swiper slider) with a minimum of 3 slides.
15. Footer: A Footer with all relevant information and eye-catching design.

**  Make sure the Navbar and Footer are showing on all pages
16. Estate Section: 
    In the Estates section you will choose a category for
    example: “Residential” and for this category you need to create a JSON
    minimum of 4 and a maximum of 9 data. Each estate card will contain -
    ○ a relevant Image,
    ○ estate_title,
    ○ id,
    ○ segment_name
    ○ description,
    ○ price,
    ○ Status => It can be “sale”, “rent”○ Area => for example- 2000 sq ft
    ○ location
    ○ facilities => in an array => [ “living room”, “swimming pool”,
    “Kitchen”]
    ○ and a “View Property” button.
    ○ You can add other information for each data if you want.

17. Estate Details: When the user clicks the “View Property” button it takes
    the user to the Estate Details page. This page will be a protected route
    and ensure that the private route moves to the login page if the user is
    not logged in.
        ○ Banner: you need to show detailed information about the selected
          estate.

**  The user shouldn't be redirected to the login page after you reload a page     
    of the private route.

18. 404 page: Create a 404 page/ not found page.
19. Extra route: Add 1 more extra route to your website. This route should be
    private/protected and the contents for that route should be meaningful
    and relevant.
20. Dynamic Title: You need to implement a dynamic title for each page.
21. Once a user is logged in, user information will show on the navbar even if
    he/she reloads the website, this info will not disappear. You can show a
    loader when the logged-in user info is in a loading state. You can
    implement this using the onAuthStateChanged method of Firebase.


# Challenges Requirements:
1.  Implement show and hide passwords on the registration page. By default
    it won’t show the password when you click on the “Eye” icon it will show
    the password. In this way, you need to toggle.
2.  Implement any of 3 packages from the following list:
    a. AOS Package,
    b. Animate.css,
    c. React-leaflet,
    d. React Hook form,
    e. Swiper slider
3.  Create a protected route where, after logging in, users can see their
    information like- name, email, photoURL displayed in a form. They can edit
    name and photoURL and save the changes. This "saving" process uses
    Firebase's updateProfile() method to update the user's information stored
    securely in Firebase.

*** Additional Information: ***
    ● Create your JSON data and host the image on imgbb
    ● Deploy your website on Firebase.

*** You need To Submit: ***
    ● Your GitHub repository
    ● Your Live site link

Name of the site: 
Live link of the site:

*** Details about the application has been mentioned here.
1. This react application has been installed using VITE and npm.
2. Tailwindcss has been used as css framework.
3. DaisyUI has been used as component library.
4. React router has been used here.
5. PropTypes has been installed here.
6. react-icons has been used here. 