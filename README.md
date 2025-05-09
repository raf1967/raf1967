├── menu.py                           # System navigation (centralized)
│
├── src/
│   ├── api.py                        # API routes (Flask endpoints)
│   ├── apiManager.py                 # Loads API configuration data
│   ├── app.py                        # Main entry point for the Flask-based web application
│   ├── main.py                       # Main entry point for the application's GUI-based interface
│   └── routes.py                     # Defines the Flask blueprint routes (API endpoints and web pages)
│
├── templates/                        # Project templates
│   ├── base.html                     # Main template
│   ├── results.html                  # Match results page
│   ├── scorers.html                  # Top scorers display
│   ├── configure_template.html       # Template selection form
│   ├── api_output.html               # API-generated output
│   ├── api_selection.html            # API selection options
│   ├── areas.html                    # Football areas display
│   ├── generated_results.html        # User-generated match results
│   ├── index.html                    # Homepage overview
│   ├── json_output.html              # JSON data display
│   ├── menu.html                     # Menu page structure
│   └── table_output.html             # Table-based data visualization
│
├── PLDB/                             # Premier League DB (Automated)
│   └── create_league_table.sql
│
├── functions/                        # Project functions
│   ├── api_helpers.py                # API data retrieval
│   ├── dashboard.py                  # System monitoring
│   ├── gui.py                        # GUI logic (Tkinter-based)
│   ├── template_generator.py         # Dynamic HTML template creation
│   └── docs/                         # Functions documentation    
│
├── utils/                            # Keeps application logic clean 
├── static/                           # CSS, JavaScript, images 
├── logs/                             # Error logs and tracking


<!---
raf1967/raf1967 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
