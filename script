function comprar(vaso){

localStorage.setItem("compraUsuario", vaso);

document.getElementById("compra").innerText =
"Compraste: " + vaso;

}

window.onload = function(){

let compra = localStorage.getItem("compraUsuario");

if(compra){
document.getElementById("compra").innerText =
"Compraste: " + compra;
}

}
