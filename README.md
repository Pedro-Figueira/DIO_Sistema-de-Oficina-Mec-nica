# DIO_Sistema-de-Oficina-Mec-nica
Sistema de Oficina Mecânica 🚗🔧

Este projeto implementa o modelo lógico de um banco de dados para uma oficina.

Objetivos:

Gerenciar clientes, veículos, ordens de serviço, peças, serviços e mecânicos.

Permitir consultas simples e complexas para apoiar a gestão da oficina.

Modelo Lógico:

Cliente (1:N) Veículo

Veículo (1:N) Ordem de Serviço

Ordem de Serviço (N:M) Mecânico

Ordem de Serviço (N:M) Serviços

Ordem de Serviço (N:M) Peças

Tecnologias: MySQL

Funcionalidades:

Cadastro de clientes, veículos e mecânicos.

Registro de ordens de serviço.

Lançamento de serviços e peças utilizados.

Consultas analíticas (valor total de OS, peças mais utilizadas etc.).
