# Amazon-Sales-Data-Analytics
<h1>Introduction</h1>
<p>Amazon Sales Data Analysis is a process that involves examining and interpreting data related to sales transactions on Amazon's platform. This type of analysis is crucial for businesses and individuals who sell products on Amazon, as it provides valuable insights into sales performance, customer behavior, market trends, and product effectiveness.</p>
<h1>Table of contents</h1>
<ol><h2> 1.Importing Dataset</h2>
<h2>2.Data preparation and cleaning</h2>
<h2>3.Data Visualizations</h2></ol>
<h2>Importing Dataset </h2>
<p>Import the Python Libraries Such as Pandas , Numpy , Matplotlib and Seaborn in Jupyter Notebook. Download the Amazon Sales Dataset from the Kaggle and Import it as a Data Frame in the Jupyter Notebook</p>
<img src="">
<h2>Data Preparation And Data cleaning </h2>
<H3>Data Preparation</H3>
<P>From the imported Dataset , Look out the columns and Data. Take the necessary Data that you want to analyse for visualisation.</P>
<img src="">
<h3>Data Cleaning</h3>
<p>In Data Cleaning, Clean the dataset with the duplicate values. These duplicate values can disturb the visualisation process. Renaming the columns with our interest and neglecting the null values in the dataset</p>
<img src="">
<h2>Data Visualizations</h2>
<p>Data Visualization helps us to know the imformation about the data with some Innovative Charts </p>
<h3>Count Plot</h3>
<p>A countplot is a type of bar plot that represents the frequency or count of occurrences for each category in a categorical variable. It is commonly used in Exploratory Data Analysis (EDA) to visualize the distribution of categorical data. When visualizing the sizes of goods, a countplot can be particularly useful to show how many items fall into each size category (e.g., small, medium, large). This allows for a quick assessment of the most common sizes and any potential imbalances in the distribution. The countplot is typically created using libraries like Seaborn, which provides an easy-to-use interface for generating these plots with additional customization options, such as color palettes and orientation.</p>
<img src="">
<h3>Bar Plot</h3>
<p>A bar plot is a versatile visualization tool that displays the relationship between a categorical variable and a numerical variable by representing the data with rectangular bars. When used to show the sizes of goods by their quantity, a bar plot can effectively illustrate how many units of each size are available. Each bar represents a different size category (e.g., small, medium, large), and the height or length of the bar corresponds to the quantity of goods in that size. This allows for easy comparison between different sizes, helping to quickly identify which size has the most or least inventory. Bar plots are particularly useful for visualizing and comparing the quantities of different categories, providing a clear and concise overview of the distribution of goods by size.</p>
<img src="">
<h3> Count Plot with two Datas </h3>
<p>A countplot is an effective visualization tool for displaying the frequency of categories within a categorical variable. When used to show the courier status of goods, a countplot can illustrate how many shipments fall into each status category, such as "In Transit," "Delivered," "Pending," or "Returned." Each bar in the countplot represents a different courier status, with the height or length of the bar indicating the number of goods in that status. This provides a clear and immediate overview of the distribution of goods across different courier statuses, making it easier to identify which statuses are most or least common and to monitor the overall progress of shipments. </p>
<img src="">
<h3> Histogram for Sizes </h3>
<p>A histogram is a useful tool for visualizing the distribution of numerical data, like the sizes of goods in an Amazon dataset. It represents the frequency of different size ranges by dividing the data into bins (intervals) and showing how many items fall into each bin. In the context of an Amazon dataset, a histogram of product sizes could reveal common size categories, such as whether most goods are small, medium, or large. This can help identify patterns in product dimensions, inform inventory management, and optimize packaging or storage strategies. The shape of the histogram (e.g., skewed, uniform, or normal distribution) can also provide insights into the variety and diversity of products offered on the platform.</p>
<img src="">
<h3>Histogram for Category </h3>
<p>A histogram is typically used for numerical data, but when dealing with categorical data, such as the categories of goods in an Amazon dataset, a bar chart is more appropriate. However, if you consider representing the count of items within each category using a histogram-like approach, it could help visualize the distribution of products across different categories.
In this context, each bar would represent a specific category (e.g., electronics, clothing, home goods), and the height of the bar would indicate the number of items within that category. This visualization can reveal the most and least common categories of products, helping to understand the distribution and variety of goods offered on Amazon. It can also aid in identifying trends in consumer preferences and inventory distribution.</p>
<img src="">
<h3>Pie - Chart for Fulfilment</h3>
<p>A pie chart is an effective tool for visualizing the proportions of different categories within a dataset, particularly when you want to show how parts contribute to a whole. In the context of an Amazon dataset, a pie chart could be used to illustrate the distribution of fulfillment methods for goods, such as items fulfilled by Amazon (FBA), third-party sellers, or direct shipping from manufacturers.
Each slice of the pie would represent a different fulfillment method, with the size of the slice corresponding to the proportion of goods fulfilled through that method. This can provide a clear visual understanding of how Amazon manages its logistics, highlighting the dominant fulfillment channels and offering insights into operational strategies and consumer preferences for shipping options. Pie charts are particularly useful when you want to quickly compare the relative sizes of these categories.</p>
<img src="">
<h3>Scatterplot for Category </h3>
<P>A scatterplot for the categories of goods in an Amazon dataset visually represents the relationship between two numerical variables, such as price and ratings, across various product categories. Each point on the plot corresponds to a product, with its position determined by its price and rating. By using different colors or markers for each category, the scatterplot reveals patterns and correlations, such as whether higher-priced items tend to receive better ratings or if certain categories have distinctive pricing or rating trends. This visualization helps in identifying trends, spotting outliers, and comparing the performance of different product categories, offering valuable insights for decision-making and strategy development.</P>
<img src="">
<h3>Barchart for Counts with respect to states </h3>
<p>A bar chart for counts with respect to states of goods in an Amazon dataset provides a clear visual representation of the distribution of products across different states . Each bar in the chart represents a state, with the height of the bar indicating the number of products in that state. This type of chart makes it easy to compare the quantity of products available in each state, highlighting which states have the most or least inventory. It helps in quickly assessing the distribution of goods and can inform inventory management and marketing strategies by showing the relative popularity or availability of different product states.</p>
<img src="">

<h2>Conclusion</h2>
<p> Visualizations of the Amazon dataset—such as scatterplots and bar charts—offer valuable insights into the distribution and relationships within the data. Scatterplots reveal patterns and correlations between numerical variables like price and ratings across different product categories, helping to identify trends and outliers. Bar charts, on the other hand, provide a straightforward view of the distribution of products across various states or conditions, highlighting inventory levels and availability. Together, these visualizations enable a comprehensive understanding of product dynamics, facilitating informed decision-making for inventory management, pricing strategies, and market analysis. By leveraging these insights, businesses can optimize their operations and better meet customer needs.</p>

