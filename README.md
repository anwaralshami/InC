<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
***
***
***
*** To avoid retyping too much info. Do a search and replace for the following:
*** anwaralshami, InC, twitter_handle, anwar.alshami@alesopi.com, InC, Emission Inventory Calculator for GCC Countries
-->



<!-- PROJECT LOGO -->
<br />

  <p align="center">
    <h1 style="text-align:center">Emission Inventory Calculator for GCC Countries</h1>
  </p>
<p align="center">
  <a href="https://github.com/anwaralshami/InC">
    <img src="images/logo.png" alt="Logo" width="100" height="100">
  </a>
</p>

  <p align="center">
    <a href="https://github.com/anwaralshami/InC/releases/download/v0.1-beta.1/InC.setup.exe">Download app</a>
    ·
    <a href="https://github.com/anwaralshami/InC/issues">Report Bug</a>
    ·
    <a href="https://github.com/anwaralshami/InC/issues">Request Feature</a>
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
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a>
	  <ul>
        <li><a href="#activity-selection">Activity selection</a></li>
        <li><a href="#activity-input">Activity input</a></li>
		<li><a href="#results-and-custom-emissions">Results and custom emissions</a></li>
      </ul>
	</li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The increased levels of pollutants in the atmosphere are of growing concern due to their detrimental effect on human health, agriculture and natural ecosystems. Ecological Footprint can be a good indicator to understand the severity of air pollution problems faced by the Gulf Cooperation Council (GCC) countries. According to the WWF/Ecological Footprint report “Our Living Planet”, which covers 150 countries around the world, GCC countries rank high in the Total Ecological Footprint, with footprints ranging between 4.6 and 11.9 global ha/person compared to the world average Total Ecological Footprint (TEF) of 1.8 global ha/person ([Grooten & Almond, 2018]( https://www.worldwildlife.org/pages/living-planet-report-2018)). Action to limit air pollution is consistent with Sustainable Development Goals that states that air pollution, both ambient and household, increases the risk of cardiovascular and respiratory disease and, in 2016, led to some 7 million deaths worldwide ([WHO, 2016]( https://www.who.int/news-room/air-pollution)).

Oil and gas related processes are primary causes of air pollution in the GCC, which result in steadily deteriorating of air quality in this region ([Alghamdi et al., 2014]( https://link.springer.com/article/10.1007/s11869-014-0263-x)). Further studies cite rapid urbanization and population growth, lack of a well-developed urban transit system, high number of personal vehicles, low fuel prices, and traffic congestion as parameters to be taken into account matter ([Elmi & al Rifai, 2012]( https://link.springer.com/article/10.1007/s10098-011-0421-x)). Assessments that have been carried out clearly indicate high atmospheric concentrations of particulates matter (PMs) in the GCC countries ([Lanouar et al., 2016]( https://www.qu.edu.qa/static_file/qu/colleges/cbe/documents/research/Charfeddine_2016.pdf)), sulfur dioxide (SO2) as the largest portion of discharged gases into the air by refineries ([Al-Jahdali & bin Bisher, 2008]( https://thescipub.com/abstract/ajessp.2008.84.88)), and prominent nitrogen oxides (NOx) emission sources being from transport, international shipping, power generation, and industry ([Lelieveld et al., 2009]( https://acp.copernicus.org/articles/9/1393/2009/)).

Source Apportionment is the practice of deriving information about pollution sources and the amount they contribute to ambient air pollution levels. Different approaches are used to determine and quantify the impacts of air pollution sources on air quality. Emission inventories are commonly used Source Apportionment techniques. They are detailed compilations of emissions from all source categories in a certain geographical area and within a specific year. Emissions are estimated by multiplying the intensity of each relevant activity (activity rate) by a pollutant-dependent proportionality constant (emission factor). Dispersion models taking emission inventories as input, such as Lagrangian models, Gaussian plume models, and Eulerian models are also applied for source identification purposes.

Good quality emission inventories are the foundation on which optimized emission prevention and control strategies can be developed at different scales. Regional issues such as tropospheric Ozone formation and increasing atmospheric loads of PMs (especially those less than 2.5 µm in diameter) also require high quality emission inventories in order to develop regionally coordinated abatement strategies. This is especially true given that the distribution of the air pollutants in this region is strongly affected by the major seasonal sandstorms ([Brown et al., 2008]( https://www.tandfonline.com/doi/abs/10.3155/1047-3289.58.8.994); [Meo et al., 2013]( https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3809255/)), and compounded by the fact that due to the small land area of some countries in the GCC members compared to the neighboring countries, such as Qatar, UAE, and Kuwait, it is difficult to determine unambiguously, which pollutants originate from inside and which are from outside of the country. The recommendations of this manual reflect the importance of this aspect.

Therefore, to achieve mutual goals and to protect public health and the environment, additional efforts to assess air quality are needed. Without detailed and reliable emission inventories, there is little opportunity to develop strategic plans of how to deal regionally, nationally, or locally with air pollution problems and to monitor the effect of such plans. In Europe and North America there is official national reporting of emission inventories for a number of pollutants to the Convention on Long-Range Transboundary Air Pollution. However, in the GCC countries, routine calculation of emission estimates of high quality is either absent or only available for a few countries and capacity to undertake the necessary calculations is generally lacking. 

Given the absence of region-specific emission factors, this manual is based on the most updated emission factors published in 2019 under the European Environment Agency (EEA) joint European Monitoring and Evaluation Program (EMEP) air pollutant emission inventory guidebook. The 2019 EMEP/EEA guidebook ([European Environment Agency, 2019](https://doi.org/10.2800/293657)) compiles 10727 Tier1 and Tier2 emission factors, abatement efficiencies, and fuel consumption figures from 429 distinct references including the United States Environmental Protection Agency, the Intergovernmental Panel on Climate Change, and various peer reviewed publications. The EMEP/EEA guidebook provides a methodology for compiling inventories and default emission factors, countries are however encouraged to collect their own specific emission factors to improve accuracy.

The manual provides technical guidance to prepare national emission inventories tailored to the GCC. The manual is accompanied by an online Inventory calculator (InC) to perform the emission calculation in a way that enables aggregation into regional inventories. 

The emission **Inventory Calculator** (**InC**) is developed for the purpose of helping the end users in the GCC  prepare national emission inventories. The embedded data related to the emission factors and abatement efficiencies in InC were extracted from the [EMEP/EEA Guidebook 2019](https://doi.org/10.2800/293657).


### Built With

* [R](www.r-project.org)
* [Tidyverse](https://www.tidyverse.org/)
* [Shiny](https://shiny.rstudio.com/)



<!-- GETTING STARTED -->
## Getting Started

Follow these simple steps to install and run **InC** on your PC

### Prerequisites

**InC** only supports for 64-bit processors. 64-bit support requires that you have both a 64-bit capable processor and a 64-bit operating system installed.

* Windows 7 SP1 with Platform Update <br> 
  or Windows 8.1 <br>
  or Windows 10 Version 1607 (build 14393) aka "Anniversary Update" or newer
* 1GHz processor (dual-core is recommended)
* 2GB RAM
* 1024 x 768 screen resolution
* 600+ MB hard drive space



### Installation

1. [Download](https://github.com/anwaralshami/InC/releases/download/v0.1-beta.1/InC.setup.exe) the **InC** installer
2. Once the installer package has been downloaded, open the setup by double-clicking the icon. You must have administrator privileges to install **InC**
3. Follow the on-screen prompts to install **InC** 



<!-- USAGE EXAMPLES -->
## Usage

Users first need to select the activities they plan to include in the national inventory and then input the associated activity rates. InC will perform all necessary calculations to give the user the sought emission inventory which can then be exported as an excel document. InC offers flexible visualizations of the the results with the ability to filter and facet the data in several ways.

### Activity selection
Use the “Activity Selection” tab to determine the activities for which the emission inventory calculation is to be conducted. Select the activities that will be included in the calculation of the emission inventory. Nested in the tree are these 8 layers

    Source sector: the 5 main emission sources: Energy, Industrial processes and product use, Agriculture,
	Waste, Natural sources, which are the broad emission sources

		Emission factor Tier: Tier1 or Tier2 factors, depending on data availability

	    	Source sub-sector: sub-sectors under each of the 5 main emission sources

	        	Sector: Activities under each subsector for the emission tier selected

        			Technology: Specific technologies available for the Sector selected

	                	Fuel: Fuel options for the selected technology

	                    	Abatement: Abatement options for the selected Fuel

	                        	Region: Regions available for the selected Abatement


![Product Name Screen Shot][tree]

### Activity input
Add the activity values for the activities you selected in the "Activity selection" tab. The results are automatically computed and displayed in the "results" tab.

![Product Name Screen Shot][input]


### Results and custom emissions
You can add emissions calculated in methodologies other than EMEP to the  to the inventory. You first need to select the corresponding activities from the "Activity selection" tab. Then in the "Activity input" tab, leave the activity value as zero and click on "Add custom (non-EMEP) emissions". This will take you to a page where you can input the emissions for the pollutants you select.

Your additional emissions will show in the "results" tab, where you can export them using the "Export results" button.
![Product Name Screen Shot][results]

<!-- LICENSE -->
## License

Distributed under the  CC0-1.0 License License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Anwar Al Shami - [anwar.alshami@alesopi.com](mailto:anwar.alshami@alesopi.com)

Project Link: [https://github.com/anwaralshami/InC](https://github.com/anwaralshami/InC)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/anwaralshami/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/anwaralshami/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/anwaralshami/repo.svg?style=for-the-badge
[forks-url]: https://github.com/anwaralshami/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/anwaralshami/repo.svg?style=for-the-badge
[stars-url]: https://github.com/anwaralshami/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/anwaralshami/repo.svg?style=for-the-badge
[issues-url]: https://github.com/anwaralshami/repo/issues
[license-shield]: https://img.shields.io/github/license/anwaralshami/repo.svg?style=for-the-badge
[license-url]: https://github.com/anwaralshami/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/anwaralshami
[tree]: images/tree.gif
[input]: images/input.gif
[results]: images/results.gif
[download]: https://github.com/anwaralshami/InC/releases/download/v0.1-beta.1/InC.setup.exe
