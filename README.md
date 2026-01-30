# 🚗 Sistema de Locadora de Veículos — Projeto POO (Java)

Este repositório contém a implementação de um **Sistema de Locadora de Veículos**, desenvolvido integralmente em **Java**, como projeto da disciplina de **Programação Orientada a Objetos (POO)**.

O sistema é responsável por gerenciar veículos, clientes, aluguéis, devoluções e faturamento, aplicando regras de negócio e tratamento de exceções.

O projeto foi desenvolvido **sem interface gráfica**, sendo executado via console e testes.

---

## 📌 Objetivo do Projeto

O principal objetivo deste projeto é aplicar os conceitos fundamentais de:

- Programação Orientada a Objetos
- Herança e Polimorfismo
- Encapsulamento
- Interfaces
- Tratamento de Exceções
- Modelagem de Domínio
- Regras de Negócio

---

## ⚙️ Funcionalidades

O sistema oferece as seguintes funcionalidades:

### 🚙 Gerenciamento de Veículos

- Cadastro de veículos
- Pesquisa por placa
- Pesquisa por tipo de veículo
- Pesquisa por características específicas
- Depreciação de valores
- Reajuste de diárias

### 👤 Gerenciamento de Clientes

- Cadastro de clientes
- Validação de clientes

### 📄 Controle de Aluguéis

- Cálculo automático de aluguel
- Registro de locações
- Registro de devoluções
- Controle de disponibilidade

### 💰 Gestão Financeira

- Cálculo de faturamento
- Quantidade total de diárias
- Relatórios por tipo de veículo

---

## 🧠 Regras de Negócio

O sistema implementa as seguintes regras:

### 📌 Cálculo de Seguro Diário

| Tipo      | Percentual |
|-----------|------------|
| Moto      | 11%        |
| Carro     | 3%         |
| Caminhão  | 8%         |
| Ônibus    | 20%        |

Fórmula:

Seguro = (valor do bem × percentual) / 365


### 📌 Cálculo do Aluguel

Aluguel = (valor da diária + seguro) × quantidade de dias


### 📌 Tipos de Veículos

| Código | Tipo     |
|--------|----------|
| 0      | Todos    |
| 1      | Moto     |
| 2      | Carro    |
| 3      | Caminhão |
| 4      | Ônibus   |

### 📌 Tipos de Carro

| Código | Tipo    |
|--------|---------|
| 1      | Passeio |
| 2      | SUV     |
| 3      | Pickup  |

---

## ⚠️ Tratamento de Exceções

O sistema possui exceções personalizadas para garantir a integridade dos dados:

- VeiculoJaCadastrado
- VeiculoNaoCadastrado
- VeiculoAlugado
- VeiculoNaoAlugado
- ClienteJaCadastrado
- ClienteNaoCadastrado

---

## 🛠️ Tecnologias Utilizadas

- Linguagem: Java
- Paradigma: Orientação a Objetos
- Estruturas: Collections (ArrayList, Map, etc.)
---

## 📚 Conceitos Aplicados
- Interfaces e Implementações
- Polimorfismo
- Herança
- Coleções Java
- Exceções Personalizadas

Separação de Responsabilidades

Boas Práticas de POO
