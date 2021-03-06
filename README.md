# ha-graphapi

<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
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
<p align="center">
  <h3 align="center">Home Assistant Graph API</h3>

  <p align="center">
    A Home Assistant package for consumption of Microsoft's Graph API
    <br />
    <br />
    <a href="https://github.com/jlweston/ha-graphapi/issues">Report Bug</a>
    ·
    <a href="https://github.com/jlweston/ha-graphapi/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

- [ha-graphapi](#ha-graphapi)
  - [Table of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
    - [Built With](#built-with)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)

<!-- ABOUT THE PROJECT -->
## About The Project

This package was born of a desire to surface Microsoft Teams presence data within Home Assistant so that users can create automated flows based on their current activity or availability. Want to illuminate a studio warning light when you're on a call? Track time spent on conference calls? Now you're covered.

Thanks to Microsoft's [Graph API](https://docs.microsoft.com/en-us/graph/overview), it's easy to get a user to authenticate once and have Home Assistant continue to poll for data in the background.

For now, the package only includes user presence data but the power of Graph API means it can eventually support features such as checking Outlook emails or the status of upcoming meetings. If you have ideas, please raise a [feature request](https://github.com/jlweston/ha-graphapi/issues) or submit a pull request.



### Built With
No frameworks. No magic. Just pure Python.
* [Python](https://www.python.org/)



<!-- GETTING STARTED -->
## Getting Started

If you'd like to contribute, check out the steps below to get set up locally and see existing example flows.



### Prerequisites

The only software required is Python 3 (the package is currently tested on 3.8).
* Python 3 (download the correct version for your OS [here](https://www.python.org/downloads/))



### Installation

1. Clone the repo
```sh
git clone https://github.com/jlweston/ha-graphapi && cd ha-graphapi
```
2. Create a virtual environment
```sh
python3 -m venv venv
```
3. Run the example (swapping the placeholders with real Azure AD application credentials)
```sh
python3 examples/presence.py --client_id {my-client-id} --client_secret {my-client-secret}
```



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/jlweston/ha-graphapi/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Jamie Weston - [@jlweston85](https://twitter.com/jlweston85) - jlweston85@gmail.com

Project Link: [https://github.com/jlweston/ha-graphapi](https://github.com/jlweston/ha-graphapi)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/jlweston/ha-graphapi.svg?style=flat-square
[contributors-url]: https://github.com/jlweston/ha-graphapi/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jlweston/ha-graphapi.svg?style=flat-square
[forks-url]: https://github.com/jlweston/ha-graphapi/network/members
[stars-shield]: https://img.shields.io/github/stars/jlweston/ha-graphapi.svg?style=flat-square
[stars-url]: https://github.com/jlweston/ha-graphapi/stargazers
[issues-shield]: https://img.shields.io/github/issues/jlweston/ha-graphapi.svg?style=flat-square
[issues-url]: https://github.com/jlweston/ha-graphapi/issues
[license-shield]: https://img.shields.io/github/license/jlweston/ha-graphapi.svg?style=flat-square
[license-url]: https://github.com/jlweston/ha-graphapi/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jamie-weston-3171055b/