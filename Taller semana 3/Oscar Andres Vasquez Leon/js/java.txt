1.
/*
let edad_1 = parseInt(prompt("Digite su edad de graduacion"));
let edad_2 = parseInt(prompt("Digite su edad actual"));

if(edad_1 > edad_2){
    alert("Todavia no te graduas");
}

else if(edad_2 > edad_1){
    alert("Ya te graduaste");
}

else if(edad_1 = edad_2){
    alert("Este año te graduas")
}
*/

2.
/*
let contador = 1
let limite = parseInt(prompt("Digite la cantidad de estudiantes"));
let acum = 0
let prom = 0
while(contador <= limite){
let estudiante = prompt("Digite el nombtre del estudiante");
let nota = parseInt(prompt("Digite la nota del estudiante"));

document.write(estudiante + "<br>");
document.write(nota + "<br>");

acum+=nota;
prom=acum/contador;

document.write("El promedio de las notas es " + prom);

contador++
}
*/

3. 
/*
let santoyseña = "dom";
let solicitud = prompt("Digite su santo y seña");

if(solicitud.toLocaleLowerCase() == santoyseña){
    alert("bienvenidos al nuevo club de los magios");
}

else if(solicitud !== santoyseña){
    alert("No puedes ingresar, no eres un miembro");
}
*/

4.
/*
let si_esta_vacunado = "si";
let no_esta_vacunado = "no"
let respuesta = prompt("Indique si o no, si esta vacunado");

if(respuesta.toLocaleLowerCase() === si_esta_vacunado){
    document.write("bienvenido");
}

else if(respuesta.toLocaleLowerCase() == no_esta_vacunado){
    document.write("por favor ve a vacunarte, no puedes ingresar");
}

else if(respuesta != no_esta_vacunado + si_esta_vacunado){
    document.write("No ingresaste una respuesta valida");
}
*/

5.
/*
function resta (){
    
    let date1 = document.getElementById("fecha_de_nacimiento").value;
    let date2 = document.getElementById("fecha_actual").value;
    let Edad = document.getElementById("Resultado").value;

    Edad=parseInt(date2) - parseInt(date1);

    document.getElementById("Resultado").value=Edad;

}

function limpiar (){
    document.getElementById("fecha_de_nacimiento").value="";
    document.getElementById("fecha_actual").value="";
    document.getElementById("Resultado").value="";

}
*/

6.
/*
function seleccionar(){
    let Colombia = document.getElementById("Colombia").value;
    let Argentina = document.getElementById("Argentina").value;
    let Peru = document.getElementById("Peru").value;
    let Japon = document.getElementById("Japon  ").value;
    let Alemania = document.getElementById("Alemania").value;
    let Capital = document.getElementById("Capital").value;

    let capital_Colombia = "Bogota";
    let capital_Argentina = "Buenos Aires";
    let capital_Peru = "Lima";
    let capital_Japon = "Tokio";
    let capital_Alemania = "Berlin";
    
    Colombia=Capital + capital_Colombia;
}
*/

7.
/*
let contador = 1;
let tabla = prompt("digite la tabla que desea multiplicar");
let limmite = 100;
while (contador<= parseInt (limmite)){
    
    document.write(tabla + " x " + contador + " = " + (tabla * contador) + "<br>");
    contador++;
}
*/

8.
/*
function traducir(){
    let Yellow = document.getElementById("Yellow").value;


}*/