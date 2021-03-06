# Begrider
*Begrider* is a simple and fluid twelve column and fourteen units grid system with a 1140px fixed width, which can be changed without problems. It should work fine all modern web browsers and has an optional backward compatibility with IE8.

## Usage

### Columns

    <div class="container">
    
      <div class="grid">
    
        <div class="row">
    
          <div class="column-two"></div>
    
            <div class="column-eight"><p>Lorem ipsum...</p></div>
    
          <div class="column-two"></div>
    
        </div>
    
      </div>
    
    </div>

#### With `.last` class for IE8 support:

    <div class="container">
    
      <div class="grid">
    
        <div class="row">
    
          <div class="column-two"></div>
    
            <div class="column-eight"><p>Lorem ipsum...</p></div>
    
          <div class="column-two last"></div>
    
        </div>
    
      </div>
    
    </div>

### Units
    
    <div class="container">
    
      <div class="grid">
    
        <div class="row">
    
          <div class="unit-one-quarter"><p>Lorem ipsum...</p></div>
    
          <div class="unit-three-quarters"><p>Lorem ipsum...</p></div>
    
        </div>
    
      </div>
    
    </div>

## License

**The MIT License (MIT)**

*Copyright (c) 2012 Ellen Gummesson*

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
