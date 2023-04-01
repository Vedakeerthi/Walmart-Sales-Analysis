# Walmart Sales Analysis

## Table of Content
  * [Demo](#demo)
  * [Synopsis](#synopsis)
  * [Appendix](#appendix)
  * [Directory Tree](#directory_tree)
  * [Color Reference](#color_reference)
  * [Features](#features)
  * [Run Locally](#run_locally)
  * [License](#license)
  * [Technology Used](#technology_used)

## Demo

![](https://github.com/Vedakeerthi/Walmart-Sales-Analysis/blob/main/Result.png)

## Synopsis

Data analysis have been made on the walmart data using the Microsoft Power BI tool for data visualization, where the different features of the walmart data are viewed with various powerful graphs. Power-BI is considered as a far most powerful visualization tool when compared to matplotlib or seaborn, because we can able to interact with the dashboards, with the help of which more insights can be obtained from the data. 

Let's consider the dataset, where the order id of the particular order, the ship date of the order, the customer name, other details of the customer name such as where he lives in, his region, the sales index about the customer and the order he purchases, then the quantity of the order, discount provided to the order, and the overall profit for the particular order.

To start with the visualization, two card charts are created based on the sales and the profit, and followed by which the profit obtained by the walmart based on the category of item it solds to its customer are shown in a Treemap.

Then the sales and profit by Year is calculated or visualized by using Area chart, then to find out the repetitive customer to the walmart, the count of order id by using the customer name is visualized using the clustered bar chart. 

A decomposition tree is used to have a overall visual of the walmart dataset where the sales is decomposed into its various categories, and another tree extends with each categories, which tells us about the customer who boughts things in the particular category and followed by the region he brought.

And overall all the visualization have been made over the dataset, and finally two slicers are created, one for the category and the other for the sub category, and if we alter the slicers we can see that there is an impact over all the other charts, so concluding this PowerBI is a very powerful tool for data visualization and very user friendly.

## Appendix

The dashboard which is created using power-bi is present in the [Walmart.pbix](https://github.com/Vedakeerthi/Walmart-Sales-Analysis/blob/main/Walmart.pbix) file.

The dataset of the walmart store is present in [Walmart.csv](https://github.com/Vedakeerthi/Walmart-Sales-Analysis/blob/main/Walmart.csv) file.

A sample image of the dashboard is stored as [Result.png](https://github.com/Vedakeerthi/Walmart-Sales-Analysis/blob/main/Result.png) image.

## Directory Tree <a name='directory_tree'></a>

```
├── LICENSE
├── README.md
├── Result.png
├── Walmart.csv
├── Walmart.pbix
```
 
## Color Reference <a name='color_reference'></a>

| Color                         | Hex                                                                  |
| ------------------------------| ---------------------------------------------------------------------|
| Background of the dashboard   | ![#eb895f](https://via.placeholder.com/15/eb895f/eb895f.png) #eb895f |
| Card Chart                    | ![#ffffff](https://via.placeholder.com/15/fffff/ffffff.png) #ffffff |
| Tree map, Clustered bar chart | ![#000000](https://via.placeholder.com/15/000000/000000.png) #000000 |
| Slicer                        | ![#a0d1ff](https://via.placeholder.com/15/a0d1ff/a0d1ff.png) #a0d1ff |

## Features

- Easy to use.
- Helps organize data.
- Customize your dashboard.
- Offers many built-in analytics.

## Run Locally <a name='run_locally'></a>

Clone the project

```bash
  git clone https://github.com/Vedakeerthi/Walmart-Sales-Analysis.git
```

Install dependencies

```bash
  Install Power-BI application
```

Open the dashboard

```bash
  Just double click on the dashboard (walmart.pbix) file and open it in power-bi application.
```

## License

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/Vedakeerthi/Walmart-Sales-Analysis/blob/main/LICENSE)

## Technology Used <a name='technology_used'></a>

<a href="https://powerbi.microsoft.com/en-au/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_powerbi/microsoft_powerbi-icon.svg" alt="power-bi" width="40" height="40"/> </a>
