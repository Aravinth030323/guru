let idly=true
let sambar=false
let poori= true
let kelangu= false
let dosa= true
let chuttny= false
let waterbootle= true

if(idly&&sambar){
    console.log("idly,sambar")
}
else if ((poori&&sambar)||(poori&&kelangu)){
    console.log("poori,kelangu")
}
else if(dosa&&chuttny){
    console.log("dosa,chuttny")
}
else
console.log("waterbootle")


