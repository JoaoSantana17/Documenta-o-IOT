# 🎉 Rolé – Aplicativo Social Inteligente

> **Um app para conectar pessoas, integrar tecnologia e transformar o jeito de marcar encontros presenciais.**

## Integantes 

**- Adão Yuri Ferreira da Silva - RM559223;**
**- João Vitor Lopes Santana - RM560781**

---
## Link Vídeo: https://www.youtube.com/watch?v=Xy1AiOvj63w&t=2s
---
## Visão Geral

O **Rolé** um aplicativo social desenvolvido para **facilitar a organização de encontros presenciais entre amigos e grupos**.  
A proposta surgiu a partir de uma situação comum: a dificuldade de coordenar horários e deslocamentos quando várias pessoas combinam um rolê.

O aplicativo centraliza **todas as informações do evento em um único lugar**, permitindo acompanhar em tempo real:

- Quem já saiu de casa  
- Quem está a caminho  
- Quem já chegou  

A plataforma combinará **geolocalização, tempo estimado de chegada (ETA)** e **sugestões de transporte**, oferecendo uma experiência prática e divertida para o usuário.

Além disso, o Rolé contará com um **feed social interativo**, onde os participantes podem **postar fotos, comentar e interagir** durante o evento.  
Ao final, o botão **“Acabou o Rolê”** encerra o encontro e gera um **resumo descontraído**, incentivando novas experiências sociais.

---

## Tecnologias Principais

| Camada | Tecnologia | Descrição |
|---------|-------------|-----------|
| **Frontend Mobile** | React Native | Interface moderna, responsiva e intuitiva. |
| **Backend API** | Python (Flask / FastAPI) | Camada intermediária de dados e integração com APIs externas. |
| **Banco de Dados** | Oracle Database Cloud / APEX | Armazenamento, dashboards e relatórios. |
| **IoT & Comunicação** | Node-RED + MQTT | Simulação de sensores e envio de dados em tempo real. |
| **Inteligência Artificial** | Python (Pandas + scikit-learn) | Recomendação de eventos personalizados via modelo KNN. |
| **Infraestrutura** | Azure VM + Docker | Deploy containerizado, monitorado e escalável. |

---

## Aplicativo Mobile

O **app mobile** é o coração do Rolê.  
Ele oferece uma **interface social em tempo real**, permitindo futuramente:

- Visualizar eventos próximos com base na localização do usuário;  
- Criar e gerenciar rolês com amigos;  
- Interagir via feed de publicações e comentários;  
- Receber notificações automáticas conforme status de presença dos participantes.

O app também **consome a API pública da Ticketmaster**, permitindo exibir eventos reais, como shows e festivais, dentro da própria aplicação.

