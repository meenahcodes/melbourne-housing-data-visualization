# 🏡 Melbourne Housing Data Analysis & Interactive Visualization

# About the Dataset

The dataset contains detailed records of residential property transactions in Melbourne during 2016, featuring:
- **Suburb:** Location of the property.
- **Rooms:** Number of rooms.
- **Price:** Selling price in Australian dollars.
- **Method of Sale:** e.g., Sold, Sold Prior, etc.
- **Type:** Property type (house, townhouse, unit).
- **Distance:** Distance from Melbourne's Central Business District (CBD).
- **Region:** Metropolitan region.
- **Property Count:** Number of properties in each suburb.
- **Additional attributes:** Bedrooms, bathrooms, car spaces, land and building sizes, year built, and local council areas.

# Tools & Technologies Used
- Python
- Pandas (for data cleaning and manipulation)
- Matplotlib (static visualizations)
- Plotly Express (interactive visualizations)
- Jupyter Notebook (interactive analysis)

# Steps 
# 1. Data Preparation

- Loaded and examined the dataset using Pandas.
- Checked for missing values and cleaned the data.
- Ensured data types were appropriate for analysis.

# 2. Data Exploration
- Generated summary statistics to understand data distributions.
- Identified key features relevant to pricing and property type.

# 3. Visualization and Analysis
- **Static Plots:** Created scatter plots, box plots, and histograms to get initial insights into property prices, property types, and location influences.
- **Interactive Plots:** Built interactive versions of scatter plots, box plots, and histograms using Plotly, providing deeper exploration capabilities
- such as (e.g., zooming, hovering to view detailed information).

# 4. Interpretation
- Analyzed plots to identify key insights, such as the influence of distance from the CBD on prices, differences in property types, and typical price distributions.

#  Key Insights & Results
- **Proximity to Central Business District:** Properties closer to Melbourne's CBD generally had higher prices.
- **Property Type Impact:** Houses typically had a wider price range and higher median price compared to townhouses and units.
- **Price Distribution:** Most properties fell within a certain price range, though some significant outliers indicated luxury or unusual sales.

Interactive visualizations provided a richer understanding of these trends by allowing detailed examination of specific data points.

# What I Learned
- Gained hands-on experience in exploratory data analysis (EDA).
- Improved my skills in Python for data analysis and visualization.
- Enhanced my understanding of how interactive visualizations can facilitate deeper insights compared to static graphs.

#  How to Run this Project

To replicate or explore this project yourself:

1. Clone this repository.
2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Open `visualization.ipynb` using Jupyter Notebook or JupyterLab.
4. Execute the notebook cells to see the visualizations and analysis step-by-step.
