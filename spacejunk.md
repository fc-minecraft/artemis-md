### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Space Junk

## Step 1
Guide the ADRV using the ``||artemis.ADRV move||`` block to each piece of debris and collect it using the ``||artemis.collect debris||`` block.

```ghost
    artemis.adrvMoveA16()
    artemis.collectDebrisA16()
```
```template
    //
```

```package
artemis-ts=github:ReWrite-Media/artemis-ts#v0.0.17
```