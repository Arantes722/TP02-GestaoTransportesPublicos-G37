# Gestão de Transportes Públicos - Grupo G37

Bem-vindo ao repositório do projeto **Gestão de Transportes Públicos**, desenvolvido no âmbito do Trabalho Prático II da Unidade Curricular **Integração de Sistemas de Informação (ISI)**, do curso de **Licenciatura em Engenharia de Sistemas Informáticos** no ano letivo 2024/2025.

## 📖 Descrição do Projeto
Este projeto tem como objetivo criar uma API e uma aplicação cliente para a gestão de transportes públicos. A API permitirá a interoperabilidade com aplicações externas e oferecerá funcionalidades como:

- Gestão de horários e rotas dos transportes públicos.
- Monitorização do estado em tempo real dos transportes.
- Notificações sobre atrasos ou interrupções no serviço.
- Integração com APIs externas para georreferenciação e localização.

## 🛠️ Funcionalidades
1. **Serviços RESTful**:
   - **CRUD** (Create, Read, Update, Delete) para rotas, horários e transportes.
   - Operações de autenticação e controlo de acesso utilizando **OAuth Tokens**.

2. **Integração com APIs Externas**:
   - Georreferenciação e visualização de rotas em mapas.
   - Localização em tempo real dos transportes.

3. **Publicação na Cloud**:
   - A API será disponibilizada numa **plataforma PaaS** (Platform as a Service), garantindo acessibilidade contínua.

4. **Dashboard**:
   - Monitorização de atrasos e interrupções.
   - Visualização de métricas de desempenho.

## 🧰 Tecnologias Utilizadas
- **Backend**: .NET C# para implementação dos serviços SOAP e RESTful.
- **Documentação**: OpenAPI (Swagger) para documentação da API.
- **Cloud Hosting**: Azure ou outra PaaS.
- **APIs Externas**: Google Maps API, OpenWeatherMap (opcional).

## 🚀 Configuração do Ambiente
1. Clone este repositório:
   ```bash
   git clone https://github.com/grupoG37/gestao-transportes-publicos.git
   cd gestao-transportes-publicos
