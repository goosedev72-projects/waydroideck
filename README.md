<a id="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
  <a href="https://github.com/goosedev72-projects/waydroideck">
    <img src="assets/logo.png" alt="Logo" width="80" height="80">
  </a>

# WaydroiDeck

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
I loved the Waydroid Cage installer by 10MinuteSteamDeckGamer, check his youtube, but I wanted a fresh version, so... Meet WaydroiDeck

### Built With
Almost PURE Python3, only Colorama needed, easy to install

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
This is easy if you follow the guide.

### Prerequisites
First, you need to **set sudo password**, with ```passwd deck```, enter your desired password, prepare pacman and install Python, pip, colorama.

Populate keyring:
```
sudo pacman-key --init
sudo pacman-key --populate archlinux
sudo pacman-key --populate holo
```
Now install Python, pip and colorama.
```
sudo pacman -S python3 python-pip python-colorama
```
### Installation

```
cd ~/
mkdir mk; cd mk
git clone https://github.com/goosedev72-projects/waydroideck.git --depth 1
cd waydroideck
python3 main.py
```

Then follow the wizard.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage
Actually... The wizard will ask you questions, save config to JSON, to backup, transfer, and easy automated recovery after SteamOS update. You can use Config to update and tune your Waydroid. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ROADMAP -->
## Roadmap

- [x] Finish README.md
- [ ] Finish the base program
- [ ] Fully finish the program
    - [ ] Debug

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

### Top contributors:

<a href="https://github.com/github_username/repo_name/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=goosedev72-projects/waydroideck" alt="contrib.rocks image" />
</a>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Use issues or my telegram @GooseDev72.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
- @ryanrudolfoba or 10MinuteSteamDeckGamer for base
- @supechicken for TV build
- @tartley for colorama
- @waydroid for such a perfect Android container
- All contributors for my repo and original one
<p align="right">(<a href="#readme-top">back to top</a>)</p>

