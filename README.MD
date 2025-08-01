🚀 Desafio POO – DIO Bootcamp
Este projeto em Java foi desenvolvido como parte de um desafio do Bootcamp da Digital Innovation One (DIO), com foco em Programação Orientada a Objetos (POO).

💡 Objetivo
Simular o funcionamento de um Bootcamp, modelando classes como:

Curso

Mentoria

Dev

Bootcamp

Conteudo (abstração)

Cada Dev se inscreve em um Bootcamp, progride em conteúdos e acumula XP conforme conclui atividades.

🔧 Funcionalidades
Cadastro de cursos e mentorias

Inscrição de devs no Bootcamp

Acompanhamento do progresso

Cálculo automático de XP

🛠️ Tecnologias
Java 11+

IDE Java (IntelliJ, Eclipse, etc.)

▶️ Execução
Clone o repositório e rode a classe Main. A saída mostrará:

Conteúdos inscritos e concluídos

XP acumulado pelo dev

🧠 Pilares da POO aplicados
Abstração

Encapsulamento

Herança

Polimorfismo

Se quiser, posso colar esse resumo diretamente no seu repositório como README.md. Deseja isso?








Você disse:
agora está muito curto, preciso demais detalhes


O ChatGPT disse:
Perfeito! Abaixo está uma versão completa, detalhada e organizada do README, com tudo que você precisa para apresentar bem o projeto:

🧠 Desafio de Programação Orientada a Objetos (POO) – DIO Bootcamp
Este projeto foi desenvolvido como parte do desafio proposto no Bootcamp da Digital Innovation One (DIO), com o objetivo de aplicar e consolidar os principais conceitos da Programação Orientada a Objetos (POO) usando a linguagem Java.

📚 Descrição do Projeto
O desafio consiste em modelar um sistema de aprendizado baseado na estrutura de um Bootcamp. A ideia é criar um domínio onde desenvolvedores possam se inscrever em cursos e mentorias, progredir nos conteúdos e acumular experiência (XP).

As classes principais envolvidas são:

Curso

Mentoria

Bootcamp

Dev

Conteudo (classe abstrata base)

🧩 Objetivos do Projeto
Praticar os pilares da POO: abstração, encapsulamento, herança e polimorfismo

Simular um fluxo realista de aprendizado online

Criar uma estrutura de código bem organizada e reutilizável

Entender como classes se relacionam entre si dentro de um domínio

🧱 Estrutura de Diretórios
A estrutura geral do projeto segue o padrão:

css
Copiar
Editar
src/
├── br/com/dio/desafio/
│   ├── dominio/
│   │   ├── Curso.java
│   │   ├── Mentoria.java
│   │   ├── Bootcamp.java
│   │   ├── Dev.java
│   │   └── Conteudo.java
├── Main.java
🛠️ Tecnologias Utilizadas
Java 11 ou superior

IDE (IntelliJ IDEA, Eclipse, VS Code ou outra de sua preferência)

Git e GitHub para versionamento

▶️ Como Executar
Clone este repositório:

bash
Copiar
Editar
git clone https://github.com/mjefs/desafio-poo-dio.git
cd desafio-poo-dio
Abra o projeto na sua IDE Java

Execute a classe Main.java

A saída deve mostrar:

Conteúdos disponíveis no Bootcamp

Conteúdos inscritos e concluídos por cada Dev

XP acumulada

🧪 Exemplo de Saída
java
Copiar
Editar
Dev João se inscreveu no Bootcamp Java Developer
Conteúdos inscritos: [Curso Java, Mentoria Spring]
João progrediu...
Conteúdos concluídos: [Curso Java]
XP acumulado: 80.0
🧠 Pilares da Programação Orientada a Objetos Aplicados
🔷 Abstração
A classe Conteudo representa a generalização dos conteúdos oferecidos (Curso e Mentoria).

🔷 Encapsulamento
Os atributos das classes são privados e acessados via métodos get e set.

🔷 Herança
As classes Curso e Mentoria herdam de Conteudo.

🔷 Polimorfismo
A lógica de cálculo de XP é implementada de forma diferente em Curso e Mentoria, mesmo herdando o mesmo método da classe Conteudo.

📦 Classes e Responsabilidades
Classe	Responsabilidade Principal
Conteudo	Classe abstrata para generalizar cursos e mentorias
Curso	Define título, descrição e carga horária. Calcula XP baseado em horas
Mentoria	Define título, descrição e data. Calcula XP fixo
Dev	Representa o aluno. Inscreve-se, progride e acumula XP
Bootcamp	Agrupa cursos/mentorias e mantém a lista de inscritos

🧑‍💻 Aprendizados
Com esse projeto, foi possível:

Aplicar na prática os conceitos fundamentais da orientação a objetos

Refletir sobre modelagem de sistemas a partir de um domínio real

Desenvolver código limpo e organizado

Reforçar lógica de programação e uso de coleções como Set e List

🤝 Contribuições
Este projeto é educacional, mas sugestões e melhorias são bem-vindas!

Para contribuir:

Faça um fork do repositório

Crie uma branch com sua feature: git checkout -b minha-feature

Faça commit das alterações: git commit -m 'Adiciona minha feature'

Envie um push para a sua branch: git push origin minha-feature

Abra um Pull Request

📄 Licença
Este projeto está licenciado sob a MIT License. Sinta-se à vontade para usá-lo e adaptá-lo com os devidos créditos.