
![](https://img.shields.io/badge/Excitement-High-red)
![](https://img.shields.io/badge/Maintained-Yes-indigo)
![](https://img.shields.io/badge/Pull_Requests-Accepting-yellow)
![](https://img.shields.io/github/forks/J-AlexandreMurray/BookManagementSys)
![](https://img.shields.io/github/contributors/J-AlexandreMurray/BookManagementSys)
![](https://img.shields.io/github/issues/J-AlexandreMurray/BookManagementSys)
![](https://img.shields.io/github/stars/J-AlexandreMurray/BookManagementSys)

![](https://img.shields.io/badge/Contributions-Accepting-pink)
![](https://img.shields.io/github/license/J-AlexandreMurray/BookManagementSys)
<br>


<!-- PROJECT LOGO -->

<br />
<p align="center">
  <a href="https://github.com/J-AlexandreMurray/BookManagementSys">
    <img src="https://github.com/J-AlexandreMurray/BookManagementSys/blob/main/BMSimages/digBooks.jpg" alt="Logo" width="160" height="100">
  </a>

  <h3 align="center">Book Management System</h3>

  <p align="center">
    System designed to keep track of book item inventory. 
    <br />
    <a href="https://github.com/J-AlexandreMurray/BookManagementSys"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/J-AlexandreMurray/BookManagementSys/issues">Report Bug</a>
    ·
    <a href="https://github.com/J-AlexandreMurray/BookManagementSys/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#live-demo">Live Demo</a></li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

![Product Name Screen Shot](https://github.com/J-AlexandreMurray/BookManagementSys/blob/main/BMSimages/MenuSelec.PNG)


This project is a management system designed for me to keep track of general information about a book within an inventory space. It is meant for anyone who wishes to keep a track of the books they are looking for, purchased, or already collected. As a soon-to-be self published short read author, I would like to have inventory on a collection of my own books as well as others in my family and some I come across in life. I plan to build on this project even more and connect it to a database as well as my own indie author website.  

### Built With

* [C++]()
* [Visual Studio Code]()


<!-- LIVE DEMO -->

![Product Name Screen Shot](https://github.com/J-AlexandreMurray/BookManagementSys/blob/main/BMSimages/MenuSelec1.PNG)
![Product Name Screen Shot](https://github.com/J-AlexandreMurray/BookManagementSys/blob/main/BMSimages/MenuSelec3.PNG)

## Live Demo

![Product Name Screen Shot](https://github.com/J-AlexandreMurray/BookManagementSys/blob/main/BMSimages/BMSgif.gif)
[Live Demo Link](https://github.com/J-AlexandreMurray/BookManagementSys/blob/main/BMSimages/BMSgif.gif)

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/J-AlexandreMurray/BookManagementSys.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/J-AlexandreMurray/BookManagementSys/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

J. Alexandre Murray - [@ProjectZilart](https://twitter.com/ProjectZilart)

Project Link: [https://github.com/J-AlexandreMurray/BookManagementSys](https://github.com/J-AlexandreMurray/BookManagementSys)

‐-------------------------------------------------------------------------------------
# This project will be heavily updated soon and become what is shown below...
‐-------------------------------------------------------------------------------------

# 📚 BookVault: Book Management Micro SaaS

BookVault is a **mobile-first** Flutter-based application designed for **readers** and **book collectors** to track, organize, and interact with their personal libraries.

## 🚀 Project Overview

BookVault helps users:
- Catalog and manage their **book collections** with detailed metadata.
- Track **reading progress** and personal notes.
- Organize by **genre, author, and custom categories**.
- Share book recommendations and wishlists.
- Export and back up book data for easy migration.

## 📱 Key Features (MVP)

- **Book Cataloging:** Add, edit, and track books with key information (title, author, genre, ISBN, etc.).
- **Reading Progress:** Log reading status (To-Read, In Progress, Completed).
- **Custom Tags & Categories:** Organize books with user-defined tags and categories.
- **Data Export/Import:** Export collections to JSON/CSV and import from similar formats.
- **Wishlist Management:** Create and manage a list of books to acquire.

## 🛠️ Tech Stack

- **Frontend:** Flutter (Dart)
- **Backend:** Local storage (Hive/SQLite for MVP)
- **State Management:** Riverpod (TBD)
- **Deployment:** Android, iOS, Web (later stage)

## 📂 Project Structure

```
bookvault/
├── lib/
│    ├── main.dart          # App entry point
│    ├── screens/           # UI screens
│    │      ├── home.dart
│    │      ├── book_list.dart
│    │      └── add_book.dart
│    ├── models/            # Data models
│    │      ├── book.dart
│    │      └── category.dart
│    ├── services/          # Data handling (Hive/SQLite)
│    └── providers/         # State management
│
├── test/                   # Unit and widget tests
└── README.md
```

## 🧑‍💻 Setup Instructions

1. **Clone the Repository:**

```
git clone <repo_url>
cd bookvault
```

2. **Install Flutter Dependencies:**

```
flutter pub get
```

3. **Run the App:**

```
flutter run
```

## 📈 Roadmap

### Week 1:
- Set up **Flutter** environment and project scaffold.
- Implement basic **book** CRUD (Create, Read, Update, Delete).

### Week 2:
- Build **reading progress** tracking and category management.
- Add **local storage** using Hive or SQLite.

### Week 3:
- Implement **wishlist** and user-defined tags.
- Introduce **data export** (JSON/CSV) functionality.

### Week 4:
- Implement **import** from JSON/CSV.
- Perform UI refinements and initial tests.

### Week 5:
- Finalize testing and bug fixes.
- Prepare for **GitHub release** and documentation.

## 📣 Contribution Guidelines

1. Fork the repository and create a feature branch.
2. Submit pull requests with clear commit messages.
3. Ensure code is formatted and tested.

## 📜 License

This project is licensed under the **MIT License**.

## 📧 Contact

For questions or contributions, open an **issue** or **pull request** on GitHub.



