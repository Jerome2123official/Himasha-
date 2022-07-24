function fn0(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+0;
}
function fn1(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+1;
}function fn2(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+2;
}function fn3(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+3;
}function fn4(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+4;
}function fn5(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+5;
}function fn6(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+6;
}function fn7(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+7;
}function fn8(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+8;
}function fn9(){
    let per =document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=per+9;
}


function feraser(){
    let per=document.getElementById("display").innerHTML;
    erasedper=per.slice(0,-1);
    document.getElementById("display").innerHTML=erasedper;

}


let op;
let fsave;


function fnAD(){
    fsave= document.getElementById("display").innerHTML;
   document.getElementById("display").innerHTML=0;
     op=1;

}
function fnMN(){
     fsave= document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=0;
      op=2;
     
 }function fnML(){
     fsave= document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=0;
      op=3;
     
 }
 function fnDV(){
     fsave= document.getElementById("display").innerHTML;
    document.getElementById("display").innerHTML=0;
      op=4;
     
 }
 function fnEQ(){
    let secondsave= document.getElementById("display").innerHTML;
    if (op==1){
        document.getElementById("display").innerHTML=parseInt(fsave)+parseInt(secondsave);
    } else if (op==2){
        document.getElementById("display").innerHTML=parseInt(fsave)-parseInt(secondsave);


    }
    else if (op==3){
        document.getElementById("display").innerHTML=parseInt(fsave)*parseInt(secondsave);


    }else if (op==4){
        document.getElementById("display").innerHTML=parseInt(fsave)/parseInt(secondsave);


    }else {
        document.getElementById("display").innerHTML="Invalid nUmber";


    }
   
     
 }
