# Atividade_TSOF_Analise-de-c-digo.

# README – Testes de Software

**Aluna:** Gabriela de Oliveira
**Turma:** ____2IG-DS_______
**Data:** 14/08/26
__

## 📚 Sobre a atividade

Nesta atividade da Aula 1, aprendemos um pouco sobre **Testes de Software** e a importância deles durante o desenvolvimento de um sistema.

Vimos os seguintes assuntos:

* Erro, defeito (bug) e falha;
* Testes funcionais e não funcionais;
* Teste unitário;
* Teste de integração;
* Teste de sistema;
* Teste de aceitação;
* Pirâmide de testes.

##  Estudo de caso

Usamos o exemplo da empresa **TechSolutions**, que criou um aplicativo para organizar eventos acadêmicos.

O sistema possui funções como:

* Fazer inscrições;
* Controlar vagas;
* Aplicar descontos;
* Emitir certificados;
* Verificar a idade dos alunos.

## 🐞 Caça aos Bugs

Na atividade, analisamos o código do sistema para encontrar possíveis erros.

Um dos problemas encontrados foi no cálculo do desconto:

```python
valor_final = valor_base - 10
```

O código tira apenas **R$ 10,00** do valor do ingresso, em vez de calcular os **10% de desconto**.

Por exemplo, em um ingresso de R$ 250,00, o desconto deveria ser R$ 25,00, mas o código daria apenas R$ 10,00 de desconto.

##  Tipos de teste

**Funcional:** verifica se uma função do sistema está funcionando corretamente.

**Não Funcional:** verifica coisas como velocidade, segurança e quantidade de usuários que o sistema suporta.

## 🔺 Níveis de teste

* **Unitário:** testa uma parte do código separadamente.
* **Integração:** testa se diferentes partes do sistema funcionam juntas.
* **Sistema:** testa o sistema completo.
* **Aceitação:** verifica se o sistema atende ao que o usuário precisa.

##  O que aprendi

Com essa atividade, aprendi como identificar bugs no código e a diferença entre os tipos e níveis de testes. Também entendi que testar o sistema ajuda a encontrar problemas antes que eles cheguem aos usuários.
