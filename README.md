### Password Manager Project Summary

**Project Objective:** Build a Password Manager application using React that includes features for adding, displaying, searching, and deleting passwords.

### Functional Requirements:

**Initial State:**

Input fields for website, username, and password should be empty.<br/> Display a "No Passwords View" when there are no passwords.<br/>

**Adding Passwords:**

When non-empty values are provided in the input fields and the "Add" button is clicked:

A new password entry is added.<br/> Password count increments.<br/> Passwords are displayed as stars by default.<br/> Input fields reset to empty.<br/>

**Display Options:**

Toggle to show/hide passwords.<br/> Display stars or actual passwords based on the toggle.<br/>

**Searching:**

Search input filters passwords by website name.<br/> Display "No Passwords View" if no matches are found.<br/>

**Deleting Passwords:**

Each password entry has a delete button.<br/> Deleting an entry decrements the password count.<br/> Display "No Passwords View" when all passwords are deleted.<br/>
