### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Building Blocks

## Step 1
Navigate the rover to (3) piles of lunar regolith using the ``||artemis.rover move||`` block and then collect them using the ``||artemis.collect regolith||`` block.

```ghost
    artemis.roverMoveA5()
    artemis.collectBlockA5()
```
```template
    //
```

```package
artemis-ts=github:ReWrite-Media/artemis-ts#v0.0.54
```