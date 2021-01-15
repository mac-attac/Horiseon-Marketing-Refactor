# Horiseon-Marketing-Refactor

In appearance, this website was mostly functional already. To refactor this code, there were only a one change that needed to be made to affect functionality. The "Search Engine Optimization" aspect of te navigation bar did not link internally in the proper fashion. This was easily fixed by changing it from a class to an id. Additionally, alt tags were added to each of the images to optimize accessibility for screen readers.

In the index.html file, after adding a descriptor to the title tag, most of the work was to change non-semantic html tags to semantic tags and then ensure the style.css reflected those changes, if necessary. The only one I found I had to change in style.css was div to nav. But, globally in the index.html file, the "div" tags were changed to header, main, aside, section and footer respectively. Comments were inserted where appropriate to mark changes made.

Lastly, the style.css page was functional after making changes in line with the semantic tag changes in the index.html. However, there were some redundancies in the code that were merged to "clean it up." Comments were placed in the areas where the code was merged to highlight these changes.
