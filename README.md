# 3-column-preview-card-component

Problems I expected to encounter:
-Wanted to try a grid for the desktop layout, no idea how to use grid yet

Problems I didn't expect:
-margin and alignment woes, as usual

So this project actually went very well! I spent a bit of extra time early on devising a page structure that would take the desktop layout into account as well within my mobile-first design process. This saved me a lot of trouble later on and was worth the effort. 

An interesting problem I encountered was the font color on the buttons matching the background of its parent container. To solve this I had the idea to use a custom variable. I could reference that (--ParentBG) to match the font color on the button. Not a huge benefit for this project but I could see this being useful on a larger project, to save ajusting so many values individually. This is probably a pretty common stategy but I was happy to have worked it out on my own! :)

Next project I'll spend less time early on trying to fix margins and padding and instead focus on getting the flex/grid positioning solid, as that has a much bigger impact early on and account for margins alongside can be tricky. Much easier to adjust paddings and margins later when things aren't so in flux. 