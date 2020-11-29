# plantuml

Docker Container for [PlantUML](http://plantuml.com)

## Usage

Given a PlantUML file you can create image files with:

```
     $> curl https://raw.githubusercontent.com/jonathar/plantuml_styles/main/samples/relational_db_schema.puml | docker run --rm -i jonathar/plantuml -tpng > db_schema_sample.png 
```
