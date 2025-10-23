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

![Screenshot 1](./images/screenshot1.png)
