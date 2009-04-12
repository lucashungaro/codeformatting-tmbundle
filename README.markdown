Code Formatting TextMate Bundle
===============================

This is a simple [TextMate][txm] bundle that strips out trailing whitespaces and replaces tabs with spaces whenever a file is saved. Based on work done by [Viget Labs developers][ext].

  [ext]: http://viget.com/extend/out-damned-tabs
  [txm]: http://macromates.com

## Installation:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/lucashungaro/codeformatting-tmbundle.git Code\ Formatting.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'
