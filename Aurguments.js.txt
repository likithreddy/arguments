function longest(){
var lng="";
for(var i=0;i<arguments.length;i++){
if(arguments[i].length>lng.length){
lng=arguments[i];
}
}
return lng;
}
console.log(longest("hello","worlds","mac","windows","linux","alphabets","android"));