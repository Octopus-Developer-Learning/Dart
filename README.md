# Curso Completo de Dart (Flutter)

Bem-vindo ao curso completo sobre Dart, a linguagem de programação desenvolvida pela Google e base essencial para o framework Flutter. Este curso foi projetado para ser didático, progressivo e abrangente, levando você do zero ao nível avançado. Vamos aprender de forma fácil, com explicações claras, exemplos de código práticos e exercícios sugeridos em cada módulo. O foco é na linguagem Dart em si, com menções ao Flutter onde relevante, mas sempre priorizando os conceitos fundamentais.

O curso é dividido em três níveis: **Básico** (fundamentos para iniciantes), **Intermediário** (conceitos para construir aplicações robustas) e **Avançado** (tópicos para desenvolvedores experientes). Cada módulo inclui:

- **Explicação teórica**: Conceitos explicados de forma simples.
- **Exemplos de código**: Snippets executáveis (você pode testá-los no DartPad: dartpad.dev).
- **Exercícios**: Tarefas práticas para fixar o aprendizado.
- **Dicas**: Boas práticas e armadilhas comuns.

Ao final de cada nível, há um projeto integrador. O curso totaliza cerca de 40-60 horas de estudo, dependendo do ritmo.

## Módulo 0: História do Dart e Seu Criador

Antes de mergulharmos no código, é importante entender o contexto da linguagem. Isso ajuda a apreciar por que Dart é tão poderosa e versátil hoje.

### A Origem do Dart
Dart foi criado pela Google em 2011 como uma resposta aos desafios do desenvolvimento web na época. Naquele período, JavaScript era a linguagem dominante para aplicações web, mas enfrentava problemas como falta de tipagem estática forte, desempenho inconsistente e dificuldade em escalar para apps complexos. A Google queria uma linguagem que fosse fácil de aprender, produtiva e capaz de substituir o JavaScript nos navegadores, permitindo desenvolvimento mais rápido e seguro.

O anúncio oficial aconteceu na GOTO Conference, em Aarhus, na Dinamarca, nos dias 10 e 11 de outubro de 2011. Inicialmente chamada de "Dash", a linguagem foi renomeada para Dart para evitar conflitos com ferramentas existentes. O objetivo era criar uma linguagem multi-paradigma (orientada a objetos, funcional e imperativa) com sintaxe familiar (inspirada em C, Java e JavaScript), mas com recursos modernos como coleta de lixo automática, suporte a programação assíncrona nativa e compilação para múltiplas plataformas.

Em 2013, a versão 1.0 foi lançada, e em 2018 veio o grande reboot com Dart 2.0, que introduziu melhorias no sistema de tipos, null safety (em 2021 com Dart 2.12) e otimizações para client-side (web e mobile). Hoje, Dart é open-source (licença BSD), mantida pela equipe da Google e comunidade, e é a espinha dorsal do Flutter, framework para apps multiplataforma (Android, iOS, web, desktop). Em 2019, com Dart 2.6, veio suporte nativo para desktop via dart2native, expandindo seu uso para servidores e back-ends.

### O Criador e a Equipe
Os principais arquitetos do Dart são **Lars Bak** e **Kasper Lund**, dois engenheiros de software da Google. Lars Bak é um nome conhecido na indústria: ele contribuiu para o desenvolvimento do V8 (motor JavaScript do Chrome) e do HotSpot JVM (para Java). Sua expertise em máquinas virtuais e otimização de performance influenciou diretamente o runtime do Dart, que usa JIT (Just-In-Time) para desenvolvimento rápido e AOT (Ahead-Of-Time) para produção eficiente.

Kasper Lund, por sua vez, focou na sintaxe e usabilidade, garantindo que Dart fosse acessível para desenvolvedores de Java, C# ou JavaScript. A equipe inicial incluía outros engenheiros da Google, e o projeto evoluiu com contribuições da comunidade Ecma International (que padronizou Dart em 2014 como ECMA-408).

Dart não substituiu JavaScript como esperado, mas encontrou sucesso no mobile e desktop graças ao Flutter, lançado em 2017. Hoje, milhões de apps usam Dart, e a linguagem continua evoluindo (versão atual em 2025: 3.9, com foco em performance, records e pattern matching).

**Por que aprender isso?** Entender a história motiva: Dart foi feito para ser produtivo, e você verá isso nos exemplos práticos.

## Sumário do Curso

Este sumário lista todos os tópicos, organizados por nível. Baseado na documentação oficial do Dart (dart.dev), cobrimos **tudo** sobre a linguagem: sintaxe, estruturas, bibliotecas core, conceitos avançados e integração com ecossistema. Não é superficial – cada tópico tem profundidade.

### Nível Básico: Fundamentos (Módulos 1-5, Semanas 1-4)
1. **Instalação e Ambiente de Desenvolvimento**
   - Download do SDK Dart.
   - Editores: VS Code, Android Studio, DartPad.
   - Execução de código: dart run, pub get, JIT vs AOT.

2. **Introdução à Sintaxe e Hello World**
   - Estrutura de um programa Dart.
   - Função main().
   - Print e saída de dados.

3. **Variáveis e Tipos de Dados**
   - Declaração: var, dynamic, final, const.
   - Tipos primitivos: int, double, String, bool, num.
   - Null safety: ? para nullable, ! para non-null assertion.

4. **Operadores e Expressões**
   - Aritméticos (+, -, *, /, %).
   - Relacionais (==, !=, >, <).
   - Lógicos (&&, ||, !).
   - Atribuição, cascate (..), spread (...).

5. **Controle de Fluxo**
   - Condicionais: if/else, switch/case (com patterns).
   - Loops: for, while, do-while, for-in.
   - Break, continue, assert.

**Projeto Básico:** Calculadora simples com menu interativo.

### Nível Intermediário: Estruturas e Orientação a Objetos (Módulos 6-12, Semanas 5-8)
6. **Funções**
   - Definição, parâmetros (posicionais, nomeados, opcionais).
   - Retorno de valores, funções anônimas.
   - Arrow functions (=>), funções de primeira classe, closures.

7. **Coleções e Estruturas de Dados**
   - Listas (List<T>), Sets (Set<T>), Maps (Map<K,V>).
   - Operações: add, remove, iterate (forEach, map, where).
   - Coleções genéricas e imutáveis.

8. **Strings e Manipulação de Texto**
   - Interpolação (${}), raw strings (r'').
   - Métodos: split, join, replace, regex.
   - Multiline strings.

9. **Classes e Objetos**
   - Definição de classes, construtores (padrão, nomeados, factory).
   - Propriedades, métodos, getters/setters.
   - Herança de Object? (tudo é objeto).

10. **Herança e Polimorfismo**
    - extends, @override.
    - super(), chamadas de construtores.
    - Polimorfismo em ação.

11. **Mixins e Composição**
    - with Mixin, múltiplos mixins.
    - Reuso de código sem herança múltipla.

12. **Interfaces, Abstrações e Enums**
    - implements, classes abstratas.
    - Enums simples e aprimorados (com métodos e propriedades).

**Projeto Intermediário:** Sistema de gerenciamento de biblioteca (classes para Livro, Usuario, com herança e coleções).

### Nível Avançado: Conceitos Profundos e Bibliotecas (Módulos 13-20, Semanas 9-16)
13. **Exceções e Tratamento de Erros**
    - throw, try/catch/on/finally.
    - Rethrow, stack traces.
    - Erros síncronos vs. assíncronos.

14. **Programação Assíncrona**
    - Future<T>, async/await.
    - Streams e async*.
    - Await for, error handling em async.

15. **Generics e Tipos Avançados**
    - Genéricos em classes, funções, coleções.
    - Bounds (extends), type erasure.
    - Null safety: ? , !, late, required.

16. **Isolates e Concorrência**
    - Isolates vs. threads.
    - Spawn, message passing.
    - dart:isolate.

17. **Bibliotecas Core do Dart**
    - dart:core (Object, Exception, etc.).
    - dart:math (constantes, random).
    - dart:convert (JSON, encoding).
    - dart:io (arquivos, HTTP, sockets).
    - dart:ffi (interoperabilidade com C).

18. **Bibliotecas para Web e Plataformas**
    - dart:html e package:web (DOM, eventos).
    - dart:js_interop (chamadas JS).
    - Compilação para JS/Wasm.

19. **Padrões de Design e Boas Práticas**
    - Singleton, Factory, Observer.
    - Effective Dart: style, documentation (///).
    - Testing com dart test.

20. **Integração com Flutter e Ecossistema**
    - Dart em apps Flutter (widgets, state).
    - Pub.dev: pacotes (http, provider, etc.).
    - Ferramentas: dart analyze, dart format, pub deps.

**Projeto Avançado:** App de chat assíncrono com isolates, JSON e integração web (usando Flutter para demo).

**Módulos Adicionais:**
- **Bibliotecas Estendidas:** dart:async, dart:collection, dart:typed_data.
- **Performance e Otimização:** Snapshots, AOT/JIT, profiling.
- **Segurança e Melhores Práticas:** Visibilidade (_private), immutability, linting.

## Nível Básico: Fundamentos

### Módulo 1: Instalação e Ambiente de Desenvolvimento

**Explicação:** Para começar, baixe o Dart SDK do site oficial (dart.dev/get-dart). Ele inclui o compilador, VM e pub (gerenciador de pacotes). Para desenvolvimento, use VS Code com a extensão Dart (instala o SDK automaticamente). DartPad é ideal para testes rápidos sem instalação.

**Exemplo de Código:**
Crie um arquivo `hello.dart`:
```dart
void main() {
  print('Olá, Dart!');
}
```
Execute com `dart run hello.dart`.

**Exercício:** Instale o SDK e rode o Hello World no terminal e no DartPad. Explore o comando `dart --version`.

**Dicas:** Sempre use Dart 3.x para null safety. Evite deprecated como `new` (opcional desde Dart 2).

### Módulo 2: Introdução à Sintaxe e Hello World

**Explicação:** Todo programa Dart inicia com `main()`, ponto de entrada. Use `print()` para saída. Sintaxe é C-like: chaves {}, ponto e vírgula ;.

**Exemplo:**
```dart
import 'dart:io'; // Importa biblioteca IO

void main() {
  stdout.writeLine('Digite seu nome:');
  String? nome = stdin.readLineSync();
  print('Olá, $nome! Bem-vindo ao Dart.');
}
```
Isso lê input e interpola string.

**Exercício:** Crie um programa que imprima "Dart é incrível!" 5 vezes.

**Dicas:** Imports são essenciais; use `dart:core` implicitamente.

### Módulo 3: Variáveis e Tipos de Dados

**Explicação:** Dart é fortemente tipada, mas infere tipos com `var`. Tipos: `int` (64-bit), `double` (float), `String`, `bool`. `final` é imutável pós-inicialização; `const` é compile-time constant. Null safety: use `?` para nullable.

**Exemplo:**
```dart
void main() {
  var idade = 25; // Infere int
  final nome = 'João'; // Imutável
  const pi = 3.14; // Constante
  String? email; // Pode ser null
  email = 'joao@email.com';
  
  print('Idade: $idade, Nome: $nome, Pi: $pi');
}
```

**Exercício:** Declare variáveis para nome, idade e salário; imprima uma mensagem formatada.

**Dicas:** Evite `dynamic` no básico; prefira tipos explícitos para clareza.

### Módulo 4: Operadores e Expressões

**Explicação:** Operadores aritméticos para cálculos, relacionais para comparações, lógicos para condições. Cascate (`..`) para chamadas encadeadas, spread (`...`) para coleções.

**Exemplo:**
```dart
void main() {
  int a = 10, b = 3;
  print(a + b); // 13
  print(a > b); // true
  print((a > 5) && (b < 10)); // true
  
  List<int> lista = [];
  lista..add(1)..add(2); // Cascate
  print(lista); // [1, 2]
  
  List<int> lista1 = [1, 2];
  List<int> lista2 = [3, 4];
  var combinada = [...lista1, ...lista2]; // Spread
  print(combinada); // [1, 2, 3, 4]
}
```

**Exercício:** Calcule área de um retângulo (largura * altura) e verifique se é maior que 50.

**Dicas:** Use `~/` para divisão inteira, `%` para resto.

### Módulo 5: Controle de Fluxo

**Explicação:** `if/else` para decisões, `switch` para múltiplas opções (suporta patterns em Dart 3). Loops para repetição.

**Exemplo:**
```dart
void main() {
  int nota = 85;
  if (nota >= 90) {
    print('A');
  } else if (nota >= 80) {
    print('B');
  } else {
    print('C');
  }
  
  for (int i = 1; i <= 5; i++) {
    print(i);
  }
  
  switch (nota ~/ 10) {
    case 8:
      print('Bom!');
      break;
    default:
      print('Ok');
  }
}
```

**Exercício:** Crie um loop que some números de 1 a 100 e use if para pares/ímpares.

**Dicas:** Use `assert` para debug: `assert(idade > 0);`. Switch deve cobrir todos cases.

**Projeto Básico: Calculadora Simples**
Crie um app de console que leia dois números e operação (+, -, *, /), execute e trate divisão por zero com if.

**Exemplo skeleton:**
```dart
import 'dart:io';

double somar(double a, double b) => a + b;
double subtrair(double a, double b) => a - b;
double multiplicar(double a, double b) => a * b;
double dividir(double a, double b) {
  if (b == 0) throw Exception('Divisão por zero!');
  return a / b;
}

void main() {
  print('Escolha: 1-Soma, 2-Subtração, 3-Multiplicação, 4-Divisão');
  int op = int.parse(stdin.readLineSync()!);
  print('Digite dois números:');
  double x = double.parse(stdin.readLineSync()!);
  double y = double.parse(stdin.readLineSync()!);
  
  switch (op) {
    case 1:
      print('Resultado: ${somar(x, y)}');
      break;
    case 2:
      print('Resultado: ${subtrair(x, y)}');
      break;
    case 3:
      print('Resultado: ${multiplicar(x, y)}');
      break;
    case 4:
      try {
        print('Resultado: ${dividir(x, y)}');
      } catch (e) {
        print('Erro: $e');
      }
      break;
    default:
      print('Opção inválida');
  }
}
```

## Nível Intermediário: Estruturas e Orientação a Objetos

### Módulo 6: Funções

**Explicação:** Funções são blocos reutilizáveis. Parâmetros opcionais com [], {}, defaults. Anônimas para callbacks.

**Exemplo:**
```dart
int somar(int a, int b, {int? c = 0}) { // Nomeado opcional
  return a + b + (c ?? 0);
}

void main() {
  print(somar(5, 3, c: 2)); // 10
  var lista = [1, 2, 3];
  lista.forEach((num) => print(num * 2)); // Anônima arrow
}
```

**Exercício:** Crie função que valide email (contém @) e retorne bool.

**Dicas:** Use `void` para sem retorno. Funções léxicas capturam variáveis externas.

### Módulo 7: Coleções e Estruturas de Dados

**Explicação:** List<T> para arrays, Set<T> para únicos, Map<K,V> para chave-valor. Genéricos para type safety.

**Exemplo:**
```dart
void main() {
  List<String> frutas = ['maçã', 'banana'];
  frutas.add('laranja');
  print(frutas.where((f) => f.startsWith('b')).toList()); // ['banana']
  
  Set<int> numeros = {1, 2, 2}; // {1,2}
  print(numeros.length); // 2
  
  Map<String, int> idades = {'João': 25, 'Maria': 30};
  idades['Pedro'] = 28;
  print(idades['João']); // 25
}
```

**Exercício:** Crie Map de produtos (nome: preço), filtre itens > R$50.

**Dicas:** Use `Iterable` methods: map, filter, reduce. Prefira List.immutable para const.

### Módulo 8: Strings e Manipulação de Texto

**Explicação:** Strings são imutáveis. Interpolação com ${}, escapes com \. Regex para padrões.

**Exemplo:**
```dart
void main() {
  String texto = 'Dart é ótimo!';
  print(texto.toUpperCase()); // DART É ÓTIMO!
  print('Nome: ${'João'.toUpperCase()}'); // Nome: JOÃO
  
  String multiline = '''
  Linha 1
  Linha 2
  ''';
  print(multiline);
  
  RegExp regex = RegExp(r'\d+'); // Números
  print(regex.hasMatch('Idade 25')); // true
}
```

**Exercício:** Função que reverta uma string e remova vogais.

**Dicas:** Use r'' para raw strings sem escapes.

### Módulo 9: Classes e Objetos

**Explicação:** Classes definem blueprints. Construtores inicializam, getters/setters controlam acesso.

**Exemplo:**
```dart
class Pessoa {
  String nome;
  int idade;
  
  Pessoa(this.nome, this.idade); // Construtor
  
  Pessoa.nomeado({required this.nome, this.idade = 0}); // Nomeado
  
  String get saudacao => 'Olá, $nome!';
  set atualizarIdade(int novaIdade) => idade = novaIdade;
  
  void falar() => print(saudacao);
}

void main() {
  var p = Pessoa('Ana', 28);
  p.falar();
  p.atualizarIdade = 29;
}
```

**Exercício:** Crie classe Carro com propriedades e método acelerar.

**Dicas:** Use factory para construtores que retornam instâncias existentes.

### Módulo 10: Herança e Polimorfismo

**Explicação:** `extends` para herdar. `@override` para redefinir métodos. Polimorfismo permite tratar subclasses como base.

**Exemplo:**
```dart
class Animal {
  void som() => print('Som genérico');
}

class Cachorro extends Animal {
  @override
  void som() => print('Au au!');
}

void main() {
  Animal meuAnimal = Cachorro();
  meuAnimal.som(); // Au au! (polimorfismo)
}
```

**Exercício:** Herde Pessoa para Estudante com método estudar().

**Dicas:** Chame super() em construtores. Herança única em Dart.

### Módulo 11: Mixins e Composição

**Explicação:** Mixins reutilizam código com `with`. Útil para comportamentos múltiplos.

**Exemplo:**
```dart
mixin Voar {
  void voar() => print('Voando!');
}

mixin Nadar {
  void nadar() => print('Nadando!');
}

class Pato extends Animal with Voar, Nadar {
  @override
  void som() => print('Quack!');
}

void main() {
  var pato = Pato();
  pato.som();
  pato.voar();
  pato.nadar();
}
```

**Exercício:** Crie mixin para Log e aplique em uma classe.

**Dicas:** Mixins não podem ter construtores. Use on para restrições.

### Módulo 12: Interfaces, Abstrações e Enums

**Explicação:** Toda classe é interface implícita. `abstract` para classes incompletas. Enums para valores fixos.

**Exemplo:**
```dart
abstract class Forma {
  double area(); // Abstrato
}

class Circulo implements Forma {
  double raio;
  Circulo(this.raio);
  
  @override
  double area() => 3.14 * raio * raio;
}

enum Cor { vermelho, azul, verde }

void main() {
  var c = Circulo(5);
  print(c.area()); // 78.5
  print(Cor.vermelho.name); // 'vermelho'
}
```

**Exercício:** Crie enum para DiasDaSemana com método éFimDeSemana().

**Dicas:** implements para múltiplas interfaces.

**Projeto Intermediário: Sistema de Gerenciamento de Biblioteca**
Crie classes Livro (título, autor), Biblioteca (List<Livro>), com herança para LivroEmprestado. Use funções para adicionar/remover, mixins para Notificacoes.

**Exemplo inicial:**
```dart
class Livro {
  String titulo;
  String autor;
  Livro(this.titulo, this.autor);
}

class LivroEmprestado extends Livro {
  DateTime? dataEmprestimo;
  LivroEmprestado(String titulo, String autor) : super(titulo, autor);
}

class Biblioteca {
  List<Livro> livros = [];
  
  void adicionar(Livro livro) => livros.add(livro);
  void listar() => livros.forEach((l) => print('${l.titulo} por ${l.autor}'));
}

void main() {
  var bib = Biblioteca();
  bib.adicionar(Livro('Dart', 'Google'));
  bib.listar();
}
```

## Nível Avançado: Conceitos Profundos e Bibliotecas

### Módulo 13: Exceções e Tratamento de Erros

**Explicação:** `throw` lança erros. `try/catch` captura. `finally` sempre executa. Distinga Exception (recuperável) de Error (fatal).

**Exemplo:**
```dart
void dividir(double a, double b) {
  if (b == 0) throw ArgumentError('Divisor zero!');
  return a / b;
}

void main() {
  try {
    print(dividir(10, 0));
  } on ArgumentError catch (e) {
    print('Erro: $e');
  } finally {
    print('Fim da divisão');
  }
}
```

**Exercício:** Crie função que leia arquivo e trate FileNotFound.

**Dicas:** Use rethrow para propagar. Stack traces com e.stackTrace.

### Módulo 14: Programação Assíncrona

**Explicação:** `Future` para ops assíncronas. `async/await` simplifica. `Stream` para fluxos contínuos.

**Exemplo:**
```dart
Future<String> fetchData() async {
  await Future.delayed(Duration(seconds: 2)); // Simula delay
  return 'Dados carregados!';
}

Stream<int> contarAte(int max) async* {
  for (int i = 1; i <= max; i++) {
    yield i;
  }
}

void main() async {
  print(await fetchData());
  await for (var num in contarAte(3)) {
    print(num);
  }
}
```

**Exercício:** Função async que some números de uma lista com delay.

**Dicas:** Trate erros com try/await/catch. Use StreamController para streams custom.

### Módulo 15: Generics e Tipos Avançados

**Explicação:** Genéricos <T> para reutilização type-safe. Null safety: late para init posterior, ! para non-null assert.

**Exemplo:**
```dart
class Caixa<T> {
  T? item;
  void colocar(T valor) => item = valor;
  T? getItem() => item;
}

void main() {
  var caixaInt = Caixa<int>();
  caixaInt.colocar(42);
  print(caixaInt.getItem()); // 42
  
  String nome = 'Dart'; // Non-null
  String? nullable; // Pode ser null
  print(nullable?.length ?? 0); // 0 se null
  
  var (nome, idade) = ('Bob', 40); // Record
  print('$nome tem $idade anos');
}
```

**Exercício:** Crie Stack genérico com push/pop.

**Dicas:** Bounds: <T extends num> para restrições.

### Módulo 16: Isolates e Concorrência

**Explicação:** Isolates são workers independentes (sem shared memory). Use ReceivePort para mensagens.

**Exemplo:**
```dart
import 'dart:isolate';

void isolateEntry(SendPort sendPort) {
  sendPort.send('Olá do isolate!');
}

void main() async {
  ReceivePort receivePort = ReceivePort();
  await Isolate.spawn(isolateEntry, receivePort.sendPort);
  print(await receivePort.first); // Olá do isolate!
}
```

**Exercício:** Isolate que calcule fatorial em background.

**Dicas:** Isolates para CPU-intensive tasks. Não compartilhe objetos mutáveis.

### Módulo 17: Bibliotecas Core do Dart

**Explicação:** dart:core é auto-importado. dart:math para utils. dart:convert para JSON. dart:io para arquivos/network.

**Exemplo:**
```dart
import 'dart:math' as math;
import 'dart:convert';
import 'dart:io';

void main() {
  print(math.pi); // 3.14
  print(math.Random().nextInt(100)); // Aleatório
  
  Map<String, dynamic> data = {'nome': 'João'};
  String json = jsonEncode(data);
  print(json); // {"nome":"João"}
  
  File('exemplo.txt').writeAsStringSync('Olá!');
}
```

**Exercício:** Leia JSON de arquivo e processe com math.

**Dicas:** Use http package para web, mas foque core aqui.

### Módulo 18: Bibliotecas para Web e Plataformas

**Explicação:** Para web, use package:web. dart:ffi para C interop.

**Exemplo (Web - use DartPad web):**
```dart
import 'package:web/web.dart' as web;

void main() {
  web.window.alert('Olá Web!');
  var div = web.document.createElement('div');
  div.text = 'Dart na Web';
  web.document.body?.append(div);
}
```

**Exercício:** Crie botão que chame função JS via js_interop.

**Dicas:** Compile com `dart compile js`. FFI requer setup.

### Módulo 19: Padrões de Design e Boas Práticas

**Explicação:** Singleton: classe com instância única. Effective Dart: use /// para docs, evite código deprecated.

**Exemplo Singleton:**
```dart
class Logger {
  static final Logger _instance = Logger._internal();
  factory Logger() => _instance;
  Logger._internal();
  
  void log(String msg) => print('[LOG] $msg');
}

/// Documenta classe Pessoa
class Pessoa {
  /// Nome da pessoa
  String nome;
  Pessoa(this.nome);
}
```

**Exercício:** Implemente Observer pattern para notificações.

**Dicas:** Rode `dart analyze` para lint. Formate com `dart format`.

### Módulo 20: Integração com Flutter e Ecossistema

**Explicação:** Dart + Flutter: use StatelessWidget/StatefulWidget. Pub para pacotes.

**Exemplo Flutter Básico (crie app):**
```dart
import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        body: Center(child: Text('Dart no Flutter!')),
      ),
    );
  }
}
```

**Exercício:** Adicione botão que chame função Dart async.

**Dicas:** Use provider para state. Pub deps: `flutter pub add http`.

**Projeto Avançado: App de Lista de Compras**
Crie app Flutter com ListView, Hive para storage, http para API (ex: JSONPlaceholder).

**Exemplo skeleton:**
```dart
// lib/models/item.dart
class Item {
  final int id;
  final String nome;
  final double preco;
  Item({required this.id, required this.nome, required this.preco});
}

// lib/main.dart
import 'package:flutter/material.dart';
import 'package:hive/hive.dart'; // Adicione no pubspec

void main() async {
  await Hive.initFlutter();
  runApp(MyApp());
}

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(home: ListaCompras());
  }
}

class ListaCompras extends StatefulWidget {
  @override
  _ListaComprasState createState() => _ListaComprasState();
}

class _ListaComprasState extends State<ListaCompras> {
  List<Item> itens = [];

  @override
  void initState() {
    super.initState();
    carregarItens();
  }

  Future<void> carregarItens() async {
    // Simule API
    setState(() {
      itens = [Item(id: 1, nome: 'Arroz', preco: 5.0)];
    });
  }

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text('Lista de Compras')),
      body: ListView.builder(
        itemCount: itens.length,
        itemBuilder: (context, index) => ListTile(title: Text(itens[index].nome)),
      ),
      floatingActionButton: FloatingActionButton(
        onPressed: () => setState(() => itens.add(Item(id: itens.length + 1, nome: 'Novo', preco: 0))),
        child: Icon(Icons.add),
      ),
    );
  }
}
```

## Conteúdo para Manter o Estudo Após o Curso

Parabéns por completar o curso! Para não perder o momentum e evoluir, siga este plano de estudos contínuo:

1. **Prática Diária (1-2 horas/dia):**
   - Resolva desafios no LeetCode ou HackerRank filtrados por Dart (implemente algoritmos como busca binária com generics).
   - Contribua para repositórios open-source no GitHub (busque "dart" + issues beginner).
   - Construa projetos reais: Todo app com Flutter, API server com Dart (shelf package), jogo simples (dart:math).

2. **Leituras e Documentação:**
   - Leia "Effective Dart" (dart.dev/effective-dart) – guia oficial de estilo.
   - Estude a API Reference completa (api.dart.dev) – foque em dart:async e dart:collection.
   - Livro: "Dart Apprentice" (raywenderlich.com) ou "Flutter in Action" (foco Dart chapters).

3. **Cursos e Comunidades:**
   - Plataformas: Udacity (Dart track), freeCodeCamp (Dart/Flutter), YouTube (canal oficial Dart).
   - Participe: Reddit r/dartlang, Discord Flutter Brasil, Stack Overflow (tag dart).
   - Certificação: Google Developer Certification for Flutter (inclui Dart).

4. **Projetos Avançados Sugeridos:**
   - **Semana 1-2:** Integre FFI para chamar libs C (ex: SQLite nativo).
   - **Mês 1:** Desenvolva back-end com Dart (Aqueduct ou Shelf) + front Flutter.
   - **Mês 2:** App web com Dart2JS, otimize performance com profiling (dart run --observe).
   - **Desafio:** Migre um app JS para Dart web.

5. **Atualizações e Ferramentas:**
   - Monitore releases no dart.dev (ex: novas features como records em Dart 3).
   - Use ferramentas: Dart DevTools para debug, pub outdated para updates.
   - Métricas: Rode testes unitários (test package) em todos projetos.
