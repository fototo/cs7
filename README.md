
<!-- README.md is generated from README.Rmd. Please edit that file -->
Welcome to cs7
--------------

This is the online, up-to-date home for the course *Intermediate and Advanced R for Spatial Data Analysis*.

Learning outcomes
-----------------

By the end of the course participants will:

-   Be more efficient general R programmers
-   Understand standard (non-spatial) data structures and how to subset, process and analyse them
-   Understand the structure of spatial data in R
-   Be able to query, subset and analyse spatial objects
-   Have a working knowledge of fundamental GIS functions such as changing projections
-   Be proficient in the use of R to create maps using add-on packages such as tmap
-   Have some experience with advanced functionality such as raster data and interactive maps

Course content
--------------

### Day 1: Intermediate R

-   (Re)introduction to RStudio (9:30 - 11:15)
    -   1 hr lecturing, 45 minutes practical
    -   Practical handout: [creating-maps-in-R](https://github.com/Robinlovelace/Creating-maps-in-R), Part I
-   Objects, functions and concepts for efficient R programming (11.30 - 13.45)
    -   30 minutes intro, 45 minutes hands on, 20 minutes lecture, 40 minutes practical
    -   Exercise: Read sections [4.1](https://csgillespie.github.io/efficientR/efficient-set-up.html#top-5-tips-for-an-efficient-r-set-up) to [4.2](https://csgillespie.github.io/efficientR/efficient-set-up.html#operating-system) of Colin Gillespie, Robin Lovelace (2016) and complete the Exercise at the end of 4.2.

**13.45 - 14.30 Lunch**

-   Data manipulation (14:30 - 16:00)

-   Plotting paradigms
    -   Lecture and practical handout: [creating-maps-in-R](https://github.com/Robinlovelace/Creating-maps-in-R) (Part IV)
    -   **Base graphics**
    -   **ggplot2**
    -   **tmap**
    -   **leaflet**
    -   **mapview**

Day 2: Basics of R as a GIS
---------------------------

-   Spatial data in R, sp classes and projections (09.00 -11.15)
    -   Practical handout 1: [Spatial data in R](https://www.dropbox.com/s/9eozr5slpj638es/Manipluating_Spatial_Objects.pdf?dl=0) by Lex Comber
    -   Practical handout 2: [creating-maps-in-R](https://github.com/Robinlovelace/Creating-maps-in-R), Part II)
-   Loading, plotting and interrogating spatial data, including shapefiles, xy and spatial queries (11:30 - 13:45)
    -   (practical handout: [creating-maps-in-R](https://github.com/Robinlovelace/Creating-maps-in-R), Part III)

**13.45 - 14.30 Lunch**

-   Manipulating spatial objects with a focus on rgeos (14:30 - 16:00)
    -   Course handout: [Manipulating Spatial Objects](https://www.dropbox.com/s/9eozr5slpj638es/Manipluating_Spatial_Objects.pdf?dl=0) by Lex Comber
-   Introduction raster data with R (16:15 - 17:45)
    -   Course handout: [Introduction to Raster Analysis](https://www.dropbox.com/home/Teaching/rmaterials-lc?preview=Raster_Analysis.pdf) by Lex Comber

Day 3: Advanced R for spatial data analysis
-------------------------------------------

-   Raster/vector operations with R - class conversions and aggregation with raster (09:00 - 11:15)

<!-- - Spatio-temporal data with **spacetime** (11:30 - 13:45) -->
-   Transport data with **stplanr** (11:30 - 13:45)
    -   Exercise: Work through the package's vignette (`ignette("introducing-stplanr")`)

**13.45 - 14.30 Lunch**

-   Points pattern analysis - points to surfaces by IDW, Kriging (14:30 - 16:00)
    -   Handout: [Point Patter analysis](https://www.dropbox.com/s/gn1i21rsvipbwom/Point_Pattern.pdf?dl=0) by Lex Comber
-   Advanced graphics: online mapping with **mapview** and leaflet and static maps with **tmap** (16:15 - 17:45)

Prerequisites and course home
-----------------------------

Working knowledge of R and RStudio is assumed.

Background reading (available online):

-   Torfs and Brauer (2014)
-   Colin Gillespie, Robin Lovelace (2016)
-   Lovelace and Cheshire (2014)

Background reading (not available online):

-   Bivand, Pebesma, and G’omez-Rubio (2013)
-   Dorman (2014)
-   Lamigueiro (2014)
-   Brunsdon and Comber (2015)

References
----------

Bivand, Roger S, Edzer J Pebesma, and Virgilio G’omez-Rubio. 2013. *Applied Spatial Data Analysis with R*. Vol. 747248717. Springer.

Brunsdon, Chris, and Lex Comber. 2015. *An Introduction to R for Spatial Analysis & Mapping*. Sage.

Colin Gillespie, Robin Lovelace. 2016. *Efficient R Programming*. <http://shop.oreilly.com/product/0636920047995.do>.

Dorman, Michael. 2014. *Learning R for Geospatial Analysis*. Packt Publishing Ltd.

Lamigueiro, Oscar Perpinan. 2014. *Displaying Time Series, Spatial, and Space-Time Data with R*. CRC Press.

Lovelace, Robin, and James Cheshire. 2014. “Introduction to Visualising Spatial Data in R.” *Comprehensive R Archive Network*, no. 03. <https://github.com/Robinlovelace/Creating-maps-in-R>.

Torfs, Paul, and Claudia Brauer. 2014. “A (Very) Short Introduction to R.” *Comprehensive R Archive Network*. <http://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf>.
