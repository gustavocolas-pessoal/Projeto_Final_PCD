<img src="Imagens do README\Cabecalho.png"/>

# Jogo do Dilema dos Prisioneiros

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.13-blue">
  <img src="https://img.shields.io/badge/Pygame-CE-green">
  <img src="https://img.shields.io/badge/Área-Game%20Theory-darkred">
</p>

Jogo interativo do Dilema dos Prisioneiros desenvolvido em Python com a biblioteca Pygame. O jogador enfrenta seis bots com comportamentos distintos - desde estratégias fixas até agentes com memória das rodadas anteriores - e deve descobrir qual é a estratégia ótima para cada adversário. Este projeto é um trabalho de final da disciplina Práticas em Ciência de Dados do primeiro semestre da ILUM do aluno Gustavo Junqueira Colas.

## Como executar:

1. Baixe ou clone o repositório e extraia os arquivos em uma pasta

2. Com o seu editor (preferencialmente o VSCode), vá em *File*, *Open Folder* e selecione a pasta **Projeto Final**

3. Instale as dependências com o comando:
```sh
pip install -r requirements.txt
```

4. Abra o arquivo **FINAL_PCD_explicado_(certo).ipynb** e execute todas as células em ordem

## Conteúdo:

<ul>
  <li>:file_folder: <b>Projeto Final</b>: contém todos os arquivos necessários para rodar o jogo</li>
    <ul>
      <li>:file_folder: <b>FINAL_PCD_IMAGENS</b>: contém todos as imagens que são usadas no jogo</li>
        <ul>
          <li>:framed_picture: <b>image-1.png</b> a <b>image-5.png</b>: frames da animação de abertura da cela no menu</li>
          <li>:framed_picture: <b>Captura de tela 2026-05-11 105120.png</b>: imagem do jornal fictício de introdução</li>
        </ul>
      <li>:notebook: <b>FINAL_PCD_explicado_(certo).ipynb</b>: relatório completo do projeto com o código comentado e pronto para rodar, acompanhado das seções de introdução, metodologia, resultados e conclusão</li>
      <li>:notebook: <b>primeiro_rascunho.ipynb</b>: versão inicial do jogo, sem interface gráfica, rodando inteiramente no terminal - incluída para que o leitor possa acompanhar a evolução do projeto</li>
      <li>:spiral_notepad: <b>requirements.txt</b>: lista das bibliotecas necessárias para rodar o projeto</li>
    </ul>
</ul>

## Tecnologias Utilizadas:

O projeto foi confeccionado inteiramente em Jupyter Notebook, particularmente na linguagem Python (versão 3.13), utilizando das bibliotecas nativas random e sys, além da biblioteca externa Pygame. Inteligência artificial (na forma de LLMs) foi utilizada para guiar o aluno nos aprendizados da biblioteca Pygame e do uso do GitHub, como também para algumas tarefas mecânicas (exemplo: revisão ortográfica). 


## Os bots:

O jogo conta com dois grupos de adversários:

**Sem memória** - tomam decisões independentemente do histórico de jogadas:
| Bot | Comportamento |
|---|---|
| **Randomico** | Escolhe aleatoriamente entre trair e cooperar a cada rodada |
| **Bonzinho** | Sempre coopera |
| **Malvadão** | Sempre trai |

**Com memória** - "adaptam" sua estratégia com base no que o jogador fez:
| Bot | Comportamento |
|---|---|
| **Vingativo** | Coopera até ser traído uma vez; depois trai para sempre |
| **Imitador** | Copia exatamente a última jogada do jogador (Tit-for-Tat) |
| **Bravo** | Retalia traições, mas perdoa após duas cooperações consecutivas |

## XKCD (adaptado) relevante:

<img src="Imagens do README\XKCD_Final_Exams_adaptado.png"/>

## Professores avaliadores:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/drcassar">
        <img src="https://avatars.githubusercontent.com/u/9871905?v=4" width="100px;" alt="Foto do Cassar no Github"/><br>
        <b>Prof. Dr. Daniel R. Cassar</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/jamesmalmeida">
        <img src="https://avatars.githubusercontent.com/u/108157661?v=4" width="100px;" alt="Foto do James no Github"/><br>
        <b>Prof. James Moraes de Almeida</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/llemos">
        <img src="https://avatars.githubusercontent.com/u/1894434?v=4" width="100px;" alt="Foto do Leandro no Github"/><br>
        <b>Prof. Leandro Nascimento Lemos</b>
      </a>
    </td>
  </tr>
</table>

## Aluno:

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/gustavocolas-pessoal">
        <img src="https://avatars.githubusercontent.com/u/284495799?s=80&v=4" width="100px;" alt="Foto do Gustavo no Github"/><br>
        <b>Gustavo Junqueira Colas</b>
      </a>
    </td>
  </tr>
</table>
<img src="Imagens do README\Rodape.png"/> 

## Agradecimentos:

Aos professores supracitados Prof. Leandro Nascimento Lemos, Prof. James Moraes de Almeida e Prof. Dr. Daniel R. Cassar, por fornecer base teórica de programação em Python e lógica computacional, como também por sanar dúvidas fundamentais na criação do projeto. Aos colegas de sala e amigos Vinícius M. M. Cutolo, Filipi Martins, Pedro Lucas M. S. de Sá e Gabriel O. Paiva, por ajudarem a avaliar o andamento do projeto (dizendo se, por exemplo, a posição dos textos estava boa) e por sugerirem materiais extras (como o vídeo do canal Veritasium). 