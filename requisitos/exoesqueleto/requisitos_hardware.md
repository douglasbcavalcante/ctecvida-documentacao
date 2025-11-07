## 3. Requisitos de Hardware

*   **Compatibilidade Eletrônica:** Necessidade de definir **requisitos de compatibilidade eletrônica** para a integração de módulos [6, 10].
*   **Barramento Padrão:** Definir um **padrão de barramento eletrônico** para conectar sensores e atuadores [33].
*   **Atuadores:** Devem ser modulares, ativos ou semi-ativos [8]. Sistemas robóticos que interagem com humanos devem possuir mecanismos que garantam uma **interação estável e complacente** [25].
    *   Podem ser utilizados atuadores com controladores de força e impedância, atuadores com rigidez variável, ou **atuadores elásticos em série (AESr)** [26, 34].
    *   O mecanismo deverá utilizar **mecanismos elásticos em série** para reduzir o impacto nos tecidos e juntas dos voluntários e minimizar o impacto dos atuadores [35].
*   **Sensores (Geral):** Deverão possuir sensores [5, 21]. Integração de uma rede de sensores para compreensão em tempo real [12].
*   **Sensores (Específicos):**
    *   Sensores de **posição**, **acelerômetros**, **giroscópios** e **sensores de pressão** devem ser integrados para fornecer dados sobre movimento e equilíbrio [12, 36].
    *   **Extensômetros** e **encoders** serão utilizados para medir forças realizadas, de interação com o paciente e a posição das juntas do aparelho [35].
    *   Para pacientes que retêm mobilidade, serão implementados **sensores de EMG e inerciais** [37].
    *   Os sistemas de monitoramento devem seguir padrões de **modularidade, compatibilidade e portabilidade** [38].
*   **Controladores e Processamento:**
    *   Os **controladores (drivers)** devem ser de qualidade, longa durabilidade, resiliência, e **facilmente obtidos no mercado nacional** [39].
    *   O **microcontrolador e o sistema embarcado** devem ser definidos pelo **desempenho esperado** sob demanda de **resposta em tempo real** [40].
    *   O microcontrolador deve ter a **capacidade de processamento** necessária para coletar e processar todos os dados e garantir a **frequência definida para cada malha** [41].
    *   Desenvolvimento de **sistemas descentralizados customizados** para pré-processamento de dados (e.g., leituras de células de carga e filtragem de sinais de módulos inerciais) para garantir modularidade [41].
*   **Alimentação e Segurança Elétrica:**
    *   Definir o ciclo de uso da fonte de alimentação com base nos usuários alvos (e.g., quantidade e meios de recargas, durabilidade) [42].
    *   Sistemas de **segurança elétrica redundantes** devem garantir a manutenção de tensão adequada, **consumo inteligente** e **limitação de corrente** [43].
*   **Compatibilidade com Cadeira de Rodas:** Levantar **requisitos de compatibilidade elétrica** para conexão e comunicação dos módulos com cadeiras de rodas [43].
