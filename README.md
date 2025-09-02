# Promised Land — Web-Based Survival Adventure

An educational, turn-based survival game you can play directly in your browser. Manage resources, make tough choices, and guide your people through iconic milestones on the journey to the Promised Land.

----------

## 🎮 Key Features

### Visual Interface
-   Resource status bars with color-coded indicators    
-   Real-time updates of people count, location, and day    
-   Interactive event panels with multiple-choice buttons   
-   Game log showing all actions and outcomes
    

### Gameplay Mechanics
-   Turn-based progression with a **Next Day** button 
-   Random events with meaningful consequences   
-   Resource management: food, water, health, morale, faith, supplies  
-   Milestone events (Red Sea crossing, Mount Sinai, etc.)  
-   Win/lose conditions with detailed end screens
    

### Biblical Events Included
-   The People Complain of Thirst   
-   Attack by the Amalekites   
-   Golden Calf Rebellion  
-   Manna from Heaven  
-   Disease Outbreak 
-   Spies Return from Promised Land
    

### Special Features
-   Responsive design (mobile + desktop)    
-   Desert-themed styling with a biblical color palette    
-   Requirement-gated choices (e.g., minimum faith levels)    
-   Population tracking with realistic death mechanics  
-   Journey progression through **8 biblical locations**

----------

## 🖼️ New Image Features Added:

### Visual Event Display
Added an #eventDisplay container that shows images above the text
Images are 400px max width, 200px height with rounded corners and shadows
Text appears below the image as requested

### Image Management System
Created a gameImages object mapping event types to image paths
Images are expected in the assets/images/ folder you already have set up
Includes fallback placeholders when images can't be loaded

### Image Categories Included:
Locations: Egypt, Red Sea, Desert areas, Mount Sinai, Promised Land
Events: Thirst, Amalekites, Manna, Bitter Water, Golden Calf, Ten Commandments
Actions: Travel, Camp, Pharaoh Pursuit
Outcomes: Victory, Defeat

### Smart Image Selection
Different images show based on context (e.g., travel vs camp vs events)
Story events have specific themed images
Fallback to desert/generic images when specific ones aren't available

## 📁 Images You'll Need:
Place these in your assets/images/ folder:

egypt.jpg, departure.jpg
red_sea.jpg, red_sea_crossing.jpg
desert.jpg, desert_shur.jpg, desert_sin.jpg
mount_sinai.jpg, promised_land.jpg
thirst.jpg, amalekites.jpg, manna.jpg
bitter_water.jpg, golden_calf.jpg, ten_commandments.jpg
travel.jpg, camp.jpg, pharaoh_pursuit.jpg
victory.jpg, defeat.jpg

The system gracefully handles missing images by showing styled placeholders, so your game will work even before you add all the images!
----------

## 🚀 How to Test Locally
1.  Save the game file as `promised-land.html`. 
2.  Open it in any modern web browser.    
3.  Click **Next Day** to advance the journey.  
4.  Make choices during events to affect your resources.   
5.  Try to reach the Promised Land with your people alive!
    
> You can freely modify events, resources, or styling—this project is designed to be easy to customize.
