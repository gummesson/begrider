# Begrider
*Begrider* is a simple, fluid twelve column and ten units grid system with a 1140px fixed width. It works great in *Chrome*, *Firefox* and *Internet Explorer 9*. It works in *Opera* too if you don’t mind that some of the columns are a tiny bit off. The goal behind it was creating something that I could actually use and to make it as simple as possible. I think I did pretty good.

Begrider comes in two different versions: The first one (begrider-new) uses attribute selectors to apply properties and values on all of the column and unit classes and to remove the gutter from the last column in the row. The second one (begrider-old) groups the column and unit classes together to apply their shared properties and values while seperating them for their unique width and margin properties. The demo uses the new version.

## Usage

### The New Version

    <div class="container">
    
      <div class="grid">
    
        <div class="row">
    
          <div class="col-two"></div>
    
            <div class="col-eight">Your content here...</div>
    
          <div class="col-two"></div>
    
        </div>
    
      </div>
    
    </div>

### The Old Version

    <div class="container">
    
      <div class="grid">
    
        <div class="row">
    
          <div class="col-two"></div>
    
            <div class="col-eight">Your content here...</div>
    
          <div class="col-two last"></div>
    
        </div>
    
      </div>

    </div>

## License

The MIT License (MIT)   
Copyright (c) 2012 Ellen Gummesson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.