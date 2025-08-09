# 🔐 Testes Manuais - Tela de Login SWAGLABS

Este projeto documenta os testes manuais realizados na tela de login do sistema SWAGLABS, como parte dos meus estudos em QA.

## 🎯 Objetivo

Validar o comportamento da tela de login com diferentes tipos de usuários e cenários de entrada.

## 🛠️ Ambiente de Testes

- Sistema: SWAGLABS (https://www.saucedemo.com/)
- Tipo de teste: Manual
- Ferramentas: Navegador Google Chrome

## 👤 Credenciais de Teste

- Usuários aceitos:
  - `standard_user`
  - `locked_out_user`
  - `problem_user`
  - `performance_glitch_user`
- Senha para todos: `secret_sauce`

## 📋 Casos de Teste

| ID   | Caso de Teste                          | Usuário               | Senha         | Resultado Esperado                      | Status |
|------|----------------------------------------|------------------------|---------------|------------------------------------------|--------|
| CT01 | Login com usuário padrão               | standard_user          | secret_sauce  | Acesso ao sistema                        | ✅     |
| CT02 | Login com usuário bloqueado            | locked_out_user        | secret_sauce  | Mensagem de erro: usuário bloqueado      | ✅     |
| CT03 | Login com usuário com falhas visuais   | problem_user           | secret_sauce  | Acesso com falhas na interface           | ✅     |
| CT04 | Login com usuário com lentidão         | performance_glitch_user| secret_sauce  | Acesso com demora de carregamento        | ✅

## 📎 Evidência do Teste CT01

Após realizar o login com o usuário `standard_user`, o sistema redirecionou para a tela principal de compras, confirmando que o login foi bem-sucedido.

![CT01 - Tela de produtos após login](<img width="1877" height="925" alt="ct01-login-sucesso" src="https://github.com/user-attachments/assets/a52129df-17d1-470b-84f8-fcf188d268f2" />)


## 📎 Evidência do Teste CT02

Ao tentar realizar login com o usuário `locked_out_user`, o sistema exibiu uma mensagem de erro informando que o usuário está bloqueado, impedindo o acesso à área de compras.

![CT02 - Usuário bloqueado] <img width="1361" height="759" alt="ct-02login-bloqueado" src="https://github.com/user-attachments/assets/76ef7c7b-9dc2-4cae-a5d2-afb13a22367d" />



## 📎 Evidência do Teste CT03

Após realizar login com o usuário `problem_user`, o sistema permitiu o acesso, mas apresentou falhas visuais na interface — como imagens quebradas, botões desalinhados ou comportamento inesperado.

![CT03 - Interface com falhas]<img width="1854" height="744" alt="ct03-interface-falha" src="https://github.com/user-attachments/assets/cfe861be-a5e0-4bef-bd36-f4554af31835" />


## 📎 Evidência do Teste CT04

Após realizar login com o usuário `performance_glitch_user`, o sistema permitiu o acesso, porém apresentou lentidão no carregamento da interface — os elementos demoraram para aparecer ou responder.

![CT04 - Lentidão após login]<img width="1915" height="1006" alt="ct-04-demora-site" src="https://github.com/user-attachments/assets/001ece69-ab35-4f98-9910-8f931a807007" />





