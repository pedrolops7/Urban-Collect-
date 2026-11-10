# Arquitetura do Sistema - Urban Collect

A arquitetura do Urban Collect foi desenhada para garantir processamento em tempo real e eficiência logística.

## Tecnologias Utilizadas
* **Front-end / App Mobile (MVP):** FlutterFlow. Escolhido pela agilidade no desenvolvimento NoCode/LowCode.
* **Back-end:** Java. Garante robustez no processamento das regras de negócio.
* **Inteligência Artificial / Roteamento:** Integração com API de roteamento externa para cálculo de rotas dinâmicas.
* **Banco de Dados:** Firebase. Essencial para atualizações em tempo real (Realtime Database), permitindo que o aplicativo do motorista seja atualizado instantaneamente quando um contêiner atinge o limite.
* **Hardware:** Sensores IoT (Células de carga). Ficam instalados na base dos contêineres para medir o peso exato, com blindagem antivandalismo.
