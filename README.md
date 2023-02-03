# Mr.-Techno-star
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styleformulabook.css">
    <title>Modern Physics</title>
</head>
<body>
    <header>
        <h1>Modern Physics</h1>
    </header>
    <formula id="formula">
        <div class="each-formula">
            <h3>1. Energy of Photon, E = <math>
                <mfrac>
                  <mrow>
                    <mi>hv</mi>
                  </mrow>
                </mfrac>
              </math> = <math>
                <mfrac>
                  <mrow>
                    <mi>hc</mi>
                  </mrow>
                  <mrow>
                    <mi>&lambda;</mi>
                  </mrow>
                </mfrac>
              </math> = <math>
                <mfrac>
                  <mrow>
                    <mi>12400</mi>
                  </mrow>
                  <mrow>
                    <mi>&lambda; (&#8491;)</mi>
                  </mrow>
                </mfrac>
              </math>
              </h3>
              <p>{ h = planck's constant = 6.62 x 10<sup>-34</sup> ;
                <br>
                &nbsp;&nbsp; v = frequency of photon ;
                <br>
                &nbsp;&nbsp; c = speed of light = 3 x 10<sup>8</sup> ; }</p>
        </div>
        <div class="each-formula">
            <h3>2. Linear momentum of Photon, P =  <math>
                <mfrac>
                  <mrow>
                    <mi>E</mi>
                  </mrow>
                  <mrow>
                    <mi>c</mi>
                  </mrow>
                </mfrac>
              </math> = <math>
                <mfrac>
                  <mrow>
                    <mi>hv</mi>
                  </mrow>
                  <mrow>
                    <mi>c</mi>
                  </mrow>
                </mfrac>
              </math> = <math>
                <mfrac>
                  <mrow>
                    <mi>h</mi>
                  </mrow>
                  <mrow>
                    <mi>&lambda;</mi>
                  </mrow>
                </mfrac>
              </math></h3>
        </div>
        <div class="each-formula">
            <h3>3. Intensity of light, I = <math>
                <mfrac>
                  <mrow>
                    <mi>E</mi>
                  </mrow>
                  <mrow>
                    <mi>At</mi>
                  </mrow>
                </mfrac>
              </math> = <math>
                <mfrac>
                  <mrow>
                    <mi>Power</mi>
                  </mrow>
                  <mrow>
                    <mi>A</mi>
                  </mrow>
                </mfrac>
              </math> = <math>
                <mfrac>
                  <mrow>
                    <mi>n(hv)</mi>
                  </mrow>
                  <mrow>
                    <mi>A</mi>
                  </mrow>
                </mfrac>
              </math> &nbsp;&nbsp;&nbsp;(<span>J/m<sup>2</sup>.s or watt/m<sup>2</sup></span>)</h3>
            <p>{ n = no. of photns per sec }</p>
        </div>
        
    </formula>
    <add>
          <button id="add_formula">+Add Formula</button>
    </add>
    <script>
      let add_formula = document.getElementById("add_formula")
      add_formula.addEventListener("click",function() {
        let formula_section = document.getElementById("formula")
        let newDiv = document.createElement("div")
        newDiv.classList.add("each-formula")
        formula_section.appendChild(newDiv)
        let newWin = window.open("about:blank", "hello", "width=200,height=200");
        newWin.document.write("Hello, world!");
      })
    </script>
</body>
</html>
