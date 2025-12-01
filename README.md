# 📰 PaperTrail Kiosk

A lightweight, single-file web application designed to provide instant access to daily ePaper editions of major Indian newspapers. Built specifically with a focus on **Amravati** and **Maharashtra** regional news.

## 🚀 Live Demo

[**Click here to view the Live App**](https://papertrail-kiosk.netlify.app/) 

## ✨ Features

* **Zero-Dependency Architecture:** The entire app lives in a single `index.html` file. No Node.js, build steps, or backend required.
* **Smart Filtering:** Instantly filter newspapers by **District** (e.g., Amravati, Nagpur) or **Language** (Marathi, Hindi, English).
* **Direct ePaper Access:** Prioritizes direct links to digital editions rather than generic homepages.
* **Search Fallback:** Automatically generates precision search queries for smaller local papers that lack stable permanent URLs.
* **Responsive Design:** Fully optimized for mobile devices using Tailwind CSS.

## 🛠️ Technology Stack

This project uses a "No-Build" React approach:

* **HTML5:** Semantic structure.
* **React (via CDN):** For state management and UI rendering.
* **Tailwind CSS (via CDN):** For styling and responsiveness.
* **Babel (via CDN):** To compile JSX in the browser on the fly.

## 📂 Project Structure

```text
/
└── index.html   # The entire application logic, styles, and data
└── README.md    # Project documentation
```
## 🚀 How to Run Locally

1. Clone this repository or download the ZIP.
2. Open the folder.
3. Double-click `index.html`.
4. The app will launch instantly in your default browser.

## 📰 Supported Publications

### Marathi
* Lokmat
* Sakal
* Deshonnati
* Loksatta
* Amravati Mandal
* Vidarbha Matadar
* *And local papers like Dainik Lokpath & Pratidin Akhabar*

### Hindi
* Dainik Bhaskar
* Navbharat
* Lokmat Samachar
* Hindustan
* Amar Ujala

### English
* The Hindu
* The Indian Express
* Times of India
* NYT / BBC / Guardian (International)

## 🤝 Contributing

1. Fork the repository.
2. Open `index.html`.
3. Add new newspapers to the `NEWSPAPERS` constant array at the top of the script.
4. Submit a Pull Request!

## ⚠️ Disclaimer

This application is a directory/aggregator. It does not host any news content. All links redirect users to the official websites or ePaper portals of the respective publishers.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
