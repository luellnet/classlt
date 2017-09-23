# classlt
Detects element's width and adds classes if its width is less than specified break points. Very useful for responsive design if you need per-element break points instead of media query's per-screen.

## Requires
jQuery and jquery.initialize.js https://github.com/pie6k/jquery.initialize

## Demo
https://jsfiddle.net/luellnet/rLt4ndj8/

## Sample Usage

```
<style>
.lt800{
  background: blue;
}

.lt600{
  background: green;
}

.lt400{
  background: red;
}
</style>
```

```
<div data-classlt="400,600,800">
  I have lt400 class if my width is less than 400 then my background will be red.<br/>
  I have lt600 class if my width is less than 600 then my background will be green.<br/>
  I have lt800 class if my width is less than 800 then my background will be blue.
</div>
```

## MIT License

Copyright (c) 2017 luell.net

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
