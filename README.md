# 🌐 Data Visualization Dashboard

An interactive data visualization dashboard built with the MERN stack (MongoDB, Express.js, React.js, Node.js) and D3.js. This application provides insights into various global parameters such as intensity, likelihood, relevance, country, region, and more through dynamic filtering and graphical representations.

## 📊 Features

* **Interactive Charts**: Utilizes D3.js to render dynamic bar charts, line graphs, pie charts, and more.
* **Comprehensive Filters**: Filter data based on:

  * End Year
  * Topics
  * Sector
  * Region
  * PEST
  * Source
  * SWOT
  * Country
  * City
* **Responsive Design**: Ensures optimal viewing experience across various devices.
* **Real-time Data Interaction**: Dynamic updates based on user-selected filters.([GitHub][1], [readme.so][2])

## 🛠️ Tech Stack

* **Frontend**: React.js, D3.js
* **Backend**: Node.js, Express.js
* **Database**: MongoDB (Data imported from JSON files)
* **Visualization**: D3.js for rendering interactive charts

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

* **Node.js**: [Download and install Node.js](https://nodejs.org/)
* **MongoDB**: [Download and install MongoDB](https://www.mongodb.com/try/download/community)
* **npm**: Comes with Node.js installation

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Khushi-2409/new_dashboard.git
   ```



2. **Navigate to the project directory**:

   ```bash
   cd new_dashboard
   ```



3. **Install dependencies**:

   ```bash
   npm install
   ```



4. **Start the development server**:

   ```bash
   npm start
   ```



The application will run on `http://localhost:3000/` by default.

## 📁 Project Structure

```plaintext
new_dashboard/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── charts/
│   ├── assets/
│   └── App.js
├── .gitignore
├── package.json
├── README.md
└── ...
```



* **public/**: Static assets and the main HTML file.
* **src/**: Source code including components, pages, charts, and assets.
* **.gitignore**: Specifies files to ignore in version control.
* **package.json**: Project metadata and dependencies.

## 📸 Screenshots

*Include relevant screenshots here to showcase the dashboard, charts, and features.*

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

## 🙌 Acknowledgements

* Inspired by modern data visualization practices and UI/UX best practices.
* Thanks to the open-source community for the tools and libraries utilized in this project.
