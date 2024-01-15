# Selenium Practical - Flight Reservation

This repository contains a Selenium Java program (`Example2.java`) for automating a flight reservation process. The program utilizes the ChromeDriver located in the `drivers` folder.

## Article on Medium

I've also authored a comprehensive Medium article detailing this setup process. If you prefer a more in-depth guide with explanations and visuals, check out the article [here](https://medium.com/@AshiBandara/setting-up-selenium-testing-environment-on-macos-with-maven-and-intellij-479b4c43297a).

## System Information
>**Operating System:** MacOS Sonoma version 14.2.1
>
>**IDE Version:** IntelliJ IDEA Ultimate 2023.3

## Features
- Navigates to the demo website (http://demo.guru99.com/test/newtours/).
- Maximizes the browser window.
- Inputs username and password for login.
- Navigates to the flight reservation page (https://demo.guru99.com/test/newtours/reservation.php).
- Sets flight details, such as one-way trip, passenger count, departing and arriving airports, departing and arriving months, service class, and airline.
- Prints the list of available airlines.
- Finds flights based on the specified criteria.

## Setup (MacOS)

Ensure you have the ChromeDriver installed at the correct path as specified in the code. Follow these steps:

1. **Download ChromeDriver:**
   - Visit the [ChromeDriver Downloads](https://sites.google.com/chromium.org/driver/) page.
   - Download the version compatible with your Chrome browser.

2. **Move ChromeDriver to `drivers` folder:**
   - Create a `drivers` folder in the project directory if not already present.
   - Move the downloaded ChromeDriver executable to this `drivers` folder.

3. **Update ChromeDriver Path in the Code:**
   - Open `Example2.java` in your preferred text editor.
   - Locate the following line and replace `/absolute/path/to/chromedriver` with the absolute path to your ChromeDriver executable.
     ```java
     System.setProperty("webdriver.chrome.driver", "/absolute/path/to/chromedriver");
     ```

## Usage (IntelliJ IDEA - MacOS)
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/your-repository.git
   ```

2. **Open Project in IntelliJ IDEA:**
   - Open IntelliJ IDEA Ultimate version 2023.3.
   - Click on `File` -> `Open` and navigate to the cloned repository.

3. **Configure Project:**
   - In IntelliJ IDEA, go to `Run` -> `Edit Configurations`.
   - Add a new configuration for `Application`.
   - Set the `Main class` to `org.example.Example2`.

4. **Run the Selenium Script:**
   - Click the green `Run` button or press `Shift + F10` to execute the Selenium script.

Feel free to modify the code according to your testing requirements. 
