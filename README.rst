Aquarium Log
============

While I wait to find some better online aquarium tracking software, I'm just going to stick data into YAML. Maybe one day I can put this into a db and wrap things up in some REST.

QUICK Syntax check
------------------
```
echo "require 'yaml'; require 'pp'; PP.pp(YAML::load_stream( File.open( 'observation.yaml' )), $>, 40)" | irb
```
