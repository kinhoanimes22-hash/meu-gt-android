<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GT Android Pro</title>
    <style>
        body { background: #0a0a0a; color: #fff; font-family: sans-serif; padding: 15px; margin: 0; }
        .container { max-width: 600px; margin: auto; }
        h2 { color: #4CAF50; text-align: center; border-bottom: 2px solid #333; padding-bottom: 10px; }
        textarea { 
            width: 100%; height: 250px; background: #151515; color: #00ff00; 
            border: 1px solid #444; border-radius: 8px; padding: 12px; 
            font-family: monospace; font-size: 14px; box-sizing: border-box;
        }
        .btns { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 15px; }
        button { 
            padding: 15px; border: none; border-radius: 8px; color: white; 
            font-weight: bold; font-size: 14px; cursor: pointer; transition: 0.3s;
        }
        #btnRun { background: #3f51b5; grid-column: span 2; }
        #btnClear { background: #f44336; }
        #btnExport { background: #4CAF50; }
        #terminal { 
            margin-top: 20px; padding: 15px; background: #000; 
            border-radius: 8px; border: 1px solid #333; min-height: 120px; 
        }
        .preview-content { background: white; color: black; padding: 15px; border-radius: 5px; margin-bottom: 10px; overflow: auto; }
    </style>
</head>
<body>
    <div class="container">
        <h2>GT ANDROID <span style="color:white">EXECUTOR</span></h2>
        <textarea id="editor" placeholder="Digite seu código HTML/JS aqui..."></textarea>
        
        <div class="btns">
            <button id="btnRun">RODAR PROJETO</button>
            <button id="btnExport">GERAR ARQUIVO</button>
            <button id="btnClear">LIMPAR</button>
        </div>

        <h4>Terminal / Visualização:</h4>
        <div id="terminal">> Aguardando comando...</div>
    </div>

    <script>
        const editor = document.getElementById('editor');
        const terminal = document.getElementById('terminal');

        document.getElementById('btnRun').onclick = () => {
            const code = editor.value;
            if(!code) return;
            terminal.innerHTML = `<div class="preview-content">${code}</div><span style="color:lime">> Executado com sucesso!</span>`;
            
            // Tenta executar scripts dentro do código inserido
            const scripts = terminal.getElementsByTagName('script');
            for (let i = 0; i < scripts.length; i++) {
                try { eval(scripts[i].innerText); } catch (e) { console.error(e); }
            }
        };

        document.getElementById('btnExport').onclick = () => {
            const blob = new Blob([editor.value], {type: 'text/html'});
            const url = URL.createObjectURL(blob);
            const a = document.createElement('a');
            a.href = url;
            a.download = "meu_app.html";
            a.click();
        };

        document.getElementById('btnClear').onclick = () => {
            editor.value = "";
            terminal.innerHTML = "> Memória limpa.";
        };
    </script>
</body>
</html>
