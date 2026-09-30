# O que é o Docker?

O Docker é uma plataforma e um serviço de virtualização baseada em contêineres.

Diferente de uma máquina virtual (que virtualiza todo o sistema operacional e hardware), o Docker é um serviço que aproveita o Sistema Operacional da máquina hospedeira para executar aplicações dentro de "caixas" isoladas, chamadas de **Containers**. Esses containers dividem e compartilham os recursos da máquina (como memória e processamento) de forma mais leve e eficiente.

**Principais Vantagens:**
- **Padronização:** Serve principalmente para padronizar o ambiente de execução das aplicações.
- **Fim do "na minha máquina funciona":** Ao encapsular a aplicação e suas dependências, o Docker garante que ela rodará da mesma forma em qualquer ambiente.
- **Versatilidade:** Você pode usar o Docker tanto para testar tecnologias e ferramentas de forma isolada (como subir apenas um banco de dados ou ambiente Node.js/Java) quanto para rodar uma aplicação completa.

---

## Conceitos Fundamentais

### 📄 Dockerfile
É a "planta" (receita) do projeto. É um arquivo de texto com as instruções de como construir a **Imagem** do ambiente necessário para rodar o app.

### 📦 Imagem (Image)
Imagem é o modelo de leitura a partir do qual o container é gerado. É o pacote pronto criado pelo Dockerfile.

### 🐋 Container
É a imagem em execução, ou seja, uma instância viva da imagem. Quando você pega uma imagem estática e a coloca para rodar, ela vira um container. Você pode rodar "n" containers a partir da mesma imagem.

### 🗄️ Registry (Registro de Imagens)
É um repositório (banco de imagens) de onde podemos baixar e reutilizar imagens já prontas para uso. O *Docker Hub* é o exemplo mais famoso, de onde você pode baixar imagens oficiais do Node, Java, .NET, bancos de dados, etc.
