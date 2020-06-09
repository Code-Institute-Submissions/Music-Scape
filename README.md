# Stamford Music Shop

This website is to help improve on an already existing website for a shop that is local where I live. For the sake of copyright names have been changed and text reworded. 
The purpose of this is to help advertise the business more effectively with improved visuals, better organisation of information and finally a simpler less cramped interface for
users to navigate the site. 

The reason I feel it is necessary to make this project is the original site is strangely broken with uneven negative space between containers, along with uneven positoned images. 
These are a few of the issues I found and wish to improve upon. My overall aim is to design and make a website with the idea of better itself financely and socially. 
Giving it a platform to better communicate with their consumers where they have full control. As well as a pleasant environment for customers to visit and wish to return to.

## UX

To achieve greater user experience I have improved on the coloration of the site opting for burgundy and ivory theme. This is not only to be gone with the original coloration of black, 
white and yellow; which did not blend well and help to separate the content in a way that doesn't flow with the page; it was chosen to give the feel of a classical instrument and a piece
of sheet music. This is to link the design to the product. 

The navigation section of every page's core concept was designed to stick out from the rest of the page being easy to find and understand. When a user hover's the cursor over one of the buttons
it fades into a lighter for two reasons. The first being to let the user know which button they are on, giving the user feedback on their actions. Making the website responsive to their actions. 
The second being the maroon used is very dark so to help the fade stand out against the background it becomes lighter to make it easier to see. This also brightens up the page making it more 
appealing.

On the orginial web page it has a carousel displaying off centred images without context. To improve on this aspect I used images covering the envire width of the slide this helps to show off
various products the business sells in a cinematic way drawing the eye of the consumer. This is ideal as the slides show information on how the business operates. Displaying it an appealing 
way catching the attention of the user.

At the bottom of index.html is an embedded view of the business as of Google Maps, this allows users to see almost first hand how the business looks and types of products that they sell. 
It is also good for locating the business in person. This is something the original site seemed very dedicated to as it also used an embedded Google Maps view point in a well appealing way, 
as well as with address used widely across pages, being included in header and footers along with giving physical directions to the business. I feel this information presented in this way 
is not the ideal way of this doing this. As those who are not local would not understead the directions or need them in somecases, and those that are local would be aware of business considering 
its location to other well known businesses. This is way I opted to go for a large map that users can use to look around the area to understand where it is along with zooming out to gather 
directions.

For the information provided on rental.html I didn't want to present it a mundane way where it was just text on a page separated by headings. Because of this the page includes alternating 
visuals and informations on either side. This is to keep the user interested in the website, enjoying their experience. The images used are of bands, concerts and an orchestra the reason 
for this is the business sells all the instruments involved in all three of these instances. This helps users to relate to the content. Whether they wish to be a pop star or a classical performer.
When the screen size is of the size of small tablet or phone the alternation stops and instead goes down in rows presenting the information above the images to keep the core concept the page was
given. 

Contact.html is very plain and simple being given a tranparent background with the input fields for the user's email an the message they wish to send. To make it more appealing for the user 
a colourful background was added to help brighten up the page as well as break away from the usual colours of the website. The purpose of the transparent background on the contact form itself 
is to allow the colour to shine through and help the two separate pieces appear as one. 

### User Stories

1. Customer, I want to use the website to find a guitar that I wish to purchase. Loading up the webpage there is no clear tab for buying instruments. I scroll down on the "home" page 
and click on the "latest products" to find they do not lead anyway. I was unable to buy a product on this website.

From this I can see that customers have no clear way of purchases items using the website. To combat this issue I will add links to the "latest products" section allowing the customer to 
see the product's information and buy it.

2. 

## Testing 

1. View Product:
    1. Go to "Home" page
    2. Scroll down to "latest products" to verify the images have displayed properly
    3. Images have appear in a row with the same styling (success)
    4. Appears carousel images have not display properly for an iOS device

The latest products appeared correctly but the user found another issue during testing that on an iOS (phone) device the carousel final image violin.jpg did display on that device. 
This lead to further testing.

2. Carousel Image Display on different platforms:
    1. Load website again on iOS phone device to ensure the problem persisted. 
    2. It does. Load website on iOS tablet device to see if the problem is an isolated issue or persisted throughout iOS devices
    3. It does. Load website on PC and test sizing of web page to ensure that isn't the reason why the bug was present.
    4. This wasn't the case. Load website on an Android to see if the problem was a phone or tablet issue.
    5. The problem wasn't present within an Android device. So it was decided this was an incompatibility with iOS devices in general.
    6. Went through code to see if the file type was the source of the issue. All the images were jpegs.
    7. To solve the issue a similar picture was chosen and tested in the same way to ensure the problem was no longer present.

This was quite an unsual bug as it only persisted on iOS devices, and all of the file type were the same. However, it was an easy fix and the carousel now works on all platforms.

