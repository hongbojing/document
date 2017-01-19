# ONF UF Degree Audit API Interface

This document records the API related to the ONE UF Degree Audit application.

## API Overview

1. Student program API
2. Load data API
3. Excess hours API
4. Footer API
5. User API
6. Dash API

## API Details

1. Student program API
/api/degreeaudit/studentprogram/

2. Load data API
/api/degreeaudit/audit/?program=program_name

3. Excess hours API
/api/degreeaudit/excesshours/

4. Footer API
/ext/common/features/footer/footer.json
Footer API is a public API, which containes the data what we use to generate the footer.

5. User API is used to identify the users.

6. Dash API determines whether a section card is avaiable for the users based on the user role.
