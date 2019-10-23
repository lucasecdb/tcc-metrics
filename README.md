# Métricas TCC

Neste repositório estão contidas todas as métricas utilizadas no meu TCC em Ciência da Computação,
na Universidade Federal de Campina Grande. Todas as métricas estão relacionadas ao projeto [Convideo](https://github.com/lucasecdb/convideo).

## Formato das métricas

| nome | descrição |
| --- | --- |
| `filename` | Nome original do arquivo. |
| `elapsed_time` | Tempo total da execução da conversão do vídeo. |
| `input_size` | Tamanho original do arquivo, em bytes. |
| `output_size` | Tamanho final do arquivo, em bytes. |
| `format` | Nome do formato utilizado para a conversão. |
| `video_codec` | Nome do codec de vídeo utilizado para a conversão. |
| `audio_codec` | Nome do codec de áudio utilizado para a conversão. |
| `wasm` | Flag indicando se a conversão foi feita usando o algoritmo do FFMPEG compilado para WebAssembly. Se for 0, indica que foi utilizado a versão em JavaScript (asm.js). |
| `index` | Índice de execução. Útil para fazer o plot do gráfico. |
| `browser` | Nome do navegador utilizado. |
