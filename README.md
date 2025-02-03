# sauce_demo_tests

## Setup & Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/yourrepo.git
    cd yourrepo
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Ensure that you have the required WebDriver installed (ChromeDriver for Chrome, GeckoDriver for Firefox, etc.).

## Running the Tests

1. To run the tests:
    ```bash
    pytest
    ```

2. To generate an HTML report:
    ```bash
    pytest --html=report.html
    ```

3. To run tests in parallel:
    ```bash
    pytest -n 4
    ```

## Assumptions and Constraints

- Used Chrome WebDriver (you may switch to another browser like Firefox by updating the driver setup).
- Tests are written for basic user interactions with the Sauce Demo site.
- Pytest is the test framework, and Selenium is used for UI automation.
