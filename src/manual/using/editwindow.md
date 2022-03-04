---
layout: manual
title: Editing a Mix
tags: using
date: 2020-02-12
---
## Editing a Mix

Edit mode lets you change the mix's description and ingredients. 
Any changes you make are immediately remembered, you don't need to "save".

![Editing a Mix](/images/EditLabeled.png)

1. The *Name*, *Alias* and *Source* fields describe the mix. 
The name, alias and tags are used when searching.

2. To add a tag either tap on a suggested tag or start typing the tag's name.
Spaces and special characters are removed from tag names.
To remove a tag tap on the existing tag and then tap on the "x".

3. The *Ingredients List* lets you change the weight of an ingredient in a mix. 
You can also use the arrows to increment the ingredient amount. 
To delete and ingredient tap on the ingredient name and then tap on the red "-" symbol.
To get out of delete mode tap the ingredient name a second time.
Tap on the Total amount to retotal the weights. Options are
    - *Scale*: Adjust the weights by a multiple that makes the total closest to 100.
    - *100*: Adjust the weights to whole numbers to total to 100.
    - *100.0*: Adjust the weights to one decimal place to total to 100.

4. To add an ingredient start typing in the "Add" field. 
You can add an ingredient and it's weight at the same time.
Mixup shows the closest match next to the return symbol, or you can press 
"Search" to search the current database plus Digital Fire or Glazy. 
For example. typing "Cust 20" shows the match "Custer Feldspar: 20",
and typing Enter will add that to the ingredient list.

5. Analysis shows the mix's analysis next to the reference mix analysis.
The reference mix is by default the original value of the mix from when
you started editing, but you can set the reference mix to any mix
by clicking the *Reference* button. If you create a new version of
a mix then the reference is the previous mix. 
You can toggle between Unity (aka UMF) amounts and percentage amounts.

    - You can adjust an oxide directly by tapping on an oxide, 
    which brings up a popup to nudge the value up or down.

        ![Oxide Popup](/images/OxidePopup.png)

    - The double chevron attempts to adjust the oxide value by one percent,
    and the single chevron attempts to adjust by a tenth of a percent.
    The blue progress bar shows how successful the attempt was.
    Sometimes it is impossible to vary just one oxide, depending on the 
    ingredients. For example, if the calcia and magnesia in a glaze were only
    supplied by Dolomite then it's hard to increase one without the other, 
    because Dolomite bundles both in one ingredient. 
    If you added whiting (just calcia) to the ingredients then it would work.

    - To try and match the reference oxides tap on any reference oxide, 
    which brings up a popup to target the reference:

        ![Oxide Popup](/images/TargetPopup.png)

    - Try tapping the Target Reference button a couple of times to optimize
    the mix to be as close to the reference as possible.

6. The [Oxide Badge](/manual/using/badge/) shows the oxides in graphical form. 
Tap on the badge to toggle between the mix and the reference.

7. You can use *Undo* and *Redo* icons in the upper left corner
to unwind or rewind any changes.

8. The icon buttons in the upper left:
- Create a new version based on this mix
- Copy a text version of the mix to the clipboard
- Print
