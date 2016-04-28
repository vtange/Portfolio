![alt tag](http://res.cloudinary.com/dmj8qtant/image/upload/c_limit,w_600/v1461785835/port1_lbrpci.jpg)
# portfolio-fcc

## Tech, Niceties
 - CSS Parallax

### Details

#### CSS:
 - Classic, Bootstrapped Header
 - Pure CSS Parallax
 
 ```
        <div name="slide1" id="slide1" class="slide">
        </div>
         
        <div name="slide2" id="slide2" class="slide">
        </div>
        
          .slide:before {
            content: "";
            position: absolute;
            top: 0;
            bottom: 0;
            left:0;
            right:0;
          }
          .slide {
            position: relative;
            box-sizing: border-box;
            padding: 25vh 10%;
            min-height: 100vh;
            width: 100vw;
            transform-style: inherit;
          }
        
        #slide1:before {
            background:
                /* dark blue */ 
                linear-gradient(
                  rgba(0, 0, 0, 0.3), 
                  rgba(0, 0, 0, 0.3)
                ),
                url("https://40.media.tumblr.com/1b916597d3e174399cb7adadddb66ede/tumblr_nt5uk4psl31ud7rr3o1_1280.jpg");
            background-repeat: no-repeat;
            background-size:cover;
            background-position: center;
            background-attachment: fixed;
            transform: translateZ(-1px) scale(1);
            z-index:-1;
        }
          
        #slide2 {
            background:url("https://41.media.tumblr.com/eb2382a5a4c996cfdab27bc0d1eb51ff/tumblr_nt5umxS1FY1ud7rr3o1_1280.jpg");
            background-repeat: no-repeat;
            background-size:cover;
            background-position: center;
            background-attachment: fixed;
        }
        
        
        
 ```
