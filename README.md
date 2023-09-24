# First attempt (other repository)
- [Repository](https://github.com/anttieskola/aje)
- Here we have an blazorserver app that has zipfile containing icons as resource.
- It reads zipfile and catalogs the svg's into memory cache
- Icon component writes the paths from memory

# Second (this repo)
- In this attempt the icon would been static file and shown thrue image tag
- This way client can ***cache*** svg data

***But I learned***, that we can't control the color. So can't continue this way.

Not sure yeat how to make the other way to work as a component library
that can be shared.

# Third attempt
 - Icon font is the best way
