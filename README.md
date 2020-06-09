# Param card

The following website is intended to explain the structure of the param card used to simulate monte carlo events using madgraph, pythia and delphes. This simulation takes into account an standard model extension, known as the Minimal Supersymmetric Standard Model (MSSM). 

The parameters associated with the MSSM are given by:

|  Parameter | Description |
|:--------:|:------------------:|
|  Signal  |         0.2        |
| $t\bar{t}$ |        504,4       |
|  w+jets  |       148.100      |
|    ww    |        65,53       |
|    wz    |        24,75       |
|  z+jets  |       43.120       |
|    zz    |        9,549       |

```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="param_card_isr.css">
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
</head>

<body>

    <header>
        <div>
            Param Card para proyecto \(\tilde{\tau} + \text{ISR jet}\)
        </div>
    </header>

    <div class="contenido">
        <p>A continuación se describirá la <i><b>Param Card</b></i> correspondiente a una simulación de eventos bajo el
            modelo estandar de mínima supersimetría (MSSM) en MadGraph a través del modelo <i><b>MSSM_SLHA2</b></i>.
            Estas
            simulaciones se corren para eventos donde se considera coaniquilación \(\tilde{\tau}-\tilde{\chi}_{1}^{0}\)
            y la
            emisión de un jet radiación de estado inicial (<i><b>ISR jet</b></i>). Estos eventos se rigen por diagramas
            de Feynman como el siguiente:
        </p>

        <div class="text-center imagenes">
            <img src="stau1_negro.png">
        </div>

        <p>
            que representa el decaimiento directo del \(\tilde{\tau}\) más un ISR jet o los siguientes dos:
        </p>

        <div class="text-center dos_imagenes">
            <img src="stau2_negro.png" style="padding: 10px 20px;">
            <img src="stau3_negro.png" style="padding: 10px 20px;">
        </div>

        <p>
            que muestran la producción de pares chargino/neutralino 2 más un ISR jet teniendo como mediadores los
            bosones \(\gamma/Z\) (izquierda) y la producción de chargino junto con neutralino 2 más un ISR jet con el
            boson \(W^{\pm}\) como mediador (derecha) respectivamente.
        </p>
    </div>

    <section class="contenedor_subtitulos flex text-center">
        <p class="subtitulos">
            Parámetros asociados al MSSM:
        </p>
    </section>
```
