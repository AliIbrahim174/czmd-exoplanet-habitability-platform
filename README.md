# CZMD — Exoplanet Habitability Assessment Platform

A NASA Space Apps Challenge project that helps users explore exoplanet data and evaluate potential habitability using scientific conditions and data from the **NASA Exoplanet Archive**.

The platform was developed as an MVP in less than 48 hours and won **1st Place at the NASA Space Apps Challenge — Port Said Branch**, later becoming a **2024 Global Nominee**.

---

## Overview

CZMD is a web-based exoplanet analysis platform designed to help users search, visualize, and assess planets outside our solar system.

The system processes exoplanet data from NASA’s Exoplanet Archive and evaluates habitability-related conditions such as radius, mass, temperature, habitable-zone position, magnetic-field potential, and detectability.

The goal of the project was to combine **space science**, **data processing**, **web development**, and **scientific visualization** into an accessible interactive platform.

---

## Awards

- **1st Place** — NASA Space Apps Challenge, Port Said Branch
- **2024 Global Nominee**
- Built as an MVP in less than 48 hours during the competition

---

## My Role

I worked as the **team leader**, and contributed to both the technical and product-development sides of the project.

My responsibilities included:

- Leading a 6-member team during the competition
- Contributing to the front-end and back-end implementation
- Building the AI/data processing component
- Working with NASA Exoplanet Archive data
- Supporting the integration between the data layer, web interface, and user-facing results
- Helping prepare the project presentation and competition submission

---

## Key Features

- Exoplanet search and exploration
- Habitability assessment based on scientific criteria
- Real-time or frequently updated exoplanet data pipeline
- Interactive web interface
- 3D visualization of star systems and exoplanets
- API-based data retrieval
- Hosted MVP deployment
- Competition-ready project documentation and presentation

---

## Habitability Conditions Evaluated

The system evaluates planets using several scientific indicators:

1. **Habitable Zone Position**  
   Checks whether a planet is located in a region where liquid water could potentially exist.

2. **Planet Radius**  
   Evaluates whether the planet radius is within a suitable range for potential habitability.

3. **Planet Mass**  
   Assesses whether the planet mass is within an acceptable range.

4. **Planet Temperature**  
   Checks if the estimated temperature falls within a potentially habitable range.

5. **Magnetic Field Potential**  
   Uses mass and radius indicators to estimate whether the planet may have magnetic-field potential.

6. **Signal-to-Noise Ratio / Detectability**  
   Estimates whether a planet can be detected or separated from its host star under observation constraints.

---

## Tech Stack

| Layer | Technologies |
|---|---|
| Data Processing | Python, Pandas |
| Machine Learning / Analysis | Scikit-learn, NumPy |
| Database | MySQL, SQLAlchemy |
| Backend / Serverless | Python, AWS Lambda, Serverless Functions |
| Frontend | React.js, JavaScript |
| 3D Visualization | THREE.js |
| Hosting | Vercel |
| Data Source | NASA Exoplanet Archive |

---

## System Workflow

```text
NASA Exoplanet Archive
        ↓
Data Fetching / Update Pipeline
        ↓
Data Processing and Cleaning
        ↓
Habitability Condition Checks
        ↓
Database Storage
        ↓
API / Serverless Functions
        ↓
Interactive Web Interface
        ↓
User Search, Results, and Visualization
```

---

## Project Links

- Team Page: https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/czmd/
- MVP Website: https://nasa-space-apps2024-czmd.vercel.app/
- Explanation Video: https://drive.google.com/file/d/1y9-xK2YMi6njxh7IWc9zcVv6nnGlr8pn/view

---

## Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/AliIbrahim174/czmd-exoplanet-habitability-platform.git
cd czmd-exoplanet-habitability-platform
```

### 2. Backend setup

Install Python dependencies:

```bash
pip install pandas sqlalchemy pymysql requests scikit-learn numpy
```

Configure the database connection according to your local or hosted MySQL setup.

### 3. Frontend setup

Install Node.js dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

> Note: The exact run command may differ depending on the final frontend structure and deployment setup.

---

## Screenshots

Add screenshots here after uploading them to the repository.

Recommended screenshots:

```text
assets/screenshots/home-page.png
assets/screenshots/search-results.png
assets/screenshots/exoplanet-visualization.png
assets/screenshots/habitability-report.png
```

Example Markdown after adding screenshots:

```md
![Home Page](assets/screenshots/home-page.png)
![Habitability Report](assets/screenshots/habitability-report.png)
```

---

## Contributors

- [Ahmed Ellaban](https://www.linkedin.com/in/ahmed-samy-ellaban/)
- [Basel Shreif](https://www.linkedin.com/in/basel-shrief/)
- [Ali Mahmoud Ahmed Ibrahim](https://www.linkedin.com/in/ali-mahmoud-ibrahim/)
- [Nour Wael](https://www.linkedin.com/in/nour-wael-3b359a2b3/)
- [Aya Mohamed](https://www.linkedin.com/in/aya-mohamed-samir-5780a9267)
- [Farah Elhebeishy](https://www.linkedin.com/in/farah-elhebeishy-46146632a/)

---

## What I Learned

This project strengthened my experience in:

- Leading a technical team under time pressure
- Working with scientific datasets
- Turning raw data into user-facing insights
- Integrating data processing with web interfaces
- Building an MVP under competition constraints
- Communicating technical work clearly for judges and users

---

## Future Improvements

- Improve scientific validation of habitability scoring
- Add more exoplanet parameters and atmospheric indicators
- Improve 3D visualization and comparison tools
- Add user-friendly filtering and ranking
- Improve deployment documentation
- Add automated tests for data-processing functions
- Add clearer API documentation

---

## License

This project is open-source and available under the MIT License.
