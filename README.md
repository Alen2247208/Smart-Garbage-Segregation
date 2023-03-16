<a name="readme-top"></a>
  [![Contributors][contributors-shield]][contributors-url]
  [![Forks][forks-shield]][forks-url]
  [![Stargazers][stars-shield]][stars-url]
  [![Issues][issues-shield]][issues-url]

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/raison024/Smart-Garbage-Segregation">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Smart Garbage Segregation</h3>

  <p align="center">
    Welcome to our project!
    <br />
    <a href="https://github.com/raison024/Smart-Garbage-Segregation"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/raison024/Smart-Garbage-Segregation">View Demo</a>
    ·
    <a href="https://github.com/raison024/Smart-Garbage-Segregation/issues">Report Bug</a>
    ·
    <a href="https://github.com/raison024/Smart-Garbage-Segregation/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About the Project</a>
      <ul>
        <li><a href="#inspiration">Inspiration</a></li>
        <li><a href="#intel-oneapi">Intel OneAPI</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#what-it-does">What it does</a></li>
    <li><a href="#how-we-built-it">How we built it</a></li>
    <li><a href="#what-we-learned">What we learned</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Smart Garbage Segregation is a project that aims to using AI/ML to efficiently and effectively sort waste into different categories such as plastic, glass, etc.
<div align="center">
  <img src="images/Home-img.png" alt="png" width="400" height="400">
</div>
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Inspiration
As of 2021, the world generated over 2.01 billion tons of municipal solid waste annually. At least 33% of that waste was not managed in an environmentally safe manner. It is estimated that up to 8 million metric tons of plastic reach the planet’s oceans each year. That equates to five grocery bags filled with plastic for every foot of shoreline on earth. Garbage segregation is a critical issue in modern times due to the rising amount of waste generated by society. Traditional methods of garbage segregation involve manual sorting, which is time-consuming, labor-intensive, and often inefficient. AI/ML can provide a solution to this problem by automating the process of garbage segregation. In this project, we propose a system that utilizes AI/ML algorithms to identify and segregate different types of garbage. The system uses image recognition techniques to analyze the images captured by a camera, and then applies machine learning algorithms to classify the garbage into different categories. The system can also learn from its mistakes and improve its accuracy over time. By automating the process of garbage segregation, we can reduce the workload on human workers, increase efficiency, and reduce environmental pollution.

### Intel oneAPI
Intel OneAPI is a comprehensive development platform for building high-performance, cross-architecture applications. It provides a unified programming model, tools, and libraries that allow developers to optimize their applications for Intel CPUs, GPUs, FPGAs, and other hardware. Intel OneAPI includes support for popular programming languages like C++, Python, and Fortran, as well as frameworks for deep learning, high-performance computing, and data analytics. With Intel OneAPI, developers can build applications that can run on a variety of hardware platforms, from edge devices to data centers, and take advantage of the performance benefits of Intel architectures.

### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [![jupyter][jupyter]][jupyter-url]
* [![React][React.js]][React-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- What it does -->
## What it does
This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## How we built it
These are the steps involved in making this project: 
* Importing Libraries
* Data Importing
* Data Exploration
* Data Configuration
* Preparing the Data
  * Creating a Generator for Training Set
  * Creating a Generator for Testing Set
* Writing the labels into a text file 'Labels.txt
* Model Creation
* Model Compilation
* Training the Model (batch_size = 32, epochs = 10)
* Testing Predictions
* Saving model as 'model.h5'
* Deploying the Model as a Web Application using Streamlit

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## What we learned
This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/raison024/Smart-Garbage-Segregation.svg?style=for-the-badge
[contributors-url]: https://github.com/raison024/Smart-Garbage-Segregation/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/raison024/Smart-Garbage-Segregation.svg?style=for-the-badge
[forks-url]: https://github.com/raison024/Smart-Garbage-Segregation/network/members
[stars-shield]: https://img.shields.io/github/stars/raison024/Smart-Garbage-Segregation.svg?style=for-the-badge
[stars-url]: https://github.com/raison024/Smart-Garbage-Segregation/stargazers
[issues-shield]: https://img.shields.io/github/issues/raison024/Smart-Garbage-Segregation.svg?style=for-the-badge
[issues-url]: https://github.com/raison024/Smart-Garbage-Segregation/issues

[product-screenshot]: images/screenshot.png

[jupyter]: https://img.shields.io/badge/jupyter-da5b0b&logoColor=white
[jupyter-url]: https://jupyter.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/

