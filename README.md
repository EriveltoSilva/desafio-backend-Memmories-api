<h1> Desafio-Backend "Memmories" - 💻 </h1>

<h2>Objetivo do Projeto:</h2>

<p>
Desenvolver um aplicativo chamado **"Memmories"**, um sistema destinado a permitir que os usuários registrem e armazenem suas memórias mais preciosas. O objetivo do aplicativo é funcionar como um diário pessoal, onde os usuários podem capturar momentos significativos de suas vidas por meio de texto, imagens, localizações geográficas e a inclusão de participantes que compartilharam esses momentos.
</p>

<h2>📄 Descrição do Projeto:</h2>

1. **Funcionalidades Principais:**
     - **Registro de Memórias:** Implementar CRUD completo para permitir que os usuários criem, leiam, atualizem e deletem suas memórias. Cada memória pode conter:
     - **Texto descritivo(obrigatório):** Onde o usuário descreve o momento.
     - **Imagens:** Upload e gestão de imagens relacionadas à memória.
     - **Localização:** Integração com APIs de mapas para permitir que o usuário adicione a localização do evento.
     - **Participantes:** Possibilidade de marcar outras pessoas que estiveram presentes no momento.
     - **Data de criação da memmory:** Salva automaticamente pelo sistema no momento do registro da memória.

2. 🔗 **Autenticação e Autorização:**
   - Implementar sistema de autenticação e autorização para garantir que as memórias sejam privadas e acessíveis apenas ao usuário que as criou. Utilizar o simplejwt para criar e gerir tokens de autenticação com Django Rest Framework.

3. **Armazenamento de Arquivos:**
   - Gerenciar o upload e armazenamento seguro de imagens relacionadas às memórias, utilizando soluções adequadas como o sistema de arquivos local ou sistema de armazenamento em nuvem AWS S3(Opcional, o modo de armazenamento não será avaliado).

4. **Integração de Localização:**
   - Implementar a integração com serviços de mapas para permitir que os usuários associem um local específico às suas memórias.

5. **Fluxo de Tempo:**
   - Criar uma funcionalidade que permita aos usuários visualizar suas memórias em uma linha do tempo, destacando a passagem do tempo e os eventos marcantes registrados ao longo dos dias.

<h2>Critérios de Avaliação:</h2>

- **Domínio do Django Rest Framework:** Estruturação de endpoints RESTful e gestão eficiente das operações CRUD.
- **Gestão de Arquivos:** Implementação de upload, armazenamento e recuperação de imagens associadas às memórias.
- **Integração de APIs de Mapas:** Capacidade de integrar e utilizar serviços externos para funcionalidades de localização.
- **Segurança:** Implementação de práticas de autenticação e autorização seguras para proteger os dados dos usuários.
- **Organização e Documentação do Código:** Qualidade do código, boas práticas de programação e documentação clara.

<h2>📍 Tecnologias Recomendadas:</h2>

- Django Rest Framework (DRF)
- Banco de dados relacional (ex.: SQLite, PostgreSQL, MySQL)
- APIs de Mapas (ex.: Google Maps, OpenStreetMap)

<h2>Conclusão:</h2>

O aplicativo "Memmories" oferece uma oportunidade para demonstrar habilidades básicas e médias no desenvolvimento de aplicativos Backend com Django e DRF, especialmente em áreas como gestão de arquivos, integração de APIs, e implementação de sistemas seguros e eficientes. Tmabém oferece uma excelente maneira de mostrar aos recrutadores que conseguirá desempenhar o seu papel de modo eficiente no projecto lhe será submetido.
