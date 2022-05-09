# Proptech Investment Opportunities
*PROPTECH INVESTMENT OPPORTUNITIES* uses a data visualization approach, including aggregation, interactive visualizations, and geospatial analysis, to find properties in different markets that are viable investment opportunities.


## Requirements

This application was writen in Jupyter Lab 3.3.2 using Python 3.9.7

**Operating System:**

-   Window 10 (or higher) using Gitbash.
-   MacOS 10.14 (or higher) using a terminal.
-   Linux Ubuntu 22.04 (or higher) using a terminal.

**Will need to be installed:**

_jupyter lab_  3.3.2

```
$ pip install jupyterlab
```

_pandas_  1.4.2
```
$ pip install pandas
```

_pathlib_  1.0.1

```
$ pip install pathlib
```

hvPlot 

```
$ pip install hvplot

```
----------

## Installation

To install the application you will need to clone the GitHub repository.

```
$ git clone https://github.com/yanickw/Proptech_Investment_Opportunities

```

----------

## Get Started

Using the  _Proptech Investment Opportunities_:

Open a gitbash, navigate to your github cloned repositery. Start  _Jupyter Lab_

```
$ jupyter lab
```

### 1. Calculate and Plot the Housing Units per Year.

Once the Jupyter Lab application running, import the data of the target market and use a numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart..


### 2. Calculate and Plot the Average Sale Prices per Square Foot.

Similar process, use a numerical and visual aggregation to calculate the average prices per square foot, and then visualize the results as a line chart.

### 3. Compare the Average Sale Prices by Neighborhood.

Using an interactive visualizations and widgets we start exploring and narrowing the average sale price per square foot by neighborhood.

### 4. Build an Interactive Neighborhood Map

Finally, we explore the geospatial relationships in the data by using interactive visualizations with hvPlot and GeoViews between neighborhood, sales price per square foot and gross rent to indentify investment opportunities within a desired timeframe.

----------

## Contributors

This application originated from a Berkeley Bootcamp.

For any inquieries, feedbacks or comments about this project please email me at  [yanickw@gmail.com](mailto:yanickw@gmail.com)

I can also be reached on  [LinkedIn](https://www.linkedin.com/in/yanickwilisky/)  or  [Twitter](https://twitter.com/yanickwilisky).

----------

## License

MIT License

Copyright (c) 2022 Yanick Wilisky

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
