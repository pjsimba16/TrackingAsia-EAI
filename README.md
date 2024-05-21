[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

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
    <a href="https://github.com/pjsimba16/TrackingAsia-EAI">View Demo</a>
    ·
    <a href="https://github.com/pjsimba16/TrackingAsia-EAI/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/pjsimba16/TrackingAsia-EAI/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

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

### Python and IDE Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### PySimpleGUI Sign Up

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/your_username_/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'ENTER YOUR API';
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Download Executable

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Executable Usage

### Home Screen
![Home Screen](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/home_page.JPG)

### Add Excel Template
![Add Excel](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/add_excel.JPG)

### Excel Template

### Select Indicators
![Select Indicators](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/indicator_selector.JPG)

### Inspect Data
![Inspect Data](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/inspect_data.JPG)

### Inspect Processed Data
![Inspect Processed Data](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/inspect_processed_data.JPG)

### Edit Processing
![Edit Processing 1](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/edit_processing_1.JPG)
![Edit Processing 2](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/edit_processing_2.JPG)

### Select Models
![Select Models](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/select_models.JPG)

### Running Operations Log
![Running Operations](https://github.com/pjsimba16/TrackingAsia-EAI/blob/main/Demo/running_operations.JPG)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Python and Command Line Interface

### Library Installation

This is an example of how to list things you need to use the software and how to install them.

* Other dependencies
  ```sh
  npm install npm@latest -g
  ```

<!-- USAGE EXAMPLES -->
### CLI Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Final Outputs

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Add Changelog
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" document to easily copy & paste sections of the readme
- [ ] Multi-language Support
    - [ ] Chinese
    - [ ] Spanish

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [Img Shields](https://shields.io)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

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
