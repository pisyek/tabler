---
title: Charts
docs-libs: [apexcharts]
summary: Tabler uses ApexCharts - a free and open-source modern charting library that helps developers to create beautiful and interactive visualizations for web pages.
description: Interactive data visualizations with ApexCharts.
---

To be able to use the charts in your application you will need to install the apexcharts dependency with `npm install apexcharts`.

See also the [ApexCharts](https://apexcharts.com/) documentation.

## Line Chart

Line charts are an essential tool for visualizing data trends over time. They are particularly useful for representing continuous data, such as stock prices, website traffic, or user activity. Below is an example of a line chart showcasing session duration, page views, and total visits:

{% capture html -%}
<div class="card">
  <div class="card-body">
    <div id="chart-demo-line" class="chart-lg"></div>
  </div>
</div>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    window.ApexCharts &&
      new ApexCharts(document.getElementById("chart-demo-line"), {
        chart: {
          type: "line",
          fontFamily: "inherit",
          height: 240,
          parentHeightOffset: 0,
          toolbar: {
            show: false,
          },
          animations: {
            enabled: false,
          },
        },
        fill: {
          opacity: 1,
        },
        stroke: {
          width: 2,
          lineCap: "round",
          curve: "straight",
        },
        series: [
          {
            name: "Session Duration",
            data: [117, 92, 94, 98, 75, 110, 69, 80, 109, 113, 115, 95],
          },
          {
            name: "Page Views",
            data: [59, 80, 61, 66, 70, 84, 87, 64, 94, 56, 55, 67],
          },
          {
            name: "Total Visits",
            data: [53, 51, 52, 41, 46, 60, 45, 43, 30, 50, 58, 59],
          },
        ],
        tooltip: {
          theme: "dark",
        },
        grid: {
          padding: {
            top: -20,
            right: 0,
            left: -4,
            bottom: -4,
          },
          strokeDashArray: 4,
        },
        xaxis: {
          labels: {
            padding: 0,
          },
          tooltip: {
            enabled: false,
          },
          type: "datetime",
        },
        yaxis: {
          labels: {
            padding: 4,
          },
        },
        labels: [
          "2020-06-21",
          "2020-06-22",
          "2020-06-23",
          "2020-06-24",
          "2020-06-25",
          "2020-06-26",
          "2020-06-27",
          "2020-06-28",
          "2020-06-29",
          "2020-06-30",
          "2020-07-01",
          "2020-07-02",
        ],
        colors: ["var(--tblr-yellow)", "var(--tblr-green)", "var(--tblr-primary)"],
        legend: {
          show: true,
          position: "bottom",
          offsetY: 12,
          markers: {
            width: 10,
            height: 10,
            radius: 100,
          },
          itemMargin: {
            horizontal: 8,
            vertical: 8,
          },
        },
      }).render();
  });
</script>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Area Chart

Area charts are ideal for representing cumulative data over time. They add visual emphasis to trends by filling the space under the line, making it easier to compare values. Here's an example of an area chart with smooth transitions and data from two series:

{% capture html -%}
<div class="card">
  <div class="card-body">
    <div id="chart-demo-area" class="chart-lg"></div>
  </div>
</div>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    window.ApexCharts &&
      new ApexCharts(document.getElementById("chart-demo-area"), {
        chart: {
          type: "area",
          fontFamily: "inherit",
          height: 240,
          parentHeightOffset: 0,
          toolbar: {
            show: false,
          },
          animations: {
            enabled: false,
          },
        },
        dataLabels: {
          enabled: false,
        },
        fill: {
          opacity: 0.16,
          type: "solid",
        },
        stroke: {
          width: 2,
          lineCap: "round",
          curve: "smooth",
        },
        series: [
          {
            name: "series1",
            data: [56, 40, 39, 47, 34, 48, 44],
          },
          {
            name: "series2",
            data: [45, 43, 30, 23, 38, 39, 54],
          },
        ],
        tooltip: {
          theme: "dark",
        },
        grid: {
          padding: {
            top: -20,
            right: 0,
            left: -4,
            bottom: -4,
          },
          strokeDashArray: 4,
        },
        xaxis: {
          labels: {
            padding: 0,
          },
          tooltip: {
            enabled: false,
          },
          axisBorder: {
            show: false,
          },
          type: "datetime",
        },
        yaxis: {
          labels: {
            padding: 4,
          },
        },
        labels: [
          "2020-06-21",
          "2020-06-22",
          "2020-06-23",
          "2020-06-24",
          "2020-06-25",
          "2020-06-26",
          "2020-06-27",
        ],
        colors: ["var(--tblr-primary)", "var(--tblr-purple)"],
        legend: {
          show: true,
          position: "bottom",
          offsetY: 12,
          markers: {
            width: 10,
            height: 10,
            radius: 100,
          },
          itemMargin: {
            horizontal: 8,
            vertical: 8,
          },
        },
      }).render();
  });
</script>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Bar Chart

Bar charts are highly effective for comparing data across different categories. They provide a clear and concise way to visualize differences in values, making them perfect for analyzing categorical data. Here's an example of a bar chart with stacked bars for enhanced readability:

{% capture html -%}
<div class="card">
  <div class="card-body">
    <div id="chart-demo-bar" class="chart-lg"></div>
  </div>
</div>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    window.ApexCharts &&
      new ApexCharts(document.getElementById("chart-demo-bar"), {
        chart: {
          type: "bar",
          fontFamily: "inherit",
          height: 240,
          parentHeightOffset: 0,
          toolbar: {
            show: false,
          },
          animations: {
            enabled: false,
          },
          stacked: true,
        },
        plotOptions: {
          bar: {
            barHeight: "50%",
            horizontal: true,
          },
        },
        dataLabels: {
          enabled: false,
        },
        fill: {
          opacity: 1,
        },
        series: [
          {
            name: "Container for a Fanta",
            data: [44, 55, 41, 37, 22, 43, 21],
          },
          {
            name: "Strange sunglasses",
            data: [53, 32, 33, 52, 13, 43, 32],
          },
          {
            name: "Pen Pineapple Apple Pen",
            data: [12, 17, 11, 9, 15, 11, 20],
          },
          {
            name: "Binoculars",
            data: [9, 7, 5, 8, 6, 9, 4],
          },
          {
            name: "Magical notebook",
            data: [25, 12, 19, 32, 25, 24, 10],
          },
        ],
        tooltip: {
          theme: "dark",
        },
        grid: {
          padding: {
            top: -20,
            right: 0,
            left: -4,
            bottom: -4,
          },
          strokeDashArray: 4,
        },
        xaxis: {
          labels: {
            padding: 0,
            formatter: function (val) {
              return val + "K";
            },
          },
          tooltip: {
            enabled: false,
          },
          axisBorder: {
            show: false,
          },
          categories: ["2008", "2009", "2010", "2011", "2012", "2013", "2014"],
        },
        yaxis: {
          labels: {
            padding: 4,
          },
        },
        colors: [
          "var(--tblr-purple)",
          "var(--tblr-green)",
          "var(--tblr-yellow)",
          "var(--tblr-red)",
          "var(--tblr-primary)",
        ],
        legend: {
          show: true,
          position: "bottom",
          offsetY: 12,
          markers: {
            width: 10,
            height: 10,
            radius: 100,
          },
          itemMargin: {
            horizontal: 8,
            vertical: 8,
          },
        },
      }).render();
  });
</script>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Pie Chart

Pie charts are a simple and effective way to visualize proportions and ratios. They are commonly used to represent data as percentages of a whole, making them ideal for displaying parts of a dataset. Below is an example of a pie chart showcasing distribution across categories:

{% capture html -%}
<div class="card">
  <div class="card-body">
    <div id="chart-demo-pie" class="chart-lg"></div>
  </div>
</div>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    window.ApexCharts &&
      new ApexCharts(document.getElementById("chart-demo-pie"), {
        chart: {
          type: "donut",
          fontFamily: "inherit",
          height: 240,
          sparkline: {
            enabled: true,
          },
          animations: {
            enabled: false,
          },
        },
        fill: {
          opacity: 1,
        },
        series: [44, 55, 12, 2],
        labels: ["Direct", "Affilliate", "E-mail", "Other"],
        tooltip: {
          theme: "dark",
        },
        grid: {
          strokeDashArray: 4,
        },
        colors: [
          "var(--tblr-primary)",
          "color-mix(in oklab, var(--tblr-primary) 0.8, transparent)",
          "color-mix(in oklab, var(--tblr-primary) 0.6, transparent)",
          "var(--tblr-gray-300)",
        ],
        legend: {
          show: true,
          position: "bottom",
          offsetY: 12,
          markers: {
            width: 10,
            height: 10,
            radius: 100,
          },
          itemMargin: {
            horizontal: 8,
            vertical: 8,
          },
        },
      }).render();
  });
</script>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Heatmap Chart

Heatmaps provide a graphical representation of data where individual values are represented by color intensity. They are particularly useful for identifying patterns or anomalies within large datasets. Here's an example of a heatmap chart to visualize data distributions:

{% capture html -%}
<div class="card">
  <div class="card-body">
    <div id="chart-demo-heatmap" class="chart-lg"></div>
  </div>
</div>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    window.ApexCharts &&
      new ApexCharts(document.getElementById("chart-demo-heatmap"), {
        chart: {
          type: "heatmap",
          fontFamily: "inherit",
          height: 240,
          animations: {
            enabled: false,
          },
          toolbar: {
            show: false,
          },
        },
        tooltip: {
          theme: "dark",
        },
        fill: {
          opacity: 1,
        },
        series: [
          {
            name: "New York",
            data: [
              { x: "Monday", y: 22 },
              { x: "Tuesday", y: 24 },
              { x: "Wednesday", y: 19 },
              { x: "Thursday", y: 23 },
              { x: "Friday", y: 25 },
              { x: "Saturday", y: 27 },
              { x: "Sunday", y: 26 },
            ],
          },
          {
            name: "Los Angeles",
            data: [
              { x: "Monday", y: 28 },
              { x: "Tuesday", y: 30 },
              { x: "Wednesday", y: 27 },
              { x: "Thursday", y: 29 },
              { x: "Friday", y: 31 },
              { x: "Saturday", y: 32 },
              { x: "Sunday", y: 33 },
            ],
          },
          {
            name: "Chicago",
            data: [
              { x: "Monday", y: 18 },
              { x: "Tuesday", y: 20 },
              { x: "Wednesday", y: 17 },
              { x: "Thursday", y: 19 },
              { x: "Friday", y: 21 },
              { x: "Saturday", y: 22 },
              { x: "Sunday", y: 23 },
            ],
          },
          {
            name: "Houston",
            data: [
              { x: "Monday", y: 25 },
              { x: "Tuesday", y: 27 },
              { x: "Wednesday", y: 24 },
              { x: "Thursday", y: 26 },
              { x: "Friday", y: 28 },
              { x: "Saturday", y: 29 },
              { x: "Sunday", y: 30 },
            ],
          },
          {
            name: "Phoenix",
            data: [
              { x: "Monday", y: 33 },
              { x: "Tuesday", y: 35 },
              { x: "Wednesday", y: 32 },
              { x: "Thursday", y: 34 },
              { x: "Friday", y: 36 },
              { x: "Saturday", y: 37 },
              { x: "Sunday", y: 38 },
            ],
          },
          {
            name: "Philadelphia",
            data: [
              { x: "Monday", y: 20 },
              { x: "Tuesday", y: 22 },
              { x: "Wednesday", y: 19 },
              { x: "Thursday", y: 21 },
              { x: "Friday", y: 23 },
              { x: "Saturday", y: 24 },
              { x: "Sunday", y: 25 },
            ],
          },
        ],
        colors: ["var(--tblr-primary)"],
        dataLabels: {
          enabled: false,
        },
        xaxis: {
          tooltip: {
            enabled: false,
          },
        },
        title: {
          text: "Average Temperature by Day and City",
        },
      }).render();
  });
</script>
{%- endcapture %}
{% include "docs/example.html" html=html %}

## Advanced example

For more complex data visualizations, you can create advanced charts with multiple series and custom configurations. Below is an example of a social media referrals chart combining data from Facebook, Twitter, and Dribbble:

{% capture html -%}
<div class="card">
  <div class="card-body">
    <div id="chart-social-referrals" class="chart-lg"></div>
  </div>
</div>
<script>
  document.addEventListener("DOMContentLoaded", function () {
    window.ApexCharts &&
      new ApexCharts(document.getElementById("chart-social-referrals"), {
        chart: {
          type: "line",
          fontFamily: "inherit",
          height: 240,
          parentHeightOffset: 0,
          toolbar: {
            show: false,
          },
          animations: {
            enabled: false,
          },
        },
        fill: {
          opacity: 1,
        },
        stroke: {
          width: 2,
          lineCap: "round",
          curve: "smooth",
        },
        series: [
          {
            name: "Facebook",
            data: [
              13281, 8521, 15038, 9983, 15417, 8888, 7052, 14270, 5214, 9587, 5950, 16852, 17836,
              12217, 17406, 12262, 9147, 14961, 18292, 15230, 13435, 10649, 5140, 13680, 4508,
              13271, 13413, 5543, 18727, 18238, 18175, 6246, 5864, 17847, 9170, 6445, 12945, 8142,
              8980, 10422, 15535, 11569, 10114, 17621, 16138, 13046, 6652, 9906, 14100, 16495, 6749,
            ],
          },
          {
            name: "Twitter",
            data: [
              3680, 1862, 3070, 2252, 5348, 3091, 3000, 3984, 5176, 5325, 2420, 5474, 3098, 1893,
              3748, 2879, 4197, 5186, 4213, 4334, 2807, 1594, 4863, 2030, 3752, 4856, 5341, 3954,
              3461, 3097, 3404, 4949, 2283, 3227, 3630, 2360, 3477, 4675, 1901, 2252, 3347, 2954,
              5029, 2079, 2830, 3292, 4578, 3401, 4104, 3749, 4457, 3734,
            ],
          },
          {
            name: "Dribbble",
            data: [
              722, 1866, 961, 1108, 1110, 561, 1753, 1815, 1985, 776, 859, 547, 1488, 766, 702, 621,
              1599, 1372, 1620, 963, 759, 764, 739, 789, 1696, 1454, 1842, 734, 551, 1689, 1924,
              1875, 908, 1675, 1541, 1953, 534, 502, 1524, 1867, 719, 1472, 1608, 1025, 889, 1150,
              654, 1695, 1662, 1285, 1787,
            ],
          },
        ],
        tooltip: {
          theme: "dark",
        },
        grid: {
          padding: {
            top: -20,
            right: 0,
            left: -4,
            bottom: -4,
          },
          strokeDashArray: 4,
          xaxis: {
            lines: {
              show: true,
            },
          },
        },
        xaxis: {
          labels: {
            padding: 0,
          },
          tooltip: {
            enabled: false,
          },
          type: "datetime",
        },
        yaxis: {
          labels: {
            padding: 4,
          },
        },
        labels: [
          "2020-06-21",
          "2020-06-22",
          "2020-06-23",
          "2020-06-24",
          "2020-06-25",
          "2020-06-26",
          "2020-06-27",
          "2020-06-28",
          "2020-06-29",
          "2020-06-30",
          "2020-07-01",
          "2020-07-02",
          "2020-07-03",
          "2020-07-04",
          "2020-07-05",
          "2020-07-06",
          "2020-07-07",
          "2020-07-08",
          "2020-07-09",
          "2020-07-10",
          "2020-07-11",
          "2020-07-12",
          "2020-07-13",
          "2020-07-14",
          "2020-07-15",
          "2020-07-16",
          "2020-07-17",
          "2020-07-18",
          "2020-07-19",
          "2020-07-20",
          "2020-07-21",
          "2020-07-22",
          "2020-07-23",
          "2020-07-24",
          "2020-07-25",
          "2020-07-26",
          "2020-07-27",
          "2020-07-28",
          "2020-07-29",
          "2020-07-30",
          "2020-07-31",
          "2020-08-01",
          "2020-08-02",
          "2020-08-03",
          "2020-08-04",
          "2020-08-05",
          "2020-08-06",
          "2020-08-07",
          "2020-08-08",
          "2020-08-09",
          "2020-08-10",
        ],
        colors: [
          "var(--tblr-facebook)",
          "var(--tblr-twitter)",
          "var(--tblr-dribbble)",
        ],
        legend: {
          show: true,
          position: "bottom",
          offsetY: 12,
          markers: {
            width: 10,
            height: 10,
            radius: 100,
          },
          itemMargin: {
            horizontal: 8,
            vertical: 8,
          },
        },
      }).render();
  });
</script>
{%- endcapture %}
{% include "docs/example.html" html=html %}
