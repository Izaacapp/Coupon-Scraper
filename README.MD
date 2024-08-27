Sure! Below is the updated `README.md` template based on your requirements, incorporating the content from the Wired Coupon Automation Tool and your new repository. I’ve included the sections you requested, with the image and new links to your repository.

```markdown
<a name="readme-top"></a>

<div align="center">
  
  [![Contributors][contributors-shield]][contributors-url]
  [![Forks][forks-shield]][forks-url]
  [![Stargazers][stars-shield]][stars-url]
  [![Issues][issues-shield]][issues-url]
  [![LinkedIn][linkedin-shield]][linkedin-url]
</div>

<br />
<div align="center">
  <a href="https://github.com/Izaacapp/Coupon-Scraper">
    <img src="scrapping.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">🛒 Wired Coupon Automation Tool 💸</h3>

  <p align="center">
    Selenium script to retrieve the latest Wired Coupons & Promo Codes for various websites such as Walmart, DoorDash, EBay, & more.
    <br />
    <a href="https://github.com/Izaacapp/Coupon-Scraper"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    ·
    <a href="https://github.com/Izaacapp/Coupon-Scraper/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/Izaacapp/Coupon-Scraper/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This project is a Python-based tool that automates the retrieval of the latest Wired Coupons and Promo Codes for popular websites such as Walmart, DoorDash, EBay, and more using Selenium.

### Built With

* ![Python][python-url]
* ![Selenium][selenium-url]

## Getting Started

### Prerequisites

Ensure you have Python installed on your system. You will also need `pip` to install the required packages.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Izaacapp/Coupon-Scraper.git
   cd Coupon-Scraper
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up the environment variables as needed.

### Usage

To run the script and scrape coupons:

1. **No Arguments:**
   ```bash
   python main.py
   ```

2. **Specify Retailers as Arguments (comma-separated):**
   ```bash
   python main.py amazon,doordash
   ```

### Example Output

Output for running `python main.py amazon`:

```Python
---------------------------------------------------------------------------
Welcome to Wired Coupon Scraper.

RETAILERS argument received.
Gathering coupon codes for: ['amazon']
--------------------------------------------------
codes.txt file already exists
----------------------------------------------------------------------
Retrieving AMAZON Promo Code Offers...

108 AMAZON Promo Codes/Coupons were found!
--------------------------------------------------
Take 40% Off select products from Kwfrhix - Amazon Promo Code:
        40MMS6OP
https://www.wired.com/coupons/get/94554598?popup=true

Appended Take 40% Off select products from Kwfrhix - Amazon Promo Code: - https://www.wired.com/coupons/get/94554598?popup=true
--------------------------------------------------
--------------------------------------------------
Enjoy 40% Off select JingLeXin products - Amazon Promo Code:
        40YPKL1X
https://www.wired.com/coupons/get/94554602?popup=true

Appended Enjoy 40% Off select JingLeXin products - Amazon Promo Code: - 40YPKL1X - https://www.wired.com/coupons/get/94554602?popup=true
--------------------------------------------------
*---Rest of Promo Codes---*
```

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact

Izaac Plambeck  
[Tweet me](https://x.com/Izaacapp)  
[Email me](mailto:izaacap@gmail.com)  

## Acknowledgments

* [Selenium](https://www.selenium.dev/)
* [Python](https://www.python.org/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/badge/Contributors-violet?style=for-the-badge
[contributors-url]: https://github.com/Izaacapp/Coupon-Scraper/graphs/contributors
[forks-shield]: https://img.shields.io/badge/Forks-green?style=for-the-badge
[forks-url]: https://github.com/Izaacapp/Coupon-Scraper/network/members
[stars-shield]: https://img.shields.io/badge/Stars-gold?style=for-the-badge
[stars-url]: https://github.com/Izaacapp/Coupon-Scraper/stargazers
[issues-shield]: https://img.shields.io/badge/Issues-red?style=for-the-badge
[issues-url]: https://github.com/Izaacapp/Coupon-Scraper/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/izaac-plambeck/
[python-url]: https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[selenium-url]: https://img.shields.io/badge/-selenium-%43B02A?style=for-the-badge&logo=selenium&logoColor=white
```

