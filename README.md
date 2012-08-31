#Begrider
*Begrider* is a simple, fluid twelve column and ten units grid system with a 1140px fixed width. It works great in *Chrome*, *Firefox* and *Internet Explorer 9*. It works in *Opera* too if you don’t mind that some of the columns are a tiny bit off. The goal behind it was creating something that I could actually use and to make it as simple as possible. I think I did pretty good.

Begrider comes in two different versions: The first one (begrider-new) uses attribute selectors to apply properties and values on all of the column and unit classes and to remove the gutter from the last column in the row. The second one (begrider-old) groups the column and unit classes together to apply their shared properties and values while seperating them for their unique width and margin properties. The demo uses the new version.

[Demo](http://ellengummesson.com/projects/begrider/demo.html "A demo of Begrider")

##License
Use it, abuse it and give me credit, if you want to.

##Usage examples

###The new version
    <div class="container">
    
      <div class="grid">
    
        <div class="row">
    
          <div class="col-two"></div>
    
            <div class="col-eight">Your content here...</div>
    
          <div class="col-two"></div>
    
        </div>
    
      </div>
    
    </div>

###The old version
    <div class="container">
    
      <div class="grid">
    
        <div class="row">
    
          <div class="col-two"></div>
    
            <div class="col-eight">Your content here...</div>
    
          <div class="col-two last"></div>
    
        </div>
    
      </div>

    </div>