# Órbitas de Satélites GNSS — Geodésia II

## Sobre o projeto

Este notebook em Python apresenta, de forma didática, as etapas necessárias para calcular as coordenadas de satélites GNSS a partir de um arquivo de navegação RINEX, utilizando as efemérides transmitidas pelos satélites.

O material foi desenvolvido para fins educacionais na disciplina de **Geodésia II**, auxiliando na compreensão da relação entre os dados de navegação, os parâmetros orbitais e o cálculo das coordenadas dos satélites.

## Objetivos de aprendizagem

* Compreender a estrutura de um arquivo de navegação RINEX.
* Identificar os parâmetros das efemérides transmitidas.
* Entender e aplicar as equações utilizadas no cálculo da posição dos satélites.
* Calcular as coordenadas dos satélites para um instante específico.
* Compreender as etapas envolvidas no cálculo das órbitas de satélites GNSS.

## Requisitos

* Python 3.
* Conta Google para utilizar o Google Colab.
* Arquivo de navegação RINEX compatível com o sistema GNSS utilizado no exercício.

## Como executar no Google Colab

1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Selecione **Arquivo → Fazer upload de notebook**.
3. Envie o arquivo `.ipynb` deste repositório.

Também é possível abrir o notebook diretamente pelo GitHub:

1. No Google Colab, selecione **Arquivo → Abrir notebook**.
2. Acesse a aba **GitHub**.
3. Informe a URL do repositório.
4. Selecione o notebook desejado.

Após abrir o notebook:

1. Carregue o arquivo de navegação RINEX solicitado pelo código.
2. Execute as células sequencialmente, utilizando o botão de execução de cada célula ou a opção **Ambiente de execução → Executar tudo**.
3. Analise os resultados e acompanhe cada etapa do cálculo das coordenadas dos satélites.

**Observação:** caso o notebook utilize bibliotecas externas, pode ser necessário instalá-las no ambiente do Colab. Os arquivos utilizados também devem ser enviados para a sessão ou acessados pelo Google Drive, conforme a implementação do código.

## Conteúdo do repositório

* `gnss_satellite_orbits.ipynb` — notebook com explicações, cálculos e exemplos de aplicação.

## Público-alvo

Estudantes de graduação em Engenharia Cartográfica, Engenharia de Agrimensura e áreas relacionadas, especialmente aqueles que cursam disciplinas de Geodésia e posicionamento por satélites GNSS.

## Referências

* [International GNSS Service (IGS)](https://igs.org/) — informações e recursos relacionados aos sistemas GNSS.
* [Especificações RINEX — IGS](https://www.igs.org/wg/rinex/) — documentação sobre o formato dos arquivos de observação e navegação GNSS.

## Licença

Salvo indicação em contrário, este material não possui uma licença explícita de reutilização ou redistribuição.