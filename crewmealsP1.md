### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Crew Meals Player 1

## Step 1
Your job is to work the rehydration station. Use the ``||artemis.toggle power||`` block to turn it on. Then use the ``||artemis.place freeze-dried||`` block to place the tomato sauce into the rehydration station and set the amount of water using the ``||artemis.rehydrate with||`` block. Check the chart to see how much water to use. Finally, don't forget to turn off the machine when you're done.

```ghost
    artemis.togglePowerA9P1()
    artemis.placeIngredientA9P1()
    artemis.rehydrateA9P1()
```
```template
    //
```

```package
artemis-ts=github:ReWrite-Media/artemis-ts#v0.0.58
```