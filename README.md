This project contains the Understand Projects (.udb) of the studied ad libraries (at the start and at the end of our study period) as a replication package of our paper _**"A Longitudinal Study of Popular Ad Libraries in the Google Play Store"**_

# A Longitudinal Study of Popular Ad Libraries in the Google Play Store
In-app advertisements have become an integral part of the revenue model of mobile apps. 
To gain ad revenue, app developers integrate ad libraries into their apps. 
Such libraries are integrated to serve advertisements (ads) to users; developers then gain revenue based on the displayed ads and the users' interactions with such ads. 
As a result, ad libraries have become an essential part of the mobile app ecosystem. 
However, little is known about how such ad libraries have evolved over time. 

In this paper, we study the evolution of the 8 most popular ad libraries (e.g., Google AdMob and Facebook Audience Network) over a period of 33 months (from April 2016 until December 2018). 
In particular, we look at their evolution in terms of size, the main drivers for releasing a new version, and their architecture.  
To identify popular ad libraries, we collect 35,462 updates of 1,840 top free-to-download apps in the Google Play Store.
Then, we identify 63 ad libraries that are integrated into the studied popular apps.
We observe that an ad library represents 10\% of the binary size of mobile apps, and that the proportion of the ad library size compared to the app size has grown by 10\% over our study period.
By taking a closer look at the 8 most popular ad libraries, we find that ad libraries are continuously evolving with a median release interval of 34 days. 
In addition, we observe that some libraries have grown exponentially in size (e.g, Facebook Audience Network), while other libraries have attempted to reduce their size as they evolved. 
The libraries that reduced their size have done so through: 
(1) creating a lighter version of the ad library, (2) removing parts of the ad library, and (3) redesigning their architecture into a more modular one. 

To identify the main drivers for releasing a new version, we manually analyze the release notes of the eight studied ad libraries. 
We observe that fixing issues that are related to displaying video ads is the main driver for releasing new versions. 
We also observe that ad library developers are constantly updating their libraries to support a wider range of Android platforms (i.e., to ensure that more devices can use the libraries without errors).
Finally, we derive a reference architecture from the studied eight ad libraries, and we study how these libraries deviated from this architecture in the study period. 

Our study is important for ad library developers as it provides the first in-depth look into how the important mobile app market segment of ad libraries has evolved. 
Our findings and the reference architecture are valuable for ad library developers who wish to learn about how other developers built and evolved their successful ad libraries.
For example, our reference architecture provides a new ad library developer with a foundation for understanding the interactions between the most important components of an ad library. 
