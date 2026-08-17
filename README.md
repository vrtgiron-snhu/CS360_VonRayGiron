# CS360_VonRayGiron

### 1. Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

For my CS 360 project, I developed an **Inventory Manager mobile app** using Android Studio and Java. The main goal of the app was to give users a simple way to manage inventory from a mobile device. The app needed to allow users to log in or create an account, view their inventory, add new items, and increase or decrease the quantity of existing items. Another requirement was to provide SMS notifications when an item's quantity reached zero, as long as the user gave the app permission to send messages. The app was designed to address the need for a simple and convenient way to keep track of inventory without requiring complicated software.

### 2. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

Several screens were necessary to make the app easy for users to understand. The first was the **login and account creation screen**, which gave users a clear starting point when opening the app. The main inventory screen displayed the user's items and their quantities in an organized layout. I also included buttons that allowed users to increase or decrease inventory quantities. Another screen handled **SMS notification permission**, giving the user the choice to allow notifications or continue without them.

While designing the interface, I tried to keep everything simple and consistent. Buttons were clearly labeled, important information was easy to find, and the screens followed a similar design style. I also used spacing, readable text, and straightforward navigation so users would not have to guess what to do next. I think the designs were successful because they focused on completing common inventory tasks without adding unnecessary features that could make the app confusing.

### 3. How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

I approached the coding process by breaking the application into smaller parts instead of trying to complete everything at once. I first made sure that each screen was created correctly and then connected the buttons and other interface components to the Java code. From there, I worked on navigation, inventory functionality, database features, and SMS permissions.

One strategy that helped me was testing each feature after making changes. This made it easier to identify where an error came from instead of writing a large amount of code and trying to troubleshoot everything at the end. I also reused similar coding patterns when possible, such as button click listeners and screen navigation. In future projects, I can use the same approach by dividing larger applications into smaller features, developing them individually, and testing them before moving forward.

### 4. How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

I tested the application regularly using the **Android Emulator in Android Studio**. I checked that the app launched correctly, buttons responded when clicked, screens opened as expected, and inventory controls worked correctly. I also tested features such as permission requests to make sure the app responded appropriately depending on the user's selection. When errors appeared, I reviewed Android Studio's error messages and went back through the related code or XML layout to locate the problem.

Testing is important because code can compile successfully while still not behave the way the user expects. Testing revealed several smaller issues during development, including problems with layouts, navigation, and code configuration. Finding these problems during development allowed me to correct them before considering the application complete.

### 5. Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

One area where I had to adapt was connecting the UI design from Project Two with the functional requirements in Project Three. Designing what the application should look like was different from making every button and screen actually work. I had to figure out how to connect multiple activities while still keeping the app easy to navigate.

The SMS notification feature was another challenge because it required more than simply creating a button. The application had to request permission from the user and respond differently depending on whether permission was granted or denied. Working through these challenges taught me to look at problems one piece at a time and adjust my original design when the technical requirements called for it.

### 6. In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I was particularly successful with the **inventory management screen and its navigation**. This part of the application brought together several skills I learned throughout the course, including Android layouts, Java programming, button event handling, and user-centered design. The inventory screen clearly displays the information users need while providing simple controls for managing item quantities.

I am also proud of the SMS permission feature because it showed that I could work with Android permissions while still keeping the user in control of the experience. Overall, these components demonstrated how much I learned about combining interface design with functional code to create a complete mobile application.
