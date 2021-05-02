# Assignment 05: Low-Fidelity Prototype

Joyce Ma <br/>
DH110: User Experience Design 

## Project Description

My project focuses on developing a platform that allows senior citizens to find senior caregivers easily and efficiently. Because many of the current options are outdated, cluttered, confusing, or not specific enough, I aim to combat all these issues when developing my prototype. The type of user persona I imagine will be using my website/app can be characterized as elderly people who can no longer take care of themselves, who are not super proficient with technology, and who want to look for caregivers themselves instead of asking a friend or family for help. The website/app I aim to build will be helpful and easy for seniors to use themselves. 

The purpose of the low fidelity prototype is to create a general layout of how my platform will look and function. By mapping out the general flow of the screens, I will be able to gain a better understanding of how everything will look in the end and where the problem areas are. By testing the low fidelity prototype, I can see which features are actually functionable and useful and which are confusing and unnecessary. The test will allow me to see my product through the eyes of the user to gain important insight which can be applied to improve user experience.


## Tasks
The low-fidelity prototype supports the following tasks:
1. Input search field
2. Select an inbound flight
3. Select an outbound flight
4. Select a hotel
5. Pay for and book the trip 

## Wireframes and Wireflow
![Wireflow Stage 1](https://user-images.githubusercontent.com/59623155/74673232-b0520980-5163-11ea-8b9e-a3696b4758b9.jpg)

*Flow Description:* The flow intends for the user to search for their bundle trip based on their departure and arrival city or airport, dates of travel, number of travelers, and travel budget (optional). Based on the hotel results, a user can sort or filter the list by hotel name, star rating, and amenities. After clicking on a hotel, a user can view and sort ratings based on their search query and trip purpose. After selecting the room, a user will select an inbound and outbound flight to and from their travel destination. Again, based on their search results, a user has the option to sort or filter flights by duration, stops, time, and airline. After selecting both flights, the user will be directed to a trip summary of their hotel and flight selections. The user has the option to change their selections. If they are satisfied with their selections, the user can proceed to pay for their flight. They will input their passenger and payment details and have the option to insure their trip. Clicking on "Complete Booking" signifies the completion of the travel booking process.  

*Features Description:* The price tool feature takes the user's input from their **travel budget**. If the user clicks on the **Price Tool** button, they will be directed to a new page where they have the option to change their search field to view more cost-efficient price options. For example, changing their departure airport to BUR from LAX. Cheaper flights will help lower the overall cost per person. The minimized flight booking process is reflected in a combined flight view. A user is able to select their inbound and outbound flight on the same screen, minimizing scrolling time and directing the user straight to booking. Flights are displayed by **Recommended** as default. The most important flight details are displayed, such as time, airline, flight duration, and price. If the user would like to see more flight details on the airline's website, they can click "See More". The recommendation tool feature is reflected in the hotel search results, displaying the highest recommended hotels on the top of the page. When viewing hotel reviews, the main points of the hotel's average rating are displayed at the top of the screen, such as **Cleanliness, Service, Comfort, Condition, and Location**. If the user clicks **Sort**, they have the option to customize the reviews based on the time of year, traveler type, and keyword in addition to rating and date. 

## Prototype Testing 

![Wireflow S1 P1](https://user-images.githubusercontent.com/59623155/74702540-29327f00-51bf-11ea-97c7-07e66789cc32.jpg)
![Wireflow S1 P2](https://user-images.githubusercontent.com/59623155/74702685-8e867000-51bf-11ea-84c7-2f76a3ae774e.jpg)

### Iteration #1

![Wireflow S2 P1](https://user-images.githubusercontent.com/59623155/74702985-a4e0fb80-51c0-11ea-9c99-d1fab76efa22.jpg)
![Wireflow S2 P2](https://user-images.githubusercontent.com/59623155/74702992-a9a5af80-51c0-11ea-82de-e6b52c140240.jpg)

*Confusions and/or unexpected interactions:* 
The user surprisingly overlooked the dropdown menu frame when mentally going through the search input for flight departure and arrival airport. This makes sense due to the nature of the paper prototype where the airport is already inputted. The user was aware of the city and airport code. This would be interesting to see how helpful the dropdown menu would be for a user who is unaware of their travel destination and surrounding airports. More specifically, which airport do they need to fly into if necessary.

The user was confused about the frame where you can further sort through reviews. Because they did not need to sort further through reviews, there was no need to utilize the tool and feature. When asked what they thought the objective of the process was, they correctly assumed that the feature would help narrow down previous reviews of the hotel. In order to properly test these features, I asked the user to complete the iteration of the wireflow again with the intention of utilizing these features given what they are *supposed to do*. 

### Iteration #2

![Wireflow S3 P1](https://user-images.githubusercontent.com/59623155/74703005-b88c6200-51c0-11ea-99d6-485576559db6.jpg)
![Wireflow S3 P2](https://user-images.githubusercontent.com/59623155/74703008-baeebc00-51c0-11ea-96e8-d882540370ef.jpg)

*Confusions and/or unexpected interactions:* 
The user again did not follow the flow to the dropdown menu when inputting the departure and arrival airport. The user was correctly able to navigate the price tool to the page and interpreted that if they changed their departure airport from LAX to BUR, they could lower the price of their trip. Despite this understanding, the user decided to ignore the suggestion and go back to the original results. 

When following the recommendation tool, the user was hesitant to filter and sort by ratings. The feature was intended for the user to select specific ratings, for example, only ratings with a 4/5 and 5/5 rating. With this understanding, the user decided not to sort by rating because she wanted to look at all ratings, regardless of how they scored the hotel. After testing, the user asked me if this was the correct interpretation. Additionally, after pressing **Done**, the user expected to return to the list of reviews. The flow instead returned to the information about the hotel. This was an error on my part in how I designed the flow.  

## Reflection 
I believe the prototype testing went relatively smoothly; the user was successfully able to utilize all intended features despite a few minor setbacks. I did not account for the possibility that a user will not need to utilize the price tool and recommendation tool on every interaction. We conducted another walkthrough of the tasks to test these features which were easy and simple for the tester to use given the change in prototype state and system's intended response. I was surprised that the layout and organization of my wireframes were intuitive enough for a first-time user. I believe how often a user travels and uses such websites and/or apps does have a little influence on how well they can understand specific terms, such as inbound and outbound. My user travels a couple of times a year, both domestically and internationally, and readily uses Expedia as her main travel booking site. I decided to follow Expedia's layout and aesthetics when creating my wireframes.

The tester was confused that the review sort and filter returned to the hotel page when she pressed **Done**. I plan to correct my error and direct the flow back to the list of sorted reviews. The tester was hesitant and unsure whether they had to select a specific rating to sort through the results. I believe this can be solved through design and color when creating my digital prototype. I plan to make these options checkable through checkboxes which are optional in most design aesthetics. In addition to these changes, while this was not mentioned during user testing, I would draw out the flow for the **See More** button under flights. I believe it would be easier and more efficient for the user to view these details, if necessary, without leaving the app. I also believe it would be convenient for the user to have the **Reset** button on the hotel and flight *Sort* features. 
