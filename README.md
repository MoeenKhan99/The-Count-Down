# The-Count-Down
//Put in a number and it counts down to zero. Then says it's done.

function CountDown(count){
  let time = setInterval (function(){
    count--;
    if (count <= 0) {
      clearInterval (time);
      console.log('DONE!');
    }else{
      console.log(count);
    }
   },1000)
 }
 
CountDown(5);

 
