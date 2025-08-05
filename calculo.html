<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Bisseção Mínimo</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
        }
        .container { 
            background-color: #fff;
            padding: 20px;
            margin-top: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            width: 400px;
        }
        input { 
            width: 100%; 
            padding: 8px;
            margin-bottom: 10px;
            box-sizing: border-box;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            color: white;
            border: none;
            cursor: pointer;
        }
        #resultado {
            margin-top: 15px;
            padding: 10px;
            background-color: #e9ecef;
            border-left: 5px solid #007bff;
            font-weight: bold;
        }
    </style>
</head>
<body>

<div class="container">
    <h2>Método da Bisseção</h2>

    <label for="funcao">Função f(x):</label>
    <input type="text" id="funcao" value="x**3 - x - 2">

    <label for="a">Início do intervalo (a):</label>
    <input type="number" id="a" value="1">

    <label for="b">Fim do intervalo (b):</label>
    <input type="number" id="b" value="2">

    <label for="precisao">Precisão:</label>
    <input type="number" id="precisao" value="0.0001">

    <button id="calcular">Calcular</button>

    <div id="resultado"></div>
</div>

<script>
document.getElementById('calcular').addEventListener('click', () => {
    const funcaoStr = document.getElementById('funcao').value;
    let a = parseFloat(document.getElementById('a').value);
    let b = parseFloat(document.getElementById('b').value);
    const precisao = parseFloat(document.getElementById('precisao').value);
    const resultadoDiv = document.getElementById('resultado');

    let f;
    try {
        const funcaoJS = funcaoStr.replace(/\^/g, '**');
        f = new Function('x', `return ${funcaoJS}`);
    } catch (e) {
        resultadoDiv.textContent = 'Erro na função. Verifique a sintaxe.';
        return;
    }

    if (isNaN(a) || isNaN(b) || isNaN(precisao)) {
        resultadoDiv.textContent = 'Valores de a, b ou precisão são inválidos.';
        return;
    }
    if (f(a) * f(b) >= 0) {
        resultadoDiv.textContent = 'Não há garantia de raiz no intervalo, pois f(a) * f(b) >= 0.';
        return;
    }

    let iteracoes = 0;
    const MAX_ITERACOES = 1000;
    let xn;

    while (iteracoes < MAX_ITERACOES) {
        iteracoes++;
        xn = (a + b) / 2;

        if (Math.abs(b - a) < precisao) {
            break;
        }
        
        if (f(a) * f(xn) < 0) {
            b = xn;
        } else {
            a = xn;
        }
    }

    if (iteracoes >= MAX_ITERACOES) {
        resultadoDiv.textContent = `Não convergiu em ${MAX_ITERACOES} iterações.`;
    } else {
        resultadoDiv.textContent = `Raiz ≈ ${xn.toFixed(6)} (encontrada em ${iteracoes} iterações)`;
    }
});
</script>

</body>
</html>
