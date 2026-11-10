# Diagramas do Projeto

## Fluxo de Dados e Integração IoT
<img width="1140" height="525" alt="image" src="https://github.com/user-attachments/assets/b0827827-76d0-436f-8d84-0b2e6037a7b2" />


**Resumo do Fluxo:**
1. O **Sensor IoT** na base do contêiner deteta que o nível de peso atingiu 95%.
2. O dado é enviado em tempo real para o **Firebase**.
3. O **Back-end (Java)** analisa a mudança e aciona a **API de IA/Roteamento**.
4. Uma nova rota otimizada é gerada e enviada para o **App Mobile (FlutterFlow)**, alertando o motorista.
