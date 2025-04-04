## Caso de Teste 01: Cadastro de Usuário

| Cadastro |                         |
|--------------|------------------------|
| Módulo       | Formulário de Cadastro |
| Funcionalidade | Criar um novo usuário no sistema |
| Requisito    | O sistema deve permitir o cadastro de um novo usuário preenchendo todas as informações obrigatórias |

| Criticidade | Alta |
| ----------- | ---- |

## Pré-condição

| Nº | Descrição |
| -- | ----------|
| 1  | O usuário deve estar na página de registro: [Demo Automation Testing](https://demo.automationtesting.in/Register.html) |

## Pós-condição

| Nº | Descrição |
| -- |----------- |
| 1  | O sistema deve exibir uma mensagem de sucesso após o cadastro |

## Passos

| Nº | Ação | Resultado Esperado | 
|----|------|---------------------|
| 1  | Acessar a página de registro | O formulário de cadastro deve ser exibido |
| 2  | Preencher o campo **Nome completo*** com "Eli Reis" | O nome deve ser inserido no campo |
| 3  | Preencher o campo **Endereço** com "Rua Teste, 123 - São Paulo" | O endereço deve ser exibido no campo |
| 4  | Preencher o campo **Endereço de email** com "elitester@test.com" | O e-mail deve ser aceito pelo campo |
| 5  | Preencher o campo **Telefone** com "11987654321" | O sistema deve aceitar o número e não permitir letras |
| 6  | Selecionar **Genero** como "Female" | O sistema deve permitir apenas uma seleção |
| 7  | Selecionar os **Hobbies** "Filmes" e "Hoquei" | O sistema deve permitir múltiplas seleções |
| 8  | Escolher **Idioma** como "Portugûes" | O idioma selecionado deve ser exibido no campo |
| 9  | Escolher **Habilidades** como "Linux" | A opção "Linux" deve ser mantida no campo |
| 10 | Escolher **País** como "Brasil" | A opção "Brasil" deve ser exibida no campo |
| 11 | Selecionar **Data de nascimento** (Ano: 1994, Mês: Julho, Dia: 22) | A data deve ser aceita pelo campo |
| 12 | Preencher **senha** com "Teste@123" | A senha deve ser aceita sem erros |
| 13 | Preencher **Confirme a senha** com "Teste@123" | O sistema deve validar que ambas as senhas coincidem |
| 14 | Clicar no botão **Enviar** | O sistema deve processar o cadastro e exibir uma mensagem de sucesso |