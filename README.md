# Labor Cost Management System (Yevmiye)

This project is a data management and automation system designed to digitize the tracking of seasonal workers, daily wages, and labor costs in agricultural enterprises or general business sectors.

## Project Objective
The goal is to transition from traditional paper-based record-keeping to a digital environment. This minimizes human error, enables historical reporting, and provides transparent management of operational costs.

## Tech Stack
- **Language:** Dart
- **Database:** SQLite
- **Libraries:** Flutter, PWA (Progressive Web App)

## Key Features
- **Worker Registration:** Storing contact details and specializations of employees.
- **Daily Entry:** Logging which worker worked on which day and in which specific field/task.
- **Automated Cost Calculation:** Calculation of wages based on predefined daily rates.
- **Reporting:** Analysis of total labor costs within specific date ranges.

## Screenshots

## 🏗️ Installation & Usage
To run this project locally, ensure you have the [Flutter SDK](https://docs.flutter.dev/get-started/install) and [python3] (https://www.python.org/downloads/) installed.

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/cemir200101-source/yevmiye.git](https://github.com/cemir200101-source/yevmiye.git)
   cd yevmiye
   
2. **Install dependencies:**
   flutter pub get

3. **Build the Web version:**
   flutter build web --release

4. **Serve the app locally:**
You can use Python's built-in server to view the PWA:
   cd build/web
   python -m http.server 8000
   Then, open http://localhost:8000 in your browser.
