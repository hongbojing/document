  # ONF UF My Schedule API Interface

This document records the API related to the ONE UF My Schedule application.

## API Overview

1. All term API (/api/myschedule/terms/all)
2. Specific term API (/api/myschedule/term_number)
3. Period time API (/api/myschedule/periods/term)
4. Footer API (/ext/common/features/footer/footer.json)
5. User API (/api/uf/user)
6. Dash API (/api/uf/dash)

## API Details

1. All term API contains all the data related to the display of the landing page.

2. Specific term API is triggered when users click the "Go to My Schedule" on the landing page, it will pass the data of each course and the total credits the user have in that semester.

3. Period time API has the data UF Fall/Spring Class Period Meeting Times.
  
4. Footer API is a public API, which containes the data what we use to generate the footer.

5. User API is used to identify the users.

6. Dash API determines whether a section card is avaiable for the users based on the user role.
