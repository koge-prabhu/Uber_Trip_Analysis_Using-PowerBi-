<h1>📊 Uber Trip Analysis<h1></h1>
This repository contains a Power BI dashboard for visualizing and analyzing Uber trip data.
The dashboard helps stakeholders explore bookings, trip distances, revenues, peak times, and location patterns from Uber ride records.
<h1>🚀 Project Overview</h1>
The Uber Trip Analysis dashboard provides summary and detailed insights into Uber ride data from June 1 to June 30, 2024. It’s designed to help understand:


<br>1.Total bookings and revenue

2.Average trip statistics

3.Booking patterns by time and day

4.Most frequent pickup and dropoff locations

5.Preferred vehicles and distance metrics

<h1>🧭 1. Overview Analysis</h1>
<img src="https://github.com/koge-prabhu/Uber_Trip_Analysis_Using-PowerBi-/blob/main/Screenshots/Screenshot%202025-12-24%20111151.png" width="800">
<table border="1">
  <tr>
    <th>Metric    </th>
    <th>Description </th>
  </tr>
  <tr>
    <td>104K Total Bookings</td>
    <td>Total trips recorded </td>
  </tr>
  <tr>
    <td>$1.6M Booking Value</td>
    <td>Combined revenue</td>
  </tr>
  <tr>
    <td>$15 Avg Booking Value</td>
    <td>Average fare value  </td>
  </tr>
  <tr>
    <td>349K Miles</td>
    <td>Total distance covered </td>
  </tr>
  <tr>
    <td>3 Miles</td>
    <td>Average distance covered </td>
  </tr>
  <tr>
    <td>16 Min</td>
    <td>Avg trip duration </td>
  </tr>
  
</table>
<h2>Visual Highlights:</h2>
1.Booking value by payment type & day/night<br>
2.Frequent pickup and drop-off locations<br>
3.Vehicle type performance

<h1>⏱ 2. Time Analysis</h1>
<img src="https://github.com/koge-prabhu/Uber_Trip_Analysis_Using-PowerBi-/blob/main/Screenshots/Screenshot%202025-12-24%20111202.png" width="800">
<h2>Explores temporal booking patterns:</h2>
1.Booking trends by pickup hour<br>
2.Heatmap of bookings by day of week and hour<br>
3.Weekday vs weekend booking behavior


<h1>📋 3. Detail Analysis</h1>
<table>
  <thead>
    <tr>
      <th>Column</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Trip ID</td>
      <td>Unique trip identifier</td>
    </tr>
    <tr>
      <td>Pickup Date</td>
      <td>Pickup date</td>
    </tr>
    <tr>
      <td>Vehicle</td>
      <td>Uber service type</td>
    </tr>
    <tr>
      <td>Payment Type</td>
      <td>Cash, Uber Pay, etc.</td>
    </tr>
    <tr>
      <td>Passenger Count</td>
      <td>Number of passengers</td>
    </tr>
    <tr>
      <td>Trip Distance</td>
      <td>Distance in miles</td>
    </tr>
    <tr>
      <td>Booking Value</td>
      <td>Fare earned</td>
    </tr>
    <tr>
      <td>Pickup Location</td>
      <td>Location ID</td>
    </tr>
    <tr>
      <td>Pickup Hour</td>
      <td>Hour of the trip</td>
    </tr>
  </tbody>
</table>

<h1>📊 Insights</h1>
<h2>🔍 Key findings from the dashboard:</h2>
1.Highest bookings occur during mid-day and early evening.<br>
2.Cash and Uber Pay are the top payment methods.<br>
3.Frequent pickups happen around Penn Station / Madison Sq West.<br>
4.Longest recorded trip was 144.1 miles.<br>
5.UberX consistently generates the most bookings and booking value.

<h1>🛠 Tools & Technologies</h1>
<table>
  <thead>
    <tr>
      <th>Tool</th>
      <th>Purpose</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Power BI Desktop</strong></td>
      <td>Data visualization and dashboard design</td>
    </tr>
    <tr>
      <td><strong>DAX</strong></td>
      <td>Calculations and measures</td>
    </tr>
    <tr>
      <td><strong>CSV / Excel</strong></td>
      <td>Source data</td>
    </tr>
  </tbody>
</table>
<h1>🧩 Data Fields (Sample)</h1>
<table>
  <thead>
    <tr>
      <th>Field</th>
      <th>Type</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Trip ID</td>
      <td>Integer</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Pickup Date</td>
      <td>Date</td>
      <td>2024-06-01</td>
    </tr>
    <tr>
      <td>Vehicle</td>
      <td>Text</td>
      <td>UberX</td>
    </tr>
    <tr>
      <td>Payment Type</td>
      <td>Text</td>
      <td>Cash</td>
    </tr>
    <tr>
      <td>Passenger Count</td>
      <td>Integer</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Trip Distance</td>
      <td>Decimal</td>
      <td>5.90</td>
    </tr>
    <tr>
      <td>Booking Value</td>
      <td>Currency</td>
      <td>$19.00</td>
    </tr>
    <tr>
      <td>Pickup Location</td>
      <td>Integer</td>
      <td>74</td>
    </tr>
    <tr>
      <td>Pickup Hour</td>
      <td>Integer</td>
      <td>2</td>
    </tr>
  </tbody>
</table>
<h1>📌 Filters & Interactivity</h1>
<h2>The dashboard includes:</h2>
✔ Date range picker (e.g., June 1–30, 2024)<br>
✔ City filter (All Cities / specific)<br>
✔ Vehicle type breakdown<br>
✔ Hover and cross-filter visual actions
