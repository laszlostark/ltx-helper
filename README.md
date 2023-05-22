# ltx-helper

### profiles.json
Profiles store two things as of now:
- traits, which are options for document creation, which might me mutually exclusive at some point. they have the following attributes:
  - `text-content`, which ist the literal text to be inserted into the document
  - `type`, which is a category of sorts to prevent clashing of traits in the future (this might be an array of types too? idk)
- profiles, which are collections of traits.


### todo:
- options
  - default profile / default options for stuff like font size, doc type etc