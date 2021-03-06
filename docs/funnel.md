##Custom Funnel Diagram##

This diagram allows you to segment your data into sections of a funnel. Such as customers going through a sales pipeline, or events going to conversion. 

![funnel image](../images/funnel.png "Funnel Visualization")

**How it works**

Create a look with one measure and one dimension. The sort is important, typically sort the measure descending as the funnel follows this direction or use a dimension that sorts in order (using order_by_field in lookML)

**Settings**

| Section | Setting Name | Description |
|---------|--------------|-------------|
| Style | Width % | Allows the user to set a width of the funnel as a % of the cell/div |
| Style | 3D Funnel | Turning this on makes a 3D/Rounded funnel compared to the flat funnel |
| Style | Hover Effects | Darkens funnel section when hovered over |
| Style | Dynamic Area | Adjusts the segment heights based on the measure amount to be sized in proportion |
| Style | Gradient Effects | Visually adds a gradient to the colors of each segment |
| Style | Show Conversion Rate | Calculates percent of previous on the value label |
| Style | Color Ranges | Array for segment colors | 


**More Images**

![funnel image](../images/funnel2.png "Funnel Visualization")
