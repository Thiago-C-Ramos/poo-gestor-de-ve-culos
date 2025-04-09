<h1>✈️🚢 Projeto Java – Herança: Veículo, Avião e Navio <br></br></h1>

<h3>📋 Descrição <br></br> </h3>
Este projeto foi desenvolvido como parte de uma atividade acadêmica da disciplina de Programação Orientada a Objetos em Java. O objetivo principal é implementar um sistema orientado a objetos que explore os conceitos de:

- Herança entre classes
- Classes abstratas e polimorfismo
- Encapsulamento com `get` e `set`
- Construtores padrão e parametrizados
- Vetores de objetos
- Interação com o usuário via terminal
- Tratamento de exceções com `try/catch`
- Estrutura de repetição com menu interativo

##
<h3>🧩 Estrutura do Projeto <br></br></h3>

<b>- Veiculo.java:</b> classe abstrata base contendo os atributos comuns <i>(identificador, capacidadeTanque, numeroPassageiros, preco)</i> e os métodos `entrada()` e `imprimir()` como abstratos. <br><br>

<b>- Aviao.java:</b> subclasse que estende <i>Veiculo</i> e adiciona o atributo <i>dataRevisao</i>, além do método <i>reajustarPreco()</i>.<br><br>

<b>- Navio.java:</b> subclasse que estende <i>Veiculo</i> e adiciona os atributos <i>numeroTripulantes</i> e <i>dataLancamento</i>, além do método <i>passageirosPorTripulante()</i>.<br><br>

<b>- Main.java:</b> classe principal com menu interativo que permite:
- Adicionar veículos (aviões ou navios)
- Listar todos os veículos cadastrados
- Reajustar o preço de um avião
- Calcular a razão de passageiros por tripulante em navios

<b>- run.bat:</b> script para automatizar a execução do programa (compila os arquivos `.java` e executa `Main.java`).

##
<h3>📷 Exemplo de Saída <br></br></h3>

```
========== MENU ==========

1 - Adicionar Avião
2 - Adicionar Navio
3 - Listar Veículos
4 - Reajustar Preço de Avião
5 - Calcular Quantidade de Passageiros por Tripulante (Navio)
0 - Sair

Seleção: 1
--== Adicionando Avião ==--

Prefixo: BOEING123
Capacidade do tanque: 8000
Número de passageiros: 200
Preço: R$150000000
Data de revisão: 2025-02-25
```

##
<h3>🚀 Como Executar <br></br></h3>

1. Compile todos os arquivos:
```bash
javac *.java
```

2. Execute a classe principal:
```bash
java Main
```

3. Ou utilize o script `run.bat` para compilar e rodar automaticamente (Windows):
```bash
run.bat
```

##
<h3>📚 Tecnologias Utilizadas <br></br></h3>
- Java 17+
- Programação Orientada a Objetos (POO)
- Scanner (entrada de dados via terminal)
- Vetores e controle de fluxo
- Tratamento de exceções

##
<h3>📌 Status <br></br></h3>
✅ Projeto finalizado, funcional e documentado conforme os critérios acadêmicos.

##
<h3>📝 Licença <br></br></h3>
Projeto de uso acadêmico. Livre para consulta, estudos e reutilização educacional.
