## 4. Requisitos de Software

*   **Arquitetura de Software:** A plataforma **ROS 2** (Robot Operating System) é a base [42], oferecendo um **ambiente modular** com um protocolo de comunicação confiável (DDS) [44, 45].
*   **Módulos:** Deve ser composta por interfaces homem-máquina (HMI), diferentes controles e porcentagem de ajuda [8].
*   **Simulação e Validação Virtual:**
    *   Integração com plataformas de emulação abertas (e.g., QEmu) para executar o mesmo binário do protótipo com precisão de ciclos [45, 46].
    *   Utilização do **Gazebo** (ambiente de modelagem 3D) com integração nativa ao ROS 2 para visualização 3D e teste de atuação em **ambiente virtual** [46].
    *   Construção de um **modelo numérico** do projeto bípede para simulação [47].
*   **Algoritmos de Controle de Marcha e Equilíbrio:**
    *   Desenvolver algoritmos de controle [37, 47].
    *   As estratégias de controle devem **gerar padrões de marcha que assegurem a estabilidade** na presença de perturbações [47, 48].
    *   Deve haver a integração de **modelos músculo-esqueléticos** para pacientes que retêm movimento [47].
    *   Desenvolvimento de uma **estratégia de comutação** entre os modos de controle [14, 31].
    *   **Lógicas de controle** para proteção em caso de queda [31, 32].
*   **Identificação de Intenção do Usuário:**
    *   Identificar a intenção do usuário de forma **rápida e segura** para reagir em tempo real [14].
    *   Uso de **procedimentos de *machine learning*** (aprendizado de máquina) em grandes quantidades de dados (ergonomia, postura, tempo de uso, telemetria) para identificar necessidades e prognósticos [49].
    *   Desenvolvimento e validação de um **modelo de aprendizado profundo** (Deep Learning) para extrair **características universais de EMG** que generalize entre diferentes usuários e dispositivos [50-52].
    *   Construir modelos matemáticos combinando dados **cinemáticos, dinâmicos e de eletromiografia** para identificação automática e simultânea de intenção motora [53, 54].
*   **Segurança (Safety):** Utilizar **técnicas de engenharia de segurança** para prever o comportamento do software e garantir uma **degradação suave do sistema** para evitar prejuízos ao usuário [55].
*   **Comunicação e Padronização:** Definir **compatibilidade de comunicação, formato e protocolo de comunicação e processamento de informações** partilhadas entre os dispositivos [56].
