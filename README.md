<!-- PROJECT LOGO -->
<p align="center">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Burn Victim Factors & Characteristics</h3>

  <p align="center">
    Using association rules to learn what causes major and minor burns.
    <br />
    <a href="https://github.com/Mathurkarishma/burn-victim-factors"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Mathurkarishma/burn-victim-factors/issues">Report Bug</a>
    ·
    <a href="https://github.com/Mathurkarishma/burn-victim-factors/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

We will be speaking into a Burn Study dataset and deciphering association rules between each of the variables.  Association analysis or mining is used to discover relationships within a dataset to help analysts understand the behavior and utilize the knowledge to make key decisions. The Apriori Algorithm of Agrawal and Srikant is the most popular method used to do this, and we will be applying this method.  We want to analyze, evaluate, and capture the results of these association rules with the burn study dataset in order to make informed decisions.

Here is a [link](https://github.com/lbraglia/aplore3/blob/master/rawdata/BURN/BURN_Code_Sheet.pdf) to the Burn Study dataset information.

### Built With

* [R](https://cran.r-project.org/)
* [RStudio](https://rstudio.com/)


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, download the `apriori_burn.R` and the text input file, `burn.csv`, into the same folder. Then run the code in an IDE software, such as RStudio.

<!-- USAGE EXAMPLES -->
## Usage

The code guides you through the following:

1. Importing the CSV file
2. Visualizing the formatting of the variables (datatypes, number of rows/columns, measures of central tendancy, statistical descriptions, etc.)
3. Exploring through histograms to find interesting variables
4. Pre-processing such as cleanup, reduction, and transformation (we removed key identifiers due to no added value, perfomed discretization, and factoring)
5. Perform the Apriori Algorithm, generate rules, and inspect those rules
6. Visualize our rules using a matrix plot

<img src="images/spam_confidence.JPG" alt="spam_confidence">

<!-- CONTACT -->
## Contact

Karishma Mathur - karishma324@gmail.com

Project Link: [https://github.com/Mathurkarishma/burn-victim-factors](https://github.com/Mathurkarishma/burn-victim-factors)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* Dr. Firdu Bati at [University of Maryland, Global Campus](https://www.umgc.edu/) - Fall 2019

