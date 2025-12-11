# ms-scraper-d365

A Node.js service that scrapes Microsoft Learn documentation pages.  
It reads URLs from `urls.txt`, crawls each page (including sidebar links), extracts:

- **Title**
- **URL**
- **Last Updated Date**

…and returns everything as a downloadable **CSV file**.

---

##  Features

- Scrapes Microsoft Learn pages
- Extracts page title and last updated date
- Follows sidebar navigation links automatically
- Deduplicates URLs
- Exports results as a CSV


---

##  Project Structure
MS-SCRAPER-D365/
│
├── node_modules/
├── .dockerignore
├── .gitignore
├── Dockerfile
├── package-lock.json
├── package.json
├── README.md   
├── server.js
└── urls.txt

- Node.js **20+**
- npm

---

##  Local Installation

1. Install dependencies:

   ```bash
   npm install







