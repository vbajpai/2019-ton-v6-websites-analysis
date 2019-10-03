A Longitudinal View of Dual-stacked Websites − Failures, Latency and Happy Eyeballs  
[IEEE/ACM Transactions on Networking &rarr;](https://ton.lids.mit.edu)  
April 2019  

---  

### Measurement Tests

The `happy` test used to collect the dataset on latency is available [here
&rarr;](https://github.com/vbajpai/happy)  

The `simweb` test used to collected the dataset on partial failures is
available [here &rarr;](https://github.com/steffiejacob/simweb)  

### Vantage Points

The dataset is collected from ~100 SamKnows probes:

![](http://i.imgur.com/zVefNfd.png)  

### Dataset

The raw dataset and mirrors are available at:
http://doi.org/10.14459/2019mp1510228

It includes the SQL schemas  and the dataset in sqlite3 format and the
metadata associated with each vantage point.

### Installation

`make` will install the python dependencies required to run the jupyter
notebooks. `make run` will run jupyter.


### Repeating the results

`plot-*` notebooks can be used to repeat the analysis on the existing
dataset. Each such notebook produces a single plot in the paper.


### Contact

Please feel welcome to contact the authors for further details.

- Vaibhav Bajpai <bajpaiv@in.tum.de>  
- Jürgen Schönwälder <j.schoenwaelder@jacobs-university.de>  
