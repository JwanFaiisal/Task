# Java Selenium Tests

This project contains automated Selenium WebDriver tests written in Java using JUnit 5.

## Project Structure

- Contains the Task classes with different test cases.

## Tests Included

1. **Navigation and Title Tests**  
   Verifies page titles and URL correctness when navigating between Google, YouTube, and LinkedIn.

2. **Page Source Validation**  
   Checks if specific keywords like "WebDriver" and "Python" exist in the page source of selenium.dev and python.org.

3. **Browser Size and Position Tests**  
   Sets browser window size and position and asserts these properties.

4. **Multiple Navigation and Verification**  
   Performs multiple navigations back and forth and asserts titles and URLs.

## Dependencies

- Selenium WebDriver  
- JUnit 5  
- ChromeDriver

## Notes

- Tests open Chrome browser and interact with live websites, so ensure you have a stable internet connection.  
- Adjust ChromeDriver path if necessary in your test setup.

---

Feel free to ask if you have any questions or need help with the tests.
