---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
# classes: wide
layout: default
---

Interested readers might want to check out the details in the jupyter notebook, including code on data analysis, preprocessing and plots: 
[Notebook](https://nbviewer.org/github/ToreVang/ToreVang.github.io/blob/0b372e251bb097e3fcaeb1f4a0547442b496b7cb/Assignment%20final/main.ipynb)


<div class="columns">
    <div class="column">
        <div class="content">
            <p> <h4>Importance of trees in cities</h4>
            Cities around the world are getting bigger and should be suited for an increasing amount of people moving into them. There are many problems connected with building big cities, and trees contribute to many of these problems by providing protection against watersheds, maintaining soil strength using their roots, reducing temperature by giving shade to surrounding buildings and roads, reducing air pollution and aesthetics to the city. Apart from this, studies have shown that trees have a positive psychological effect on the people in the neighborhood such as reduced crime rates, higher occupancy and property value (1). <br>
            <h4>Development of street trees in Copenhagen</h4>
            Copenhagen is a city that has been focusing a lot on street trees over the past many years. This tendency is shown in the figure below of the development of planted trees in Copenhagen from 1920 to 2022. It both gives the number of trees planted and the number of different species planted. 
            The plot gives a clear impression that Copenhagen is focusing more and more on planting trees, but also that biodiversity is a key factor when choosing trees.
            This data does however not say anything about how many trees died or were cut down due to other reasons, and the amount of trees present could seem much different than the number of trees planted as shown here.
            <img src="https://raw.githubusercontent.com/ToreVang/ToreVang.github.io/main/public/tree_amount_tree_diversity.png"  width="700" height="550"> <br>
            <em>The development of the number of total planted trees and number of different species of planted trees from 1920 to 2022. </em>
            <h4>Species</h4>
            Diversity is very important both to ensure more species and wildlife but also to decrease the risk of spreding decease among the trees, such that they die and have to be replanted. The stacked area plot below gives the number of planted trees for the 10 most represented species from 1920 to 2022, the remaining species is collected in "other". Notice that planting of trees is often done in big projects why the original data was very spiky, for better interpretation some smoothing was applied. The species are sorted such that the tree with heighst rations are shown at the top of the legend and in the button of the stacked area plot. The most represented species is "Lind", and the very popular street tree platan is the second most planted tree. The focus on diversity is very clear in both plots, and it can be seen that from year 2000, the degree of "other" trees has increased a lot. Interesetingly many of the most popular trees like Platan and Lind have seen a big decrease in these same years </p>
        </div>
    </div>
    <div class="column">
        <div class="content">
            <p> <img src="https://raw.githubusercontent.com/ToreVang/ToreVang.github.io/main/public/stacked_copenhagen.png"  width="700" height="550"> <br>
            <em>The development of the number of total planted trees of each species in Copenhagen from 1920 to 2022. </em>
            <h4>Difference between regions</h4>
            Street trees thus both have physical, social and economical positive impacts and are therefore important in all cities. Street trees are however not equally representet in every part of Copenhagen, neither in terms of amount of trees or species. In the figure below is a combined bar chart of every part of Copenhagen showing the density of trees and trees/population ratio. As mentioned before this is the number of planted trees, the number of present tree might give a other understanding.
            <img src="https://raw.githubusercontent.com/ToreVang/ToreVang.github.io/main/public/tree_density_tree_population_ratio.png"  width="700" height="550">  <br>
            <em> The density of trees and the number of planted trees per citizen in the region for each part of Copenhagen. </em>  </p>
        </div>
    </div>
    <div class="column">
        <div class="content">
            <p> If all regions were weighted equally the number of trees per citizen should be close to equal, but in this case some regions like Indre By and Østerbro have more than 2 times as many trees planted pr. number of citizens in the region, than regions like Bispebjerg, Husum and Amager Øst. An explanation could be that Indre By and Østerbro are less populated and thus large areas for more trees. This is however not the case as these are very central parts of Copenhagen. It is thus clear that Copenhagen favores some parts of the city above others, but it can also be seen that they actually tried to keep the ratio of trees per citizens somewhat equal. 
            Nørrebro has a high population of people, to accomodate for this Copenhagen have planted many trees even though it means that the density of tree here are almost 4 times that of other parts like Husum, while keeping the same trees per citizens ration as many other regions like Husum.<br>
            Notice again how this figure might be misleading, Amager vest is the far biggest area, with the far biggest population. A big part of amager vest are actual forrest, which has not been included in this dataset, and it may therefore seem like the area with the smallest density of planted trees, while this might be true it might not the region with the smallest density of total trees.
            <h4>Expense of trees</h4>
            What is the reason for this uneven map, that expecitially are due to Indre by and Østerbro that are much better in terms of trees to live in than any other part of the town. According to statistikbank.dk Indre by and Østerbro are where the citizens live with the far greatest income, this is when looking at the 10. decile group for the average equivalised disposal income. But even the 6. decile does not show that Østerbro or Indre By are much above average. This means that these parts of Copenhagen seems to consist of a wide range of income groups just like any other parts of Copenhagen, but the few citizens with the highest income are located in these areas. 
            <h4>Conclusion</h4>
            Street trees are contributing to a wide range of positive effects in a neighborhood, and with this in mind it is unfortunate that street trees are not planted where the most people live so that more people could get the advantages. Street trees are constributing to a lot of good things in the cities, but they also contribute to increase property value, which for some people makes it harder for them to live in the city, with prices already very high in most parts of the city. With this in mind it might some times be a good idea to have cheaper neighborhood, such that people have the option to live a cheaper alternative. Some might even argue that the difference between the regions of Copenhagen should be greater. </p>
        </div>
    </div>
</div>
<!-- <embed
    type="text/html" 
    src="{{site.baseurl}}/public/custom_filename.html"
    width="1400"
    height="900"
    > -->

### References
Dataset from
https://www.citypopulation.de/en/denmark/copenhagen/admin/
https://kk.statistikbank.dk/statbank5a/Graphics/MapAnalyser.asp?Maintable=KKIND5&lang=1&DECILGEN=1&OMRKK=1001


Towards a Better Tomorrow: Street Trees and Their Values in Urban Areas:
https://reader.elsevier.com/reader/sd/pii/S1877042812004004?token=5AF9B753CF9161848BB42AF57D4B9019C4159CB05F6681F4D7207B7B7454A00FC9FF6DA37512D47B6AA0E20A3E54EE33&originRegion=eu-west-1&originCreation=20230424070201

(1) Robert B PhD, Mark M PhD, Kevin Miller (2007), Trees Invest in a Better Tomorrow NC State University