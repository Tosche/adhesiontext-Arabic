# adhesiontext Arabic

This is a repository for a Python script for the font editor [Glyphs font editor](http://glyphsapp.com/) by Georg Seifert.

[Adhesiontext](http://adhesiontext.com) by Miguel Sousa is an amazing website, which argurably one of the most revolutionary tools in modern type design. But when it comes to Arabic, your glyph set are often partial (i.e. the website assumes you have all positional forms of a given letter). This adhesiontext Arabic is sensitive to positional forms!

The script looks at your Glyphs file, and suggests only the words you have positional forms for. The word dictionary comes with the package and must be stored in the same place as the script. The dictionary can be used for other stuff too, of course.

The source dictionary file is big, so it takes a lot of time picking words from that. You can save time by shrinking the dictionary (this will be only done internally, not saved to the text file).

### Installation

1. Download the complete ZIP file and unpack it, or clone the repository.
2. Place the script and dictionary files ("adhesiontext Arabic.py" and "adhesiontext Arabic Dictionary.txt") under Glyphs's Scripts folder.

### License

Copyright 2018 Toshi Omagari (@tosche_e).

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

See the License file included in this repository for further details.
