### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Moon Mapping

## Step 1
Once your partner marks three locations to visit, you'll see three green X's show up on your screen. Use the ``||artemis.VIPER move||`` block to navigate to each location, and the ``||artemis.take picture||`` block to take a picture at each location.

```ghost
    artemis.takePictureA8P2()
    artemis.viperMoveA8P2()
```
```template
    //
```

```package
artemis-ts=github:ReWrite-Media/artemis-ts#v0.0.54
```