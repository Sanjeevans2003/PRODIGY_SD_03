Title :Contact Management System

This project provides a user-friendly Contact Management System (CMS) written in Python. It allows you to effectively organize, manage, and interact with your contact information.

Features:

* Create Contacts: Easily add new contacts by providing their name, phone number, and email address.
* View Contacts: Display a clear and organized list of all saved contacts in the system.
* Edit Contacts: Modify existing contact details by name, phone, or email, ensuring your information remains current.
* Delete Contacts: Remove unwanted contacts from your list to maintain a streamlined and organized contact database.
* Save Contacts (Persistence): Persist your contact data by saving it to a JSON file. This allows you to retrieve your contacts even if you restart the program.
* Load Contacts (Persistence): Load previously saved contacts from a JSON file, eliminating the need for manual re-entry upon program restarts.

Getting Started(Prerequisites):
Installation:
* Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))

Usage:

1. Run the program:

   ```
   python main.py
   ```

2. Follow the on-screen menu:

   The program will display a menu with options for adding, viewing, editing, deleting, saving, and loading contacts. Select the desired option by entering the corresponding number and following the prompts.

Example Usage:

1. Add a new contact:

   - Choose option 1 (Add Contact)
   - Enter the contact's name, phone number, and email address when prompted.
   - The new contact will be added to the list.

2. View all contacts:

   - Choose option 2 (View Contacts)
   - The program will display a formatted list of all saved contacts.

3. Edit a contact:

   - Choose option 3 (Edit Contact)
   - Enter the index of the contact you want to modify.
   - Update the desired details (name, phone, or email) or leave them blank to keep them unchanged.
   - The contact information will be updated.

4. Delete a contact:

   - Choose option 4 (Delete Contact)
   - Enter the index of the contact you want to remove.
   - The contact will be deleted from the list.

5. Save contacts to a file:

   - Choose option 5 (Save Contacts)
   - Enter the filename where you want to save the contact data (e.g., 'my_contacts.json').
   - The contact list will be saved in JSON format for persistence.

6. Load contacts from a file:

   - Choose option 6 (Load Contacts)
   - Enter the filename containing the saved contact data (e.g., 'my_contacts.json').
   - The previously saved contacts will be loaded and displayed.

Additional Notes:

Persistence (Saving and Loading Contacts):

The provided code utilizes JSON to save and load contact data. This allows for easy data exchange and persistence between program runs. However, consider these options for advanced usage:

* Database Integration: For managing a large number of contacts, explore integrating with a database like SQLite or MySQL for better scalability and performance.
* Cloud Storage: Consider saving contacts to cloud storage services like Google Drive or Dropbox to provide accessibility from any device and facilitate collaboration.

This Contact Management System provides a solid foundation for managing your personal or professional contacts efficiently. 
