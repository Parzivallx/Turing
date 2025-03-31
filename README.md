# Turing

# O Jogo da Imitação – Análise e Relação com as Estruturas de Dados 🎬💡

O objetivo desta atividade é demonstrar como as estruturas de dados podem ser aplicadas e ajudar na decodificação através do filme *O Jogo da Imitação*. Após assistir ao longa, percebi como a programação e a computação estão presentes em nosso dia a dia. Mesmo sem saber, usamos seus conceitos para realizar tarefas emocionantes e interessantes, como a quebra de códigos.

## 1. Contextualização 📽️

Assistindo ao filme, fiquei muito interessado na jornada de Alan Turing e sua equipe, tentando quebrar o código Enigma usado pelos nazistas na Segunda Guerra Mundial. Alan enfrentava o problema de testar milhões de combinações até encontrar a chave certa. A parte criptográfica do desafio era gigantesca, e o tempo era escasso. Alan sabia que não conseguiriam resolver o problema manualmente.

Foi aí que entrou a máquina Bombe, que acelerava significativamente o processo de tentativa e erro. Mesmo com a máquina, Alan ainda precisava ser estratégico e descartar muitas combinações. Ele não podia simplesmente testar todas as possibilidades aleatoriamente, mas sim organizar e filtrar de maneira eficiente.

Embora o filme não tenha falado explicitamente sobre estruturas de dados, percebi que as soluções usadas por Turing e sua equipe têm muito a ver com o que hoje chamamos de estruturas de dados. A organização e eliminação de combinações pelas quais a Bombe passava são práticas que usamos atualmente em computação.

---

## 2. Trecho Selecionado do Filme 🎬

Enquanto assistia ao filme, observei como a máquina Bombe, desenvolvida pela equipe de Turing, testava uma quantidade imensa de combinações de letras e códigos. Alan e sua equipe programaram algoritmos para eliminar rapidamente as possibilidades improváveis, baseadas em pistas e dicas lógicas. O processo me fez pensar que o fluxo de tentativas da máquina poderia ser comparado com uma fila (FIFO).

A fila funciona de forma a garantir que cada tentativa seja testada na ordem certa, sem perder nenhuma tentativa importante. A Bombe não testava as combinações de forma aleatória; ela seguia um fluxo organizado, como uma fila. Isso é altamente benéfico, pois garante que nenhuma combinação seja perdida.

---

## 3. Reflita! 💭

Assistindo ao filme, percebi como o trabalho de Turing e sua equipe se conecta com os conceitos de estruturas de dados que usamos na programação. Mesmo que esses termos não fossem explicitamente utilizados, o processo de organização das tentativas e a eliminação de combinações improváveis eram fundamentais para o sucesso da decodificação.

### Fila (FIFO) 🚶‍♂️
A fila é uma estrutura simples, onde o primeiro a entrar é o primeiro a sair (FIFO). Isso foi muito útil para a máquina Bombe, que testava as combinações de forma organizada e sem perder nada. Se fizéssemos as tentativas de forma aleatória, facilmente perderíamos combinações importantes ou faríamos tentativas repetidas. A fila garante que tudo seja testado na ordem certa.

### Pilha (LIFO) 📦
Agora, se uma tentativa falhasse, seria necessário voltar atrás e tentar uma nova possibilidade. Isso é onde uma pilha (LIFO) entraria em cena. A pilha permite que a última tentativa seja a primeira a ser desfeita, o que ajuda a economizar tempo. Em vez de recomeçar o processo inteiro, a pilha permite que a equipe volte rapidamente ao ponto de falha e continue a partir dali.

---

## 4. Desafio para a Próxima Aula 🔍

Agora que refleti sobre o filme e como ele se conecta com estruturas de dados, o desafio para a próxima aula será explorar como filas, pilhas e listas poderiam ser aplicadas no processo de decodificação de forma prática, como Turing fez, mas de maneira mais estruturada.

### Fila (FIFO) 🚶‍♂️
Se as combinações de letras fossem armazenadas em uma fila, o processo de decodificação seria mais organizado. A fila garantiria que as combinações fossem testadas de acordo com o princípio FIFO: o primeiro a entrar seria o primeiro a ser testado. Testar de forma aleatória poderia resultar em combinações perdidas ou tentativas repetidas, o que a fila evita.

### Pilha (LIFO) 📦
Se fosse necessário voltar atrás em alguma combinação, uma pilha (LIFO) seria útil. A pilha funciona de forma que a última tentativa feita seja a primeira a ser revisitada. Isso ajuda a economizar tempo, pois não é necessário recomeçar todo o processo. Ao invés disso, você pode "desfazer" rapidamente o último passo e tentar outra possibilidade.

### Lista 📋
Por fim, uma lista seria crucial para evitar que padrões já testados fossem repetidos. Armazenando as combinações já testadas, a máquina poderia facilmente verificar se uma tentativa foi feita antes, sem perder tempo. Uma lista encadeada seria a escolha ideal, pois permite inserir e remover itens de forma mais eficiente, sem a necessidade de reorganizar a memória, como seria necessário com um vetor.

---
