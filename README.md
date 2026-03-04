# OPSCPART1--Research

RESEARCH, PLANNING AND 
DESIGN 

OPSC6312 
DORCAS MUPATAIE ST10285710 
GOMOLEMO MOTSEBE ST10356945 
JENNIVIEVE OBIANUJU UDODI ST10398118 

 
 
Introduction 
 
In today’s busy society, people often have difficulties when it comes to trying to figure 
out what to cook using the ingredients they have at home. PantryPal is designed to solve 
this problem by helping the user discover recipes based on what is in their fridge or 
pantry. It does so by combining features such as ingredient input, recipe suggestions, 
smart shopping lists, and meal planning, the aim of the app is to make cooking easier, 
more efficient, and personal to the user. 
This report will be researching three similar Android apps: CookBook, SuperCook, and 
KitchenPal, to analyse their features, strengths, weaknesses, and  the likely 
implementation methods, including RESTful API usage and backend integration. The 
best features to add to PantryPal are highlighted by a comparison of these apps, 
guaranteeing a productive, customised, and easy-to-use experience. 
After the individual app analyses, a comparative evaluation infographic will highlight  
the main similarities and differences between the apps. Finally, the report ends with a 
summary of what was learnt from this research and an explanation of how these results 
will affect the design, development, and use of PantryPal. 
 
Research  
1.Cookbook 
Overview 
Cookbook is an Android app designed to help users explore, organize, and create 
recipes easily. Users can upload their own recipes, complete with ingredients, 
directions, and images, or browse a sizable database of existing recipes. The app offers 
features like meal planning, favourites, and shopping lists, making it easier for users to 
manage cooking at home. Cookbook also allows users to filter recipes by their dietary 
preferences, cuisine preference, or preparation time. Its user-friendly interface makes it 
suitable for both beginner and experienced cooks, offering the user an organized way to 
store and access recipes. 
Strengths 
• It has a large recipe database and ability to add personal recipes 
• It allows for meal planning and scheduling features 
• It has a shopping list generation feature for missing ingredients 
• Ability to save favourite recipes and organize them for quick access 
• Allows for dietary and cuisine filters 


Weaknesses 
• Some advanced features may require an account or subscription 
• The integration with external grocery delivery services is limited 
• Offline functionality can be restricted depending on stored recipes 
• Less AI-driven personalization compared to other recipe apps 
• Interface, while functional, may feel basic compared to competitors 
Implementation Insights 
• Likely developed using Java/Kotlin for Android Studio 
• XML layouts for screen design and RecyclerView for recipe lists 
• RESTful API integration for fetching recipes and user data 
• RoomDB or SQLite for offline storage of recipes and pantry items 
• MVVM architecture for clean separation of UI and data logic 
• Could use local notifications for meal reminders or shopping alerts 


Screenshots 
Login & Signup Page 
It allows for users to have their data on multiple devices saving their information and 
preferences. 

Dashboard Page: 
It shows saved recipes and allows for you to have access to recipes that were recently 
looked at and allows for you to import your own recipes. 

Recipe board Page: 
you can filter recipes that fall under a category or dietary restriction all grouped together 
in one place 

Calendar Page: 
This page allows for meal prepping and meal planning 
Grocery list Page: 
Allows for easy grocery shopping by putting all the groceries  

2. SuperCook 
Overview 
SuperCook focuses on using items users already have at home. It is a recipe discovery 
app that creates recipes using the ingredients the user entered from from their pantry. 
Additionally, SuperCook generates shopping lists for missing ingredients and allows for 
dietary filtration.

Strengths 
• Ingredient-based recipe search helps reduce food waste. 
• it has dietary filters (vegan, gluten-free, keto, etc.) 
• Automatically generates shopping lists for missing ingredients 
• Simple, intuitive interface which is focused on pantry-based cooking 

Weaknesses 
• The recipe variety is limited compared to larger platforms 
• UI works but less visually appealing than the other competitors 
• Offline usage is limited; requires internet for full recipe search 
• Has less video tutorials and step-by-step instructions 

Implementation Insights 
• Likely uses Kotlin/Java for Android development 
• XML layouts and RecyclerView for ingredient lists and recipes 
• RESTful API integration to fetch recipes dynamically 
• SQLite or RoomDB for offline pantry data storage 
• Could use MVVM architecture to separate UI from data logic 
• Lightweight UI suggests minimal external libraries for performance 

Screenshots 
Pantry Page: 
It allows for the user to add ingredients via text and audio, based on ingredients it will 
help generate a recipe using the ingredients in your pantry. 
Favourites Page: 
It allows for you to favourite recipes that you like, bugt this is only available once you’ve 
signed up for the app 
Shopping List Page: 
This page has a shopping list where you can add your groceries making it easier to 
complete ingredients for meals 
4. KitchenPal 
Overview 
KitchenPal is an Android app focusing on helping users manage their pantry and cook 
with the ingredients they already have. The users can add items manually, via barcode 
scanning, or optionally through image recognition. The app can track the pantry 
inventory provides alerts for items that are expiring soon, and suggests recipes based 
on available ingredients. KitchenPal also includes shopping list generation, dietary 
f
ilters, and meal planning features. Its emphasis on ingredient management and 
reducing food waste makes it particularly useful for home cooks aiming for efficiency 
and sustainability. 
Strengths 
• Ingredient-based recipe suggestions that reduce food waste 
• Helps with pantry management with expiry alerts 
• Has a barcode scanning feature for easy ingredient input 
• Meal planning and shopping list generation 
• Simple, intuitive interface focused on user convenience 
Weaknesses 
• Recipe databases is smaller than larger platforms. 
• Limited offline functionality for recipe searches 
• Fewer multimedia instructions (videos or step-by-step tutorials) 
• Some features do require account creation or subscription 
• Less personalized AI recommendations compared to other apps 
Implementation Insights 
• Likely developed using Kotlin/Java in Android Studio 
• XML layouts for UI screens, RecyclerView for pantry and recipe lists 
• RESTful API integration to fetch recipes dynamically 
• RoomDB or SQLite for local pantry and user data storage 
• MVVM architecture to separate UI from business logic 
• Optional integration with image recognition APIs or ML models for identifying 
ingredients 
Screenshots 
The Dashboard: 
This page allows you to choose what it is you want to do whether it is reducing food 
waste, find healthy products, ease your grocery shopping or get quick ides for cooking. 
Kitchen page: 
This is an easy way to track what is in you inventory and pantry as they added a feature 
to swipe left or right depending on whether or not you have to ingredient. 
Grocery Page: 
This helps you to assemble a grocery list for produce that you will actually use. 
Recipe Page: 
This allows for you to personalise your app to your taste and have the recipes you like or 
explore other peoples recipes. 
Planner Page: 
The planner allows for you to plan meals and ingredients ahead of time easing the 
cooking process. 

SIGN IN PAGE: 
The profile allows for you to have a more personalizedexperience and also allows for 
you to have your information on other devices once it’s saved. 
Comparison 
Differences between CookBook, SuperCook and 
KitchPal 

Best Features 
Features to Include in the Final App with Motivations 
1. Ingredient-Based Recipe Search  
o Feature: Users can input the ingredients they have at home to find 
suitable recipes.

o Motivation: Reduces food waste and helps users make meals without 
needing extra ingredients. 

3. Limit Missing Ingredients  
o Feature: Users can set a maximum number of missing ingredients for 
recipe suggestions.

o Motivation: Provides flexibility for users who only want to shop for a few 
extra items and make the recipes mostly from their pantry. Improves 
usability and convenience. 

5. Personalized Recipe Recommendations  
o Feature: Suggest recipes based on dietary restrictions, allergies, and 
taste preferences.

o Motivation: Ensures the app caters to individual user needs, increasing 
engagement and satisfaction. It also promotes healthy and tailored 
cooking. 

7. Step-by-Step Cooking Guidance with Nutrition Info  
o Feature: Detailed instructions, timers, and nutrition breakdown for each 
recipe.

o Motivation: Helps users cook confidently, learn new recipes, and track 
their dietary intake. Supports both novice and experienced cooks. 
9. Pantry Management & Expiry Tracking  

o Feature: When users store pantry items they’ll receive alerts for soon-to
expire ingredients. 

o Motivation: Promotes efficient usage of ingredients, helps reduces food 
waste, and ensures that the user can plan meals effectively. 

10. Suggestions Based on Available Ingredients and Expiry Dates  
o Feature: Recommends recipes that use ingredients that are about to 
expire or are int the pantry.

o Motivation: This encourages sustainable cooking habits and ensures 
users make the most of their ingredients. 

12. Shopping List Generator  
o Feature: Automatically creates a shopping list for missing ingredients or 
weekly meal plans.

o Motivation: Simplifies grocery shopping by reducing forgotten items and 
integrating with the recipe suggestions for a complete cooking 
experience. 

14. Meal Planning & Calendar Sync  
o Feature: Schedule meals and sync with Google Calendar or iCal.

o Motivation: Helps users to organize their meals and therefore helps to 
increase the consistency of cooking homemade meals encouraging 
healthier eating habits. 

16. Favourites & User Profiles 
o Feature: Save favourite recipes, track cooking history, and set dietary 
preferences.

o Motivation: Increases user retention by creating a personalized 
experience and encourages repeated app usage.


- Read the attached file for more in depth readme 
