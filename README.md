# CS-360 Mobile Architecture and Programming

## Inventory Management Application

This repository contains my completed Inventory Management Android application developed for CS-360 at Southern New Hampshire University. The Project Three ZIP file includes the application's source code, finalized user interface, and Android Studio project files.

### App Requirements and Goals

The goal of this project was to develop a functional Android application that allows users to manage inventory efficiently. The application was designed with individuals and small businesses in mind, particularly those who need a straightforward way to monitor stock levels and update inventory quantities. The main requirements included account creation and login, persistent inventory storage, the ability to add and remove items, quantity adjustments, and optional SMS notifications when items become out of stock.

### User Interface Design

To support these requirements, I designed four primary screens: a login and account creation screen, an inventory management screen, an add-item screen, and an SMS notification settings screen. I focused on keeping the interface simple and organized so users could quickly access the features they needed. The inventory screen displays item names, quantities, and controls for increasing, decreasing, or deleting items. I also incorporated visual low-stock warnings to make inventory shortages easier to identify. Consistent colors, clearly labeled buttons, and straightforward navigation helped create a user-centered design.

### Development Approach

I approached development by breaking the project into smaller, manageable components. I started with the user interface and then implemented the functionality behind each screen. I used Java and Android Studio to develop the application and SQLite to store user credentials and inventory records locally. I tested each feature after implementing it before moving on to the next component. This approach helped me stay organized and made troubleshooting easier. I plan to continue using incremental development and testing in future software projects.

### Testing and Functionality

I tested the application using the Android Emulator to verify that its primary features worked correctly. This included creating an account, logging in, closing and reopening the application to verify persistent storage, adding inventory items, adjusting quantities, and deleting records. I also tested the low-stock notification feature by decreasing an item's quantity to zero. The application displayed an out-of-stock warning and submitted an SMS send request. Testing was important because it allowed me to identify potential problems and verify that the application behaved as expected. It also reinforced the importance of testing individual features rather than waiting until the entire project is finished.

### Challenges and Innovation

One challenge I encountered was transitioning from a user interface containing sample inventory information to a fully functional application connected to a database. I needed to make sure the inventory screen could display actual SQLite records and update automatically when users changed quantities or added items. I addressed this by dynamically generating inventory rows from the database and refreshing the display after changes. Another challenge involved implementing SMS notifications while ensuring that inventory management remained functional even if users denied SMS permission. These experiences helped improve my understanding of Android development, database integration, and handling optional application permissions.

### Areas of Success

I believe my strongest accomplishment was implementing the SQLite database and connecting it to the inventory management interface. This component demonstrated my ability to integrate persistent data storage with a functional mobile user interface. Successfully adding, updating, deleting, and retrieving inventory records showed how the different parts of an application work together. I was also proud of implementing the SMS notification feature because it required coordinating inventory updates with Android permissions and system services.

### Reflection

Overall, this project helped me better understand the complete mobile application development process, from planning and interface design to coding, testing, and finalization. I learned that developing a successful application involves more than simply writing functional code. It also requires understanding user needs, designing intuitive interfaces, and thoroughly testing the finished product. I plan to apply these lessons to future development projects and continue expanding my GitHub portfolio as I pursue a career in software and cloud engineering.
