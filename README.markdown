# LimeChat Log.tmbundle

[TextMate](http://macromates.com/) bundle for viewing [LimeChat](http://limechat.net/mac/) IRC logs in glorious Technicolor.


## Screenshot

![Screenshot](http://github.com/henrik/limechat-log.tmbundle/tree/master/screenshot.png?raw=true)


## Installation

### Without git

In a terminal:

    cd /tmp
    curl -L http://github.com/henrik/limechat-log.tmbundle/tarball/master > limechat_log.tar
    tar xvf limechat_log.tar
    mv henrik-limechat-log.tmbundle-* LimeChat\ Log.tmbundle
    open LimeChat\ Log.tmbundle

### With git, for hackers

In a terminal:

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/henrik/limechat-log.tmbundle.git LimeChat\ Log.tmbundle
    osascript -e 'tell app "TextMate" to reload bundles'

## Credits and license

By [Henrik Nyh](http://henrik.nyh.se/) under the MIT license:

>  Copyright (c) 2008 Henrik Nyh
>
>  Permission is hereby granted, free of charge, to any person obtaining a copy
>  of this software and associated documentation files (the "Software"), to deal
>  in the Software without restriction, including without limitation the rights
>  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
>  copies of the Software, and to permit persons to whom the Software is
>  furnished to do so, subject to the following conditions:
>
>  The above copyright notice and this permission notice shall be included in
>  all copies or substantial portions of the Software.
>
>  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
>  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
>  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
>  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
>  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
>  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
>  THE SOFTWARE.
