# Projeto Fonte de Tensão - Eletrônica para Computação - BCC 020 - ICMC- USP

Grupo:
 - [Ana Vitória Gouvea](mailto:anavitoria_gouvea@usp.br)
 - [Eduardo Amaral](https://rolimans.dev)
 - [Matheus Luis Oliveira](mailto:matheuslos@usp.br)
 - [Sofhia de Souza](mailto:sofhiasouza@usp.br)

Turma: 
    BCC 020

Disciplina:
    SSC0180 - Eletrônica para Computação

Docente responsável:
    Eduardo do Valle Simões

# Vídeo de apresentação do projeto:

[![Vídeo de apresentação](https://img.youtube.com/vi/vGMtHB2vUWk/0.jpg)](https://www.youtube.com/watch?v=vGMtHB2vUWk)

# Lista de componentes do circuito:

- 1x  [Transformador Trafo 24V 1A - 110/220VAC](https://www.baudaeletronica.com.br/transformador-trafo-1a-24v.html)
- 4x [Diodo 1N4004](https://www.baudaeletronica.com.br/diodo-1n4004.html) (Ponte de diodos retificadora / MAX 400V - 1A)
- 1x [Capacitor 220uF - 35 V](https://www.baudaeletronica.com.br/capacitor-eletrolitico-220uf-35v.html)
- 1x [Led Azul](https://www.baudaeletronica.com.br/led-de-alto-brilho-azul.html) (Gastará aprox 5mA)
- 2x [Resistor 2k2](https://www.baudaeletronica.com.br/resistor-2k2-5-1-4w.html) (Fica em série com o LED e o - Potênciometro)
- 1x [Diodo Zener 13V - 0.5W](https://www.baudaeletronica.com.br/diodo-zener-bzx55c-13v-0-5w.html) (Recebe no máximo 0.3W)
- 1x [Resistor 2k](https://www.baudaeletronica.com.br/resistor-2k-5-1-4w.html) (Fica em série com o Zener)
- 1x [Potênciometro 5K](https://www.baudaeletronica.com.br/potenciometro-linear-de-5k-5000.html)
- 1x [Transistor NPN BC337](https://www.baudaeletronica.com.br/transistor-npn-bc337.html)
- 1x [Switch](https://www.baudaeletronica.com.br/chave-alavanca-mrs-101n-amarela-com-neon.html)


# Simulação do Circuito no simulador Falstad:

- Acesse o simulador [Falstad](https://falstad.com/circuit/circuitjs.html)
- Vá em `File > Import from Text` e cole o conteúdo do arquivo `./circuitoFalstad.txt` presente neste repositório.

A simulação aberta deve ser semelhante a esta:

<img src="https://imgur.com/HP81oYS.png" alt="Simulação Falstad" width="1200" />

# Esquemático do Circuito no software CAD Eagle:
 - Obtenha o software [Eagle](https://www.autodesk.com/products/eagle/blog/how-to-install-autodesk-eagle-on-windows-mac-and-linux/)
 - Vá em `File > Open > Schematic...` e selecione o arquivo `./EagleFiles/fonte_simoes.sch` presente neste repositório.

O esquemático aberto deve ser semelhante a este:

<img src="https://imgur.com/SwUxT6b.png" alt="Esquemático Eagle" width="1200" />

# PCB   do Circuito no software CAD Eagle:
 - Obtenha o software [Eagle](https://www.autodesk.com/products/eagle/blog/how-to-install-autodesk-eagle-on-windows-mac-and-linux/)
 - Vá em `File > Open > Board...` e selecione o arquivo `./EagleFiles/fonte_simoes.brd` presente neste repositório.

O PCB aberto deve ser semelhante a este:

<img src="https://i.imgur.com/cCj0ZJz.png" alt="Esquemático Eagle" width="1200" />



# Licença
Este projeto é livre; você pode redistribuí-lo e/ou modificá-lo sobre os termos da GNU General Public License publicada pela Free Software Foundation; versão 3 ou superior.
