# boostrap5-basics
The Bootstrap5-basics is the repo all about the basics of the magical framework. This can also be used as a torurial for begginers.
![image](https://github.com/Hameedullah-Asadi3300/boostrap5-basics/assets/123219655/8767aa89-5974-4cd2-9c13-2f41d0120bdd)

Installation: Boostrap5 is the latest version and there are two ways of instalation.

With CDN We directly paste these two links within the head secstion of HTML.
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

Or Downloading from https://getbootstrap.com/

##  Description
Classes in Bootstrap5:
1. Container
   
          Boostrap5 requires container which holds the whole content in. There are two types of container
          classes:
          1. container: provides a fixed width size container.
          2.container-fluid: provides a full width size container.
          The container.html files contains examples of both containers. in bootstrap5.
3. Grid System

          Bootstrap allows us 12 column on a page and the grid system has 12 classes:
            •	.col- (extra small devices - screen width less than 576px)
            •	.col-sm- (small devices - screen width equal to or greater than 576px)
            •	.col-md- (medium devices - screen width equal to or greater than 768px)
            •	.col-lg- (large devices - screen width equal to or greater than 992px)
            •	.col-xl- (xlarge devices - screen width equal to or greater than 1200px)
            •	.col-xxl- (xxlarge devices - screen width equal to or greater than 1400px)
          Example, a row of four columns that each covers quarter of the page:
       <div class="row">
          <div class="col"><h2>HTML</h2>
          <p>Column 1</p>
          </div>
          <div class="col"><h2>CSS</h2> 
          <p>Column 2</p>
          </div>
          <div class="col"><h2>Bootstrap5</h2>
          <p>Column 3</p>
          </div>
          <div class="col"><h2>JavaScript</h2>
          <p>Column 4</p>
          </div>  
        </div>
            Creating 4 equal columns:
         <div class="row">
             <div class="col-sm-3">column 1</div>
             <div class="col-sm-3">column 2</div>
             <div class="col-sm-3">column 3</div>
             <div class="col-sm-3">column 4</div>
         </div>  
            Creating 2 anequal columns:
         <h1 style="text-align:center">How to create 2 anequal columns?</h1>
         <div class="row">
             <div class="col-sm-4">Small Column</div>
             <div class="col-sm-8">Large Column</div>
         </div>
## Typography
         In typography.html file you will find the following classes and elements:
         1: h1-h6                            6: <kbd></kbd>              11: .text-end          
         2: <display></display>              7: <lead></lead>            12: .list-inline
         3: <small></small>                  8: .text-center             13: .list-inline-item
         4: <mark></mark>                    9: .text-start              14: <blockquote></blockquote>
         5: <pre></pre>                      10: <del></del>             15: <blockquote-footer></blockquote-footer>
                                                                         16: .text-truncate
##   Colors
         In colors.html file you can find all the classes for .text-colors, bg-colors, and opacity for dark and white colors:
         background Colors:
   ![image](https://github.com/Hameedullah-Asadi3300/boostrap5-basics/assets/123219655/a873cd30-0247-4afa-8d50-fe800fc1ee20)
         text-colors:
 ![image](https://github.com/Hameedullah-Asadi3300/boostrap5-basics/assets/123219655/5de38d86-eda2-491d-a5af-d337d7ad13db)

## Tables
      In tables.html you can find all the bootstrap classes for creating tables:
         1: .table                  6: .table-striped                              11: .table-sm                  16: .table-responsive-xl
         2: .table-striped          7: .table .table-dark .table-hover             12: .table-responsive          17: .table-responsive-xxl
         3: .table-bordered         8: .table-borderless                           13: .table-responsive-sm
         4: .table-hover            9: .table-bordered                             14: .table-responsive-md
         5: .table-dark             10: .table-warning                             15: .table-responsive-lg
      
## Images
      The images.html file contains all the image classes in bootstrap 5 as follows:
         1: .img-thumbnail                        |   gives a 1px border around the image
         2: .rounded                              |   gives a rounded corner to the image
         3: .rounded-circle                       |   makes an image absloutely rounded
         4: .rounded mx-auto d-block              |   positions an image at the center
         5: .img-fluid                            |   makes an image responsive which scales to the parent element width
         6: .rounded float-start                  |   floats an image to the left
         7: .rounded float-end                    |   floats an image to the right







      

         

