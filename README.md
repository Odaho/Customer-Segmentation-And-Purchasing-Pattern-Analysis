<body style="font-family: Arial, Helvetica, sans-serif; line-height: 1.6;">

<div align="center">
    <h1>Customer Segmentation & Purchasing-Pattern Report</h1>
</div>

<table align="center" width="1000">
<tr>
<td>
<h2 align="center">Project Background</h2>
<p>
<strong>ShopEase Retail</strong> is a fast-growing e-commerce fashion retailer operating across Clothing, Accessories, Footwear, and Outerwear categories.
</p>
<p>
With approximately <strong>3900 active customers</strong> and thousands of transactions over the last 12 months, ShopEase has accumulated detailed transactional and behavioral data spanning revenue, purchasing patterns, discounts, subscription status, and demographic segmentation.
</p>
<p>
Reporting to the <strong>Head of Commercial Strategy</strong>, this analysis was conducted to evaluate revenue drivers, customer loyalty dynamics, product performance, and long-term profitability risks.
</p>
<p>
The objective of this report is to provide clear, data-backed strategic recommendations to enhance:
</p>
<ul>
<li>Revenue growth sustainability</li>
<li>Customer acquisition and retention</li>
<li>Subscription program performance</li>
<li>Margin protection and discount optimization</li>
<li>Demographic targeting strategy</li>
</ul>
<h3 >Northstar Metrics</h3>

<ul>
<li><strong>Total Revenue Performance</strong> – Category and demographic contribution</li>
<li><strong>Average Purchase Value (APV)</strong> – Basket size trends</li>
<li><strong>Customer Segmentation</strong> – New vs Returning vs Loyal</li>
<li><strong>Subscription Impact</strong> – Revenue and repeat purchase comparison</li>
<li><strong>Discount Sensitivity</strong> – Product-level dependency on promotions</li>
</ul>

</td>
</tr>
</table>
<h2 align="center">Dataset Structure</h2>

<p align="center">
The dataset consists of a transactional customer-level table containing ~3,900 records.
</p>

<table align="center" border="1" cellpadding="8">
  <tr>
    <th>Field</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>customer_id</td>
    <td>Unique customer identifier</td>
  </tr>
  <tr>
    <td>gender</td>
    <td>Customer gender</td>
  </tr>
  <tr>
    <td>age_group</td>
    <td>Customer age segment</td>
  </tr>
  <tr>
    <td>category</td>
    <td>Product category</td>
  </tr>
  <tr>
    <td>item_purchased</td>
    <td>Specific product purchased</td>
  </tr>
  <tr>
    <td>purchase_amount</td>
    <td>Transaction value</td>
  </tr>
  <tr>
    <td>review_rating</td>
    <td>Product rating (1–5)</td>
  </tr>
  <tr>
    <td>shipping_type</td>
    <td>Standard or Express</td>
  </tr>
  <tr>
    <td>subscription_status</td>
    <td>Subscriber vs Non-Subscriber</td>
  </tr>
  <tr>
    <td>previous_purchases</td>
    <td>Number of historical purchases</td>
  </tr>
  <tr>
    <td>discount_applied</td>
    <td>Whether discount was used</td>
  </tr>
</table>

<div align="center">
<h1>Executive Overview</h1>
    <br></br>
<img width="2500" src="images/Executive KPI Overview.png" alt="Executive KPI Overview Placeholder"/>
</div>
<br></br>
<ul>
<li>The business currently serves approximately 3,900 active customers, with revenue primarily driven by a single dominant category: Clothing.</li>
<li>Customer purchasing behavior shows strong loyalty patterns but limited new customer expansion.</li>
<li>Revenue is concentrated across:</li>
    <ul>
        <li>Specific product categories</li>
        <li>Select demographic segments</li>
        <li>Repeat customers</li>
    </ul>
<li>This concentration creates both stability and structural risk.</li>
</ul>

<h1 align="center">Revenue & Volume Performance by Category</h1>

<h2 align="center">Revenue by Category</h2>

<div align="center">
<img width="650" src="images/Revenue By Product Category.png" alt="Revenue by Category"/>
</div>

<table align="center" width="1000">
<tr>
<td>

<h3>Revenue Insights</h3>

<ul>
<li>Revenue is heavily concentrated in the <strong>Clothing</strong> category, making it the primary commercial driver.</li>
<li><strong>Accessories</strong> contribute meaningful secondary revenue but at a materially lower level than Clothing.</li>
<li><strong>Footwear</strong> and <strong>Outerwear</strong> generate comparatively lower revenue contribution.</li>
<li>Revenue distribution indicates limited diversification across categories.</li>
</ul>

<p><strong>Commercial Risk:</strong> High dependency on a single category increases exposure to demand volatility and seasonal fluctuations.</p>

<p><strong>Strategic Consideration:</strong> Revenue diversification initiatives should be explored to reduce structural concentration risk.</p>

</td>
</tr>
</table>

<br><br>


<h2 align="center">Units Sold by Category</h2>

<div align="center">
<img width="650" src="images/Unit Sold By Product Category.png" alt="Units Sold by Category"/>
</div>

<table align="center" width="1000">
<tr>
<td>

<h3>Volume Insights</h3>

<ul>
<li><strong>Clothing</strong> leads in total units sold, confirming strong underlying customer demand.</li>
<li>Accessories maintain moderate volume performance, supporting their role as a complementary category.</li>
<li>Footwear and Outerwear show lower unit volumes, indicating weaker demand relative to other categories.</li>
<li>Volume patterns closely mirror revenue patterns, suggesting that revenue performance is primarily driven by demand rather than price variation.</li>
</ul>

<p><strong>Demand Insight:</strong> Revenue strength in Clothing is volume-driven, not price-driven.</p>

<p><strong>Operational Implication:</strong> Inventory planning should prioritize high-demand categories to prevent stock constraints.</p>

</td>
</tr>
</table>

<br><hr><br>

<h1 align="center">Demographic Revenue Contribution</h1>

<div align="center">
<img width="700" src="images/Revenue by Age Group.png" alt="Revenue by Age Group Placeholder"/>
</div>

<table align="center" width="1000">
<tr>
<td>

<ul>
<li>Young Adults and Middle-Aged customers represent the highest revenue segments.</li>
<li>Seniors contribute the lowest revenue volume.</li>
<li>Revenue aligns strongly with purchase frequency across age groups.</li>
</ul>

<p><strong>Strategic Implication:</strong> Marketing investment should prioritize high-yield demographic groups.</p>

</td>
</tr>
</table>

<br><hr><br>

<h1 align="center">Customer Segmentation Analysis</h1>

<div align="center">
<img width="700" src="images/Customer Segmentation.png" alt="Customer Segmentation Placeholder"/>
</div>

<table align="center" width="1000">
<tr>
<td>

<table align="center" border="1" cellpadding="8">
<tr>
<th>Segment</th>
<th>Definition</th>
</tr>
<tr>
<td>New</td>
<td>1 Purchase</td>
</tr>
<tr>
<td>Returning</td>
<td>2–10 Purchases</td>
</tr>
<tr>
<td>Loyal</td>
<td>More than 10 Purchases</td>
</tr>
</table>

<br>

<ul>
<li>Loyal customers represent the largest proportion of total customers.</li>
<li>New customer acquisition is comparatively low.</li>
</ul>

<p><strong>Strategic Direction:</strong> Retention mechanisms are effective; acquisition strategy requires reinforcement.</p>

</td>
</tr>
</table>

<br><hr><br>

<h1 align="center">Subscription & Loyalty Impact</h1>

<div align="center">
<img width="450" src="images/AVG Spend By Subscription.png" alt="Average Spend by Subscription Placeholder"/>
<img width="450" src="images/Oders By Subscription.png" alt="Orders by Subscription Placeholder"/>
</div>

<table align='center' border="1" cellpadding="6">
<tr>
<th>Metric</th>
<th>Subscribers</th>
<th>Non-Subscribers</th>
</tr>
<tr>
<td>Average Spend</td>
<td>Similar</td>
<td>Similar</td>
</tr>
<tr>
<td>Repeat Purchase Rate</td>
<td>Higher</td>
<td>Lower</td>
</tr>
<tr>
<td>Revenue Contribution</td>
<td>27%</td>
<td>73%</td>
</tr>
</table>

<table align="center" width="1000">
<tr>
<td>

<ul>
<li>Subscribers contribute approximately 27% of total revenue.</li>
<li>Subscribers do not significantly outspend non-subscribers per order.</li>
<li>Subscribers exhibit stronger repeat purchase behavior.</li>
</ul>

<p><strong>Conclusion:</strong> Subscription drives retention rather than increasing basket size.</p>

</td>
</tr>
</table>

<br><hr><br>

<h1 align="center">Business Risks Identified</h1>

<table align="center" width="1000">
<tr>
<td>

<ul>
<li>Revenue concentration within Clothing category.</li>
<li>High discount dependency on selected SKUs.</li>
<li>Low new customer acquisition proportion.</li>
<li>Revenue imbalance across demographic segments.</li>
</ul>

</td>
</tr>
</table>

<br><hr><br>

<h1 align="center">Strategic Recommendations</h1>

<table align="center" width="1000">
<tr>
<td>

<h3>Revenue Strategy</h3>
<ul>
<li>Diversify category-level revenue exposure.</li>
<li>Optimize pricing for high-demand SKUs.</li>
</ul>

<h3>Marketing Strategy</h3>
<ul>
<li>Prioritize Young Adult and Middle-Aged segments.</li>
<li>Develop gender-targeted campaigns.</li>
<li>Strengthen new customer acquisition initiatives.</li>
</ul>

<h3>Loyalty & Subscription Strategy</h3>
<ul>
<li>Focus on retention-based value (exclusive access, loyalty rewards).</li>
<li>Reduce reliance on heavy discount incentives.</li>
</ul>

<h3>Product Strategy</h3>
<ul>
<li>Prioritize inventory for high-rated and high-volume items.</li>
<li>Reduce exposure to low-performing SKUs.</li>
</ul>

</td>
</tr>
</table>

<br><hr><br>

<table align="center" width="1000">
<tr>
<td>

<h2 align="center">Technology Stack</h2>

<ul>
<li>SQL Server – Advanced Querying & Aggregation</li>
<li>Power BI – Executive Dashboard Development</li>
<li>Python (Jupyter Notebook) – Exploratory Analysis</li>
<li>GitHub – Documentation & Version Control</li>
</ul>

<h2 align="center">Project Outcome</h2>

<p>
This engagement demonstrates the transformation of transactional customer data into executive-level commercial insights.
</p>

<p>
The findings provide actionable strategies to improve profitability, retention, and long-term revenue sustainability.
</p>

</td>
</tr>
</table>

<br><br>

</body>
</html>
