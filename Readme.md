
## Requisitos básicos
- **Hardware**:
  - Estrutura da planta impressa em ABS;
  - 3 motores Nidec 24H (ou equivalentes);
  - ESP32 (ou Arduino com desempenho equivalente);
  - IMU (MPU-6050, MPU-9250 ou similar);
  - Fonte/bateria compatível.

- **Software**:
  - Onshape (para CAD e ajustes mecânicos);
  - Arduino IDE / PlatformIO;
  - MATLAB/Octave 
  - Python (control, numpy, matplotlib).

## Como usar
1. **Imprima e monte a estrutura da planta** usando os arquivos em `cad/`.  
2. **Carregue o firmware** em um ESP32/Arduino.  
3. **Conecte sensores e motores** conforme os esquemas.  
4. **Experimente e sitonize diferentes controladores** (PID, LQR) e compare o desempenho.  

## Licença e uso
Este projeto é distribuído sob licença **MIT** — você pode usar, modificar e distribuir livremente, desde que mantenha a atribuição ao autor original.  
Objetivo principal: **democratizar o acesso a plantas didáticas de controle**.

## 👥 Contribuindo
Contribuições são bem-vindas!  
Sugestões de melhorias, novos controladores ou adaptações de hardware podem ser enviadas via **pull request** ou **issue**.

---

**Autor:** *Alex de Assis Filho*  
Trabalho de Conclusão de Curso — Engenharia de Controle e Automação  
Universidade Federal de Minas Gerais, 2025

