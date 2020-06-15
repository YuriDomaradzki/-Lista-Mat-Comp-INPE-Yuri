# -Lista-Mat-Comp-INPE-Yuri
Contém os exercícios resolvidos da lista de exercício sobre Análise Estatística e Processos Estocásticos da disciplina Matemática Computacional.

<h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Sinais%20Estocasticos">Series Estocásticas</a></h1>
  <ul>
    <li>Gera 10 sinais para cada família com N elementos: 
    N1: 64; N2:128; N3:256; N4:512; N5:1024; N6: 2048; N7:4096; N8: 8192. Total do Grupo Noise: 80.</li>
    <li>Normaliza as séries criadas acima entre 0 e 1 e obtém o respectivo Histograma. </li>
    <li>Calcula os 4 momentos estatísticos respectivos.</li>
    <li>Aplica a técnica K-means para caracterizar, se houver, classes nos espaço de parâmetros composto por variância, skewness e kurtosis. </li>
    <li>Obtém os valores
respectivos do seguintes atributos: S2 , K, β (via PSD) e α (via DFA)</li>
  </ul>

<h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Pmodel">PModel</a></h1>
  <ul>
    <li>Gera 20 sinais para 3 famílias com N 8192 elementos. As famílias são: white noise, pink noise e red noise. </li>
    <li>Obtém o respectivo Histograma. </li>
    <li>Calcula os 4 momentos estatísticos respectivos.</li>
    <li>Aplica a técnica K-means para caracterizar, se houver, classes nos espaço de parâmetros composto por variância, skewness e kurtosis. </li>
    <li>Obtém os valores
respectivos do seguintes atributos: S2 , K, β (via PSD) e α (via DFA)</li>
  </ul>

<h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Colored%20Noise">Colored Noise</a></h1>
  <ul>
    <li>Gera 30 sinais para 2 famílias com N 8192 elementos. As famílias são: endógeno e exógeno. Para endógeno é considerado 3 valores de p na faixa (0.32-0.42) e exógeno é considerado 3 valores de p na faixa (0.18-0.28). </li>
    <li>Obtém o respectivo Histograma. </li>
    <li>Calcula os 4 momentos estatísticos respectivos.</li>
    <li>Aplica a técnica K-means para caracterizar, se houver, classes nos espaço de parâmetros composto por variância, skewness e kurtosis. </li>
    <li>Obtém os valores
respectivos do seguintes atributos: S2 , K, β (via PSD) e α (via DFA)</li>
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
    <li>Obtém os valores
respectivos do seguintes atributos: S2 , K, β (via PSD) e α (via DFA)</li>
  </ul>
  
  <h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Ex%206.2"> Ex 6.2 </a></h1>
  <ul>
    <li>Classifica, nos espaços de parâmetros do PSD e DFA, as séries temporais: (a) ST-Sol3GHz, (b) ST-surftemp504 e (c) ST-OWS_NDC_Covid1 para a Nova Zelãndia.  </li>
  </ul>

  <h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/Ex%206.3"> Ex 6.3 </a></h1>
  <ul>
    <li> Aplica k-means para todas as series ST-OWS_NDC_Covid1 considerando os seguintes
Espaços de atributos: S2 x α e K x α. Obtém os melhores agrupamentos e identifique os grupos. </li>
  </ul>
  
  <h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/MDFA"> MDFA </a></h1>
  <ul>
    <li>Obtém o espectro de singularidade para todos os sinais do dataset_signal e inclue os valores
 de Ψ como mais um atributo </li>
  </ul>

  <h1>Global Wavelet Spectrum</h1>
  <ul>
    <li>Obtém o Global Wavelet Spectrum de todas as séries temporais do dataset_signal à partir dos resultados obtidos no exercícios 6.2</li>
  </ul>
  
  <h1><a href="https://github.com/YuriDomaradzki/-Lista-Mat-Comp-INPE-Yuri/tree/master/SOC"> Self Organized Criticality </a></h1>
  <ul>
    <li> Gera 100 Séries Temporais (50 exo e 50 endo) com p-model para N=8192  e aplica SOC.py para as 50 de cada grupo</li>
    <li> Aplica o SOC.py para todas as Séries Temporais do exercício 6.3. </li>
  </ul>
