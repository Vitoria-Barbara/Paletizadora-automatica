# Paletizadora Automática

## Passos Iniciais:

1. Crie um novo projeto.
2. Selecione o dispositivo (PLC) a ser utilizado.
3. Configure o dispositivo para garantir o funcionamento adequado do projeto, observando as seguintes condições:

- Clock de Memória Habilitado:

O Memory Clock é fundamental para o bom desempenho do PLC, garantindo a execução eficiente do programa e o sincronismo adequado das operações. A configuração correta do Memory Clock assegura:

Varredura do Programa: Controle da frequência de leitura das entradas, execução das lógicas e atualização das saídas.
Operações Temporizadas: Precisão nos temporizadores, contadores e outras funções dependentes de tempo.
Sincronização e Estabilidade: Fluxo contínuo e estável dos processos internos do PLC.
Sem o Memory Clock habilitado corretamente, o desempenho do sistema pode ser comprometido, gerando falhas e imprecisões. A configuração adequada é essencial para garantir que a execução do programa ocorra de forma eficiente e sem atrasos.

Importância do Memory Clock no PLC (Ladder):
Ciclo de Varredura: Controla a frequência de execução do ciclo de varredura, afetando diretamente o desempenho e a estabilidade do sistema.
Sincronização de Processos: Garante que os processos internos do PLC sejam executados de maneira coordenada.
Execução de Operações Temporizadas: Garante a precisão de temporizadores e contadores.
Gerenciamento de Memória: Assegura a atualização constante e eficiente da memória interna do PLC.
A correta habilitação e configuração do Memory Clock são essenciais para o sucesso do projeto.

![image](https://github.com/user-attachments/assets/28b308e0-ed28-4be0-ab90-ab2efac8e767)

- Proteção e Segurança:
Desative a proteção de dados confidenciais na configuração do PLC para garantir acesso total e permitir a conexão com o Factory.io. O acesso total (Full Access) é necessário para garantir que o PLC se comunique corretamente com softwares externos, permitindo a troca de dados, a modificação de configurações em tempo real e o monitoramento do sistema sem restrições.

![image](https://github.com/user-attachments/assets/d9730572-114d-421e-8122-d742023d814e)

- Conexão e Mecanismos:
Habilite a comunicação PUT/GET para acesso remoto. Essa configuração permite que o PLC troque dados com sistemas externos, possibilitando controle e monitoramento remoto em tempo real, além de facilitar a integração com outras ferramentas de automação. O protocolo PUT/GET é crucial para o envio e recebimento de informações, garantindo flexibilidade e eficiência no gerenciamento do sistema.

![image](https://github.com/user-attachments/assets/aa01e13f-a9ec-4619-8fed-9f0020582679)

4. EM PROGRAMS BLOCKS NO MAIN , CARREGAR A LIBRAIS  que permite a conecxaop do factory com o tia portal, pode encontrar esta briblioiteca no site oficial fo factory
   -libries :

![image](https://github.com/user-attachments/assets/28cdd9fc-b7c4-4c90-a969-e7fa37817626)

abrir a biblioteca :

![image](https://github.com/user-attachments/assets/58d42163-7210-40b2-a8ab-61887b65ee68)

mude o tipo de arquivo que esta procurando para abrir 

![image](https://github.com/user-attachments/assets/6709ffbc-6aed-4131-9b77-504371fc7870)

procure este arquivo:

![image](https://github.com/user-attachments/assets/d74999bb-774d-4107-a2bf-636ce64e6994)

atualize para sua versao:

![image](https://github.com/user-attachments/assets/f1ba27b7-52b8-4101-bc06-d3a20cf36e88)

 arraste esta biblioteca para o o começo do ob main 
 
 ![image](https://github.com/user-attachments/assets/32de729a-e9c3-4f32-a4bc-b81e52a73f9b)







6. CARREGANDO AS CONFIGURAÇÕES PARA O plcsim
   start simulation:
   abrirá o simulador do plc
   
![image](https://github.com/user-attachments/assets/3c483654-a695-4f90-bdb0-35947e9a318c)

select ok:

![image](https://github.com/user-attachments/assets/d47c7507-d68e-4e86-a3c8-e8fd4a187024)

selecione "considere as trusted ..."

![image](https://github.com/user-attachments/assets/8c656650-9fdd-4a50-a373-03b1f1c1c6df)

aguarde a copilação do progama :

![image](https://github.com/user-attachments/assets/96ce74d1-c735-4e73-b45c-68cc16760235)

careregue em load

![image](https://github.com/user-attachments/assets/13baa209-5892-4fc2-86d5-68ecbd947d9c)

startmodule:

![image](https://github.com/user-attachments/assets/1d6d2a84-4a39-4e9c-a3b6-523509cfa523)

o plcsim estara pronto para simulação 
carregado com as configurações corretas para deviido funcionamento:

![image](https://github.com/user-attachments/assets/df737dcb-852e-4647-814a-df7088430d7c)


no factory:
ir em drivres
![image](https://github.com/user-attachments/assets/4a845065-299b-45ac-9542-75b5c560639d)
selecionar plcsim:
![image](https://github.com/user-attachments/assets/79c758a3-083d-4948-9cbb-3a012c5a7510)






 
