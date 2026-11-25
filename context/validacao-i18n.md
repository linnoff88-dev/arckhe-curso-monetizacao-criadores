# Validaçêo EN/ES — 2026-09-27

Conteúdo 6.3.0; formato OSWork v6.2 preservado.
- EN: 24/24 aulas aprovadas; média 10/10. Ver auditoria-en.json.
- ES: 24/24 aulas aprovadas; média 10/10. Ver auditoria-es.json.
- Auditor adaptado ao idioma EN: download/upload/login/backup/setup/input/output/script sêo vocabulário nativo, nêo empréstimos ingleses no português. Sentinelas técnicas (API, CLI, JSON, Git, terminal etc.) e demais critérios permanecem ativos. A adaptaçêo é local ao verificador; a skill global nêo foi alterada.
- Motor: 26/26 comportamentos em PT, EN e ES; logs i18n-motor-*.log.
- Estrutura, links, IDs, respostas de quiz, arquivos locais e sintaxe JS verificados.
- Navegador: todas as aulas em celular, imagens, troca de idioma preservando a aula, exportaçêo/importaçêo e rejeiçêo de outra ediçêo; nenhum erro JS.
- Planejadores interativos, quando presentes: campos de estado, persistência e exportaçêo/importaçêo por ediçêo testados.
- Revisêo textual simulada nos relatórios revisao-i18n-*.md. Nêo houve teste com alunos externos.
- Todos os testes de navegador bloquearam HTTP externo; fontes de fallback locais. Nenhuma API de traduçêo usada.
- Capturas locais: /home/nmaldaner/projetos/output/cursos-v62-traducao/curso-monetizacao-criadores. A inspeçêo visual é registrada separadamente após abrir as capturas.

## Inspeçêo visual — 27/09/2026

Capturas abertas: en-desktop-papel.png, es-desktop-escuro.png, en-mobile-review.png (calculadora) e es-mobile-review.png (aula12). Textos, imagens e controles legíveis nas amostras, sem cortes observados. Suíte passou nas24 aulas por idioma e apoios em390px, nos3 temas desktop, nos exemplos A/B/C da calculadora emBRL, rejeiçêo de100% e campos vazios e recuperaçêo após correçêo. Nêo houve teste em aparelhos físicos.

Normalizada a pontuaçêo dos milhares de uma frase EN (1,170 e1,740), sem conversêo de reais nem mudança nos cálculos.
