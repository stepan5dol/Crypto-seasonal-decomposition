# Cryptocurrencies seasonal decomposition: what to expect and when to buy for long?
## Abstract
Seasonal decomposition of 3 different cryptocurrencies – `Bitcoin`, `Binance coin` and `USDT` was performed to analyze main traits of cyclical exchange rate. Binance coin was chosen beacuse of the controlled emission, USDT – because of its belonging to "stablecoins" group, and Bitcoin – because of its uniqueness.

All three cryptocurrencies showed seasonal patterns of `elevation around april` and `decrease around august`. All of them demonstrated the `downward tendency since 2021`. 

The most stable coin of observed was proven to be USDT.

Libraries used: `pandas`, `matplotlib`, `seaborn`, `statsmodels.tsa.seasonal`

## Bitcoin
Bitcoin was analized from 2017.[(Fig.1)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/e1b4e0a14ff6e5cf78d9b2621829a71ccc6629a3/Figures/Fig.01.png). Distribution of its prices was described using boxplot, showing enormous variaty of values. [(Fig.2)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/e1b4e0a14ff6e5cf78d9b2621829a71ccc6629a3/Figures/Figure%2002.png). 
![(Fig.1)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/e1b4e0a14ff6e5cf78d9b2621829a71ccc6629a3/Figures/Fig.01.png)

![(Fig.2)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/e1b4e0a14ff6e5cf78d9b2621829a71ccc6629a3/Figures/Figure%2002.png)
![(Fig.3.2)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2003.2.png)

While providing `seasonal_decompose`, some intresting facts were found out. First of all, trand is going down since the middle of 2021. Seasonal patterns are with `downs in July-August`, `steady growth till April-May`. In the long run, as it is shown by residues, bitcoin stock parameters are quite unpredictable. [(Fig.3,](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2003.png) [ Fig.4)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2004.png). To analise "the edges of stability" boxplot was plotted, those whiskers are shown as red lines on the graph 3. [(Fig.3.2)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2003.2.png)

![Fig. 3](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2003.png) 
![Fig. 4](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2004.png).

In general, it is rational to wait until the end of August to buy Bitcoin, but the main trend of the last to years does not incline us to buy it.

## Binance coin
BC was analysed since the 2017 [(Fig.5)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2005.png). Despite the fact that cost of this cryptocurrency might be significant, the median is quite low [(Fig.6)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2006.png). 

![(Fig.5)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2005.png)
![(Fig.6)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/ebbffe426266476a5e70f4be46ef30a465eb690c/Figures/Figure%2006.png)
![(Fig.7.2)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/2eb165140740add4c9c77869e5c4aa1732370f2b/Figures/Figure%2007.2.png)

After the decomposition we can see the significant downward trend from the end of 2021. While the seasonality remains much the same, residues are telling us that its course is not predictable in long run. On the other hand, we see that by the very beginning of 2023 trend seems to be going on the plateau. [(Fig.7)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/2eb165140740add4c9c77869e5c4aa1732370f2b/Figures/Figure%2007.png). In my opinion, it is considerable to wait untill the end of August - beginning of Autumn to see weather dynamics would change.

## USDT
USDT was analysed since 2015 [(Fig.8)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/2eb165140740add4c9c77869e5c4aa1732370f2b/Figures/Figure%2008.png). After the boxplot investigation it was revealed that USDT is way less fluctuant compared with previously analysed currencies [(Fig.9)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/2eb165140740add4c9c77869e5c4aa1732370f2b/Figures/Figure%2009.png).

![(Fig.8)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/2eb165140740add4c9c77869e5c4aa1732370f2b/Figures/Figure%2008.png)
![(Fig.9)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/2eb165140740add4c9c77869e5c4aa1732370f2b/Figures/Figure%2009.png)
![(Fig.10.2)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/4a1445f950f720b2ba5c252061cdfa85b910e32b/Figures/Figure%2010.2.png)

After the decomposition in the same way the trend of USDT seems to be way more stable with a slight decrease since the middle of 2021. The only fluctuation found during the residues investigation was during the spring of 2022, when all the cryptocurrencies showed peak [(Fig.10, ](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/4a1445f950f720b2ba5c252061cdfa85b910e32b/Figures/Figure10.png) [Fig.10.2)](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/4a1445f950f720b2ba5c252061cdfa85b910e32b/Figures/Figure%2010.2.png). USDT seems to be a good analogue for storing money in stable currencies, such as dollars or euro. Also it is important to note a plateau at the end of the trend segment, though growth might be possible from the beginning of Autumn of 2023. 

To visualise the seasonality the [graph 11](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/4a1445f950f720b2ba5c252061cdfa85b910e32b/Figures/Figure11.png) is provided.

![Fig.10](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/4a1445f950f720b2ba5c252061cdfa85b910e32b/Figures/Figure10.png)
![Fig.11](https://github.com/stepan5dol/Crypto-seasonal-decomposition/blob/4a1445f950f720b2ba5c252061cdfa85b910e32b/Figures/Figure11.png)
