# Invoice-Generator
This is really cool invoice generator that has been made using the file handling module in Python. Basically, there's this text file that has a list of items, and what happens is that this generator fetches all the details about these items from the file and then magically creates an awesome invoice for you. It's super handy and saves you a lot of time and effort. So, next time you need to generate an invoice, just let this Python script do all the work for you.

Here's a simplified explanation of how the program work:

**1. Data Storage:**
   The list of items and their details are stored in a products file, with each line representing a different item. For example, the file could have entries like:

    Item, Price, Quantity
    Phone,30000,37
    Laptop,60000,38
    HDD,5000,18
    
**2. File Handling:**
    The program uses Python's file handling module to read and extract information from the products file. This involves opening the file, reading its content, and then parsing the data to extract item details.
   
**3. User Interaction:**
    The program prompt the user to enter personal details, select items for the invoice, specify quantities, and provide the additional information needed for the invoice.
   
**4. Invoice Generation:**
    Using the gathered information from both the user input and the products file, the program calculates the total amount for the selected items. It then formats this information into an invoice.
   
**5. Output:**
    The generated invoice is saved as a separate text file for future reference. The invoice typically includes details such as item names, quantities, unit prices, discounts and the total amount.
   
This type of program simplifies the invoicing process for businesses, reducing manual effort and minimizing errors.
