---
layout: "post"
title: "Instachart: A Dynamic Visualization of Instacart" 
---

[Instachart Link](https://instachartapp.herokuapp.com)

My goal in this project was to build a visualization tool for the Instacart 2017 Dataset. I've been asked to visualize vast amounts of data for projects in the past. I was inspired by Tableau to make this visualization dynamic. It allows interested parties to indentify grocery categories and products, and to see how those orders correspond based on the day of the week or hour of the day. 

I initially wanted to be able to filter every order. I was able to successfully do this locally. However when I deployed the app it would have required payment to host the additional data. The version you see has limited the orders as a result. 

The app was built using Streamlit. However I filtered and cleaned the data prior using Python and the Pandas Library. The plotting was done in Matplotlib and the entire project is hosted on Heroku. 