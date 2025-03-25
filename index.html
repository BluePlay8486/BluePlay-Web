<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerador de XML de Séries</title>
    <style>
        body { font-family: Arial, sans-serif; background-color: #f4f4f9; color: #333; }
        .container { max-width: 800px; margin: 20px auto; padding: 20px; background-color: white; border-radius: 8px; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1); }
        h1 { text-align: center; }
        input, button { width: 100%; padding: 10px; margin: 10px 0; font-size: 16px; }
        button { background-color: #4CAF50; color: white; border: none; cursor: pointer; }
        button:hover { background-color: #45a049; }
        .episode-list { margin-top: 20px; }
        .episode-item { padding: 10px; background-color: #f9f9f9; margin: 5px 0; border-radius: 5px; }
    </style>
</head>
<body>
    <div class="container">
        <h1>Gerador de XML de Séries</h1>
        <input type="text" id="serie-name" placeholder="Nome da Série">
        <input type="text" id="episode-name" placeholder="Nome do Episódio">
        <input type="text" id="episode-link" placeholder="Link do Episódio">
        <button onclick="addEpisode()">Adicionar Episódio</button>

        <div class="episode-list" id="episode-list"></div>

        <button onclick="generateXML()">Gerar XML</button>
    </div>

    <script>
        let episodes = [];

        function addEpisode() {
            const serieName = document.getElementById('serie-name').value;
            const episodeName = document.getElementById('episode-name').value;
            const episodeLink = document.getElementById('episode-link').value;

            if (serieName && episodeName && episodeLink) {
                const episode = { serieName, episodeName, episodeLink };
                episodes.push(episode);
                updateList();
            } else {
                alert('Preencha todos os campos!');
            }
        }

        function updateList() {
            const listContainer = document.getElementById('episode-list');
            listContainer.innerHTML = '';
            episodes.forEach(episode => {
                const div = document.createElement('div');
                div.classList.add('episode-item');
                div.innerHTML = `<strong>${episode.serieName}</strong> - Episódio: ${episode.episodeName} - <a href="${episode.episodeLink}" target="_blank">${episode.episodeLink}</a>`;
                listContainer.appendChild(div);
            });
        }

        function generateXML() {
            let xmlContent = '<?xml version="1.0" encoding="UTF-8" standalone="yes"?>\n<items>\n';

            episodes.forEach(episode => {
                xmlContent += `  <item>\n    <title>[B]${episode.serieName}[/B] [COLOR yellow](COMPLETO)[/COLOR]</title>\n`;
                xmlContent += `    <link>${episode.episodeLink}</link>\n`;
                xmlContent += `    <thumbnail></thumbnail>\n`;
                xmlContent += `    <fanart></fanart>\n`;
                xmlContent += `    <info></info>\n`;
                xmlContent += `  </item>\n`;
            });

            xmlContent += '</items>';

            const blob = new Blob([xmlContent], { type: 'application/xml' });
            const link = document.createElement('a');
            link.href = URL.createObjectURL(blob);
            link.download = 'series.xml';
            link.click();
        }
    </script>
</body>
</html>
