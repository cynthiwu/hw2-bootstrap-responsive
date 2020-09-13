# HOMEWORK ASSIGNMENT 2: Responsive Portfolio with Bootsrap

Explore the [project page](https://github.com/cynthiwu/hw2-bootstrap-responsive)

View it live on [github-pages](https://cynthiwu.github.io/hw2-bootstrap-responsive/)


- [HOMEWORK ASSIGNMENT 2: Responsive Portfolio with Bootsrap](#homework-assignment-2-responsive-portfolio-with-bootsrap)
  - [About The Project](#about-the-project)
    - [The Navbar](#the-navbar)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgements](#acknowledgements)


## About The Project

The directive of this assignment was to create the initial framework of a mobile responsive portfolio. This framework was to include three HTML files and contain a navbar within a responsive layout. CSS was meant to be primarily constructed using Bootstrap (v4.5.2) with final interface closely replicating screenshots included in the assignment documentation. These screenshots represented the page layout of each file at three different breakpoints (i.e., 992px, 768px, and 400px). The 992px screenshots have been provided below to represent the starting point of this portfolio.

<span>
<img src="assets/992-index.png" alt="Example index file at 992px." width="200px" height="250px">

<img src="assets/992-portfolio.png" alt="Example portfolio file at 992px." width="200px" height="250px"/>
    
<img src="assets/992-contact.png" alt="Example contact file at 992px." width="200px" height="250px"/>
</span>


The approach to creating this project is outlined below by feature or portfolio page. 


### The Navbar

![Navbar Screenshot][assets/navbar.png] 

*  The Navbar was created using the existing code from Bootstrap's components. It includes the navbar.brand class, which allows my name (a.k.a brand) to appear top left, and navigation links to the right. 
*  The default version of this code pulled the nav links to the left hand side of the brand, which I overrode by including the Bootstrap ml-auto class in the nav link container. 
*  I utilized Bootstrap's fixed-top class to max the navbar expand full width across the screen. This caused issues 
*  The Navbar has responsivness built in, tranforming the nav links to a toggler menu at the 992px breakpoint.

<iframe src="https://drive.google.com/file/d/1e2CFZi1F83xH5d11X5mtyxgx-tuHZeHk/preview" width="640" height="480"></iframe>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* npm
```sh
npm install npm@latest -g
```

### Installation

1. Clone the repo
```sh
git clone https://github.com/github_username/repo_name.git
```
2. Install NPM packages
```sh
npm install
```



<!-- USAGE EXAMPLES -->
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_



<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/github_username/repo_name/issues) for a list of proposed features (and known issues).



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

Your Name - [@twitter_handle](https://twitter.com/twitter_handle) - email

Project Link: [https://github.com/github_username/repo_name](https://github.com/github_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* []()
* []()
* []()





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=flat-square
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=flat-square
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=flat-square
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=flat-square
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=flat-square
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username
[product-screenshot]: images/screenshot.png