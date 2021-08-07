[< Day 3, Part 2](https://negeenaghassi.github.io/openscholarship-dataviz/day-3/day-3-part-2 "Day 3, Part 2") | [Return to homepage](https://negeenaghassi.github.io/openscholarship-dataviz/index.html "Return to homepage") | [Day 4, Part 2 >](https://negeenaghassi.github.io/openscholarship-dataviz/day-4/day-4-part-2 "Day 4, Part 2") 

Reminder: Use the [ongoing discussion post](https://github.com/negeenaghassi/openscholarship-dataviz/discussions/8 "ongoing discussion post") for any questions or thoughts that come up. 
## Day 4, Part 1
Welcome to Day 4! Today will cover accessibility and data visualization. Many thanks to Reed Witherspoon, University of Washington Libraries Open Scholarship Commons Graduate Assistant, who co-created and co-taught the original version of the content below. 
### Accessibility
While equity, diversity, and inclusion have become increasingly more common in discussions about data visualization, accessibility is another critical element that deserves to be addressed as well. Accessibility sits at the foundation of inclusive data visualization design and is not an option or feature that can be turned on or off. While there are no formal around creating accessible data visualizations in the same way that there are for general web design, it can be helpful to make progress, even if not perfect. 

One of the guiding principles of this work is universal design -- designing for everyone regardless of disability. The comic below depicts a person in a wheelchair who says, “Could you please shovel the ramp?” A person shoveling some stairs responds, “All these other kids are waiting to use the stairs. When I get through shoveling them off, then I will clear the ramp for you.” The person in the wheelchair responds, “But if you shovel the ramp, we can all get in!”

<img src="http://etec.ctlt.ubc.ca/510wiki/images/4/47/Clearing_a_pat.png" alt="Comic that demonstrates Universal Design using the example of clearing a ramp rather than stairs to give everyone in the comic access to a building." width="550"/>

This comic demonstrates how universal design is beneficial for all. This approach to data visualization can help make visualizations more accessible for all. 

#### Standards
There are federal requirements for web accessible materials. You may be familiar with [Section 508](https://www.section508.gov/ "Section 508"), which outlines accessibility requirements. There are also additional state-specific standards. The University of Washington has their [own policy requirements](https://www.washington.edu/accessibility/guidelines/ "own policy requirements") as well. For more background information, check out the [Accessibility Self-Paced Training](https://canvas.uw.edu/courses/1351896 "Accessibility Self-Paced Training") in Canvas by Ana Thompson (Learning & Access Designer, Office of Digital Learning & Innovation, UW Bothell). 
#### Design choices
There are specific design choices that can make visualizations more or less accessible. The next section will go through some of these choices. 
##### Color
Whenever possible, don’t use color as the only medium to communicate information. People perceive colors differently. Instead, try using a combination of color, text, and shapes to label information.

When you use only color to distinguish between variables, such as in the example below...
<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/colorbars.png" alt="Stacked bar chart with red bars for cat pet licenses and green bars for dog pet licenses." width="550"/>

...your chart might look like this to some readers. 
<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/colorgray.png" alt="Stacked bar chart with gray bars for cat and dog pet licenses." width="550"/>

In addition, some data visualization software doesn't design for better options due to so-called "best practices."
<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/tableaupatternfill.png" alt="Conversation on Tableau Community Forum where a Tableau rep shares that pattern fill is not part of Tableau's design and a member of the Forum explains that pattern fill is important for colorblindness." width="550"/>

This screenshot of a conversation on a Tableau forum shows where some tools might prioritize aesthetics over function and accessibility. In the thread, the Tableau representative says, in a longer thread asking about pattern fills, that “Pattern fill colors are not a visual best practice. Tableau was built from the ground up with best practices in mind...hence, not having this functionality. Try using different shades of hue for printing purposes.” A Tableau user responds with, “Pattern fill is visible to those with colorblindness. That’s why we use it...hue works, but not nearly as well.”

This conversation demonstrates the tension here between some *industry-defined* best practices and *accessibility* best practices. 

One way around this issue is using icons to note length. In the visualization below of the five most popular names of pet licenses in Seattle, you can see a dog icon that ends where the bar for dog ends and a cat icon where the bar for cat ends. Given the data, it might even make more sense to separate the animals or do a side by side, both alternatives that may be more accessible. 
<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/colorwithshapes.png" alt="More accessible bar chart that distinguishes by icons as well as colors." width="550"/>

If the tool you are using allows for a pattern fill, that is another way to distinguish between variables using an element other than color, as seen in the chart below. 
<img src="https://negeenaghassi.github.io/openscholarship-dataviz/images/patternfillexcel.png" alt="Bar chart with pattern fill for the bars." width="550"/>

##### Layout

