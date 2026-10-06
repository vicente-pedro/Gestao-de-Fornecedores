# Sistema de Gestão de Fornecedores

## 👥 Integrantes do Grupo
- Luiz Henrique Tozeti
- Henrique Martinelli de Godoy
- Pedro Alcântara Meneses
- Pedro Pereira Vicente

## 🎯 Propósito do Projeto
Simular o desenvolvimento de uma miniaplicação web para a Gestão de Fornecedores utilizando um repositório Git hospedado no GitHub. O projeto tem como finalidade a prática de controlo de versões, abordando a criação de branches, commits, pull requests, tags e a execução de releases de software.

## 📅 Plano de Releases
- **Primeiro Release:** Construção da tela de login (index.html) que exibe a mensagem "em construção" (working.html) ao clicar no botão de entrar.
- **Segundo Release:** Evolução da página de login para chamar a página do administrador (pg001.html), ainda sem validação e consistência nos campos de acesso.
- **Terceiro Release:** Funcionamento completo do sistema. Validação de campo em branco redirecionando para a página de erro (msg.html); credencial "admin" direcionando para a tela do administrador (pg001.html); e qualquer outro dado remetendo para a página do operador (pg002.html).

## ✨ Funcionalidades
- **Autenticação de Utilizadores:** Validação de login em tempo real.
- **Painel de Administrador (`pg001.html`):** Acesso à gestão de fornecedores, configuração global e relatórios.
- **Painel de Operador (`pg002.html`):** Acesso às rotinas de visualização e relatórios básicos.
- **Tratamento de Exceções:** Redirecionamento automático para páginas de aviso ou erro (`msg.html`).

## 🛠️ Tecnologias Utilizadas
- **HTML5:** Estruturação semântica de todos os ecrãs.
- **JavaScript (Vanilla):** Lógica de validação do formulário e roteamento entre as páginas.

## 🚀 Como Executar o Projeto

1. Faça o clone deste repositório para a sua máquina local:
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
