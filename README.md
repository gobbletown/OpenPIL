<div id="top"></div>




<!-- PROJECT LOGO -->

<br>

<br />
<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/OpenPILReadME.png" alt="Logo" width="60%" style="padding-top: 100px">
  </a>
    <br>
    <br>
  <h3 align="center">The non-profit making medication information freely accessible and reliable using AI.</h3>
    <br>
  
</div>

<p align="center">
  <a href="https://github.com/badges/shields/graphs/contributors" alt="Contributors">
          <img src="https://img.shields.io/badge/organisation-Non--Profit-brightgreen?style=flat&logo=UniversityOfManchester?style=flat" /></a>
  <a href="https://github.com/badges/shields/graphs/contributors" alt="Contributors">
        <img src="https://img.shields.io/github/license/OpenPIL/OpenPIL?color=brightgreen" /></a>
    <a href="https://github.com/badges/shields/graphs/contributors" alt="Contributors">
          <img src="https://img.shields.io/badge/🏆%20awards-University%20of%20Manchester%20Making%20A%20Difference%20Award-brightgreen?style=flat&logo=UniversityOfManchester?style=flat" /></a>
      <a href="https://github.com/badges/shields/graphs/contributors" alt="Contributors">
        <img src="https://img.shields.io/github/languages/count/OpenPIL/OpenPIL?color=brightgreen?style=flat" /></a>
    <a href="https://github.com/badges/shields/graphs/contributors" alt="Contributors">
          <img src="https://img.shields.io/badge/pypi%20package-v2.0.1-brightgreen?style=flat" /></a>
    <a href="https://github.com/badges/shields/graphs/contributors" alt="Contributors">
          <img src="https://img.shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-brightgreen?style=flat" /></a>
</p>

<br>
<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>

<!-- TABLE OF CONTENTS -->
## Table of Contents

<!-- <details> -->
<!--   <summary>Table of Contents</summary> -->
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
         <ul>
             <li><a href="#what-is-openpil">What is OpenPIL AI?</a></li>
             <li><a href="#why-is-this-important">Why is this important?</a></li>
        </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#usage">Usage</a></li>
      </ul>
    </li>
    <li><a href="#datasets">Datasets</a></li>
    <li><a href="#development">Development</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#references">References</a></li>
  </ol>
  
<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>
<!-- </details> -->

<!-- ABOUT THE PROJECT -->

## About The Project

### What is OpenPIL

OpenPIL is a non-profit organisation with an AI at its core. The AI, maintained and developed by Malik Ahmed (MPharm), extracts essential drug information from Summary of Product Characteristics (SmPC) documents. These are drug documents which hold all the important information that doctors and pharmacists use to make decisions about prescribing medicine. OpenPIL AI requires the user to write one line of code, and a path to the SmPC .pdf file. It then processes the natural language in the document using datasets curated by Malik, sourced from copyright-free libraries (see references below), to show information on active-substances, active-excipients, formulation, drug-drug interactions, and drug-class interactions. It took the OpenPIL team of clinical advisors about 1 hour on average to extract that information into an excel spreadsheet manually per SmPC; the AI run time is approx. 4 minutes for a medium length SmPC document, so it's pretty fast, especially considering the volume of data it's processing through.

### Why is this important

Currently this essential clinical medication information is highly-privatised, which restricts access to healthcare technology developers who need it to create ground-breaking products for patients. This restriction limits the current state of healthcare-technology, and indirectly is putting peoples health at greater risk. This is particularly of concern for those in developing and war-torn countries, whose access to up-to-date medicinal information is limited, even though it doesn't have to be. The aim of making the OpenPIL AI open-source is to accelerate the development of affordable drug-databases and healthcare technology around the world!


<p align="right">(<a href="#top">back to top</a>)</p>


<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>

<!-- GETTING STARTED -->
## Getting Started

These are the instructions to install the OpenPIL AI locally and get started with analysing those Summary of Product Characteristics Documents (.pdf). NOTE: The AI currently only works for SmPC's in European format.

### Installation
The OpenPIL AI is really easy install. Simply type the below command into your terminal.

```
pip install OpenPIL
```


_If this doesn't work, make sure you have the dependencies, as can be seen below._

<!-- <p align="right">(<a href="#top">back to top</a>)</p> -->

### Dependencies

You will need the latest version of python.
```
pip install --upgrade python
```

You will need the following modules (nltk, PyPDF2, pdftotext):

```
pip install nltk
```
```
pip install PyPDF2
```
```
pip install pdftotext
```

<!-- _or if you already have them_
```
pip install --upgrade nltk
```
```
pip install --upgrade PyPDF2
```
```
pip install --upgrade pdftotext
``` -->

All other modules should come pre-installed with Python3, they are as follows incase you are missing any:

<ul>
    <li><a >re</a></li>
    <li><a >string</a></li>
    <li><a >math</a></li>
    <li><a >ctypes</a></li>
    <li><a >sys</a></li>
    <li><a >platform</a></li>
</ul>
<!-- 
```
pip install re
```
```
pip install string
```
```
pip install math
```
```
pip install ctypes
```
```
pip install sys
```
```
pip install platform
``` -->
<!-- <p align="right">(<a href="#top">back to top</a>)</p> -->

<!-- USAGE EXAMPLES -->
### Usage

The OpenPIL AI requires only one line of code to run, so it's really easy! Here is how to set it up in a python environment.

<!-- <div align="center">
<img src="https://im7.ezgif.com/tmp/ezgif-7-56d6a6ff6c.gif" width="100%" />
</div> -->


```python
from OpenPIL import OpenPIL

date = OpenPIL.AI("/path/to/the/SmPC.pdf")

print(data)
```

and approx. 4 minutes later, you should see this in your python terminal!

```
Compiling positive class interactions...
Compiling negative class interactions...
Compiling caution classes...
Compiling caution drugs...
Compiling positive interaction drugs...
Compiling negative interaction drugs...
SmPC Complete!
{
    'SMPC NAME': '/path/to/the/SmPC.pdf', 
    'BRAND NAME': 'drug's brand name', 
    'ACTIVE SUBSTANCE(S)': ['array of all active substances in drug'], 
    'ACTIVE EXCIPIENT(S)': ['array of all active excipients in drug'], 
    'FORMULATION': ['form of drug e.g. tablet'], 
    'INTERACTIVE DRUG CLASSES': ['array of any drug-classes that interact with the drug'], 
    'INTERACTIVE DRUGS': ['comprehensive array of all drug's that interact, including those contained within each drug-class that interacts'], 
    'CAUTIONS': ['array of drugs that are cautioned for use']
}
```

And that's it! Get a group of summary of product characteristic documents in the .pdf format stored locally, run a simple for-loop through them, sit back 🪑😎, wait, and then BOOM 💥🤯! You're very own clinical drug-information database!

Please note, that the accuracy and reliability hasn't been fully tested yet, although, OpenPIL are working on a research paper to publish that will verify the current results. So, OpenPIL makes no guarantees to the safety of the information extracted, and does not recommend its use in clinical practice. The [Apache License 2.0](https://github.com/OpenPIL/OpenPIL/blob/main/LICENSE) applies.

<p align="right">(<a href="#top">back to top</a>)</p>


<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>

## Datasets

The datasets used for the OpenPIL AI were curated by Malik Ahmed and they are as follows:
* [drugNameDataset.py](https://github.com/OpenPIL/OpenPIL/)
* [drugClassSynonymDataset.py](https://github.com/OpenPIL/OpenPIL/)
* [drugClassDataset.py](https://github.com/OpenPIL/OpenPIL/)


<p align="right">(<a href="#top">back to top</a>)</p>



<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>

<!-- ROADMAP -->
## Development

- [x] Add Active Substance Detection
- [x] Add Active Excipient Detection
- [x] Add Formulation Detection
- [x] Add Drug-Class Interaction Detection
- [x] Add Drug-Drug Interaction Detection
- [x] Replace python similarity algorithm with C to improve performance from ~40 minutes/SmPC to ~4 minutes/SmPC
- [x] Launch OpenPIL AI open source!
- [ ] Add Side-Effects Detection
- [ ] Add Use in Pregnancy and Breastfeeding Detection
- [ ] Add Storage Conditions Detection
- [ ] Publish peer-reviewed research to validate the accuracy and reliability of the AI

<p align="right">(<a href="#top">back to top</a>)</p>


<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/CoolFeature`)
3. Commit your Changes (`git commit -m 'Add some CoolFeature'`)
4. Push to the Branch (`git push origin feature/CoolFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>


<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>

<!-- LICENSE -->
## License

Distributed under the under the [Apache License 2.0](https://github.com/OpenPIL/OpenPIL/blob/main/LICENSE). See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>

<!-- CONTACT -->
## Contact

Malik Ahmed - malik@openpil.org

Project Link: [https://github.com/OpenPIL/OpenPIL](https://github.com/OpenPIL/OpenPIL)

<p align="right">(<a href="#top">back to top</a>)</p>


<div align="center">
    <a href="https://github.com/OpenPIL/OpenPIL">
    <img src="/Assets/Seperator 20.59.10.png" alt="Logo" width="100%">
  </a>
</div>

<!-- REFERENCES -->
## References

Below are all the resources listed that were used to compile the OpenPIL AI Datasets, with their respective licensing information as of January 27 2022.

* [drugNameDataset.py](https://github.com/OpenPIL/OpenPIL/blob/main/OpenPIL/drugNameDataset.py) was compiled by extracting the drug and supplement names listed under the [European Medicines Agency](https://www.ema.europa.eu/en/about-us/about-website/legal-notice#european-medicines-agency-copyright-and-limited-reproduction-notices-section), [OpenFDA NDC](https://open.fda.gov/data/ndc/) (CC0) and [Drugs@FDA](https://open.fda.gov/data/drugsfda/) (CC0), [NHS BSA](https://www.nhsbsa.nhs.uk/our-policies/terms-and-conditions) (Open Government License), [Netherlands Medicines Agency](https://english.cbg-meb.nl/copyright) (Re-use of Government Information Act).
* [drugClassSynonymDataset.py](https://github.com/OpenPIL/OpenPIL/blob/main/OpenPIL/drugClassSynonymDataset.py) was compiled using the [ChEBI](https://www.ebi.ac.uk/chebi/), listed under 'CC0' for 'Synonyms' in the [User Manual](https://docs.google.com/document/d/1_w-DwBdCCOh1gMeeP6yqGzcnkpbHYOa3AGSODe5epcg/edit).
* [drugClassDataset.py](https://github.com/OpenPIL/OpenPIL/blob/main/OpenPIL/drugClassDataset.py) was compiled using the [OpenFDA NDC API](https://open.fda.gov/data/ndc/) (CC0) and the [OpenFDA Drugs@FDA API](https://open.fda.gov/data/drugsfda/) (CC0).
The [malik_similarity_algorithm.c](https://github.com/OpenPIL/OpenPIL/) includes two sources of external code: the [jaro winkler distance algorithm](https://github.com/miguelvps/c/blob/master/jarowinkler.c) ([GNU General Public License V3 or Later](https://www.gnu.org/licenses/gpl-3.0.en.html)) and the [ratcliff obershelp distance algorithm](https://github.com/wernsey/miscsrc/blob/master/simil.c) (terms of [unlicense](https://unlicense.org)).

All project code other than that mentioned above, was written by Malik Ahmed, and is hereby placed under the [Apache License 2.0](https://github.com/OpenPIL/OpenPIL/blob/main/LICENSE).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot]: images/screenshot.png
