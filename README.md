# 🧪 Testes Manuais - Tela de Login SWAGLABS

Este projeto documenta os testes manuais realizados na tela de login do sistema **SWAGLABS**, como parte dos meus estudos em **Garantia de Qualidade (QA)**.

---

## 🎯 Objetivo
Validar o comportamento da tela de login com diferentes tipos de usuários e cenários de entrada.

---

## 🛠️ Ambiente de Testes
- **Sistema:** [SWAGLABS](https://www.saucedemo.com/)
- **Tipo de teste:** Manual
- **Ferramentas:** Navegador Google Chrome

---

## 👤 Credenciais de Teste
Usuários aceitos:  
- `standard_user`  
- `locked_out_user`  
- `problem_user`  
- `performance_glitch_user`  

Senha para todos: `secret_sauce`

---

## 📋 Casos de Teste

| ID   | Caso de Teste                               | Usuário                  | Senha          | Resultado Esperado                                     | Status |
|------|---------------------------------------------|--------------------------|----------------|--------------------------------------------------------|--------|
| CT01 | Login com usuário padrão                    | standard_user            | secret_sauce   | Acesso ao sistema                                      | ✅     |
| CT02 | Login com usuário bloqueado                 | locked_out_user          | secret_sauce   | Mensagem de erro: usuário bloqueado                    | ✅     |
| CT03 | Login com usuário com falhas visuais        | problem_user             | secret_sauce   | Acesso com falhas na interface                         | ✅     |
| CT04 | Login com usuário com lentidão              | performance_glitch_user  | secret_sauce   | Acesso com demora de carregamento                      | ✅     |

---

## 📎 Evidências

### 📌 CT01 - Login com usuário padrão
<p align="center">
  <img src="https://github.com/user-attachments/assets/92e7fd12-524e-4ca9-acbb-19e27aad117f" alt="CT01 - Tela de produtos após login" width="900"/>
</p>

---

### 📌 CT02 - Login com usuário bloqueado
<p align="center">
  <img src="https://github.com/user-attachments/assets/76ef7c7b-9dc2-4cae-a5d2-afb13a22367d" alt="CT02 - Usuário bloqueado" width="900"/>
</p>

---

### 📌 CT03 - Login com usuário com falhas visuais
<p align="center">
  <img src="https://github.com/user-attachments/assets/cfe861be-a5e0-4bef-bd36-f4554af31835" alt="CT03 - Interface com falhas" width="900"/>
</p>

---

### 📌 CT04 - Login com usuário com lentidão
🎥 [Clique aqui para assistir à gravação do teste](https://github.com/user-attachments/assets/a0f71b88-14dc-4918-af7d-d22bdd937991)

---

## 📂 Estrutura do Repositório
📦 testes-manuais-swaglabs
┣ 📜 README.md
┗ 📂 evidencias

yaml
Copiar
Editar

---

✍️ **Autor:** Josiana Cruz  
📅 **Ano:** 2025



<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Fotos</title>
</head>
<body>
    <h2>Galeria de Fotos</h2>
    <ul>
        <li><a href="[LINK_DA_IMAGEM_1](https://github.com/user-attachments/assets/92e7fd12-524e-4ca9-acbb-19e27aad117f)" target="_blank">📷 Foto 1</a></li>
        <li><a href="LINK_DA_IMAGEM_2" target="_blank">📷 Foto 2</a></li>
        <li><a href="LINK_DA_IMAGEM_3" target="_blank">📷 Foto 3</a></li>
        <li><a href="LINK_DA_IMAGEM_4" target="_blank">📷 Foto 4</a></li>
    </ul>
</body>
</html>





