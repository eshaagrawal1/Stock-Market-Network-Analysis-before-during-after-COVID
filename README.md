# Stock-Market-Network-Analysis-before-during-after-COVID
This research dives into the effects of COVID-19 on the stock market, exploring how different business sectors coped before, during, and after the pandemic. Our objective was to categorize companies into sectors and understand how each sector responded to the crisis.We recognized a gap in understanding the pandemic's nuanced impact on individual companies and sought to fill it by applying Social Network Analysis. The study involved the analysis of vast datasets, employing complex algorithms to uncover patterns and trends.The data comprised correlation matrices representing the relationships between companies in various sectors. Our findings reveal dynamic shifts in mean correlation and maximum eigenvalues across sectors over the years. In simple terms, we unraveled how companies within sectors related to each other and how these relationships evolved through the pandemic.The outcomes provide strategic insights for investors and policymakers, offering a deeper understanding of how companies navigate crises. This study not only contributes to academic research but also equips market participants with valuable knowledge for informed decision-making.
# Methodology
- Data Collection and Description: 
Standard and Poor’s 500(SP500) dataset of four year (2019, 2020,2021, 2022) time period is used in the project . In this study, the methodology commenced with obtaining historical stock market data for various companies. The data was sourced from reliable financial databases, ensuring its accuracy and relevance to the research objective. The data included daily stock prices, company information, and other relevant financial metrics.The data cleaning process involved the removal of missing values, outliers, and any inconsistencies that could impact the analysis. Additionally, we filtered the data to include only the relevant time periods, specifically before, during, and after the COVID-19 crisis.

![Screenshot 2024-06-20 213156](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/48dd2c47-db9d-4a51-ad77-bd440cbbbeea)
                     
                      The flowchart representing the data downloading, cleaning and filtering process.
                      
- Correlation Analysis: 
Our analysis extends beyond traditional statistical methods, incorporating advanced techniques rooted in Social Network Analysis (SNA). We construct correlation matrices, unveiling the intricate relationships between companies within sectors. The application of community detection algorithms reveals clusters of tightly interconnected companies,
providing insights into sectoral dynamics. Centrality measures, such as degree centrality, betweenness centrality, and eigenvector centrality, play a pivotal role in understanding network structures. These measures identify the importance of specific companies within sectors, uncovering key players that significantly influence the broader network.

- Comparative Analysis and Trend Identification: 
To capture the dynamic nature of the stock market, our methodology integrates a comparative analysis across consecutive years. Changes in community structures, alterations in centrality measures, and shifts in correlation patterns enable the identification of evolving sectoral trends.

- Statistical Measures and Network Metrics: Quantitative measures, such as mean correlation and maximum eigenvalues, offer a numerical foundation for our analysis. Mean correlation provides an overall indication of interconnectedness within sectors, while maximum eigenvalues signify the stability of sector-specific networks.

- Analytical Techniques
  
1 Minimum Spanning Tree (MST): 
Minimum Spanning Tree (MST) analysis was applied to identify the most critical connections within the stock market network. By emphasizing the essential relationships between companies, the MST technique helps unveil key interdependencies and structural aspects of the market.

2 Community Detection: 
Community detection was employed to identify cohesive groups within the stock market. The code implements an algorithm that detects communities or clusters of companies that share similar characteristics. This allows for a nuanced understanding of how companies interact within their respective sectors.

3 Centrality Measures: 
Centrality measures were utilized to assess the importance of individual companies within their sectors. This involved the calculation of metrics such as degree centrality, providing insights into the influence and prominence of specific companies within the stock market network.

4 Time-Series Analysis: 
Time-series analysis was conducted to discern temporal patterns in stock market dynamics. This included evaluating mean correlation and maximum eigenvalue for different sectors across the years 2019-2022. Trends and variations in these metrics provide valuable information on how the market evolved over time.

5 Predictive Modeling: 
The study incorporated predictive modeling techniques to anticipate future market trends.
This involved leveraging historical data to train models, enabling the projection of potential stock market changes. The choice of modeling techniques was driven by their suitability for time-series forecasting and predictive analytics.

# Results
- Network construction :-

![Screenshot 2024-06-20 213751](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/1c684f68-45e9-45c7-8439-dbb24b7923b5)
                       
                          Showing MST of the year 2019 of all the companies having different sectors

![Screenshot 2024-06-20 213801](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/2ab065dc-45b5-4aaf-8622-7d8e0d368d5f)
                         
                          Showing MST of the year 2020 of all the companies having different sectors

![Screenshot 2024-06-20 214103](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/c71e90ff-f9a5-4c61-828e-cb513ccfb217)
                        
                          Showing MST of the year 2021 of all the companies having different sectors

![Screenshot 2024-06-20 213823](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/253d46b0-5d59-4495-8b17-56dadf4cfd48)

                          Showing MST of the year 20122 of all the companies having different sectors

- Centrality Measures
Each centrality measure in a network analysis provides unique insights into the structure and characteristics of the network.
1. Degree Centrality: 
Nodes(Stocks) with high degree centrality are having a higher number of connections or interactions. In the below figure 6 , high-degree nodes representing the stocks that are frequently traded or have many connections with other sectors, indicating their prominence in trading activity across the four years.

![Screenshot 2024-06-20 214422](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/93b5fec4-d211-447a-a0fa-30f3abfa2d0b)
                       
                        Showing the stocks of particular sector that were highly connected with other stocks across different years.
2 Closeness Centrality: 
Nodes with high closeness centrality are showing that they have shorter average path lengths to other nodes in the network. In this network, nodes with high closeness centrality may represent stocks that are well-connected and can quickly influence or be influenced by other nodes.

![Screenshot 2024-06-20 214436](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/713875a7-defd-4cb9-a26d-fb0e5dc5fded)
                      
                      Showing the stocks of particular stocks are very close with others.

3 EigenVector Centrality: 
Nodes that are high eigenvector centrality are anticipated to have influence or importance within the network. They represent influential sectors or stocks that are connected to other influential nodes.

![Screenshot 2024-06-20 214653](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/c3073e95-9555-4447-8040-3a97a08a75b2)
                     
                      High peaks showing the high influential sector at particular year.

![Screenshot 2024-06-20 214805](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/025e6720-25a2-4375-8993-3b34bf357432)

                      Showing the influential of sectors across various years.

- Community detection :-
![Screenshot 2024-06-20 215024](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/f16daa9c-adf7-49f8-b326-69ddd0ecc265)

![Screenshot 2024-06-20 214837](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/a227c9a6-2de5-43c7-9cf1-71dc711fdb15)
                        
                          Showing community detection in 2022

![Screenshot 2024-06-20 215008](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/1e3075a2-d527-4fe8-b9bf-debc0c389a84)
                            
                              Showing Community having different sectors correlated with it.

- Maximum EigenValue and Mean Correlation:
  
![Screenshot 2024-06-20 215133](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/caf80c08-a20f-4f31-9b33-e848cbe8ada0)

![Screenshot 2024-06-20 215230](https://github.com/eshaagrawal1/Stock-Market-Network-Analysis-before-during-after-COVID/assets/90109712/39bdc658-394a-4adb-9ecf-f2f1c00494ec)

The results show us that the healthcare, and has boomed significantly

# Conclusion
In a nutshell, our journey through the stock market's twists and turns from 2019 to 2022 revealed some fascinating insights. We started by carefully collecting and cleaning financial data, ensuring everything was in tip-top shape for analysis.Our detective work involved identifying groups of companies that often moved together, thanks to a nifty technique called community detection. We also figured out who the big shots were in each sector using centrality measures – kind of like finding out who the popular kids are in school. Looking at how things changed over time was crucial. By analyzing the ups and downs, we could see patterns emerge, helping us understand how the market responded to events like the COVID-19 pandemic. But we didn't stop there. We peeked into the future using predictive modeling, making educated guesses about what might happen next based on what we've seen before. Adding a cool tool called the Minimum Spanning Tree (MST) to our kit, we simplified the complex web of connections between companies. This let us spot the most important relationships, giving us a clearer picture of how the market was wired. So, what did we find out? Well, our research isn't just about numbers and charts; it's about helping people make sense of the financial world. Investors, decision-makers, and even everyday folks can benefit from these insights as they navigate the unpredictable seas of the stock market.As we wrap up this journey, remember that the stock market is like a living, breathing organism. It changes, adapts, and sometimes surprises us. By peeling back its layers, we've gained a deeper understanding of its nuances. This isn't just research for the sake of it – it's a guide for those steering the ship through the ever-shifting waters of finance. So, as the market continues to dance to its own tune, armed with these insights, we're better equipped to away along.
