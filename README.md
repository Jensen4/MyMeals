# MyMeal
Team Name: we <3 CS
Domain: Social Media


Software Specification:
An app similar to BeReal, but instead of random notifications, users receive alerts at their set meal times (e.g., breakfast, lunch, dinner). The app prompts them to take a photo of their meal and share it, along with the location of the restaurant (if applicable) or details about their dish. Users can see what their friends are eating, explore nearby popular meal spots, and get inspired by each other’s meals. 
Key App Features


Customizable Meal Times:
Users can set their preferred meal times, and the app will send a notification to take a picture when it’s time to eat.
Photo Sharing:
Users take a picture of their meal and share it with friends. The photo can be tagged with the name of the dish and restaurant or marked as a home-cooked meal.
Restaurant and Dish Tagging:
Users can tag their meals with the restaurant name, location, or recipe details if it’s homemade, with the option to see the restaurant’s details, like address, menu, and reviews.
Meal Feed:
A social feed where users can browse meals posted by friends and discover what others are eating.
Explore Nearby Restaurants:
Users can explore popular meal spots near them, based on meals shared by others.
Core Features

User Authentication
Users can sign up, log in, and log out using Firebase Authentication.
Social logins (optional for future development).


Meal Time Notifications
Users can set customizable meal times for breakfast, lunch, and dinner.
Notifications prompt the user to take a meal photo.


Photo Capture & Upload
Use react-native-camera for capturing meal photos.
Upload photos to Firebase Storage.
Save photo URLs, meal details, and timestamps in Firebase Firestore.


Meal Feed
Display a feed of meal photos shared by friends.
Allow users to like and comment on posts.


Restaurant & Location Tagging
Use Google Maps API and Geolocation to tag and display the location of meals.
Fetch nearby restaurants for easy tagging.


Explore Nearby Meals
Discover popular meal spots shared by other users.
Integration with Yelp API for restaurant details and reviews.


Settings & Profile
Users can update meal times and manage their profile.
Options to turn notifications on or off.




Additional Implementations


Track the times you eat and get a weekly summary report of the average time you eat your first and last meal of the day.

Provide feedback and insights:
Implement Logic to Analyze Patterns:
If a user consistently eats late at night, suggest earlier dinner times.
If meal times are irregular, suggest times they should be eating at.
Examples of Insights:
“You’re having dinner on average at 9:30 PM, which may disrupt your sleep. Consider having dinner earlier between 6:00 PM and 8:00 PM.”
“You missed breakfast 3 times this week. Regular breakfasts can boost your energy levels throughout the day.”

Tools

Frontend: React Native, JavaScript
User Interface: Figma
Backend: Firebase (Authentication, Firestore, Storage, Cloud Messaging)
APIs:
Google Maps API: For location services
Yelp API: For restaurant data and reviews


App Flow

User Onboarding: Users sign up and set their meal times.
Meal Notifications: Notifications go off at meal times, prompting the user to take a photo of their meal.
Photo Capture & Upload: Users take a photo and can tag the meal with a name, description, and location (or mark it as homemade, toggle button).
Viewing & Interacting: Users can browse a feed of meal posts, like or comment on friends’ meals, and view details of tagged restaurants.
Explore Restaurants: Users can explore meal spots shared by others and get recommendations for nearby restaurants.
