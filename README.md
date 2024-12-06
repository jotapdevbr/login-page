## 📋 Formulário de Login - Página Responsiva

Este repositório contém o código de uma página de formulário de login simples e responsiva, ideal para projetos iniciais ou templates básicos de autenticação.

# 💡 Visão Geral

A página foi projetada com HTML e CSS puro, seguindo os princípios de design minimalista e responsividade. Ela pode ser facilmente integrada em aplicações web maiores ou usada como um modelo base para personalização.

# 🚀 Funcionalidades
Design responsivo;
Campo de entrada para usuário e senha;
Botão estilizado com efeitos de transição;
Interface limpa e amigável;
Foco automático nos campos de entrada (ao interagir);
Fácil integração com back-end via método POST.

# 🛠️ Tecnologias Utilizadas
1. HTML5: Estrutura do layout;
2. CSS3: Estilização e design responsivo;
3. Flexbox: Alinhamento e posicionamento dinâmico.

# 📁 Estrutura do Repositório
- Formulário/
- ├── image/
- │ └── Logo-Test.png # Logo utilizada na página
- ├── style/
- │ └── style.css # Arquivo de estilização principal
- ├── index.html # Arquivo HTML principal
- └── README.md # Documentação do projeto

# 📄 Detalhes do Código
`Estrutura do HTML`
Html
Copiar
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Formulário</title>
  <link rel="stylesheet" href="style/style.css">
</head>
<body>
  <div class="container">
    <div class="logo">
      <img src="./image/Logo-Test.png" alt="GrupoSC Logo">
      <p class="text-sm">Seja bem-vindo, realize o login para acessar.</p>
    </div>

    <form action="/login" method="POST">
      <div class="form-group">
        <label for="usuario">Usuário</label>
        <input type="text" id="usuario" name="usuario" required>
      </div>

      <div class="form-group">
        <label for="senha">Senha</label>
        <input type="password" id="senha" name="senha" required>
      </div>

      <button type="submit" class="btn">Entrar</button>
    </form>
  </div>
</body>
</html>

Estilização em CSS
Css
Copiar
body {
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  background-color: #f9fafb;
  font-family: Arial, sans-serif;
}

.container {
  width: 100%;
  max-width: 400px;
  background-color: rgba(255, 255, 255, 0.9);
  backdrop-filter: blur(5px);
  border-radius: 8px;
  padding: 2rem;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.logo {
  text-align: center;
  margin-bottom: 1rem;
}

.logo img {
  width: auto;
  height: auto;
  max-width: 200px;
  max-height: 80px;
  margin-bottom: 0.5rem;
}

.text-sm {
  font-size: 0.875rem;
  color: #4b5563;
  text-align: center;
  margin-bottom: 1rem;
}

form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.form-group {
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}

.form-group label {
  font-size: 0.875rem;
  color: #4b5563;
}

input[type="text"],
input[type="password"] {
  width: 100%;
  padding: 0.5rem;
  font-size: 1rem;
  border: 1px solid #d1d5db;
  border-radius: 4px;
  background-color: #fff;
}

input[type="text"]:focus,
input[type="password"]:focus {
  outline: none;
  border-color: #2563eb;
  box-shadow: 0 0 0 2px rgba(37, 99, 235, 0.3);
}

.btn {
  width: 100%;
  padding: 0.75rem;
  font-size: 1rem;
  font-weight: bold;
  color: #fff;
  background-color: #2563eb;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  transition: background-color 0.3s;
  text-align: center;
}

.btn:hover {
  background-color: #1d4ed8;
}

🌐 Links Úteis
Documentação HTML
Documentação CSS
Guia Flexbox
🤝 Como Contribuir

Contribuições são sempre bem-vindas! Siga os passos abaixo para contribuir:

Faça o fork do repositório;
Crie uma nova branch com a sua funcionalidade: git checkout -b minha-nova-feature;
Faça o commit das suas alterações: git commit -m 'Adicionando nova feature';
Suba a branch: git push origin minha-nova-feature;
Abra um Pull Request.
📝 Licença

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo LICENSE.

Espero que este arquivo README.md seja útil para seu projeto no GitHub! 🚀

Notas:
Este arquivo em Markdown está formatado de forma que o GitHub renderize ele com títulos, blocos de códigos, listas e estrutura bem organizada.
Lembre-se de verificar se os links internos (como o nome da imagem ou os paths dos diretórios) estão de fato corretos para o seu repositório.

Se precisar de algo mais, só me chamar! 😊
