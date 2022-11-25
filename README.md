# Southern Water Corp Economical Analysis

# Economic Market Analsis Tab
We will be working with the concepts of Elasticity and Inelasticity and the relation this has to Products. Now this is a very important concept for data analysis in the actual world; our insights will have repercussions on the business and its important we understand how these insights tie into the business. Say for example, if we suddenly had our Netflix account fees raise to $100 per month - a number of us might reconsider whether we still want this subscription. The insight here is that the product is **elastic** (i.e. if we increase the price too sharply, people will leave and go to other streaming platforms). This is tied to the concept of Elasticity (i.e. when the price is low enough, demand is high. Inversely, when the price is high - demand reduces). Now, there are situations that even IF the price rises, we will still purchase the same quantity of goods. Take for example, a particular drug for a pre-existing medical condition. If the price was to rise from its current amount to 10% higher than usual - the amount demanded won't decrease as the product is still required. When this occurs, the product is known as an **inelastic** product. (i.e. Regardless of whether the demand increases or decreases, the price will not change in any substantial manner). With what you've learned, let's take a look at Southern Water Corps Economic Data and see what trends we can identify from an Elasticity and Inelasticity Perspective. Let's be objective and ask ourselves - what does the data tell us? 

**Q1. Please calculate the Average Water Balancing Market Price (WBMP) and Average Quantities of Water Demanded for 1) Hard and Soft Water Combined, 2) Hard Water Only and 3) Soft Water Only across Jan-14 to Dec-14. Do you notice any trends when comparing the Price and Quantity Per Product?** 

We've now taken a look at the data and we can see that there may exist some type of relationship between Quantity of Water Procured and the Overall Price. However, it would be easiest to visually consume this information at both a monthly and daily level. We'll do this first at a macro and then micro level.

**Q2. Using a Scatter Plot and the data you've calculated above, with the Y-Axis set to Avg. Quantity of Water and X-Axis set to Avg. WMBP, create three (3) separate charts showing the Overall (Hard Water + Soft Water) Scatter Plot, Hard Water Scatter Plot and Soft Water Scatter Plot. Note whether the relationship appears to be Elastic or Inelastic alongside your reason as to why this is the case.**

We've now taken plotted three (3) scatter plots and identified whether or not the trend looks elastic or inelastic.
This is the macro view of our analysis. As Data Analysts, it is equally important that we take a micro oriented view of the data. Often looking at the data from a 'macro' perspective, gives us an indication of where we might look and a 'micro' view provides a clearer approach as to whether or not our macro trend is actually legitimate or not. 

**Q3. Using a Scatter Plot and the data in the Water Trading Repository Table, create three (3) separate charts showing the Overall (Hard Water + Soft Water) Scatter Plot, Hard Water Scatter Plot and Soft Water Scatter Plots. (Note: Set the X-axis to the Price and the Y-Axis to the Quantity of Water) Note whether the relationship appears to be Elastic or Inelastic alongside your reason as to why this is the case. Remember, this is the micro analysis so we are now using the Raw Data Entries (individual data points in the Water Trading Repository Table Tab) as opposed to the aggregated averages.**


# Economic Cost Analysis Tab

In Economic Data Analysis, we seek to make use of as much data as possible to help us better understand and extract key business insights. Now a common phrase in economic data analysis is, "We need to compare things in an apples-for-apples like methodology". With Southern Water Corp, we have a bunch of economic and financial data. We're going to use the tools of Economic Data Analysis to create insights from this and identify which of our three desalination plants are most cost effective. Previously we've calculated the proportion of revenues that are generated, the expenses and the associated amount of water production. Using economics, we are now going to combine all this information together and create an economic metric to evaluate each plants performance to create our own 'apples-to-apples' comparison. For each of the three Southern Water Corp. Desalination Plants, we have an econometric measure called the Desalinated Plant Cost to Produce, or *Cost to Produce* for short. The Cost to Produce ties together the different costs for each Plant and enables us to create a metric to evaluate how cost-effective the plant is.

**Q4. Please calculate the Cost to Produce for each of the three (3) desalination plants below using the following formula per plant:
Plant Cost to Produce = ( Chemical Costs + Facility Costs + Operational Maintenance Costs + Labour Costs ) / Total Volume of Water Produced for the Month (GL) * 1,000 (To Convert to Mega-Litres from Giga Litres). What trends are you able to pick up from completing the table below?**

You've now calculated the Desalinated Cost to Produce for each of the three desalination plants (Kootha, Surjek and Jutik). This has given you a micro-view of the trends, but let's take a look at the macro-view of the situation and look at how the aggregated cost to produce (Kootha + Surjek + Jutik) look.

**Q5) Aggregate the Cost Centre(s) for each Plant (i.e.Chemical Costs, Facility Costs, Operational Maintenance Costs, Labour Costs) in the table below.
Subsequently, in one chart, plot out the Overall Cost to Produce, as well as the Cost to Produce for Kootha, Surjek and Jutik for comparison. What trends do you note when looking at the data in this way? **

In Economics, we care about our overall Cost to Produce Desalinated Water as it gives us an indication of how cost-effective our plants are. It's important in our Economic Data Analysis to also interpret this price-point with respect to the volume of water that is produced.

This touches upon a concept known as **economies of scale**. Essentially, the more water we produce - the cheaper we should see our production costs. On the other hand, the less water we produce, the more our Cost to Produce will increase on scaled basis. 

**Q6) Using the Monthly Cost to Produce you've calculated for each Plant (Kootha, Surjek and Jutik), create a scatter-plot which shows the Cost to Produce (Y-Axis) against the Total Volume of Water produced.**

You will end up with three Scatter Plots that will let you see whether a relationship exists between Cost to Produce and the Volume of Water produced. Does there appear to be a relationship between Cost to Produce and Volume of Water Produced?

We've now analysed our Cost to Produce and we can clearly see the following trends emerge:
A) There are differences in cost effectiveness between plants which are largely influenced by the costs and the volume of water produced
B) We can pick up a relationship between the Cost to Produce and Quantity of Water being produced.

This brings us to our last questions for the Economic Cost Analysis.
1. How are our desalination plants performing according to our budget at a macro level?
2. What is driving this variance, or difference, between the Actuals and Budget?
3. Are there any Units which are not cost effective with respect to the Water Balancing Market Price?

Let's answer these questions by first calculating the Budgeted Desalinated Cost to Produce and then calculate our respective variances to understand what costs are driving these respective negative variances (if any). 

**Q7. A) Utilising the Financial Budget Information contained in the Data Repository Tab, complete the 4 tables below for all the Desalination Plants combined (Kootha + Surjek + Jutik), and then individually for each Desalination Plant.**

Now we've populated the Financial Budget - it's time for us to calculate the Financial Variance between the Actuals you've calculated in Q4 and the budget you've just completed. **Financial Variance** is the difference between the Budget and the Actuals that have been incurred (this is not to be confused with statistical variance which measures the level of dispersion between data). Say for example, you're interested in understanding whether you've spent all the money you said you would for this month - or whether you were able to spend less. We use Financial Variance to better inform us of any discrepencies between our Budget and Actuals. If we spend far more than we expected, then we've got a problem. Using the formula, *Budget - Actuals*, create a table of the variance. 

**Q7. B) Using the formula Budget - Actuals, complete the Financial Variance Calculation for each of the tables below.**

And now we're finally at the last question for the Economic Cost Analysis Assignment! We've understood how supply and demand factors influence the pricing of our products. We've also understood how an economic metric (Cost to Produce for Desalinated Water) provides us a view as to how cost-effective our plants are and compared this to the budget. Now we'll close off the Economic Cost Analysis with an understanding of comparing the Market Price against the $/Mega-Litre of our individual desalination plants. 

**Q8. Completing the table below, create a combo-chart (e.g. Column Chart to represent Overall Desalination Cost to Produce $/ML & Line Chart showing the Overall Average WBMP Market Price) that clearly illustrates the Overall Desalination Cost to Produce and the Overall Average WBMP Market Price. What do you note from this?**
