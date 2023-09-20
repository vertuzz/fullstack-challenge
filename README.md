**W&D Lead Fullstack Engineering Challenge**

Welcome to our Lead Fullstack Engineering Challenge repository. This document will guide you through the challenge. Please fork this repo before you begin, as we will evaluate the code on your fork.

**Challenge Overview:**

Design and implement a system that allows users to manage their personal property list. Users should be able to sign up, log in, and then add or remove properties to/from their property list.

**Requirements:**

1. **User Authentication**:
    - Implement a basic login and sign-up page.

2. **Database Design and Implementation**: 
    - We recommend using SQLite for the sake of simplicity, but feel free to choose another database if you have a specific preference. Justify your choice.
    - Initiate the database using the data from the provided Excel file. Automation is not necessary. 

3. **Backend Development**:
    - Develop a backend in Python to interact with the database.
    - Choose a suitable Python framework (e.g., Flask, Django, FastAPI, Falcon) and justify your choice.

4. **Frontend Development**:
    - Implement the frontend using Vue.js.
    - Once logged in, users should see their property list.
    - Each property in the list should display:
        - Full Address
        - Class Description
        - Estimated Market Value
    - Users should be able to search for properties from the database and add them to their property list.
        - Users should be able to search on the following values:
            - Full Address
            - Class
            - Estimated_Market_Value
            - BLDG_USE
            - BUILDING_SQ_FT
    - Properties on the users list should have an option to be removed.

5. **Security**:
    - Implement basic security practices for the backend API and user authentication.

6. **Documentation**:
    - Provide a brief README detailing how to set up and run your application.
  
7. **Bonus**:
    - **Optimization**: Propose at least one optimization that can help the application perform better under increased data loads.
    - **Additional Feature**: Propose a feature you believe would enhance the user's experience while managing their property list.
