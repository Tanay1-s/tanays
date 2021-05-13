var countdown = document.getElementById("num");

var countval = countdown.innerHTML ;
var bgelement = document.getElementById('bg-image');
setInterval(function(){
countval =countval>0?countval=countval-1:0 ;
countdown.innerHTML = countval ;
var bgpath = countval % 2 === 0 ?  'https://static.theceomagazine.net/wp-content/uploads/2018/10/15093202/elon-musk.jpg' :'https://www.viralbake.com/wp-content/uploads/2018/08/manoj-Tiwari-1.jpg';
bgelement.src = bgpath ;
},1000)
