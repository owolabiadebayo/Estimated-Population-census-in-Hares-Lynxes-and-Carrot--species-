# Population census in Hares,Lynxes and Carrot (species)
 describes the populations of hares and lynxes (and carrots) in northern Canada during 20 years.

## question
The data in populations.txt describes the populations of hares and lynxes (and carrots) in northern Canada during 20 years:

Computes and print, based on the data in populations.txt...

The mean and std of the populations of each species for the years in the period.
Which year each species had the largest population.
Which species has the largest population for each year. (Hint: argsort & fancy indexing of np.array([‘H’, ‘L’, ‘C’]))
Which years any of the populations is above 50000. (Hint: comparisons and np.any)
The top 2 years for each species when they had the lowest populations. (Hint: argsort, fancy indexing)
Compare (plot) the change in hare population (see help(np.gradient)) and the number of lynxes - Check correlation (see help(np.corrcoef)).

```javascript
# year |	hare |	lynx  |	carrot <====== This is the heading of the table
1900    |	30e3    |	4e3 |	48300 
1901|	47.2e3|	6.1e3|	48200
1902|	70.2e3|	9.8e3|	41500
1903	77.4e3	35.2e3	38200
1904	36.3e3	59.4e3	40600
1905	20.6e3	41.7e3	39800
1906	18.1e3	19e3	38600
1907	21.4e3	13e3	42300
1908	22e3	8.3e3	44500
1909	25.4e3	9.1e3	42100
1910	27.1e3	7.4e3	46000
1911	40.3e3	8e3 	46800
1912	57e3	12.3e3	43800
1913	76.6e3	19.5e3	40900
1914	52.3e3	45.7e3	39400
1915	19.5e3	51.1e3	39000
1916	11.2e3	29.7e3	36700
1917	7.6e3	15.8e3	41800
1918	14.6e3	9.7e3	43300
1919	16.2e3	10.1e3	41300
1920	24.7e3	8.6e3	47300
```

>Compare (plot) the change in hare population (see help(np.gradient)) and the number of lynxes 

