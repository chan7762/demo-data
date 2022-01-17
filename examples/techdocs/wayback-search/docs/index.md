# Overview

This is an example of what you can do in techdocs.

Here is the overview page for the wayback search component.

It's cool isn't it?

# Assets, links

Look at this lovely cat!

![This is a pretty cute cat](./cute-cat.png)

We can also link you to a lovely video of a cat: [this is a lovely cat video](https://www.youtube.com/watch?v=cbP2N1BQdYc)


# Relationship diagrams

```plantuml format="png" classes="uml myDiagram" alt="Roadie" title="My super diagram" width="300px" height="300px"
  Roadie ->  Cats: loves
  Roadie <-- Cats: Returns love
```

::uml:: format="png" classes="uml myDiagram" alt="My super diagram placeholder" title="My super diagram" width="300px" height="300px"
  Roadie ->  Cats: loves
  Roadie <-- Cats: Returns love
::end-uml::

# Code blocks

``` bash
#!/bin/bash

function doesRoadieLoveCats(){
  return 1
}

if [ doesRoadieLoveCats ];then
  echo "Roadie really loves cats and the world is better for it!"
else
  echo "There is no way roadie doesn't love cats >:("
fi

exit 1;
```