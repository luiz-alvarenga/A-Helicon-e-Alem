# A-Helicon-e-Alem

Trantor não era mais a joia do Império. Onde antes se erguiam torres infinitas e corredores administrativos
fervilhavam com decisões que moldavam a galáxia, agora restavam ruínas silenciosas e vegetação selvagem
forçando passagem entre estruturas corroídas. Era ali, entre os escombros da outrora majestosa Biblioteca

Imperial, que Arcadia Darell caminhava com determinação. Seus olhos examinavam um terminal semi-
enterrado, vestígios da civilização que Hari Seldon previra desmoronar.

Arcadia, agora mais velha e mais decidida, sabia que havia mais no Plano Seldon do que o mundo jamais
soubera. A psico-história, essa ciência quase mítica que previa os rumos da humanidade em larga escala,

ainda era envolta em mistério — e ela, neta de Bayta Darell, decidira que era hora de entender seus verda-
deiros contornos. Mas para isso, teria que sair de Trantor.

Sua nave, Lumen, repousava silenciosa nos arredores da cidade devastada. Equipada com motores gravitaci-
onais, ela era uma maravilha da engenharia oculta: uma tecnologia raríssima, capaz de manipular os campos

gravitacionais ao redor da nave para gerar movimento sem propulsores tradicionais. Sem combustão, sem
vibração — apenas um silêncio elegante enquanto dobrava espaço e inércia à sua vontade. A bordo, Arcadia
podia acelerar a velocidades incríveis, pairar sobre mundos sem perturbar a atmosfera, ou descer suavemente
mesmo nos ambientes mais inóspitos.
Um dos grandes desafios de Arcadia é encontrar as coordenadas certas para que a nave, que funciona de
maneira autônoma, possa traçar rotas levando assim Arcadia aos lugares mais inóspitos do universo. Para
isso, ela está nas ruínas da Biblioteca Imperial em Trantor vasculhando manuais e informações que vieram
de Terminus séculos atrás quando as primeiras naves gravitacionais surgiram, ela achou vários fragmentos
dos manuais de operações e configuração de rotas, cada rota que ela encontra é uma sequência de valores que
ela deverá inserir no console navegador nave, entretanto essas sequências de valores foram contaminadas
com informação espúria, uma vez que os cubos de informação quântica que armazenam essas rotas estão
deteriorados pelo tempo. Entretanto, ela conseguiu descobrir que dada uma sequência qualquer, os valores
que fazem parte de um rota, ou seja, não são ruídos de informação podem estar separados por k passos de
distância, e assim ela deve encontrar a maior soma de uma sequência que esteja a k passos de distância
considerando todos os valores possíveis para 1 ≤ k ≤ N/2, onde N é o tamanho das sequência encontrada
que reúne valores verdadeiros e ruidosos.
Sua jornada seria longa. Pretendia começar em Helicon, planeta natal de Seldon, em busca de vestígios
acadêmicos esquecidos. De lá, seguiria para Terminus, onde a Primeira Fundação fora plantada — talvez
ainda houvesse registros não corrompidos pela política. Planejava visitar Rossem, onde Seldon surgira em
projeção décadas atrás, e Gaia, cuja consciência coletiva parecia compreender a psico-história de um modo
totalmente diferente. E, se restasse tempo e coragem, arriscaria uma passagem discreta por Kalgan, antigo
domínio do Mulo, na esperança de entender como uma anomalia tão poderosa havia alterado o curso do
destino galáctico.
Na cabine de comando, ao observar o céu encoberto de Trantor, Arcadia registrou em seu diário:
Se a psico-história ainda vive, ela deixou rastros. E se o futuro pode ser guiado, preciso primeiro entender 
o passado.

Entrada
A primeira linha contém um número inteiro N (1 ≤ N ≤ 105), o tamanho do vetor. A segunda linha contém N inteiros A1, A2, . . . , An(−104 ≤ Ai ≤ 104), os elementos do vetor.

Saída
Imprima um único inteiro que é a maior soma possível de uma subsequência de rotas.
Exemplo de Entrada 1  | Exemplo de Saída 1
6                     | 12
3 -1 4 -1 5 -9        |  
  
Exemplo de Entrada 2             | Exemplo de Saída 2
12                               | 20
-5 2 1 7 -3 -4 -8 10 -6 1 -1 3   | 

