# EMCICT311 - Student Grade Calculator

## Project Overview
The Student Grade Calculator is a web application built for EMCICT311. 
It helps automate the process of calculating student results. Users can enter 3 assessment scores and the system will automatically compute the Total, Average, Grade, and Pass/Fail status. All records are saved in the browser.

## Key Features
- **Student Management**: Add and delete student records
- **Automated Calculation**: Calculates Total, Average, and Grade instantly
- **Data Validation**: Prevents invalid inputs like empty fields and scores outside 0-100
- **Persistent Storage**: Student data is saved using browser localStorage
- **Responsive Design**: Works well on both desktop and mobile devices

## Technologies Used
- **HTML5** - Page structure
- **CSS3** - Styling and layout
- **JavaScript ES6** - Application logic, OOP, and DOM manipulation
- **localStorage** - Client-side data storage
- **GitHub Pages** - Project deployment

## How to Run the Application
1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Enter student name and 3 scores between 0-100
4. Click "Calculate & Save" to view results

## Grading System
| Score Range | Grade | Status |
|-------------|-------|--------|
| 70 - 100    | A     | Pass   |
| 60 - 69     | B     | Pass   |
| 50 - 59     | C     | Pass   |
| 45 - 49     | D     | Fail   |
| 40 - 44     | E     | Fail   |
| 0 - 39      | F     | Fail   |

## Author
**Name:** ONYEAKA VICTORY EKENE  
**Matric No:** 2023030211276  
**Course:** EMCICT311 - Web Development
