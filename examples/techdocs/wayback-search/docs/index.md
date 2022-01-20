# Overview

This is an example of what you can do in techdocs.

Here is the overview page for the wayback search component.

It's cool isn't it?

# Assets, links

Look at this lovely dog!

![This is a pretty cute dog](./cute-dog.png)

We can also link you to a lovely video of a dog: [this is a lovely dog video](https://www.youtube.com/watch?v=W-J-LSWQL-o)


# Relationship diagrams

```plantuml format="png" classes="uml myDiagram" alt="Roadie" title="Look at this! Built with plantUML" width="300px" height="300px"
  Roadie ->  Dogs: loves
  Roadie <-- Dogs: Returns love
```

::uml:: format="png" classes="uml myDiagram" alt="My super diagram placeholder" title="Look at this! Another diagram built with UML" width="300px" height="300px"
  Roadie ->  Dogs: loves
  Roadie <-- Dogs: Returns love
::end-uml::

# Code blocks

``` bash
#!/bin/bash

function doesRoadieLoveDogs(){
  return 1
}

if [ doesRoadieLoveDogs ];then
  echo "Roadie really loves dogs and the world is better for it!"
else
  echo "There is no way roadie doesn't love dogs >:("
fi

exit 1;
```
