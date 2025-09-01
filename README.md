# RFID-based-Smart-Trolley
A smart and interactive shopping cart that uses RFID technology and Arduino to automate in-cart billing. It is designed to eliminate long checkout queues and enhance the overall shopping experience.

# Components and Tools
* Hardware: 
1. MFRC522 RFID Reader
2. Arduino UNO Board
3. I2C Module
4. 16*2 LCD Display
5. RFID Tags & Cards

* Software: 
1. Arduino IDE for development

# How It Works
- Each product in the store is tagged with an RFID.
- The cart is equipped with an RFID reader and a Bluetooth module.
- As items are placed in or removed from the cart, it automatically detects the changes and updates the bill.
- The cart's LCD screen displays the current items and total price.
- A companion Android app syncs with the cart in real time to show live updates.

# Workflow
1. Shopper adds an item to the trolley.
2. RFID tag is detected by the onboard reader.
3. Item data is sent to the mobile app via Bluetooth.
4. LCD shows product details and current total.
5. Checkout happens instantly and no cashier is required!

# Key Outcomes: 
- Faster checkouts and reduced need for staff.
- Achieved 83% tag-read accuracy in the prototype.
- Concept is scalable with higher-grade RFID readers and tags.

# Future Scope
- Adding in-app payment processing for full automation.
- Integrate with central inventory systems for large-scale retail use.

# Documentation
A detailed report explaining the design, hardware setup, and testing outcomes is available in the Documentation folder.





