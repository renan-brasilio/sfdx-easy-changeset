<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/renan-brasilio/sfdx-easy-changeset">
    <img src="https://avatars.githubusercontent.com/u/60192002?s=200&v=4" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">SFDX ORG Easy Changeset/Package Downloader</h3>

  <p align="center">
    Using SFDX + Shell/Bash Scripts, Retrieve a Changeset/Package from Salesforce based on the Origin ORG and the Changeset/Package Name
    <br />
    <br />
    <br />
    <a href="https://github.com/renan-brasilio/sfdx-easy-changeset/issues">Report Bug</a>
    ·
    <a href="https://github.com/renan-brasilio/sfdx-easy-changeset/issues">Request Feature</a>
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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

Just to make life a little bit easier when retrieving a Changeset/Package on Salesforce using SFDX <!--`github_username`, `repo_name`, `twitter_handle`, `linkedin_username`, `email`, `email_client`, `project_title`, `project_description`-->

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

* [Salesforce CLI](https://developer.salesforce.com/tools/sfdxcli)
* [./jq](https://stedolan.github.io/jq/)
* [Shell Scripting Primer](https://developer.apple.com/library/archive/documentation/OpenSource/Conceptual/ShellScripting/shell_scripts/shell_scripts.html)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This especifc script was created for Mac OS users, I have no information (yet) about the OS version necessary to run it, only that it should works for almost all OS versions since it relys on bash.

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```
* brew
  ```sh
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```
* jq
  ```sh
  brew install jq
  ```

### Installation

1. Follow the pre-requisites listed above.
2. Install Salesforce CLI, instructions [here](https://developer.salesforce.com/docs/atlas.en-us.sfdx_setup.meta/sfdx_setup/sfdx_setup_intro.htm).
3. Download the file from the latest release [here](https://github.com/renan-brasilio/sfdx-easy-changeset/releases/latest).
4. Put the file downloaded on your Project folder.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

On your Visual Code, go on Terminal (Bash/zsh) and type:
```sh
  ./changeset
  ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [14/10/2021] Creation

<p align="right">(<a href="#top">back to top</a>)</p>



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

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Renan Rocha - [@renanbrasilio](https://twitter.com/renanbrasilio) - renanfamous@gmail.com

Project Link: [https://github.com/renan-brasilio/sfdx-easy-changeset](https://github.com/renan-brasilio/sfdx-easy-changeset)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* None (Yet?)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/renan-brasilio/sfdx-easy-changeset.svg?style=for-the-badge
[contributors-url]: https://github.com/renan-brasilio/sfdx-easy-changeset/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/renan-brasilio/sfdx-easy-changeset.svg?style=for-the-badge
[forks-url]: https://github.com/renan-brasilio/sfdx-easy-changeset/network/members
[stars-shield]: https://img.shields.io/github/stars/renan-brasilio/sfdx-easy-changeset.svg?style=for-the-badge
[stars-url]: https://github.com/renan-brasilio/sfdx-easy-changeset/stargazers
[issues-shield]: https://img.shields.io/github/issues/renan-brasilio/sfdx-easy-changeset.svg?style=for-the-badge
[issues-url]: https://github.com/renan-brasilio/sfdx-easy-changeset/issues
[license-shield]: https://img.shields.io/github/license/renan-brasilio/sfdx-easy-changeset.svg?style=for-the-badge
[license-url]: https://github.com/renan-brasilio/sfdx-easy-changeset/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/renan-brasilio
[product-screenshot]: images/screenshot.png