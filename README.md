"# Week3_Tasks" 

Task 1: Build a Menu Navigation System
In this task, we will build a hierarchical menu using object-oriented principles. We'll use a tree structure to represent the menu hierarchy and allow navigation.
MenuItem Class: Represents each menu item, with an option to store sub-menu items.
Menu Class: Manages the navigation logic between the root menu and submenus.
Navigation: Users can navigate down to a submenu or up to the previous level using the choices in the menu.


Task 2: Simulate an Instrument Cluster Data Display
For this task, we'll create a VehicleData class to store speed, fuel level, and engine temperature. We'll simulate real-time updates and warnings when thresholds are exceeded.
VehicleData Class: Contains attributes for speed, fuel level, and engine temperature.
updateData(): Randomly generates values for these attributes.
displayData(): Displays the current vehicle data and shows warnings if certain thresholds are exceeded (e.g., temperature > 100°C or fuel < 10%).


Task 3: Event Handling System for Touchscreen Input
In this task, we simulate a touchscreen event system with an event queue. We'll process events like taps and swipes.
Event Class: Represents a touchscreen event with type (tap or swipe), coordinates, and a timestamp.
EventQueue Class: Manages a queue of events, processes them one by one, and handles different types of events.
Random Event Generation: Simulates random events by randomly choosing event types and coordinates.


Task 4: HMI Skin Customization System
This task involves building a theme customization system where users can switch between different skins. We'll use a Theme class and a simple interface for switching between themes.
Theme Class: Holds attributes for theme customization (background color, font color, etc.). It has methods for previewing and applying themes.
Theme Switching: The user can select a theme and see a preview before applying it.
