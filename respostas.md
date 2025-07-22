Respostas da Semana JS -

[M01S06] Exercício 1: Explorando métodos avançados de Array

Nesse exercício, eu pratiquei os métodos `.map()`, `.filter()` e `.reduce()`.  
Aprendi que:

- `.map()` é usado para transformar os elementos de um array. Usei ele para dobrar todos os números, e foi interessante ver como ele retorna um novo array com os valores alterados.
- `.filter()` serve para selecionar elementos com base em uma condição. Usei para pegar só os números pares, e achei legal como ele ignora os que não atendem ao critério.
- `.reduce()` foi o mais desafiador no começo. Ele percorre o array e vai acumulando um resultado, que no caso foi a soma de todos os números.

Esses métodos facilitam muito o trabalho com listas e evitam a criação de muitos loops manuais.

---

[M01S06] Exercício 2: Módulos JavaScript (ESModules)

Aqui eu aprendi a dividir o código em **módulos**, usando o `export` e `import`.  
No `funcoes.js`, criei duas funções simples (`soma` e `dobro`) e exportei elas.  
Depois, no `main.js`, importei essas funções e usei com alguns valores reais.

O mais interessante foi ver como isso organiza melhor o código e facilita a reutilização.  
Tive que ajustar o arquivo para rodar com `type="module"` no HTML ou usar Node no modo `module`, o que também me ajudou a entender mais sobre como o JS funciona fora do navegador.

---

[M01S06] Exercício 3: Trabalhando com Promises e Async/Await

Esse exercício foi ótimo para entender melhor a **assincronicidade** em JavaScript.

Criei uma função `buscarDados()` que simula uma requisição com `setTimeout`.  
Fiz duas versões da chamada:

- Com `.then()` e `.catch()`: aqui eu pude ver o fluxo de execução encadeado, mas achei um pouco confuso quando começa a ficar aninhado.
- Com `async/await`: muito mais fácil de ler e entender, principalmente com o uso do `try/catch` para tratar erros.

Entendi melhor como os dados "chegam depois", e que o JS não espera automaticamente — precisamos controlar isso com Promises.

---

[M01S06] Exercício 4: LocalStorage e Temporizadores

Esse exercício foi bem prático e me fez sentir como se estivesse criando algo real.

- Aprendi a usar o `localStorage` para salvar e recuperar o nome do usuário, mesmo depois que a página é atualizada.
- Usei `setInterval` para criar um relógio que atualiza a cada segundo — foi legal ver a hora mudando em tempo real!
- Com `setTimeout`, exibi uma mensagem de boas-vindas após 3 segundos, o que me fez pensar em UX (experiência do usuário).

Juntar tudo isso em uma única página foi desafiador, mas me ajudou a consolidar o uso de APIs do navegador.

Exercício 5: Classes e Herança
Nesse exercício, eu aprendi como aplicar os conceitos de Programação Orientada a Objetos (POO) em JavaScript usando class, extends, e super.

Criei uma classe Pessoa, com os atributos nome e idade, e um método apresentar() que retorna uma mensagem com essas informações.

Depois, criei uma classe Aluno que herda de Pessoa usando extends. Isso me permitiu reaproveitar os atributos e métodos da classe base sem reescrevê-los.

A classe Aluno adiciona um novo atributo (curso) e um novo método chamado estudar(), que só existe nessa subclasse.

Também pratiquei a sobrescrita de métodos, modificando o método apresentar() na classe Aluno para incluir o curso junto com o nome e idade.

Esse exercício me ajudou a entender como reutilizar código com herança, como organizar melhor as responsabilidades entre classes, e como sobrescrever métodos para personalizar comportamentos em subclasses.

Foi interessante ver que, apesar de JavaScript ser uma linguagem dinâmica, ele oferece uma sintaxe clara para trabalhar com POO moderna.
---

Conclusão

Essa semana foi a mais prática até agora.  
Aprendi sobre arrays avançados, módulos, Promises e também APIs do navegador.  
Foi um ótimo equilíbrio entre lógica de programação e construção de interfaces dinâmicas.
