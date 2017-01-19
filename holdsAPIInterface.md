# ONF UF Holds API Interface

This document records the API related to the ONE UF Holds application.

## API Overview

1. All holds API
2. Footer API
3. User API
4. Dash API

## API Details

1. All holds API provides the data for the holds, and the structrue of the JSON file is:

  + 0:
    - description: "holds content"
  + holdsCount: "01"
  + regOpen: "Y"
  
2. Footer API is a public API, which containes the data what we use to generate the footer.

3. User API is used to identify the users.

4. Dash API determines whether a section card is avaiable for the users based on the user role.
