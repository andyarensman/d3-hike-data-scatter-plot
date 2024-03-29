# D3: Hiking Data Scatter Plot

[Checkout the full node version on Github here](https://github.com/andyarensman/Hiker-Tracker)

A D3 scatter plot connected to a Google Sheet that shows mileage vs elevation gain, top locations visited, and other statistics from my hiking trips in 2021. When the Google Sheet is updated, the graph automatically updates with the new point(s). If the new points do not fit on the graph, the scales adjust on their own. You can see what it looks like below as well as one of the mouseover functions.

![Example Image](https://i.imgur.com/zIaEz3Q.gif)

## More Info
This was originally created as a pen on CodePen.io: [https://codepen.io/arensmandy/pen/VwpmggN](https://codepen.io/arensmandy/pen/VwpmggN). It has since been turned into a fullstack app: [[github]](https://github.com/andyarensman/Hiker-Tracker) [[app]](https://hiking-data-logger.adaptable.app/)

The project was created as a way to practice D3 data visualization while going through the [freeCodeCamp certification](https://www.freecodecamp.org/learn/data-visualization/), and as a fun way to keep track of my hiking. I also wanted to learn how to connect Google Sheets to an app using JavaScript and practice my CSS skills to make a more finished looking graph.

In the future I may add pop-up images from the hikes when the user hovers over each point. I may also make this into a template that others can easily use by simply cloning my Google Sheet, putting in their hiking data, and updating the link in the code that connects to the Google Sheet. This isn't hard to do now, but it could be more user friendly. Finally, I might also try to automate the process of taking the hiking data from the app I use (Map My Run) and putting it into the Google Sheet.

The next step was to turn this into a full stack app with MongoDB ([completed here](https://github.com/andyarensman/Hiker-Tracker)). User's are able to input their own hike data and see their own graphs.

## Tutorials & Guides Used:
- How to Use Google Sheets with D3.js and Google Visualization by Amit Agarwal: [https://www.labnol.org/code/google-sheet-d3js-visualization-200608](https://www.labnol.org/code/google-sheet-d3js-visualization-200608)
- Sunlight StyleGuide DataViz by Amy Cesal: [https://github.com/amycesal/dataviz-style-guide/blob/master/Sunlight-StyleGuide-DataViz.pdf](https://github.com/amycesal/dataviz-style-guide/blob/master/Sunlight-StyleGuide-DataViz.pdf)
- FreeCodeCamp Data Visualization: [freeCodeCamp certification](https://www.freecodecamp.org/learn/data-visualization/)
