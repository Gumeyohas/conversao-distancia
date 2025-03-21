Conversão de Distância - Desafio Aula 1

Este repositório contém a solução do desafio da Aula 1, que envolve a construção de imagens Docker, publicação no Docker Hub e boas práticas na criação de imagens.

🚀 Tecnologias Utilizadas

Docker: Para criação e execução de contêineres.

Docker Hub: Para armazenamento e versionamento da imagem.

GitHub: Para versionamento do código-fonte.

📌 Desafios Concluídos

✅ Construção de um Dockerfile eficiente e otimizado.

✅ Build da imagem a partir do Dockerfile criado.

✅ Execução do contêiner garantindo o acesso pela porta especificada.

✅ Versionamento da imagem utilizando tags.

✅ Publicação da imagem no Docker Hub.

📥 Como Usar

1️⃣ Clonar o Repositório

git clone https://github.com/Gumeyohas/conversao-distancia.git
cd conversao-distancia

2️⃣ Criar a Imagem Docker

docker build -t meu-usuario/conversao-distancia:1.0 .

3️⃣ Executar o Contêiner

docker run -p 8080:8080 meu-usuario/conversao-distancia:1.0

A aplicação estará acessível em http://localhost:8080.

4️⃣ (Opcional) Baixar a Imagem do Docker Hub

Você pode baixar a imagem diretamente do Docker Hub sem precisar construir manualmente:

docker pull meu-usuario/conversao-distancia:1.0

🔗 Links

📂 Repositório no GitHub: Gumeyohas/conversao-distancia

🐳 Imagem no Docker Hub: meu-usuario/conversao-distancia

Para mais detalhes sobre a publicação no Docker Hub, consulte o arquivo dockerhub.md.
