var jqry = document.createElement('script');
jqry.src = "https://code.jquery.com/jquery-3.3.1.min.js";
document.getElementsByTagName('head')[0].appendChild(jqry);
jQuery.noConflict();

(function($) {
    $(document).ready(function() {
      setInterval(function() {
if(parseInt($(".ytp-progress-bar").attr("aria-valuenow"))==parseInt($(".ytp-progress-bar").attr("aria-valuemax"))){

$x('/html/body/app-root/app-classroom-app/app-selected-content/div/div[2]/app-classroom-right-panel/div/div/app-video-content/div/div/app-video-feedback/div/div/div/div[1]/img')[0].click()
$(".action .ng-star-inserted").click();
$(".close-dialog").click();
$x('/html/body/app-root/app-classroom-app/app-selected-content/div/div[2]/app-classroom-right-panel/div/div/app-video-content/div/div/app-video-feedback/div/div/div/div[1]/img')[0].click()

console.log($(".ytp-progress-bar").attr("aria-valuenow"));
console.log($(".ytp-progress-bar").attr("aria-valuemax"));
setTimeout(function(){
}, 1000); 
        }
      },120)
    });
  })(jQuery);

(function($) {
    $(document).ready(function() {
      setInterval(function() {
     if($(".ytp-progress-bar").length==0){
var esc = $.Event("keydown", { keyCode: 27 });
$("body").trigger(esc);
      $(".action .ng-star-inserted").click();
      $("#heading-close").click();
      $(".close-dialog").click();
var esc = $.Event("keydown", { keyCode: 27 });
$("body").trigger(esc);
$('.cdk-overlay-backdrop').click()
}
      },6000)
}
);
  })(jQuery);
