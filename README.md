# BizCardX-Extracting-Business-Card-Data-with-OCR

**Technologies Used :** Python,easy OCR, Streamlit, SQL, Pandas
**About** : Bizcard is a Python application designed to extract information from business cards.
The main purpose of Bizcard is to automate the process of extracting key details from business card images, such as the name, designation, company, contact information, and other relevant data. I was created two tabs as upload & modify and delete the details

**Fetching the data from image:**
- Fetched the data from image and stored into SQL

**SQL Integration:**
- Created tables to store the datas in SQL.
- Transferred the data to SQL tables using Python with sqlite3.

**Streamlit Interface:**
- Utilized Streamlit for the front-end interface.
- Created multiple options to do different activites as below
- Options like Home,Upload & Save, Preview, Modify and Delete

*Home* - Just about the application
*Upload & Save* - Upload the image and store the fetched data into the SQL
*Preview* - Used to show all the data which is available in database
*Modify* - Used to modify the data if there is any modification required
*Delete* - Used to delete the data from database if the data is not required
