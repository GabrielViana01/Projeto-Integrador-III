# iBarber - Sistema de Barbearia.

O iBarber é um sistema de barbearia confeccionado durante as aulas de **projeto integrador do Centro Universitário de Brasília (UniCEUB).**

![Captura de tela 2025-06-16 221004](https://github.com/user-attachments/assets/61558b1c-6e17-4946-8d2d-5b6672bafb10)


## Índice

1. [Descrição](#descrição)
2. [Objetivo](#tecnologias)
3. [Público-Alvo](#público-alvo)
4. [Funcionalidades](#funcionalidades)
5. [Arquiteturas e Tecnologias](#arquitetura-e-tecnologias)
6. [Como Usar](#como-usar)
7. [Equipe de Desenvolvimento](#equipe-de-desenvolvimento)
8. [Diagramas](#diagramas)
9. [Banco de Dados](#banco-de-dados)
10. [Cronograma de Atividades](#cronograma-de-atividades)
11. [Protótipo de Alta Fidelidade](#protótipo-de-alta-fidelidade)

# Descrição
Este é um Projeto Mobile desenvolvido por alunos do Centro Universitário de Brasília (UniCEUB), com objetivo de criar um aplicativo que revolucione o mercado digital na àrea masculina, entre uma faixa etária de 16 à 50 anos. Os colaboradores do projeto são: Vitor Szervinsks, Gabriel Viana e Filipe Ali.
# Visão Geral do Projeto
O iBarber é uma plataforma web e mobile criada para facilitar o contato entre clientes e barbearias, centralizando informações detalhadas sobre serviços, agendamentos online, comunicação direta e opções de atendimento domiciliar. O projeto resolve problemas comuns como falta de padronização, dificuldade de agendar horários e baixa divulgação de benefícios extras, tornando o processo mais prático e confiável.
# Objetivo
Este projeto tem como objetivo desenvolver uma plataforma que facilite a comunicação entre clientes e prestadores de serviços, melhorando a experiência do usuário e otimizando o processo de contratação.
# Público-Alvo
O público-alvo do iBarber são clientes que buscam praticidade e qualidade ao contratar serviços de barbearia, além de barbeiros autônomos e barbearias de todos os portes que desejam divulgar seus serviços, atrair mais clientes e gerenciar agendamentos de forma organizada e eficiente.
# Funcionalidades 
- **Sistema de Cadastro e Login:** Permite o cadastro de novos clientes com informações pessoais e de contato.
- **Controle de Pagamentos:** Exibição do extrato e vencimento da mensalidade.
- **Utilização de API do Mercado Pago:** Integração para pagamentos.
- **Intermediação de Contato:** Sistema de mensagens interno para comunicação entre clientes e empregados.
- **Sistema de Avaliação e Feedback:** Avaliações e comentários de clientes sobre os serviços prestados e listagem detalhada dos serviços oferecidos pelos empregados.
- **Geolocalização:** Sistema de localização para mostrar a distância entre o cliente e o empregado e a opção de selecionar empregados baseados na proximidade geográfica.
- **Atendimento Domiciliar:** Opção para que os clientes solicitem atendimento em domicílio e Agenda de disponibilidade dos empregados para serviços domiciliares. 
- **Benefícios Adicionais:** Listagem de possíveis benefícios oferecidos pelo estabelecimento, como bebidas, jogos e outros tipos de entretenimento. 
# Arquiteturas e Tecnologias
O iBarber é uma aplicação mobile desenvolvida no Android Studio, voltada exclusivamente para dispositivos Android, aproveitando os recursos nativos da plataforma para garantir melhor desempenho e experiência do usuário. Toda a lógica de backend e autenticação é estruturada com Firebase, que gerencia o cadastro de usuários, agendamentos e armazenamento de dados em nuvem de forma segura. As funcionalidades de localização e cálculo de distância entre cliente e barbearia são integradas por meio da API do Google Maps. A prototipação da interface foi feita no Figma, e o mapeamento dos processos de negócio foi realizado com o Bizagi.
**Requisitos Não Funcionais**
- Atualização de dados de forma imediata e com registro histórico.

- Compatibilidade com dispositivos Android.

- Interface responsiva, com layout intuitivo e fácil de usar.

- Atender aos princípios de usabilidade e experiência do usuário (UX).

- Realização de backups periódicos para segurança dos dados.

- Escalabilidade para suportar grande volume de usuários e dados.

- Permitir manutenção e atualizações sem impactar os serviços.
# Como Usar

**1. Baixe o aplicativo:**

Instale o iBarber em seu dispositivo Android diretamente pela Play Store ou utilizando o arquivo APK disponibilizado pelo desenvolvedor.

**2. Crie sua conta:**

Abra o aplicativo, cadastre-se informando seus dados básicos e valide seu e-mail ou número de telefone, caso solicitado.

**3. Faça login:**

Acesse sua conta com seu usuário e senha cadastrados.

**4. Explore os serviços:**
Navegue pela lista de barbeiros e barbearias disponíveis, visualize informações detalhadas, benefícios oferecidos e a distância até o local.

**5. Agende seu horário:**

Escolha o serviço desejado, selecione o dia e horário disponíveis e confirme o agendamento pelo próprio app.

**6. Comunique-se diretamente:**

Utilize o chat ou botão de ligação para tirar dúvidas ou ajustar detalhes com o barbeiro, se necessário.

**7. Acompanhe e avalie:**

No dia agendado, compareça ao local ou receba o atendimento em casa (caso disponível). Após o serviço, avalie sua experiência no aplicativo.

# Equipe de Desenvolvimento
- Gabriel Viana J. Silva

- Filipe Ali de Sousa

- Vitor Szervinsks Wandalsen

# Diagramas

**1. Caso e Uso**

![Captura de tela 2025-06-17 090518](https://github.com/user-attachments/assets/de5f8289-6c5a-465e-9d9e-b069a2207d0c)

**2. Diagrama de Classe**

![Captura de tela 2025-06-16 215851](https://github.com/user-attachments/assets/5902f8e2-e49b-44b7-86bb-0379cc15c18f)

**3. Diagrama de Atividades**

![image](https://github.com/user-attachments/assets/01d218d8-4039-4094-9a3f-a8241077ec01)

# Banco de Dados

**1. Modelo Conceitual**

![Captura de tela 2025-06-16 222650](https://github.com/user-attachments/assets/221e985b-d6a5-4b02-a678-2fed003a2343)

**2. Modelo Lógico**

![Captura de tela 2025-06-16 222744](https://github.com/user-attachments/assets/4b82d361-e79e-43fa-a0cf-b5cd6c492409)

**3. Modelo Físico**

![Captura de tela 2025-06-16 222838](https://github.com/user-attachments/assets/daeec812-8cf9-48a2-be62-cbe0beae48bc)

## Cronograma de Atividades

| Etapa                       | Data Inicial  | Data Final | Responsável              |
|-----------------------------|---------------|------------|--------------------------|
| Planejamento e Definição    | 12/02/2024    | 19/08/2024 | Gabriel V.; Vitor S.; Filipe Ali |
| Desenvolvimento             | 26/08/2024    | --/--/2025 | Gabriel V.; Vitor S.; Filipe Ali |
| Testes e Validação          | 17/03/2025    | --/--/2025 | Gabriel V.; Vitor S.; Filipe Ali |
| Finalização e Apresentação  | --/--/2025    | --/--/2025 | Gabriel V.; Vitor S.; Filipe Ali |


# Protótipo de Alta Fidelidade

**FIGMA:** https://www.figma.com/design/JBRbWTQgA4pgAjo7wOTURH/Prot%C3%B3tipo-de-Alta-Fidelidade?node-id=122-468&p=f&t=MqyLjLfXuZjt7clc-0 
