
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/pjsimba16/TrackingAsia-EAI">
    <img src="https://asianbondsonline.adb.org/macroeconomictracker/images/field-with-building-background-trackingasia2.jpg" alt="Logo">
  </a>

  <h3 align="center">Economic Activity Index Tracking Tool</h3>

  <p align="center">
    Track business cycle trends using your own data.
    <br />
    <a href="https://github.com/pjsimba16/TrackingAsia-EAI"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/README.md#executable-usage">View Demo</a>
    ·
    <a href="https://github.com/pjsimba16/TrackingAsia-EAI/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/pjsimba16/TrackingAsia-EAI/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

## Github Directory

- Resources: ReadMe resource files.
- country_samples: Sample, country specific data for EAI program testing.
- logos: TrackingAsia and CEIC logo icons.
- scripts: Python scripts for CEIC extraction and EAI modelling programs.
- CEIC_extraction_template.xlsx: Template for extracting data from CEIC using the PyCEIC package.
- EAI_excel_template.xlsx: Template for adding data.
- EAI_script.py: Current Python script used for the executable. Can be ran using CLI.
- TrackingAsia_code_overview.pptx: Quick rundown of the code behind the EAI program.
- installation_pre_read.ipynb: Installation guide.
- requirements.txt: Contains required packages to install before running the code for the first time.

---

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#python-and-ide-installation">Python and IDE Installation</a></li>
        <li><a href="#pysimplegui-sign-up">PySimpleGUI Sign Up</a></li>
        <li><a href="#download-executable">Download Executable</a></li>
      </ul>
    </li>
    <li><a href="#executable-usage">Executable Usage</a></li>
    <li><a href="#ceic-data-extraction-tool">CEIC Data Extraction Tool</a></li>
    <li>
      <a href="#python-and-command-line-interface">Python and Command Line Interface</a>
      <ul>
        <li><a href="#library-installation">Library Installation</a></li>
        <li><a href="#cli-usage">CLI Usage</a></li>
      </ul>
    </li>
    <li><a href="#final-outputs">Final Outputs</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

TrackingAsia was developed by researchers at the Asian Development Bank. The purpose in designing the framework was to complement toolkits of governments, businesses, investors, and analysts for monitoring current economic conditions and their likely direction.

The business cycle, represented by fluctuations in real GDP per capita around a long-term estimated trend, can gauge the state of an economy. But data on real GDP are often not timely and hence the grasp of overall cyclical conditions is not as current as required for real-time decision making. Even though GDP of the previous quarter is released with fairly long lags in many Asian economies, other statistical indicators are available every month that contain an abundance of information about activity in various sectors and the aggregate economy.

The TrackingAsia project designed the Economic Activity Index (EAI) as an indicator to capture economic activity so that business cycles can be tracked monthly. The predicted metric draws data series for each economy from six categories and sectors—consumption, investment, trade, government, financial, and the external sector—and identifies the broad groups that are driving economic expansions and downturns, historically and currently.

The goal of this project was to allow governments, businesses, investors and analysts to generate EAI figures for their respective economies using their own data. To do this, we built a Python based executable that allows users to interact with a simple graphical user interface (GUI) when generating EAI analyses. With this tool on hand, non-programmers are able to utilize the machine learning framework developed by ADB researchers for economic cycle tracking on the TrackingAsia website using various models on their personalized datasets, allowing for a more simple and flexible business cycle tracking tool.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

[![Python][python.org]][Python-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

1. Install Python and Visual Studio Code
2. Install and Register to PySimpleGUI
3. Download the Executable Program

<details>
  <summary>Python and IDE Installation</summary>

  ### Python and IDE Installation

  A Quick Guide for Installing Python on Common Operating Systems

  #### Windows ![Windows](https://github.com/PackeTsar/Install-Python/raw/master/img/windows_65.png)
  1. Visit the official download page for Python on the Windows operating system: https://www.python.org/downloads/windows/ and locate a reliable version of Python 3, preferably the Python 3.11.8 version
  2. Choose the correct link for your device from the options provided: preferably Windows installer (64-bit) and proceed to download the executable file.
  3. Once you have downloaded the installer, open the .exe file, such as python-3.11.8-amd64.exe, by double-clicking it to launch the Python installer.
    - Choose the option to Install the launcher for all users by checking the corresponding checkbox, so that all users of the computer can access the Python launcher application.
    - Enable users to run Python from the command line by checking the Add python.exe to PATH checkbox.

  <p align="center"><img src="https://media.geeksforgeeks.org/wp-content/uploads/20230503122459/p1.jpg" width="" height=""></p>

  4. After Clicking the Install Now Button the setup will start installing Python on your Windows system.
  5. To verify successful installation, access the command line, click on the Start menu and type “cmd” in the search bar. Then click on Command Prompt. Type “python --version” on the command line.
  
  <p align="center"><img src="https://media.geeksforgeeks.org/wp-content/uploads/20230503123238/p4.png" width="" height=""></p>

  [Reference: More Information](https://www.geeksforgeeks.org/how-to-install-python-on-windows/?ref=ml_lbp)

  #### MacOS ![MacOS](https://github.com/PackeTsar/Install-Python/raw/master/img/apple_65.png)

  1. Download an installer package from https://www.python.org/downloads/; it detects your operating system automatically and shows a big button for downloading the latest version of Python installer on your Mac. If it doesn't, click the macOS link and choose the latest Python release.
  2. Once the download is complete, double-click the package to start installing Python. The installer will walk you through a wizard to complete the installation, and in most cases, the default settings work well, so install it like the other applications on macOS. You may also have to enter your Mac password to let it know that you agree with installing Python. NOTE If you're using Apple M1 Mac, you need to install Rosetta. Rosetta enables Intel-based features to run on Apple silicon Macs.

  <p align="center"><img src="https://www.dataquest.io/wp-content/uploads/2022/01/installing-python-on-mac-screenshot-r.webp" width="" height=""></p>

  3. When the installation completes, it will open up the Python folder.

  <p align="center"><img src="https://www.dataquest.io/wp-content/uploads/2022/01/installing-python-on-mac-screenshot-q.webp" width="" height=""></p>

  4. Let’s verify that the latest version of Python and IDLE installed correctly. To do that, double-click IDLE, which is the integrated development environment shipped with Python. If everything works correctly, IDLE shows the Python shell as follows

  <p align="center"><img src="https://www.dataquest.io/wp-content/uploads/2022/01/installing-python-on-mac-screenshot-p.webp" width="" height=""></p>

  [Reference: More Information](https://www.dataquest.io/blog/installing-python-on-mac/)  

</details>
<details>
  <summary>Visual Studio Code</summary>

  #### Visual Studio Code <img src="https://code.visualstudio.com/assets/images/code-stable.png" width="" height="70">

  Visual Studio Code is a free coding editor that helps you start coding quickly. Use it to code in any programming language, without switching editors. Visual Studio Code has support for many languages, including Python, Java, C++, JavaScript, and more. [Learn more](https://code.visualstudio.com/)

  #### For Windows

  1. Download the Visual Studio Code installer for Windows: https://code.visualstudio.com/docs?dv=win
  2. Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe). This will only take a minute.
  
  #### For MacOS

  1. Download Visual Studio Code for macOS: https://code.visualstudio.com/docs?dv=osx
  2. Open the browser's download list and locate the downloaded app or archive.
  3. If archive, extract the archive contents. Use double-click for some browsers or select the 'magnifying glass' icon with Safari.
  4. Drag Visual Studio Code.app to the Applications folder, making it available in the macOS Launchpad.
  <p align="center"><img src="https://www.dataquest.io/wp-content/uploads/2022/01/installing-python-on-mac-screenshot-k.webp" width="" height=""></p> 
  5. Open VS Code from the Applications folder, by double clicking the icon.


  #### Video Instructions

  The following video will run through the following:
  - Download and install VS Code.
  - Create a new file.
  - See an overview of the user interface.
  - Install support for your favorite programming language.
  - Change your keyboard shortcuts and easily migrate from other editors using keymap extensions.
  - Customize your editor with themes.
  - Explore VS Code features in the Interactive Editor Playground.

  [![IMAGE ALT TEXT HERE](https://i3.ytimg.com/vi/ITxcbrfEcIY/maxresdefault.jpg)](https://www.youtube.com/watch?v=ITxcbrfEcIY&ab_channel=VisualStudioCode)
</details>
<details>
  <summary>PySimpleGUI</summary>

  ### PySimpleGUI Sign Up

  PySimpleGUI is a Python library that simplifies the creation of graphical user interfaces (GUIs).

  1. Register as a hobbyist in PySimpleGUI by selecting “Get Started as Hobbyist”: https://www.pysimplegui.com/pricing
  2. Fill in details to create an account as a hobbyist and confirm all terms and conditions (Note: GitHub ID is optional)
  3. Enter verification code sent to registered email
  4. Copy the license key provided
  5. The first time you run PySimpleGUI you will see a series of windows beginning with this Welcome Window. Check the terms and click OK.

  <p align="center"><img src="https://docs.pysimplegui.com/en/latest/documentation/installing_licensing/install1.jpg" width="" height=""></p> 

  6. The final step is to paste your license key on the panel.

  <p align="center"><img src="https://docs.pysimplegui.com/en/latest/documentation/installing_licensing/install2.jpg" width="" height=""></p> 

</details>

<details>
  <summary>Download Executable</summary>

  ### Download Executable
  You can download the executable program, together with other relevant files in this [current version folder.](https://drive.google.com/drive/folders/1YlF_lXOGKMl3tJViK1rGmYh69GXVGhJV?usp=drive_link) The files in this folder will always contain the latest versions of each. If you would like to see older versions of each file, you can find them in the [version history folder.](https://drive.google.com/drive/folders/1kxTxQAlclVArnTpcQ2577LFQrl7fP3Pb?usp=drive_link)

  **Directory summary:**
  - **EAI_excel_template.xlsx** -> Template file to be used when adding data to be included in the EAI prediction and visualization generation.
  - **CEIC_extraction_template.xlsx** -> CEIC extraction template for automatic extraction program.
  - **CEIC_extraction_program.exe** -> CEIC extraction executable program.
  - **EAI_program_windows.exe** -> Final executable file for Windows.
  - **EAI_GUI_MacOS.dmg** -> Final executable file for MacOS.
  
</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Executable Usage

<details>
  <summary>Executable Usage Guide</summary>

  ### Home Screen

  The home screen contains information that can also be found on the [TrackingAsia website](https://asianbondsonline.adb.org/macroeconomictracker/index.php), where you can also find the updated EAI dashboards for selected Asian economies.

  <p align="left"><img src="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_images/home_page.JPG" width="" height="350"></p></p>

  ### Add Excel Template

  The excel template where you've added your indicator and GDP level data series should be referenced to using the browse button in this screen. A quick rundown of the sheets in the excel template can be found in the section below.

  <p align="left"><img src="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_images/add_excel.JPG" width="" height="150"></p>

  ### Excel Template

  You may add the data series that you would like to include in the EAI machine learning analysis within the excel template. Just ensure that the filename contains 'EAI_excel_template' in it. While the template can be filled in manually, you may also utilize the automatic data extraction tool that we created, if you have access to CEIC's Python API (PyCEIC).

  The excel template contains 5 sheets:
  - Instructions: Guide for accepted values in each column for each sheet.
  - InfoQ: Information for each data series of quarterly frequency.
  - QuarterlyData: Where you can input the series name and datapoints of quarterly frequency.
  - InfoM: Information for each data series of monthly frequency.
  - MonthData: Where you can input the series name and datapoints of monthly frequency.

  Reminders: 
  - The current version of the program is optimized to run with quarterly GDP data as the target variable and monthly indicators for other data series. You may encounter errors if you use any other frequency data series.
  - Ensure that data series titles are uniform across data and info sheets.

  ### Select Indicators

  The indicator selection screen summarizes all the indicators found in the excel file, separated into one of six economic sectors, together with the target variable. You may also inspect the data or reconfigure the preprocessing steps for each data series by clicking on the inspect data or edit processing buttons respectively.

  <p align="left"><img src="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_images/indicator_selector.JPG" width="" height="350"></p>

  ### Inspect Data

  This screen will show you a line chart with the date on the x axis and a chosen data series on the y axis. The table on the right contains summary statistics for the chosen data series. You can choose which data series and frequency to inspect using the dropdowns on the left. Morever, you may choose preprocessing steps using the checkboxes and inspect what the data will look like post processing by clicking the inspect processed data button. You can also save the chart or underlying data using the save buttons below the chart.

  <p align="left"><img src="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_images/inspect_data.JPG" width="" height="350"></p>

  ### Inspect Processed Data

  This screen shows you a line chart with the date on the x axis and a chosen data series on the y axis for the processed data. You will find the selected processing steps listed on the right, below the summary statistics. Similarly, you can save the chart or underlying data using the save buttons below the chart.

  <p align="left"><img src="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_images/inspect_processed_data.JPG" width="" height="350"></p>

  ### Edit Processing

  In this screen, you can change the processing steps associated with each data series, as well as choose whether or not to include each variable in the modelling. If you'd like to, you may also save the settings that you change directly into the original excel file.

  <p align="left"><img src="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_images/edit_processing_2.JPG" width="" height="200"></p>

  ### Select Models

  In this screen, you can determine the starting and ending dates to use for the initial model training process. If left blank, the models will initially be trained on the earliest 50% of the dataset. Below that, you need to choose a location that you'd like all the outputs to be saved in. We suggest that you create a new folder for each particular modelling run. Lastly, use the checkboxes to select the models you'd like to get outputs from using your dataset.

  <p align="left"><img src="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_images/select_models.JPG" width="" height="350"></p>

  ### Running Operations Log

  The log screen will show you the progress of the entire process. Don't worry if windows informs you that the screen is not responding, this is a bug that occurs when functions run for a long time; just wait for the screen to end. This will be addressed in future versions using multithreading.

  <p align="left"><img src="https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_images/running_operations.JPG" width="" height="250"></p>

</details>
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## CEIC Data Extraction Tool

<details>
  <summary>CEIC Data Extraction Tool</summary>

If you have access to the CEIC Python API, you may use our custom data extraction tool.

1. Login to [CEIC](https://insights.ceicdata.com/login) and use their interface to find and list down data series IDs that you would like to use in your analysis.
2. Input the data IDs in the CEIC_extraction_template.xlsx file and select economic categories for each one.
3. Run the CEIC_extraction_program.exe executable file.
    - Login to CEIC.
    - Choose the extraction template and the location where you would like to place the final file.
    - Choose a name for the file. This filename will appear at the end of 'EAI_excel_template_' (eg. if you choose filename to be test_v1, the file EAI_excel_template_test_v1.xlsx will be saved in your chosen folder.)
4. The final excel file will be ready to be used in the main executable file.

Reminder: By default, each data series will have pre-selected preprocessing steps including normalization and YoY growth calculation, you may change this on the generated file later.

</details> 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Python and Command Line Interface

<details>
  <summary>Library Installation and CLI Usage</summary>

  The EAI program executable was built to include all relevent packages, including Python. However, if the executable doesn't run on your device, you can still run the program using Python and the command line interface (CLI). 

  1. Open your file explorer to the location where you saved the EAI_script.py file.
  2. Click on the filepath on the top of the screen, type 'cmd' and press enter. This should open a terminal screen inside your chosen directory.
  3. Ensure all relevant dependencies are installed before running the program. If dependencies are not yet installed, run the following:
  ```
  pip install -r requirements.txt
  ```
  1. Once dependencies are installed; run the following line to run the script.
  ```
  python EAI_script.py
  ```
</details>   

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Final Outputs

<details>
  <summary>Output Guide</summary>

  ### Summary of output files to expect inside output folder

  - For each model chosen:
    - Folder named after the model
      - [data.xlsx](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_files/data.xlsx): contains all the raw and calculated data for this model, including EAI predictions monthly and quarterly.
      - [EAI_dashboard.pdf](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_files/EAI_dashboard.pdf): contains component charts to breakdown EAI based on economic sector importance, and a business cycle chart showing a comparison between predicted EAI and real GDP growth gap values.
    - [EAI_dial_charts.pdf](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_files/EAI_dial_charts.pdf): contains dial charts for EAI, GDP growth gap and each economic sector for the past 3 years.
  - [EAI_predictions_comparison.pdf](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_files/EAI_predictions_comparison.pdf): contains a line chart comparing the performance of each model when predicting EAI against real GDP growth gap, together with bar charts comparing metrics (R2, MAE, RMSE).
  - [ml_error_metrics.csv](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Resources/demo_files/ml_error_metrics.csv): metrics data.

  You may click on any of the files above to see a sample version.


</details>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Build all required files.
- [x] Build executables for MacOS and Windows.
- [x] GUI for automatic data extraction from CEIC into EAI template for modelling
- [ ] Add screen resolution window resizing support
- [ ] Expand elements when resizing windows.
- [ ] Incorporate multithreading to avoid program not running errors.
- [ ] Add functionality for annual data.

See the [open issues](https://github.com/pjsimba16/TrackingAsia-EAI/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/NewFeature`)
3. Commit your Changes (`git commit -m 'Add some NewFeature'`)
4. Push to the Branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact Developers

Patrick Jaime A. Simba - [LinkedIn](https://www.linkedin.com/in/patrick-jaime-simba/) - psimba.consultant@adb.org

Sharyl Rose T. Sy - [LinkedIn](https://ph.linkedin.com/in/sharylsy) - srsy.consultant@adb.org


Project Link: [https://github.com/pjsimba16/TrackingAsia-EAI](https://github.com/pjsimba16/TrackingAsia-EAI)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/pjsimba16/TrackingAsia-EAI.svg?style=for-the-badge
[contributors-url]: https://github.com/pjsimba16/TrackingAsia-EAI/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/pjsimba16/TrackingAsia-EAI.svg?style=for-the-badge
[forks-url]: https://github.com/pjsimba16/TrackingAsia-EAI/network/members
[stars-shield]: https://img.shields.io/github/stars/pjsimba16/TrackingAsia-EAI.svg?style=for-the-badge
[stars-url]: https://github.com/pjsimba16/TrackingAsia-EAI/stargazers
[issues-shield]: https://img.shields.io/github/issues/pjsimba16/TrackingAsia-EAI.svg?style=for-the-badge
[issues-url]: https://github.com/pjsimba16/TrackingAsia-EAI/issues
[license-shield]: https://img.shields.io/github/license/pjsimba16/TrackingAsia-EAI.svg?style=for-the-badge
[license-url]: https://github.com/pjsimba16/TrackingAsia-EAI/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/patrick-jaime-simba/
[product-screenshot]: images/screenshot.png
[Python.org]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[Python-url]: https://www.python.org/
