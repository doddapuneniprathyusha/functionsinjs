# functionsinjs
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script>
        //1
       function add(){
       return "hello";
       }
       var a=add;
        console.log(a);
    //2
    function add(){
        return "hello";
        }
        var a=add();
      console.log(a);
    //3 dynamic reusability
    function add(a,b){
        return a+b;
     }
     var c=add(10,5);
     console.log(c);
     var r=add(20,30);
     console.log(r);
     var e=add(600 + "hello");
     console.log(e);
     var e=add(600 +"hello",);
     console.log(e);
    //default parameter
    function add(a,b=0)
     {
      return a+b;  
    }
     var r=add(10);
     console.log(r)
    //task1
     function print(a){
      if ((a>=0 && a<=5))
        {
       console.log("early morning");
       }
       else if(a>=6 && a<=12)
       {
       console.log("good morning");
       }
       else if(a>=13 && a<=16)
       {
        console.log("good afternoon");
       }
        else if(a>=17 && a<=20)
        {
       console.log("good evening");
    }
        else if(a>=20 && a<=24)
      {
        console.log("good night");
        }
     else if(a>24)
       {
        console.log("no time");
      }
      return a;
     }
    var a=print(7);
    console.log(a);
    //task2
     function max(a,b,c){
         if(a>b && a>c){
             console.log("a is max");
        }
        else if
            (b>a && b>c){
                 console.log("b is max");
             }
             else if(c>a && c>b){
                 console.log("c is max")
             }
             return a,b,c;
        }
        var d=max(2,8,6);
        console.log(d);
    //task3
    function avi(a,b){
        if(a<b){
           console.log("b is max");
       }
       else if(b<a) {
             console.log("a is max");
         }
        return a,b;
    }
     var c=avi(2,3);
     console.log(c);
    //task4
    function avi(a){
        if(a==0){
            console.log("sunday");
        }
        else if(a==1){
            console.log("monday");
        }
        else if(a==2){
            console.log("tuesday");
        }
        else if(a==3){
            console.log("wednessday");
        }
        else if(a==4){
            console.log("thursday");
         }
         else if(a==5){
            console.log("friday");
         }
         else if(a==6){
             console.log("saturday");
        }
        return a;
     }
     var b=avi(3);
    //task5
     function avi(a){
       switch(a){
           case 0:
               console.log("jan");
                break;
                case 2:
                console.log("feb");
                break;
                case 3:
                console.log("march");
                break;
                 case 4:
                 console.log("april");
               break;
                 case 5:
                 console.log("may");
                 break;
                 case 6:
                 console.log("june");
                break;
                 case 7:
                console.log("july");
                 break;
                case 8:
                console.log("sep");
                break;
                 case 9:
                 console.log("oct");
                break;
                case 10:
                console.log("nov");
                break;
                case 11:
                console.log("dec");
                break;      
         }
         return a;
 }
    var b=avi(8);
     task6
    function avi(a,b,c){
        if(c="+"){
           console.log(a+b);
      }
       else if(c="-"){
          console.log(a-b);
          }
         else if(c="*"){
              console.log(a*b);
             }
           else if(c="/"){
             console.log(a/b)
          }
            else if(c="/"){
               console.log(a%b)
        }
        return a,b,c;
   }
     var g=avi(2,4,"*");
    //task7
     function avi(a){
         if(a%2==0){
          console.log("even");
         }
        else{
        console.log("odd");
         }
         return a;
     }
    var b=avi(4);
     
    //task8
       function avi(a){
  for( var a=1;a<=10;a++){
       alert(a);
    }
    return a;
 }

var b=avi();
console.log(b);
//task9
debugger
function avi(a){
     for(var a=3;a<=10;a++){
        console.log(a);
         a +=3;
     return a;
    }

}
var b=avi();
console.log(b);
//task10
function avi(a){
    var a="avinash";
    for(var b=0;b<=7;b++){
        console.log(a[b]);
    }
    return b;
 }
 var b=avi(b);
//task11
function avi (a)
 {
    a<5 && a>=8 ? alert("hello"):alert("correct number");
return a;
    }
var b=avi(2);
//task12
function avi(a)
{
    for(var a=10;a>=0;a--){
        console.log(a);
    }
        return a;
    
}
var a=avi(a);

//task13
function avi(a){
    var b=0;
    for(i=0;a[i]!=undefined;i++){
      
         b++;

    }
    console.log(b);
   
 }
 avi("prathyusha")
//default parameter

 function add(a,b=3){
    return a+b;
 }
 var r=add(10);
 console.log(r);





    

        
    

 
    
    </script>
</body>
</html>
