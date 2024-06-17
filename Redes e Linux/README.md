![evidencias](evidencias/cisco-packet-tracer.png)
# Instruções do projeto
Para o show da banda de Miguel, será necessário configurar uma rede de computadores. A comunicação entre os membros da equipe de produção, que estarão espalhados pelo teatro, é fundamental para manter todos informados e verificar se nada está fugindo do controle. O agente da banda decidiu modernizar a infraestrutura do show para melhorar essa comunicação. Para ajudá-los, você deve usar o Cisco Packet Tracer para criar uma topologia de rede estrela que permita a toda a equipe se comunicar facilmente.

Passos:
1. Definir o cenário
- Imagine que cada membro da equipe possui um computador que precisa de uma conexão de rede para se comunicar com os outros membros da produção.

![evidencias](evidencias/cenário.png)

2. Montar a topologia
- Crie uma nova topologia no Cisco Packet Tracer; 
- Arraste um switch para o centro da área de trabalho; 
- Arraste quatro PCs e posicione-os ao redor do switch, representando cada membro da equipe de produção.

![evidencias](evidencias/Topologia.png)

3. Conectar os dispositivos
- Conecte cada PC a uma porta diferente no switch usando cabos ethernet;
- Visualize os computadores da equipe de produção formando uma estrela ao redor do switch central.

**PC0: IP = 192.168.1.2, Subnet Mask = 255.255.255.0**
**PC1: IP = 192.168.1.3, Subnet Mask = 255.255.255.0**
**PC2: IP = 192.168.1.4, Subnet Mask = 255.255.255.0**
**PC3: IP = 192.168.1.5, Subnet Mask = 255.255.255.0**

!![evidencias](evidencias/PC0.png)
![evidencias](evidencias/PC1.png)
![evidencias](evidencias/PC2.png)
![evidencias](evidencias/PC3.png)


4. Configurar os endereços IP
- Crie um senso de identidade para cada computador, atribuindo nomes e números de endereços IP;
- Configure os endereços IP para as interfaces dos PCs e do switch de acordo com a mesma sub-rede.

![evidencias](evidencias/0.png)
![evidencias](evidencias/1.png)
![evidencias](evidencias/2.png)
![evidencias](evidencias/3.png)

5. Testar a comunicação
- Para verificar se todos os computadores estão devidamente configurados, acesse um dos PCs da equipe, abra o prompt de comando e tente fazer um ping para o endereço IP do computador de outro membro da equipe.

![evidencias](evidencias/ping.png)

6. Arquivo do projeto
[evidencias](projeto/show_banda_de_miguel.pkt)