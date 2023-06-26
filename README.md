# Void World Generator

There's nothing special here. It's just an empty world generator.

Add it to your plugins folder, then go into your `bukkit.yml` and add the following at the bottom:

```yml
worlds:
  world:
    generator: VoidWorldGenerator
  world_nether:
    generator: VoidWorldGenerator
  world_the_end:
    generator: VoidWorldGenerator
```

Now the main world, the nether _and_ the end will be void worlds. If you don't want all of them to be, 
just remove the ones you'd like to generate normally.

Not tested with multiverse or anything else.