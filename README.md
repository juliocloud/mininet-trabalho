# Introdução ao mininet
| Esse repositorio tem objtivo de descrever o trabalho de mininet, proposto na disciplina de C115

### Requisitos:
Conforme orientado pelo professor, os requisitos pra executar são:
- Putty
- Xterm
- VM que o professor disponibilizou

## 1. Criação da topologia
Para criar a topologia proposta, é necessário executar o seguinte comando, via putty:

```
sudo mn --topo=linear,6 --mac --link tc,bw=25
```

1. --topo=linear,6 -> descreve a topologia que queremos (6 switch)
2. --mac -> relacionado a orientação de ter um MAC padronizado
3. --link tc,bw=25 -> bandwidth de 25Mbps

### Resultado do comando:

![Screenshot 1](./screenshot1.png)

## 2. Inspecionando a rede
Aqui vamos executar os comandos `nodes` , `net` , `dump` e `ifconfig`

- nodes: mostra os nós da rede
- net: quais portas conectam e os links
- dump: informação IP e MAC de cada nó
- ifconfig: detalhes da interce de cada nó

  
![Screenshot 2](./screenshot2.png)
![Screenshot 3](./screenshot3.png)
![Screenshot 4](./screenshot4.png)
![Screenshot 5](./screenshot5.png)

## 3. Testes de ping

- pingall pra realizar um teste de ping de toda a rede
- testes isolados de ping, de nó pra nó
- 
![Screenshot 6](./screenshot6.png)
