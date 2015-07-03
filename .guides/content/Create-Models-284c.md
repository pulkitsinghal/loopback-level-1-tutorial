# Create models

* Kick off the model generator

``` bash
$ cd hello-world
$ slc loopback:model
```

* The generator guides you through creating your model. Enter the values highlighted in blue. To accept the default, just press Enter.

``` bash
? Enter the model name: person                                                      
? Select the data-source to attach person to: db (memory)                           
? Select model's base class: PersistedModel                                         
? Expose person via the REST API? Yes                                               
? Custom plural form (used to build REST URL): people                               
Let's add some person properties now.
```

* Define a firstname property for the person model

``` bash
Enter an empty property name when done.
[?] Property name: firstname
```

* Hit Enter to accept the default string type:
``` bash
[?] Property type: (Use arrow keys)
❯ string
  number
  boolean
  object
  array
  date
  buffer
  geopoint
  (other)
```

* Make the property required.
``` bash
[?] Required? (y/N) y
```

* Repeat these steps for lastname property.

* Press Enter when prompted for a property name to finish up and create the model.