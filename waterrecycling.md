### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Water Recycling

## Step 1
Guide the Agent through the pipes using the ``||artemis.agent move||`` block and remove each piece of debris using the ``||artemis.remove debris||`` block.

```ghost
    artemis.agentMoveA20()
    artemis.removeDebrisA20()
```
```template
    //
```

```package
artemis-ts=github:ReWrite-Media/artemis-ts#v0.0.64
```