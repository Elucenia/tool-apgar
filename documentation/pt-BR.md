<!-- ELUCENIA technical documentation · apgar · pt-BR · no clinical/professional/rights approval -->

# Escore de Apgar

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/apgar)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Frequência cardíaca

`fc`

- `0` — Ausente
- `1` — \< 100 bpm
- `2` — ≥ 100 bpm

### Esforço respiratório

`resp`

- `0` — Ausente
- `1` — Lento, irregular
- `2` — Bom, choro forte

### Tônus muscular

`tonus`

- `0` — Flácido
- `1` — Alguma flexão
- `2` — Movimentos ativos

### Irritabilidade reflexa

`reflexo`

- `0` — Sem resposta
- `1` — Careta
- `2` — Choro, tosse ou espirro

### Cor

`cor`

- `0` — Cianose ou palidez
- `1` — Corpo róseo, extremidades cianóticas
- `2` — Completamente róseo

## Edição do método

Apgar 1953:5 sinais 0–2; seguimento AAPACOG 2015 em 1/5 min e repetição se\<7

## Fórmula documentada

Cinco sinais, cada um de 0 a 2 pontos: frequência cardíaca, esforço respiratório, tônus, irritabilidade reflexa e cor. Total de 0 a 10, aplicado no 1º e no 5º minuto; se o 5º minuto for \< 7, repetir a cada 5 minutos até 20 minutos.

## Limites e população

Apgar registra a condição do recém-nascido e a resposta à ressuscitação; não define os passos iniciais da ressuscitação, não diagnostica asfixia e não prevê sozinho mortalidade ou desfecho neurológico individual. O escore atribuído durante ressuscitação não equivale ao obtido em respiração espontânea. Prematuridade, medicamentos maternos e variabilidade do exame podem influenciar o resultado.

## Referências

- [Apgar V. A proposal for a new method of evaluation of the newborn infant. Curr Res Anesth Analg, 1953 (republicado em Anesth Analg, 2015).](https://doi.org/10.1213/ANE.0b013e31829bdc5c)

- [American Academy of Pediatrics; American College of Obstetricians and Gynecologists. The Apgar Score. Pediatrics, 2015.](https://doi.org/10.1542/peds.2015-2651)

- [AAP/ACOG2015;DOI10.1542/peds.2015-2651](https://publications.aap.org/pediatrics/article/136/4/819/73821/The-Apgar-Score)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
