# SPICE-IN-LENS
<img src="https://img.shields.io/badge/License-MIT-blue.svg">

[![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)]()
[![Selenium](https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white)]()

This project contains automated tests created using Selenium IDE and Command Line Runner for downloading the pdf from the website of [IFSCA](https://www.ifsca.gov.in/)

## Requirements

- Good Internet Connection
- For Command Line Runner to work
    - Node
    - NPM

## Install Selenium IDE

  https://www.selenium.dev/selenium-ide/

## Install Selenium Side Runner

```bash
  npm install -g selenium-side-runner
```

## Install ChromeDriver

```bash
  npm install -g chromedriver
```

## Testing on Selenium IDE

- Launch your browser (I did it on Chrome) and open Selenium IDE extension icon from the toolbar.
- After downloading the ```.side``` file Click on Open an Existing Project from the popup.
- Inport the downloaded file in the IDE.
- Click on ```Run Current Test``` at the top panel of the IDE.
- Log present at the bottom of the IDE will show each step getting executed.

## Testing from Command Line using Selenium Side Runner

-Open Command Prompt in your system
- After all installations are properly completed, hit the below mentioned command in your cmd accordingly

```bash
selenium-side-runner /path/to/your-project.side
```
In my case it was

```bash
selenium-side-runner "C:\Users\shard\Downloads\ifscasite.side"
```
