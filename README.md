# Sendy Retail
In July of 2020, myself and my business partner embarked on our new venture – Sendy Retail. While this business started out by utilising arbitrage to make profit, we quickly spotted a gap in the market for our business to take advantage of. Wholesale on Amazon is a method whereby the seller sources products in bulk, usually from a distributor, and sells on listing where they can make a profit. The beauty of this method is its simplicity, once an account is secured, the seller simply has to piggyback on listings, **sharing** sales with other sellers. This method allows for **volume**, however provides **no real exit value** – A prospective buyer could simply ask to see the accounts held by the seller as part of due diligence, and then go and contact these distributors themselves.

Our method is different, and based off the beautiful prospect of exclusive deals. The majority of brands listings on Amazon were made years ago carelessly, with no updates since. We reach out to brands directly, we build **relationships** with these brands, we do the work needed on their listings, we **boost** their sales, and we give ourselves a chance at obtaining an exclusive deal – The crème de la crème – the exclusive rights to sell this brand on Amazon. This method may be less lucrative on the short term, however a single exclusive deal **creates exit value** for our business that cannot be matched by any number of distributors accounts. This website (which will soon be under www.sendyretail.com) is targeted towards these prospective brands, it gives an overview of our company while handling typical objections that we hear. This website gives us the opportunity to have brands come directly to us, rather than requiring us to find these brands ourselves. In the future, we hope this website will have a testimonials sections, as well as more interactive elements (Navbar, Potential Sales Increase Calculator) once I complete the JavaScript module with Code Institute. 


 ![Responsiveness Image](/readme-images/sendyresponsive.jpeg)

## Features
### Existing Features
#### Navigation Bar
* Our Navigation Bar remains consistent across all three pages. It features links to each page and removes the necessity for users to click the “back” button
* Our Logo is also responsive, with a wide desktop version and a shorter mobile version. Our standard logo is now displayed on our mobile site, with this new custom version recently being created for our desktop site. 

  ![Sendy Retail Logo Wide](/readme-images/navbarwide.jpeg)
  ![Sendy Retail Logo Short](/readme-images/navbarshort.jpeg)

#### Landing page
* The goal of our landing page is to capture the users attention, while giving a professional feel.
* The brands that we have historically worked with have performed well in retail stores, and are misrepresented on Amazon. Our catchphrase “Helping Great Brands Become Greater” encourages a positive UX from the offset.

 ![Main Landing Sendy](/readme-images/mainlanding.jpeg)
 
#### Who Are We Section
* This section gives a brief overview of our company, while also portraying the necessity for businesses to take control of their Amazon sales.
* The image used matches the colour scheme of the website, while encapsulating the meticulous work done by our preparation team. 
* This section is fully responsive, with display changing to vertical on smaller screen sizes.
 
 ![Who Are We Section](/readme-images/whoarewe-section.jpeg)

#### What Do We Do Section
* This section gives the user an insight in to the four stages of work we do. These four stages encapsulate all potential areas of demand from prospective future clients. We tackle pain points while also encouraging a positive emotional response from the user.
* This section is fully responsive, with display changing on medium screens and small screens.
 
 ![What Do We Do Section](/readme-images/whatwedo-section.jpeg)

#### Differences Section
* This section handles our most common objections when working with brands. We recognise the pain points brands typically have when working with Amazon sellers, while ensuring them that we work differently.
* This section is fully responsive, with the middle figure changing to “display:hidden;” on small screen sizes and the orientation of the elements switching to vertical.

 ![Differences Section](/readme-images/differences-section.jpeg)

#### Our Brands Section
* This section works on creating trust for our business, with a bold image and link to the “Our Brands” page. The image used fits in with the colours of our theme. 
* The “Our Brands” button changes background colour opacity when hovered over. 
* This section is fully responsive, with the orientation of elements switching to vertical on smaller screens sizes.

 ![Our Brands Section](/readme-images/ourbrands-section.jpeg)
 
#### Contact Us Section
* This section allows for prospective clients to redirect to our “Contact Us” page. 
* The “Contact Us” button changes background colour opacity when hovered over. 
* This section is fully responsive, with elements sized based off viewport width and orientation changing to horizontal on mobile. 

 ![Contact Us Section](/readme-images/contactus-section.jpeg)

#### Footer
* The Footer provide the user with further information on our business, as well as direct contact information.
* Font Awesome icons are used here to make this section visually appealing. 
* The Footer is consistent across all three pages. 
  ![Footer](/readme-images/footer.jpeg)

#### Our Brands Page
* This page serves as social proof for our business, showing the nine brands we currently work with. 
* Upon hovering a pointer appears, as well as an orange border, encouraging the user to click the images. Each image opens a link to the website of each brand. 
* The images are displayed in columns of three, two and one on different screen sizes.
 
 ![Our Brands Page](/readme-images/ourbrands-page.jpeg)

#### Contact Us Page
* This page provides the user with an interactive map of our warehouse, as well as a Contact Form.
* This page is fully interactive, giving the user the experience of interacting with our site. 
* The Contact Form has four fields; Name, Email, Subject and Message.
* Each text field has a placeholder and the subject field has a dropdown menu with options. Upon submitting, the form opens an email in a new tab. In the future this form will send an email without need for redirection. 
 
 ![Contact Us Page](/readme-images/contactus-page.jpeg)

### Features Left to Implement
•	Testimonials section: In the coming months, we hope to ask the brands we are working with for a small testimonial to be included on the home page. This will serve as social proof. 
•	Timeline section: Once we have a more confident understanding of the length of time needed to complete our services, we would love to include a timeline section. This would help to both manage expectations and form a social contract. 
•	Collapsing Navbar with bars icon: Attempting to do this with just HTML and CSS was heart breaking. My attempt to create a pseudo-interactive navbar in the form of a div with position (-100%) that appeared upon clicking a button (in the form of a nav icon) resulted in 8 hours of coding to no avail. I am genuinely excited to be able to alleviate this frustration and create this navbar using JavaScript. 

## Design Choices

#### Colour Scheme
•	Our Colour Scheme for the website was based off our initial logo colours. The colours are blue and orange terracotta. 
•	These colours were inspired by the chart below, which can be found here: https://www.fabmood.com/blue-and-orange-color-scheme/.
•	Our main colour for the website is blue, with all accents orange. 
 
#### Typography
•	I used the pairing of Oswald and Lato for this website, with Oswald being used for headings and Lato for the remainder of the website. 
•	I find this font combination to be sleek and professional, perfect for our B2B website.



## Testing
Sendy Retail was thoroughly tested in terms of validation, responsiveness and UX through the use of Lighthouse and Peer Reviews. I am satisfied with the results of this testing and believe that Sendy Retail is ready to be pushed to a live audience.

#### Validator Testing
•	HTML
* No errors were returned when passing through the official W3C validator
•	CSS
* No errors were found when passing through the official (Jigsaw) validator

#### Responsiveness Testing
•	The responsive design tests were carried out using Google Chrome DevTools and Responsive Design Checker.
•	Each page responds as expected on a variety of screen sizes, from 24” Desktop to iPhone 6.
•	Overall I am completely satisfied with the responsiveness of Sendy Retail.

#### Lighthouse
The site was also tested using Google Lighthouse in Chrome Developer Tools to test each of the pages for:
•	The site was tested for Performance , Accessibility, Best Practices and SEO. 
•	The site was tested on an incognito window to increase accuracy of these tests.
•	The sites images were compressed and updated in order to increase Performance scores.
•	Overall, after compression of media files, the website performs very well on both desktop and mobile.
 
#### Peer review (Social Testing)

Upon completion of this project, I sent the deployed link to my peers and business partner. My business partner advised that I make all headings uppercase and fix some sizing issues on the home page – these changes are reflected in the final deployed website. Overall the feedback was very positive on this front – I asked my peers to point out any issues, and none were found within the scope of this project.

#### Fixed Bugs

On small screen sizes, my navigation bar list order was incorrect. I attempted use column-reverse, translate, float-left, direction:rtl and many other methods to fix this, however none of these worked. I reached out to peers within the slack chat for this. Robert Kennedy was kind enough to come up with an idea to fix this, whereby I targeted the list item children individually and reversed their order with this method. I used a variation of this in my code in order to resolve the issue. I am thankful for this input, and armed with this knowledge I will be able to solve any similar future issues.
 

## Deployment
* The site was deployed to GitHub pages. The steps to deploy are as follows:
* In the GitHub repository, navigate to the Settings tab
* From the source section drop-down menu, select the Master Branch
* Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
The live link can be found here - https://jyan366.github.io/Sendy-Retail/our-brands.html

## Credits

#### Content
•	The font came from Google Fonts.
•	The map is embedded from Google Maps.
•	The colour palate was inspired by FabMood.
•	The icons came from Font Awesome.
•	The “What do we do” section was inspired by the club ethos section of Love Running, however the finished product is different. 
•	All brands mentioned are real clients of Sendy Retail.

#### Media
•	The photos used on this website were taken from Canva, as well as google images for brand logos. All brands mentioned are clients of Sendy Retail.
•	Our logo was designed on Fiverr, by a best seller named shailene_george. When I told him that I needed a wider variation of the logo made for the website he created this quickly and free of charge. 

