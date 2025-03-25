<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Organizador de Séries</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f4f4f9; color: #333; }
        .container { max-width: 800px; margin: 20px auto; padding: 20px; background-color: white; border-radius: 8px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
        h1 { text-align: center; }
        input, button { width: 100%; padding: 10px; margin: 10px 0; font-size: 16px; }
        button { background-color: #4CAF50; color: white; border: none; cursor: pointer; }
        button:hover { background-color: #45a049; }
        .serie-list { margin-top: 20px; }
        .serie-item { padding: 10px; background-color: #f9f9f9; margin: 5px 0; border-radius: 5px; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Organizador de Séries</h1>
        <input type="text" id="serie-name" placeholder="Nome da Série">
        <input type="text" id="season-name" placeholder="Nome da Temporada">
        <input type="text" id="episode-name" placeholder="Nome do Episódio">
        <button onclick="addEpisode()">Adicionar Episódio</button>

        <div class="serie-list" id="serie-list"></div>

        <button onclick="generateList()">Gerar Lista XML</button>
    </div>

    <script>
        let series = [];

        function addEpisode() {
            const serieName = document.getElementById('serie-name').value;
            const seasonName = document.getElementById('season-name').value;
            const episodeName = document.getElementById('episode-name').value;

            if (serieName && seasonName && episodeName) {
                const episode = { serieName, seasonName, episodeName };
                series.push(episode);
                updateList();
            } else {
                alert('Preencha todos os campos!');
            }
        }

        function updateList() {
            const listContainer = document.getElementById('serie-list');
            listContainer.innerHTML = '';
            series.forEach(episode => {
                const div = document.createElement('div');
                div.classList.add('serie-item');
                div.innerHTML = `<strong>${episode.serieName}</strong> - Temporada: ${episode.seasonName} - Episódio: ${episode.episodeName}`;
                listContainer.appendChild(div);
            });
        }

        function generateList() {
            let xmlContent = '<?xml version="1.0" encoding="UTF-8"?>\n<series>\n';

            series.forEach(episode => {
                xmlContent += `  <serie>\n    <name>${episode.serieName}</name>\n    <season>${episode.seasonName}</season>\n    <episode>${episode.episodeName}</episode>\n  </serie>\n`;
            });

            xmlContent += '</series>';

            const blob = new Blob([xmlContent], { type: 'application/xml' });
            const link = document.createElement('a');
            link.href = URL.createObjectURL(blob);
            link.download = 'lista_series.xml';
            link.click();
        }
    </script>
</body>
</html>
