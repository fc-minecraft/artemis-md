### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# ISS Help

## Step 1
Extend the robotic arm using the ``||artemis.extend arm||`` block to the red piece of cargo and then use the ``||artemis.load cargo||`` block to grab it and load it onto the ISS.

```ghost
    artemis.extendArmA21()
    artemis.loadCargoA21()
```
```template
    //
```

```package
artemis-ts=github:ReWrite-Media/artemis-ts#v0.0.56
```