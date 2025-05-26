# Figuras Geométricas com Programação Orientada a Objetos

Este projeto tem como objetivo principal demonstrar, de forma clara e prática, os conceitos fundamentais da **Programação Orientada a Objetos (POO)** aplicados ao cálculo de **áreas** e **volumes** de diversas figuras geométricas, tanto **planas** quanto **espaciais**. 

Através da implementação estruturada em classes e objetos, o projeto ilustra como organizar, reutilizar e proteger dados e comportamentos, facilitando a compreensão dos pilares da orientação a objetos como abstração, encapsulamento e herança. 

Além disso, serve como um recurso didático para estudantes e profissionais que desejam fortalecer seu conhecimento em POO enquanto aplicam esses conceitos a problemas matemáticos reais.

---

## Conceitos de POO

- Abstração  
- Encapsulamento  
- Herança  

---

## Estrutura do Projeto

O projeto está dividido em três partes, cada uma focando em um conceito de POO:

### Abstração

- Oculta detalhes internos e mostra apenas o essencial.  
- Pacotes:
  - `br.edu.principal` → Classe principal para testes  
  - `br.edu.figurasgeometricasplanas` → Classes de figuras planas

### Encapsulamento

- Controla o acesso aos atributos com métodos `get` e `set`.  
- Pacotes:
  - `br.edu.principal`  
  - `br.edu.figurasgeometricasplanas`  
  - `br.edu.figurasgeometricasespacias`

### Herança

- Reutiliza código criando subclasses que herdam superclasses.  
- Pacotes:
  - `br.edu.principal`  
  - `br.edu.figurasgeometricasplanas`  
  - `br.edu.figurasgeometricasespacias`

---

## Diagramas UML

#### Abstração  
![Diagrama UML - Abstração](https://github.com/user-attachments/assets/680759c0-c425-4bc8-935a-736292f7537c)

#### Encapsulamento  
![Diagrama UML - Encapsulamento](https://github.com/user-attachments/assets/97535320-bfa7-4d7c-af14-a0544285c153)

#### Herança  
![Diagrama UML - Herança](https://github.com/user-attachments/assets/d94644c8-ee11-4d58-852b-f6f6184e3bed)

---

## Figuras Geométricas Implementadas

### Figuras Planas

- Triângulo, Retângulo, Quadrado, Círculo, Trapézio, Paralelogramo, Losango, Pentágono e, Hexágono.

### Figuras Espaciais

- Cubo, Prisma, Esfera, Pirâmide, Cone, Cilindro, Paralelepípedo, Tetraedro

---

## Métodos em Todas as Classes

- Atributos privados  
- Construtor para inicializar  
- Métodos públicos:
  - `calcArea()`  
  - `calcVolume()` (só para figuras espaciais)
