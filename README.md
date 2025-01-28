# Table-Top-RPG-Price-Charting-Site
	I am developing a Web App that will keep track of Table Top RPG book price charting.
## Introduction
	In this paper I am going to detail how I am going to be creating an RPG Encyclopedia where users can enter the information about a specific Table Top RPG book and the current price based on online listings. I want this to also be a way for users to keep track of the books they own. It will consist of a public list that users can access not signed in, a signed in view of the list where users can add entries and, see their current list of games they own, and a database that contains this information. It will be a web app with a client portal and an API that connects the client to a database. 
## Client portal
	I am going to code the client portal in HTML5, CSS, and Bootstrap. This will be the main portal where individuals can access the list on the web. It will have a login section that allow users to login to the portal, and it will have the individual components such as uploading information to the database. This is how I will create a basic HTML5 form for the login process https://www.w3schools.com/howto/howto_css_login_form.asp. And then I would like to add something similar to this: https://dzone.com/articles/ceate-a-login-system-using-html-php-and-mysql. 
## API Development
	I believe I will try to keep the API development simple and develop my API in PHP using a simple REST API. An example is this: https://developer.okta.com/blog/2019/03/08/simple-rest-api-php. I want it to be the simplest transfer of information possible while also being secure and beneficial to the project as a whole. “EST APIs are the backbone of modern web development. Most web applications these days are developed as single-page applications on the frontend, connected to backend APIs written in various languages.” (Hristozov, 2019).
## Database Development
	I want to be familiar with the database I use to keep this simple and yet effective. So far there are two that I think would work well for my project. I will use either mondoDB or I will use mySQL. I am leaning more toward mySQL but it might take more effort to set up. Yet, mySQL is versatile and free to set up. MySQL is located here: https://www.mysql.com/. MondoDB is located here: https://www.mongodb.com/lp/cloud/atlas/try4-reg?utm_source=google&utm_campaign=search_gs_pl_evergreen_mongodb_core-high-int_prosp-brand_gic-null_amers-us_ps-all_desktop_eng_lead&utm_term=mongodb&utm_medium=cpc_paid_search&utm_ad=e&utm_ad_campaign_id=22124314743&adgroup=173195490443&cq_cmp=22124314743&gad_source=1&gclid=EAIaIQobChMIzIq_n5KHiwMV81N_AB28hCq-EAAYASAAEgJO7PD_BwE. 
## Hosting
	I am looking at several options to host my site. I may use the free space I can get through Santa Fe College if they allow me to upload a database, but I could also host my site and API on Santa Fe, and then use a free Database offsite to store my information. At this time, I do believe that will be possible. MondoDB has a free version so that might be the best option for me to go to, although Amazon Web Services and Microsoft Azure also has some options that I am going to be looking into. The most important part is getting the code to function, and then having plenty of time to test the live implementation both during the development and when it comes time for deployment. 
## Types of Application
	My entire model for this application will be https://www.pricecharting.com/category/video-games. My application is unique because it will allow people to specifically track their Pen and Paper games and the current prices on the site. They should also be able to create their own lists, and add them to their personal account as I have detailed before. I do believe there is a market for this as Pen and Paper RPGs are becoming more popular, with collectors’ editions becoming more common now. While there are ample places to find this information for comics and cards, I just do not see a great deal of emphasis placed on TTRPGs.  

## My Process
	It is my desire in this project to first develop the HTML5 client and then add the API and Database as I go along. It is possible the API and Database will be developed together for testing purposes and for coherency. The easiest solution code wise would be a mySQL implementation, as PHP, HTML, and mySQL are very compatible. The more complex implementation would be the mondoDB implementation, but may be more beneficial where I choose to host the web app. Here is a list of some free options https://dev.to/pulkitsingh/free-database-hosting-for-your-next-project-2cbd. Again, if Santa Fe lets me host the database on my personal account that would be ideal, but I must do some research to see if that is possible.
## Types of Data
	I will be collecting username, password, email, and input information such as specific TTRPGs and their prices. PID will be private, specific lists will be private, but the total list will be public. 
## Security
	For this project, I will be implementing the best security practices I am able, but if I deploy this on a permanent basis, I may have a security expert look over my site to make sure the data integrity is safe. 
## Conclusion
	I believe that this is a project I can complete within the time frame of the semester. I do not believe it is overreaching in any way. It will also be beneficial not only for my personal portfolio, but I also believe it will benefit not only myself, but others. Once I have completed the app, after the semester, I am strongly considering buying my own website space and hosting it on a continual basis allowing it to grow. 
![Preview](https://github.com/wavesymphony/Table-Top-RPG-Price-Charting-Site/blob/Images/architecturediagram.drawio.png?raw=true)</p>	
![Preview](https://github.com/wavesymphony/Table-Top-RPG-Price-Charting-Site/blob/Images/TTRPGPriceChartWireFrame.drawio-2.png?raw=true)
![Preview](https://github.com/wavesymphony/Table-Top-RPG-Price-Charting-Site/blob/Images/Database%20PHP.drawio-2.png?raw=true)
## User Stories
	As a user
	I want/need to document my collection
	So that I can keep track of my items
 	As a user
	I want/need to price my items
	So that so that I can keep track of my collections value
	As a user
	I want/need to track items I don't own
	So that I know what items to add to my collection
 	As a user
	I want/need to view others collections
	So that I know what people are buying/selling
 	As a user
  	I want/need to see what is being sold
   	So that I can sell my own items
## User Cases
	### Logging in
		User access to database/website
		Users of the site
	### Users will log into a log in portal
		The user is logged in
	### Personal User Portal
		The user
		The user will be greeted by a portal with all there personal items
		The user will manage and add/delete from their collection
 	### Database
		Main item database
		The user
		The user will browse the collection catalog
		The user will be able to browse, find, and add items from the main collection
 	### Add to catelog
		Add to the catalog
		The user
		The user seeks to add a product to the main catalog
		The item is added to the main catalog
 	### Browsing the catalog by type
		Price charting
		The user
		Organize by price/items/popular/new
		The user will be able to organize or sort the list by certain criteria
##Use Case Diagram
	![Preview](https://github.com/wavesymphony/Table-Top-RPG-Price-Charting-Site/blob/Images/UserCases.drawio.png?raw=true)
