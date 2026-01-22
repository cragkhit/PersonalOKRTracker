# PersonalOKRTracker

## Financial Study Tracker

A simple web application to track your financial study sessions with date/time and duration.

### Features

- ✅ Add study sessions with date/time and duration
- ✅ Track total sessions, hours, and average duration
- ✅ View all study sessions in a clean interface
- ✅ Export data to JSON file
- ✅ Import data from JSON file
- ✅ Delete individual sessions
- ✅ Clear all data

### How to Use

1. **Open the application**: Simply open `financial-study-tracker.html` in any modern web browser
2. **Add a study session**: 
   - Select date and time (defaults to current time)
   - Enter duration in minutes
   - Optionally add notes about what you studied
   - Click "Add Session"
3. **View your sessions**: All sessions are displayed below the form, sorted by date
4. **Export your data**: Click "Export JSON" to download your data as a JSON file
5. **Import data**: Click "Import JSON" to load previously exported data
6. **Delete sessions**: Click the "Delete" button on any session to remove it

### Data Storage

- Data is stored locally in your browser using localStorage
- Export your data regularly to keep backups
- The JSON file can be easily edited or processed with other tools

### No Server Required

This is a fully client-side application - no server or backend needed. Just open the HTML file and start tracking!