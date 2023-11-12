Projeto de Monitoramento Ambiental com Arduino e IoT:

Este projeto ilustra a criação de um sistema de monitoramento ambiental por meio da integração de um Arduino, sensores ultrassônicos, um LDR (resistor dependente de luz), um display LCD e tecnologia IoT (Internet das Coisas) para a visualização e análise em tempo real dos dados coletados.

Sensores Integrados em Postes:

A proposta central deste projeto é otimizar o consumo de energia e minimizar a poluição visual associada aos postes de iluminação. A estratégia consiste em manter uma iluminação mínima na ausência de presença humana ou veicular. Assim que detectada a presença de um pedestre ou carro, os postes ajustam-se automaticamente para fornecer a luminosidade necessária à mobilidade na área específica. Este enfoque busca aplicar as tecnologias estudadas no curso para contribuir com a concepção de cidades inteligentes e promover a sustentabilidade. A coleta de dados provenientes dos sensores de movimento possibilita uma compreensão detalhada do fluxo de pessoas e veículos em locais onde essa tecnologia é implementada. Com tais informações, é viável reduzir congestionamentos em áreas específicas e aprimorar a eficiência de aplicativos de navegação.

Contextualização Geral:

A Internet das Coisas (IoT) viabiliza a conexão entre dispositivos do mundo físico e a internet, permitindo o monitoramento e controle remoto de diversos parâmetros. Neste projeto, um Arduino é empregado para coletar dados de sensores ultrassônicos e LDR, que mensuram distância e luminosidade, respectivamente. Esses dados são então transmitidos a um servidor Node-RED por meio do protocolo MQTT (Message Queuing Telemetry Transport) e, posteriormente, enviados à plataforma TagoIO para análise e visualização.

Hardware:

-Sensor Ultrassônico HC-SR04
-Arduino Uno
-LDR (Light-Dependent Resistor)
-Fonte de Tensão
-Display LCD 16x2
-Jumpers e cabos diversos

Componentes:

-Ultrassônico
Display LCD
-Potenciômetro
-LED
-LDR
-Resistor

Configuração:

-Montagem do Hardware: Realize a montagem dos componentes conforme o esquema de conexão fornecido (inserir esquema aqui).

-Programação do Arduino: Carregue o código específico para o Arduino disponível neste repositório utilizando a Arduino IDE.

-Node-RED: Configure um fluxo no Node-RED para receber os dados provenientes do Arduino via MQTT. Ajuste as configurações MQTT de acordo com as especificidades da sua rede.

-TagoIO: Registre uma conta no TagoIO e estabeleça uma integração MQTT para receber os dados transmitidos pelo Node-RED.

-Dashboard TagoIO: Personalize um painel no TagoIO para a visualização em tempo real dos dados coletados.

Dashboard:

![tago-sprint4-edge](https://github.com/OsFiapeiros/sprint4-edge/assets/127514461/a72bc0ce-32a3-49b1-b6ef-e930802f7dfa)

