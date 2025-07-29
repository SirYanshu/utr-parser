🎾 UTR Tennis Match Parser
A simple web tool that converts UTR (Universal Tennis Rating) HTML files into organized CSV spreadsheets containing all your match data.
What Does This Tool Do?
The UTR Parser extracts tennis match information from UTR HTML files and converts it into a clean, organized CSV file that you can open in Excel, Google Sheets, or any spreadsheet application.

How to Use
Step 1: Get Your UTR HTML File

Go to your UTR profile on the UTR website
Navigate to your match history/results page
Save the page as an HTML file:

Chrome/Edge: Right-click → "Save as" → Choose "Webpage, Complete"
Firefox: Right-click → "Save Page As" → Choose "Web Page, complete"
Safari: File menu → "Save As" → Choose "Web Archive"



Step 2: Upload and Parse

Visit the UTR Parser website
Click the upload area or drag your HTML file onto it
Click "Parse & Download CSV"
Your CSV file will automatically download

Step 3: View Your Results
Open the downloaded CSV file in any spreadsheet application to see your organized match data.
What Information Gets Extracted?
The CSV file contains three columns:

Date: When the match was played (date and time)
Player: Your information including name, UTR rating, and set scores
Opponent: Opponent's information including name, UTR rating, and set scores

Example Output:
```
Date,Player,Opponent
"Jan 15, 2025 2:30 PM","John Smith (UTR: 8.5) [6,4,6]","Mike Johnson (UTR: 8.2) [4,6,3]"
"Jan 10, 2025 10:00 AM","John Smith (UTR: 8.5) [6,6]","Sarah Williams (UTR: 7.8) [3,4]"
```
