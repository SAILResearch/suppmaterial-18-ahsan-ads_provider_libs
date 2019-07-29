This project contains the Understand Projects of the studied ad libraries (at the start and ad the end of our study period) as a replication package of our paper _**"A Longitudinal Study of Popular Ad Libraries in the Google Play Store"**_

# A Longitudinal Study of Popular Ad Libraries in the Google Play Store
In-app advertisements have become an integral part of the revenue model of mobile apps. 
To gain ad revenue, app developers integrate ad libraries into their apps. 
Such libraries are integrated to serve advertisements (ads) to users; developers then gain revenue based on the displayed ads and the users' interactions with such ads. As a result, ad libraries have become an important part of the mobile apps ecosystem. 
However, little is known about how such ad libraries have evolved over time. 

In this paper, we study the evolution of the eight most popular ad libraries (e.g., Google AdMob and Facebook Audience Network) over 18 months. In particular we look at their evolution in terms of size, the reasons for releasing a new version, and their architecture.  We observe that ads represent 10\% of the binary size of mobile apps, and that the proportion of the ad library size compared to the app size has grown by 10\% over our study period. 
We also find that ad libraries are continuously evolving with a median release interval of 32 days. 
A closer look at the size of ad libraries reveals that some libraries have grown exponentially in size (e.g, Facebook Audience Network), while other libraries have attempted to reduce their size as they evolved. 
The libraries that reduced their size have done so through: 
(1) creating a lighter version of the ad library, (2) removing parts of the ad library, and (3) redesigning their architecture into a more modular one. 

To identify the main drivers for releasing a new version, we manually analyze the release notes of ad libraries. 
We find that fixing issues that are related to displaying video ads is the main driver to release new versions during our study period. 
We also observe that ad library developers are constantly updating their libraries to support a wider range of Android platforms (i.e., to ensure that more devices can execute the libraries without errors).
%Our investigation of the evolution of the architecture of ad libraries shows that ad library designers are actively evolving their architecture.
Finally, we extract a reference architecture from the studied ad libraries, and we study how these libraries deviated from this architecture in the study period. 

Our study is important for ad library developers as it provides the first in-depth look into how the important mobile app market segment of ad libraries has evolved. Our findings and the reference architecture are valuable for ad library developers who wish to learn about how other developers built and evolved their successful ad libraries.

