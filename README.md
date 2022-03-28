## Start-up Scripts
```bash
# Create your graph
mkdir graph
mkdir graph/people
mkdir graph/notes
mkdir graph/pictures
# Add yourself as graph owner
cp example_graph/people/hari-seldon.md graph/people/<your_name>.md
```

## Creation Scripts
```bash

# Add a person
cp example_graph/people/salvor-hardin.md graph/people/<person_name>.md

# Add a picture by hand
cp example_graph/pictures/1.json graph/pictures/1.json

# Upload pictures from google photos
# TODO

# Add a note
cp example_graph/notes/foundation.md graph/notes/<note_name>.md
```

## Composition Scripts
```bash

# open graph
open -a "Google Chrome" .

# timestamp
echo "\n *$(date)*" >> manav.md"

# VIM move file deeper
:%s/notes/..\/notes/g
:%s/people/..\/people/g
```

## Query Scripts
```bash
# get todos
grep -r "TODO" *graph

# get dates
grep -r "DATE" *graph

# get all pictures with this person
TODO
```
