# Covid-19 Information in Thailand

## 📚 About the Project

This project is a desktop application built using **Python** and **Tkinter** during my **first year** at university. It allows users to view COVID-19 statistics in Thailand by fetching real-time data from a public API. The data is visualized using interactive graphs, with options to select either a specific date or a range of dates.

The goal of the project was to apply API usage, data visualization, and GUI development into a functional tool with a practical purpose.

## 🛠️ Technologies Used

- **Python** – Main programming language  
- **Tkinter** – For creating the graphical user interface (GUI)  
- **Matplotlib** – For generating graphs  
- **Pandas** – For data manipulation and processing  
- **Public API** – To fetch COVID-19 data for Thailand  
- **tkcalendar** – For date selection in the UI  

## 🎯 Features

- 📅 Date picker for selecting individual or range of dates  
- 📊 Interactive graphs showing:
  - Daily new cases
  - Total confirmed cases
  - Recoveries and deaths  
- 🔄 Real-time data fetching from a COVID-19 API  
- 🧩 Responsive and user-friendly interface using Tkinter widgets  

## ⚠️ Important Notice

Due to potential changes in the public API used for fetching COVID-19 data, the program may encounter errors or fail to retrieve data if the API undergoes updates or modifications. Please be aware that this project might not work correctly if the API source is altered or discontinued.

## 🚀 How to Run

1. Make sure you have Python 3 installed.
2. Install required packages:
   ```bash
   pip install tkcalendar pandas matplotlib requests
   ```
3. Run the main Python file:
   ```
   python Covid-19_Information_in_Thailand.ipynb
   ```
4. Select a date or date range from the calendar and view the results in graph form.
   
