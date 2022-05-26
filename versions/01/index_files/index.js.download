window.addEventListener("scroll", parallax, false);

function parallax() {
  var prlx_lyr_1 = document.getElementById('prlx_lyr_1');
  var prlx_lyr_2 = document.getElementById('prlx_lyr_2');
  var prlx_lyr_3 = document.getElementById('prlx_lyr_3');
  var prlx_lyr_4 = document.getElementById('prlx_lyr_4');
  var prlx_lyr_5 = document.getElementById('prlx_lyr_5');
  var prlx_lyr_6 = document.getElementById('prlx_lyr_6');
  var prlx_lyr_7 = document.getElementById('prlx_lyr_7');
  var prlx_lyr_8 = document.getElementById('prlx_lyr_8');
  var prlx_lyr_9 = document.getElementById('prlx_lyr_9');
  var prlx_lyr_10 = document.getElementById('prlx_lyr_10');

  var scrollValue = (window.pageYOffset);

  prlx_lyr_1.style.top = (-scrollValue) * 0 + 'px';
  prlx_lyr_2.style.top = (-scrollValue) * -.1 + 'px';
  prlx_lyr_3.style.top = (-scrollValue) * -.2 + 'px';
  prlx_lyr_4.style.top = (-scrollValue) * -.3 + 'px';
  prlx_lyr_5.style.top = (-scrollValue) * -.4 + 'px';
  prlx_lyr_6.style.top = (-scrollValue) * -.45 + 'px';
  prlx_lyr_7.style.top = (-scrollValue) * -.50 + 'px';
  prlx_lyr_8.style.top = (-scrollValue) * -.55 + 'px';
  prlx_lyr_9.style.top = (-scrollValue) * -.60 + 'px';
  prlx_lyr_10.style.top = (-scrollValue) * -.65 + 'px';
}


document.addEventListener("DOMContentLoaded", function(){

    el_autohide = document.querySelector('.autohide');
    
    // add padding-top to body (if necessary)
    navbar_height = document.querySelector('.navbar').offsetHeight;
    // document.body.style.paddingTop = navbar_height + 'px';
  
    if(el_autohide){
      var last_scroll_top = 0;
      window.addEventListener('scroll', function() {
            let scroll_top = window.scrollY;
           if(scroll_top < last_scroll_top) {
                el_autohide.classList.remove('scrolled-down');
                el_autohide.classList.add('scrolled-up');
            }
            else {
                el_autohide.classList.remove('scrolled-up');
                el_autohide.classList.add('scrolled-down');
            }
            last_scroll_top = scroll_top;
      }); 
      // window.addEventListener
    }
    // if
  
  }); 
  // DOMContentLoaded  end