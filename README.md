# java
.
 <h1>Aparecida Nutrição</h1>
.
Aparecida Nutrição
............
............................................................................................................................

 <script>

    var titulo = document.querySelector("h1");
    console.log(titulo);
    console.log(titulo.textContent);

    titulo.textContent = "Banana";
</script>

 <script>

    var titulo = document.querySelector("h1");

    titulo.textContent = "Aparecida Nutricionista";
</script>

 <header>

    <div class="container">
        <h2>Aparecida Nutrição</h2>
    </div>
</header
 Uncaught TypeError: Cannot set property 'textContent' of null
 
 <!-- ... -->

        </section>
    </main>
<script>
    var titulo = document.querySelector("h1");

    titulo.textContent = "Aparecida Nutricionista";
</script>

 <header>

    <div class="container">
        <h2 class="titulo">Aparecida Nutrição</h2>
    <<header>
    <div class="container">
        <h2 class="titulo">Aparecida Nutrição</h2>
    </div>
</header>/div>
</header>

 <script>

    var titulo = document.querySelector(".titulo");
    titulo.textContent = "Aparecida Nutricionista";
</script>

 var titulo = document.querySelector(".titulo");

titulo.textContent = "Aparecida Nutricionista";
 <!-- ... -->

        </section>
    </main>
<script src="js/principal.js"></script>

</body>
 IMC = peso / altura x altura;
 <tr class="paciente">

    <td class="info-nome">Paulo</td>
    <td class="info-peso">100</td>
    <td class="info-altura">2.00</td>
    <td class="info-gordura">10</td>
    <td class="info-imc">0</td>
</tr>
 var titulo = document.querySelector(".titulo");

titulo.textContent = "Aparecida Nutricionista";

var paciente = document.querySelector(".paciente");
 <tr class="paciente" id="primeiro-paciente">

    <td class="info-nome">Paulo</td>
    <td class="info-peso">100</td>
    <td class="info-altura">2.00</td>
    <td class="info-gordura">10</td>
    <td class="info-imc">0</td>
</tr>
 var titulo = document.querySelector(".titulo");

titulo.textContent = "Aparecida Nutricionista";

var paciente = document.querySelector("#primeiro-paciente");

console.log(paciente)
 <tr class="paciente" id="primeiro-paciente">

    <td class="info-nome">Paulo</td>
    <td class="info-peso">100</td>
    <td class="info-altura">2.00</td>
    <td class="info-gordura">10</td>
    <td class="info-imc">0</td>
</tr>
 var titulo = document.querySelector(".titulo");

titulo.textContent = "Aparecida Nutricionista";

var paciente = document.querySelector("#primeiro-paciente");
var tdPeso = paciente.querySelector(".info-peso");

console.log(paciente); // tr
cons < tr class="paciente" id="primeiro-paciente">...</tr>

<td class="info-peso">100</td> ole.log(tdPeso); // td que tem o peso
 var paciente = document.querySelector("#primeiro-paciente");

var tdPeso = paciente.querySelector(".info-peso");

var peso = tdPeso.textContent;

console.log(paciente); // tr
console.log(tdPeso); // td que tem o peso
console.log(peso); //Obter 100
 < tr class="paciente" id="primeiro-paciente">...</tr>

    <td class="info-peso">100</td>
100
 var paciente = document.querySelector("#primeiro-paciente");


var tdPeso = paciente.querySelector(".info-peso");
var peso = tdPeso.textContent;

var tdAltura = paciente.querySelector(".info-altura");
var altura = tdAltura.textContent;
 var tdAltura = paciente.querySelector(".info-altura");

var altura = tdAltura.textContent;

console.log(paciente); // tr
console.log(tdAltura); 
console.log(altura); 
 <tr class="paciente" id="primeiro-paciente">...</tr>

<td class="info-altura">2.00</td>

2.00<tr class="paciente" id="primeiro-paciente">...</tr>
<td class="info-altura">2.00</td>

2.00
 IMC = peso / altura x altura
 var tdAltura = paciente.querySelector(".info-altura");

var altura = tdAltura.textContent;

var imc = peso / (altura * altura);
 IMC = 100 / (2.00 x 2.00)

IMC = 100 / 4.00
IMC = 25
 var paciente = document.querySelector("#primeiro-paciente");


var tdPeso = paciente.querySelector(".info-peso");
var peso = tdPeso.textContent;

var tdAltura = paciente.querySelector(".info-altura");
var altura = tdAltura.textContent;

var imc = peso / altura * altura; // 100 / 2.0 x 2.0 = 100 / 4 =>>>>>>> 25

console.log(imc);
