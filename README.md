<h1  align="center">
<a  href=""  target="_blank"><img  src="*/Landingpage/Homepage colour.png"  alt="Trend setter"/></a>

</h1>

Trend Setter

  

This project is for fullstack web development milestone4 for code institute.

<br>
</div>

  

## Table of Contents

1.  [**UX**](#ux)
-  [**Project Goals**](#project-goals)
-  [**User goals**](#user-goals)
-  [**User Stories**](#user-stories)
-  [**Design**](#design)
-  [**Wireframes**](#wireframes)

  
2.  [**Features**](#features)
-  [**Existing Features**](#existing-features)
-  [**Features Left to Implement**](#features-left-to-implement)

3.  [**Technologies used**](#technologies-used)
4.  [**Testing**](#testing)
5.  [**Deployment**](#deployment)
6.  [**Acknowledgements**](#acknowledgements)
7.  [**Disclaimer**](#disclaimer)

  
## UX

  

### Project Goals

  
The goal of this project was to creat a fully functional e-commerce website that would allow the user to 
create and account put items in a virtual shopping bag and checkout while being secure and simple to use.
  

#### User goals
User goals in brief are as follows:

 1. To be able to create and verify an account
2. To browse a store front to see whats for offer
   3. To be able to choose what specificaly i am searching for
   4. To be able to put multiple items in the shopping bag
   5. To be able to remove items from the shopping background
   6. To be able to log in and out once an account has been created 
   7. To save my shopping bag for the next session 
    

  

#### User Stories

1. Can i see how much the items in my shopping bag total as i add more to it 
2. I want to be able to see details on all of the products that i am looking at
3. I want to be able to easily make an account 
4. i want to be able to search for specific items on the store
5. i want to be able to search for key words
6. I want mu payments to be secure
7. I want to know that my account has been verified 
8. I want to know when the verification email has been sent 
9. I would like to be able to log in easily when details are correct.
10. I want the ability to adjust quantity of the items in my shopping bag
11. I want the abilty to view my profile and i should be able to view any reviews associated to my account.
12. There should be options to register and login on the site navigation,
13. If im logged in i should see navigation options to log out

  

### Design

  
**Fonts**

I decided to use the 'Ubuntu' font from google("https://fonts.googleapis.com/css?family=Ubuntu") It has a nice and easy look that makes it stand out and is not sharp and jarring


**Colours**

I went with a simple black and white colour for all the main elements so that they wont stand out and detract attention away from the shopping items
the main home page image has a nice calming blue background

**Topography**

The site uses bootstrap 4 be responsive across devices, also media queries were used to change how the intro text appears across different devices to provide a smooth user experience.

### Wireframes

WireFrames were created using Figma at recomendation of my tutor. https://www.figma.com/  
they can be found here [desktop](documentation/WireFrames) 



  

## Features

### Existing Features

1. Users can view all the items at the same time 
2. Users can search for specific keywords
3. Users can look at the current deals 
4. Users can add and remove items from the shoping bags
5. Users can register an account 
6. Users can log in and log out with only a few button clicks 
7. Users can securly make purchases using stripe 
8. Users can select the quantity of the items they want 
9. Users can see the cost of the total items in the shopping bag from anywhere

### Future Features to Implement

Future versions of the project may have the following:

1. Ability to reset an account password.
2. Add a review system where users can input reviews 
3. Ability for user to view in their profile their past purchases 




 

## Dataset

The dataset used was the one supplied by code institute in the boutique ado project as it is a robust and ready made 
collection of items.


## Technologies Used

  

This project uses Python, Stripe, Amazon Web services(S3), HTML, CSS, JavaScript technologies and Heroku for deployment.

  

-  [Python](https://www.python.org/)
The project uses **Python 3** to create the app, create the routes, create the functions within those routes and handles all back end interactions.

-  [Stripe]https://stripe.com/en-gb)
The project uses **Stripe** to make sure that transactions and emails are handled securely .

-  [Amazon Web Services](https://aws.amazon.com/free/?trk=ps_a134p000003yHmZAAU&trkCampaign=acq_paid_search_brand&sc_channel=PS&sc_campaign=acquisition_EEM&sc_publisher=Google&sc_category=Core-Main&sc_country=EEM&sc_geo=EMEA&sc_outcome=acq&sc_detail=amazon%20web%20services&sc_content=Brand_amazon_web_services_e&sc_segment=444219541646&sc_medium=ACQ-P|PS-GO|Brand|Desktop|SU|Core-Main|Core|EEM|EN|Text&s_kwcid=AL!4422!3!444219541646!e!!g!!amazon%20web%20services&ef_id=Cj0KCQjw1a6EBhC0ARIsAOiTkrHwarLnI5MYeI6c_pvCNubkmKtFoD3tRYQJkCjjgy5ll5Vbh6RCVF8aAhcGEALw_wcB:G:s&s_kwcid=AL!4422!3!444219541646!e!!g!!amazon%20web%20services&all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all)
The project uses **Amazon Web Services** to store all of the collections.


-  [Bootstrap 4](https://getbootstrap.com/)
The project uses **Bootstrap** to simplify the structure of the website and make the website responsive easily.

-  **HTML 5 and CSS3**
The project uses **HTML5 and CSS3** for website structure and design.

-  [Google Fonts](https://fonts.google.com/)
The project used the **Google fonts** across the site

-  [GitHub](https://github.com/)
This project uses **GitHub** to remotely store the source code in a repository. The project can be cloned or downloaded from here. See [Deployment](#deployment) section

-  [StackEdit](https://stackedit.io)
This project uses **StackEdit** to build the markdown for this readme file

 
  
  

## Testing

  

Testing was done incrementaly and influnced the end result of the project.

  
As each individual app was created it was also tested to make sure that it works as was intended while also checking with the boutique ado 
lessions to make sure that i was doing the correct things


i tested the python code with https://extendsclass.com/python-tester.html and came back with no syntax errors 
CCS was tested with https://jigsaw.w3.org/css-validator/ there where 2 warnings but i have chosen to ignore these as they cause no problems
the html validator https://validator.w3.org/ showed up multiple errors as the techincque to create templates was casuing flags these where ignored.

  

When the project was fully completed i went through the below testing scenarios to further test the project to make sure that it reached my goal.


  

| Test | Expected |Passed |
| :------------- |:-------------| :-----:|
| User loads the landing page of site | Page displays without error  | &#9745; |
| User can click on shop now | Shop now opens to all of the products   | &#9745; |
| User can use the searchbar | The searchbar works and can be used to check for keywords and specific items | &#9745; |
| User can create an account | The user can register an account | &#9745; |
| User can logout| the user can log out in a few steps  | &#9745; |
| User can add to the shopping bag | the user can add to the shoping bag and the price shows an increase  | &#9745; |
| User can make secure payments| Using stripe the user can make secure payments |&#9745; |
| User gets a verification email| verification email is sent (tested using temp mail)| &#9745; |




## Deployment

I personally used vscode on my local machine to develop the site using Python 3.7.3  and deployed to Heroku via Github.

1. To download or clone the site to your local machine you will need to go to (https://github.com/OriHillairetdev/Milestone-project-3) see steps in https://help.github.com/en/articles/cloning-a-repository .
2. Before you download or clone the site you will need to ensure you have [Python 3.7](https://www.python.org/downloads/) installed. 
3. Once you have Python installed, created a virtual environment as appropriate to you chosen IDE and os.
4. Run the requirements.txt file as appropriate to your IDE to install the relevant required packages dependencies for the project into your virtual environment.
5. Run the app.py file as appropriate to your chosen environment and os.
6. You should now be able to view the site on your localhost on port 5000.

### Acknowledgements

A lot of threads on Stackoverflow whos links are gone now helping me with code snipits and multiple guides on how to do certain vhunks of code
Thanks to the people on slack for always posting usefull information
thanks to the Codeinstitute templates
and Thanks to my Mentor Precious Ljege for teaching me some tricks of the trade
  

#### Disclaimer

The content of this website is educational purposes only  