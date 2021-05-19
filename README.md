# Web Voyager: Lightweight Visualization Of Website Data

![Alt text](./final/overview.png?raw=true "Overview of Web Voyager")

## Abstract

Many websites have data that we would like to visualize but it is not available in a form that can be readily used such as a JSON or CSV file. The few websites that do make their data available provide it via an API which often requires setting up an account, registering for an API key and configuring a programming environment which can be time consuming and complex.

In this work, I present an interaction model for lightweight visualization of structured website data right in the context of the website. The key idea is to provide a mechanism to scrape the desired data from the website and feed it into a visualization pipeline that enables lightweight visualization of the data without having to leave the website.

To illustrate this approach, I have implemented a Chrome browser extension called Web Voyager. Through case studies, I show that Web Voyager can be used to visualize data on real-world websites. Finally, I discuss the limitations of Web Voyager and opportunities for future work.

Team Members: Kapaya Katongo
Paper: https://github.com/6859-sp21/final-project-web-scraping-for-visualization/tree/main/final/paper.pdf
Demo: https://github.com/6859-sp21/final-project-web-scraping-for-visualization/tree/main/final/demo.mp4

## Setup

To test out Web Voyager you can follow these steps:
1. Clone the repository
2. Open Chrome and load its browser extensions page by pasting "chrome://extensions/" into the search bar
3. Make sure "Developer mode", in the top right, is toggled on
4. Click "Load unpacked" and select the root of the repository folder you cloned
5. Navigate to https://www.timeanddate.com/holidays/us/ and follow the steps shown in the demo video. Website data is scraped by clicking on a value while pressing the Alt key (Option on Mac). 
6. While Web Voyager is active on a website, you will not be able to click on links or buttons. To close it, simply refresh the page. For convenience, the Vega-lite configuration shown in the demo video can be found in the vega-lite-configs folder