# CSA4302 - Internet Programming Lab Experiments

A comprehensive collection of modern, responsive, and interactive web applications developed for the **CSA4302 - Internet Programming** laboratory curriculum.

Each experiment is built using modern HTML5, CSS3 (Glassmorphism, CSS Grid, Flexbox, custom design systems), and Vanilla JavaScript (ES6+), complete with an interactive dashboard portal and an integrated Node.js server.

---

## 📚 Experiments Index

| Experiment | Title | Description | Technologies |
| :--- | :--- | :--- | :--- |
| **Experiment 1** | **[LibraryHub](Experiment%201.html)** | Local Library Management System with catalog search, book issues/returns, and fine tracker. | HTML5, CSS3, JavaScript |
| **Experiment 2** | **[Grand Azure Resorts](Experiment%202.html)** | Online Hotel Room Booking & Reservation System featuring room selection, date filters, amenities, and pricing calculator. | HTML5, CSS3, JavaScript |
| **Experiment 3** | **[RapidExpress](Experiment%203.html)** | Online Bus Ticket Booking System with live seat selection map, route filter, boarding points, and boarding pass generator. | HTML5, CSS3, JavaScript |
| **Experiment 4** | **[RailConnect](Experiment%204.html)** | National Train Reservation & PNR Status System with quota selection, berth preference, and live booking summary. | HTML5, CSS3, JavaScript |
| **Experiment 5** | **[AeroGlobal](Experiment%205.html)** | Online Flight Reservation & Airline GDS with multi-class seat selection, luggage add-ons, and dynamic ticket preview. | HTML5, CSS3, JavaScript |
| **Experiment 6** | **[SweetArtisan](Experiment%206.html)** | Buy a Cake Online E-Commerce Portal featuring flavor customizations, weight selection, eggless options, and cart management. | HTML5, CSS3, JavaScript |

---

## 🌟 Master Portal

The project includes an **`index.html`** landing portal that unifies all 6 experiments into a single hub with quick launch cards, experiment summaries, and instant browser previews.

---

## 🚀 How to Run Locally

### Option 1: Direct Browser Opening
Simply double click on `index.html` or any of the `Experiment [1-6].html` files to open them directly in any modern browser (Chrome, Edge, Firefox, Safari).

### Option 2: Using the Included Node.js Server
A zero-dependency Node.js HTTP server is included in `server.js`.

1. **Start the server:**
   ```bash
   node server.js
   # or
   npm start
   ```

2. **Access the portal in your browser:**
   ```text
   http://localhost:3000
   ```

3. **Direct links to experiments:**
   - **Portal**: [http://localhost:3000/index.html](http://localhost:3000/index.html)
   - **Experiment 1**: [http://localhost:3000/Experiment%201.html](http://localhost:3000/Experiment%201.html)
   - **Experiment 2**: [http://localhost:3000/Experiment%202.html](http://localhost:3000/Experiment%202.html)
   - **Experiment 3**: [http://localhost:3000/Experiment%203.html](http://localhost:3000/Experiment%203.html)
   - **Experiment 4**: [http://localhost:3000/Experiment%204.html](http://localhost:3000/Experiment%204.html)
   - **Experiment 5**: [http://localhost:3000/Experiment%205.html](http://localhost:3000/Experiment%205.html)
   - **Experiment 6**: [http://localhost:3000/Experiment%206.html](http://localhost:3000/Experiment%206.html)

---

## 🛠️ Project Structure

```text
├── Experiment 1.html        # Library Management System
├── Experiment 2.html        # Hotel Room Booking System
├── Experiment 3.html        # Bus Ticket Booking System
├── Experiment 4.html        # Train Ticket Reservation System
├── Experiment 5.html        # Flight Ticket Reservation System
├── Experiment 6.html        # Online Cake Shop Portal
├── Library Management.html  # Additional Library Reference
├── index.html               # Master Portal Dashboard
├── package.json             # NPM metadata and scripts
├── server.js                # Zero-dependency Node.js HTTP Server
├── .gitignore               # Git ignore rules
└── README.md                # Project documentation
```

---

## 📄 License
Academic & Educational Use Only.
