# 🎓 UIU Exam Routine Schedule

A fast, beautiful, and completely client-side exam routine planner for United International University (UIU) students. Say goodbye to manually searching through long scattered spreadsheets!

## 🚀 Live Demo
**[Try it out here!](https://labib1610.github.io/uiu_routine_schedule/)**

## ✨ Features
- **Smart Course Search**: Type-to-search input to quickly find your specific enrolled courses.
- **Section Filtering**: Auto-populates the exact available sections based strictly on your selected course.
- **Beautiful UI**: Clean, polished, and responsive interface built entirely with Tailwind CSS.
- **Fast & Private**: Parses the official Excel (`.xlsx`) routine locally in your browser using SheetJS. No database or backend required!
- **Error-Free**: Fallback capabilities included in case the browser blocks auto-fetching.

## 🛠️ How to setup for next Trimester
1. Download the new exam routine `.xlsx` file provided by the university.
2. Rename the file to exactly `routine.xlsx`.
3. Replace the existing `routine.xlsx` in this repository with your new file.
4. Push to the `main` branch. The app will automatically sync and read the new schedule!

## 👨‍💻 Tech Stack
- HTML5 & JavaScript (Vanilla)
- [Tailwind CSS](https://tailwindcss.com/) (Styling)
- [SheetJS](https://sheetjs.com/) (Excel parsing in the browser)