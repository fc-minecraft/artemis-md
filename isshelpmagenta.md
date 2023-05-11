### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Lunar Garden

## Step 1
The crew needs help loading the Magenta colored cargo box onto the ISS. Use the ``||artemis: retrieve cargo||`` block to select the Magenta cargo box and then use the ``||artemis: load cargo||`` block to load it onto the ISS.

```ghost    
    artemis.retrieveMagentaGoalA21()
    artemis.loadCargoA21()
```
```template
    //
```

```package
artemis-ts=github:ReWrite-Media/artemis-ts#v0.0.57
```
