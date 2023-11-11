# Sistema de Placa Solar para Poste com Arduino
<h2>Descrição</h2>
Este projeto consiste em um sistema de placa solar projetado para ser instalado em postes. Utiliza placas solares para capturar energia do sol e alimentar um conjunto de baterias. Essa energia é então utilizada para alimentar e controlar dispositivos conectados ao Arduino, permitindo uma operação autônoma e sustentável.
O projeto de Postes Solares tem como objetivo melhorar a eficiência e a sustentabilidade da iluminação pública.

<h2>Funcionalidades</h2>
Monitoramento de Energia: O Arduino pode monitorar a energia capturada pela placa solar e a energia armazenada nas baterias.
Controle de Dispositivos: Os dispositivos conectados podem ser ligados/desligados automaticamente de acordo com a energia disponível.
Eficiência Energética: O sistema prioriza o uso de energia solar, alternando para as baterias apenas quando necessário.

<h2>Arquitetura Proposta</h2>
A arquitetura do projeto envolve três componentes principais:

<h2>IoT Devices</h2>
<li>Sensores de luminosidade: Para medir a intensidade da luz ambiente.</li>
<li>Painéis solares: Para gerar energia solar.</li>
<li>Controlador de carga solar: Para regular o carregamento da bateria.</li>
<li>Bateria: Para armazenar energia.</li>
<li>Módulo de comunicação IoT: Para transmitir dados para o backend.</li>
