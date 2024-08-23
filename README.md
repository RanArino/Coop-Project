# Project Title: Co-op Project - Pricing Calculator App

This project is a Python-based web application that I developed at [Drone Cleaning Company](https://www.linkedin.com/company/dronecleaningcompany/posts/?feedView=all) that I joined as a Co-op Innternship placement. 

Note: I got the permission to post the following system architecture and web app application.

**Key Features:**

1. Secure User Authentication: Restricts access to authorized users via a robust login system using Firebase and GCP Identity
Platform.[^1]
2. Data Entry and Real-time Calculation: Enables efficient data input with intuitive forms and provides instant feedback through real-time calculation updates, enhancing user experience and productivity.[^2]
3. Integrated Location Services: Utilizes Google Maps API for seamless address geocoding, location search, and interactive map visualization, enhancing user experience with location-based data.[^3]
4. Automated Data Verification: Implements robust data validation to ensure accuracy and consistency, generates Google Sheets based on user demand, supports seamless verified data upload to Cloud SQL for persistent storage.[^4]
5. Interactive Data Exploration & Dashboards: Provides intuitive dashboards on the homepage and a dedicated dashboard page, enabling users to select attributes, and input queries for data retrieval and analysis, monitor cleaning project completion, facilitate quick review for each cleaning project.[^5]
6. Seamless Database Update: Allows users to efficiently update database records with a user-friendly interface and built-in data validation, ensuring data accuracy and integrity while providing real-time feedback on update status.[^6]
7. Feedback System with Notion: Streamlines user feedback collection by integrating with Notion API, allowing users to submit feedback and optional screenshots directly to a designated Notion page, facilitating efficient issue tracking and web app improvement.[^7]
8. AI-Powered Source Code Exploration: Leverages Google Gemini LLM and a FAISS vector database, providing Retrieval Augmented Generation(RAG) system through a user-friendly chat interface to understand web application source codes.[^8]

![Key Features Visualization](https://github.com/RanArino/Coop-Project/blob/main/docs/KeyFeatures.png)

---

**Technologies Used:**

* **Frontend:** Dash/Plotly (React.js base)
* **Backend:** Python (Flask)
* **Cloud Platform:** Google Cloud Platform (GCP)
* **Database:** GCP's Cloud SQL(PostgreSQL)
* **Loging:** Firebase & GCP's Identity Platform
* **Version Control:** Git (GitHub)
* **Additional API Services:**
    - Notion API
    - Google Drive/Sheet/Map API
 
![Technology Used Visualization](https://github.com/RanArino/Coop-Project/blob/main/docs/TechnologyUsed.png)

---

**Architecture Overview:**

For a detailed visual representation of the system's workflow and interactions, refer to the diagrams provided in the docs/architectures/ folder or check the links on footnotes.

---

**Contact:**
- Emails:
  - rarino@myseneca.ca
  - ranarino0611ca@gmail.com
- LinkedIn: https://www.linkedin.com/in/ran-arino-25253022b/ 


[^1]: More details about the authentication process can be found in [Login.png](https://github.com/RanArino/Coop-Project/blob/main/docs/architectures/Login.png).
[^2]: The real-time calculation feature significantly improves user experience by providing immediate feedback. [DataEntry.png](https://github.com/RanArino/Coop-Project/blob/main/docs/architectures/DataEntry.png)
[^3]: Google Maps API enables seamless integration of location-based services, enhancing the app's functionality. [GoogleMap.png](https://github.com/RanArino/Coop-Project/blob/main/docs/architectures/GoogleMap.png)
[^4]: Automated data verification ensures data accuracy and consistency, a crucial aspect of the application. [DataVerify.png](https://github.com/RanArino/Coop-Project/blob/main/docs/architectures/DataVerify.png)
[^5]: The interactive dashboards provide users with powerful tools for data exploration and analysis. [Dashboard.png](https://github.com/RanArino/Coop-Project/blob/main/docs/architectures/Dashboard.png)
[^6]: Seamless database updates streamline data management and ensure data integrity. [DBUpdate.png](https://github.com/RanArino/Coop-Project/blob/main/docs/architectures/DBUpdate.png)
[^7]: The Notion API integration facilitates efficient feedback collection and issue tracking. [Feedback.png](https://github.com/RanArino/Coop-Project/blob/main/docs/architectures/Feedback.png)
[^8]: The RAG system led by Google Gemini and FIASS vector DB boosts the understanding of source codes. [CodingRAG.png](https://github.com/RanArino/Coop-Project/blob/main/docs/architectures/CodingRAG.png)
