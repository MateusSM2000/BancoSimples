## Projeto para estudo de lógica de programação

Este projeto foi feito com o intuito de aperfeiçoar minhas técnicas em lógica de programação em uma linguagem (no caso
Python) muito versátil por implementar muito bem a base de lógica de programação. Para fazer esse projeto utilizei de
funções, classes, métodos, condicionais, loops, dicionários, listas, try/except, POO, design patterns, assincronismo e
módulos como pathlib, re, json, datetime, os, platform, csv, dotenv, asyncio, aiosmtplib, abc, entre outros.

O projeto representa de uma maneira bem simplificada um sistema bancário, no qual o usuário pode cadastrar uma conta
com usuário e senha, fazer login e efetuar movimentações no saldo da conta ou alterar dados pessoais. Os dados bancários
são armazenados localmente em um arquivo .json no diretório onde se encontra o projeto. Alterações dos dados bancários
são arquivados no arquivo log.csv. O arquivo staff_user_client_side.py pode fazer alterações no arquivo .json sem a
necessidade de fazer login.

Mude o arquivo dotenv-example para .env e altere os valores para o programa conseguir enviar o e-mail automático.

Possui um Dockerfile caso necessite. Basta apenas dar build nele.
