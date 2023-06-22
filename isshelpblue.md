### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# ISS Help

## Step 1
The crew needs help loading the Blue colored cargo box onto the ISS. Use the ``||artemis: retrieve cargo||`` block to select the Blue cargo box and then use the ``||artemis: load cargo||`` block to load it onto the ISS.

```ghost    
    artemis.retrieveBlueGoalA21()
    artemis.loadCargoA21()
```
```template
    //
```

```package
artemis-ts=github:ReWrite-Media/artemis-ts#v0.0.66
```