## What does APIWeatherapp do?
The program retrieves an API key from the weather service provider [openweathermap](https://openweathermap.org/) and fetches weather data from it's servers. 

### Package Versions Used
* requests 2.32.3
* PyQt5 5.15.11

### Installation

1. Get a free API Key at [openweathermap](https://openweathermap.org/)
  
2. Clone the repo
   ```sh
   git clone https://github.com/Aerobrid/APIWeatherapp.git
   ```

3. Build Virtual Environment

Windows Activation:
  ```sh
  venv_name/Scripts/activate
  ```
  
4. Install pip packages
   ```sh
   pip install requests
   ```

    ```sh
   pip install PyQt5
   ```
   
5. Replace your API on line 71 in `py.py', with 'REDACTED'
   ```js
   api_key = 'REDACTED';      # Before
   api_key = 'YOUR_API_KEY';  # After
   ```
6. Change git remote url to avoid accidental pushes to base project
   ```sh
   git remote set-url origin github_username/repo_name
   git remote -v # confirm the changes
   ```
