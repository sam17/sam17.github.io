# sam17.github.io
Personal Website of [Soumyadeep Mukherjee](http://soumyadeepmukherjee.com).

#Using Template

* Navigation
    * Add ``` <a href="#section" onclick = $("#menu-close").click-menu(); >section</a>``` at appropriate place.
* Header
    * Add ```<li><a href="https://link" class="icon" style="font-size:32px;color:white" ></a></li>``` for icon of external link.
* About
    * Add for About section icons and description
    ```     
                <div class="service-item">
                  <span class="fa-stack fa-4x">
                    <i class="fa fa-circle fa-stack-2x"></i>
                    <i class="fa ICON fa-stack-1x text-primary"></i>
                  </span>
                  <h4>
                    <strong>NAME</strong>
                  </h4>
                  <p>TEXT TEXT TEXT </p>
                </div>
              </div>
              ```
* Portfolio 
    *  Add New Section
        * Add ```<li><a href="#" class="current btn-theme btn-small" data-filter=".TYPE">TYPE</a></li>```
    * Add the following segment to add new project icon. 	  
    ```
        		  <article class="col-md-4 isotopeItem TYPE">
        			<div class="portfolio-item">
        			  <a href="#PORTFOLIO-ID" class="portfolio-link" data-toggle="modal">
        				<div class="portfolio-hover">
        				  <div class="portfolio-hover-content">
        					<i class="fa fa-plus fa-3x"></i>
        				  </div>
        				</div>
        				<img src="IMAGE" class="img-responsive" alt="TEXT">
        			  </a>
        			  <div class="portfolio-caption">
        				<h4>TEXT</h4>
        				<p class="text-muted">TEXT</p>
        			  </div>
        			</div>			
        		  </article>
    ```
    * Portfolio Description
        * Add the following segment with description and kind of image/video/frame.
```
    <div class="portfolio-modal modal fade" id="PORTFOLIO-ID" tabindex="-1" role="dialog" aria-hidden="true">
      <div class="modal-content">
    	<div class="close-modal" data-dismiss="modal">
    	  <div class="lr">
    		<div class="rl">
    		</div>
    	  </div>
    	</div>
    	<div class="container">
    	  <div class="row">
    		<div class="col-lg-8 col-lg-offset-2">
    		  <div class="modal-body">
    			<h2>HEADING</h2>
    			<p class="item-intro text-muted">Google Cloud Developers' Challenge</p>
    			<iframe     ></iframe><br><br>
    			<p>TEXT TEXT</p>
    			<ul class="list-inline">
    			  <li><a href="LINK">Web-Link</a></li>
    			  <li>TEXT</li>
    			  <li><a href="LINK">Github</a></li>
    			</ul>
    			<button type="button" class="btn btn-primary" data-dismiss="modal"><i class="fa fa-times"></i> Close Project</button>
    		  </div>
    		</div>
    	  </div>
    	</div>
      </div>
    </div>
```



    		  
	 
