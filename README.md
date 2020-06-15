# -Lista-Mat-Comp-INPE-Yuri
Contém os exercícios resolvidos da lista de exercício sobre Análise Estatística e Processos Estocásticos da disciplina Matemática Computacional.

<h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Sinais%20Estocasticos">Series Estocásticas</a></h1>
  <ul>
    <li>Gera 10 sinais para cada família com N elementos: 
    N1: 64; N2:128; N3:256; N4:512; N5:1024; N6: 2048; N7:4096; N8: 8192. Total do Grupo Noise: 80.</li>
    <li>Normaliza as séries criadas acima entre 0 e 1 e obtém o respectivo Histograma. </li>
    <li>Calcula os 4 momentos estatísticos respectivos.</li>
    <li>Aplica a técnica K-means para caracterizar, se houver, classes nos espaço de parâmetros composto por variância, skewness e kurtosis. </li>
  </ul>

<h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Pmodel">PModel</a></h1>
  <ul>
    <li>Gera 20 sinais para 3 famílias com N 8192 elementos. As famílias são: white noise, pink noise e red noise. </li>
    <li>Obtém o respectivo Histograma. </li>
    <li>Calcula os 4 momentos estatísticos respectivos.</li>
    <li>Aplica a técnica K-means para caracterizar, se houver, classes nos espaço de parâmetros composto por variância, skewness e kurtosis. </li>
  </ul>

<h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Colored%20Noise">Colored Noise</a></h1>
  <ul>
    <li>Gera 30 sinais para 2 famílias com N 8192 elementos. As famílias são: endógeno e exógeno. Para endógeno é considerado 3 valores de p na faixa (0.32-0.42) e exógeno é considerado 3 valores de p na faixa (0.18-0.28). </li>
    <li>Obtém o respectivo Histograma. </li>
    <li>Calcula os 4 momentos estatísticos respectivos.</li>
    <li>Aplica a técnica K-means para caracterizar, se houver, classes nos espaço de parâmetros composto por variância, skewness e kurtosis. </li>
  </ul>

<h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Cullen_frey"> Espaço de Cullen-Frey e Distribuições de Probabilidades </a></h1>
  <ul>
    <li>Pega duas séries de cada uma das oito famílias dos exerícios anteriores e plota no mapa de cullen and frey. </li>
    <li>Ajusta uma PDF para os histogramas das famílias colored Noise.</li>
  </ul>
  
  <h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/MapHenonLogistico"> Chaos Noise </a></h1>
  <ul>
    <li> Gera 2 famílias de series Temporais com 30 séries em cada uma. Para a família logística varia o parâmetro ρ na faixa
(3.85 a 4.05). Para gerar a família Henon varia os parâmetros a e b nas respectivas faixas: (de 1.350 a 1.420) e (0.210-0.310). </li>
    <li> Aplica o mapeamento de cullen and frey e ajusta a PDF do histograma de cada um.</li>
  </ul>
  
  <h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/MDFA"> PSD e DFA </a></h1>
  <ul>
    <li> Obtém, para cada série, os valores respectivos do seguintes atributos: S2 , K, β (via PSD) e α (via DFA) </li>
  </ul>
