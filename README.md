# Projects
Repositório apenas para projetos
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Cálculadora de Gorjetas</title>
</head>
<body>
    <div id="container">
    <div>
        <h1 class="title">Cálculadora de Gorjetas</h1>
    </div>
        <form class="tipsForm" id="tipsForm">
            <label form="bill">
                <p>Quanto ficou a conta?</p>
            </label>
            <p>
                R$ <input tybe="number" placeholder="100" name="bill" id="bill" class="formInput">
            </p>
            <label form="serviceQual">
                <p>Como foi seu serviço?</p>
            </label>
            <p>
                <select name="serviceQual" id="serviceQual" class="formSelect">
                    <option disable selected value="0">-- Escolha uma opção</option>
                    <option value="0.3">30% - Incrivel</option>
                    <option value="0.2">20% - Bom</option>
                    <option value="0.15">15% - Aceitavel</option>
                    <option value="0.10">10% - Ruim</option>
                    <option value="0.05">0.5% - Pessimo</option>
                </select>
            </p>
            <label form="people">
                <p>Quantas pessoas vão dividir a conta?</p>
            </label>
            <p>
                <input type="number" placeholder="1" name="people" id="people" class="formInput"> pessoa(s)
            </p>
            <button type="submit" class="formSubmit">Cálcular!</button>
            <div id="totalTip">
                Gorjeta total:
                R$<span id="tip">0.00</span>
                <span id="each">cada</span>
            </div>    
        </div>
        </form>
    </div>

 </div> 
 <script type="text/javascript" src="Java.js"></script>
</body>
</html>
