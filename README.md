# TestingHack
This repo is a collection of resources which will help you to write scripts while doing automation testing.


Write web login script using chromedriver:-
  ```
System.setProperty("webdriver.chrome.driver","<chrome exe path>");
ChromeOptions options = new ChromeOptions();
options.addArguments("user-data-dir= <full local path Google Chrome user data default folder>);

WebDriver driver = new ChromeDriver(options);
driver.get("https://mail.google.com");
```
