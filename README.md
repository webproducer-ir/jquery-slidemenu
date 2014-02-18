Jquery Slide Menu
=================

HOW TO USE

1- Include font-awesome.min.css in head

2- Include jquery-slide-menu.css in head

3- Include jquery-x.xx.x.min.js in end of body

4- Include jquery-slide-menu.js in after jquery plugin

5 - Next create new javascript code and include :

    <script type="text/javascript">
    	$(document).ready(function(e) {
            $('.nav-slide').SlideMenu({
    			speedLR: 1000,
    			speedUD: 500,
    			expand: true,
    			collapse: true
    		});
      });
    </script>
    
6- Html template :

<div class="nav-slide">
    <div class="btn-slide"></div>
    <div class="nav-body">
        <div class="head-slide">Main Menu</div>
        <div class="body-slide">
            <ul class="nav">
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
    </div>
    <div class="nav-body">
        <div class="head-slide">Software</div>
        <div class="body-slide">
            <ul class="nav">
                <li><a href="#">Windows</a></li>
                <li><a href="#">Linux</a></li>
                <li><a href="#">Apple Mac</a></li>
            </ul>
        </div>
    </div>
    <div class="nav-body">
        <div class="head-slide">Games</div>
        <div class="body-slide">
            <ul class="nav">
                <li><a href="#">Wrcraft III</a></li>
                <li><a href="#">Dota 2</a></li>
                <li><a href="#">Diablo III</a></li>
            </ul>
        </div>
    </div>
</div>
