### 🎮 Placa de Vídeo

As placas de vídeo utilizam o padrão **PCI Express (PCIe)**, que possui diferentes versões:  
**1.0, 2.0, 3.0, 4.0 e 5.0**.  
O encaixe usado geralmente é o **PCIe x16** (slot principal da placa-mãe).  

Além disso, existem variações de **4x, 8x e 16x**, que indicam quantas linhas de comunicação serão usadas (quanto maior, mais banda disponível).  

---

#### 🔧 Exemplo Prático
- Se você tem uma placa de vídeo **PCIe 3.0** e instalar em uma placa-mãe com **PCIe 2.0**, haverá **perda de desempenho**.  
- Se instalar em uma placa-mãe **PCIe 4.0**, ela funcionará normalmente, mas **não aproveitará todo o potencial do slot** (ficará limitada ao 3.0).  

---

### 💡 Tecnologias da Placa de Vídeo

- **Ray Tracing** → tecnologia que simula o comportamento real da luz, deixando os gráficos mais realistas.  
  ⚠️ Porém, exige muito da placa e pode causar **queda de desempenho**.  

---

### 📺 Observação Importante
- Uma placa de vídeo potente perde qualidade se for usada com um **monitor de baixa qualidade** (baixa taxa de atualização ou resolução).

  ### ⚙️ Tecnologias de Vídeo e Otimização

- **DLSS (NVIDIA), FSR (AMD), XESS (Intel):**  
  Técnicas de upscaling que aumentam a taxa de quadros (FPS) renderizando o jogo em resolução menor e ampliando por IA.  

- **Frame Generation:**  
  Cria **quadros extras com IA**, aumentando o FPS aparente.  
  - 🚨 Porém, **aumenta a latência** (resposta dos comandos).  
  - Recomendado usar apenas se o **FPS base já for ≥ 60**.  

- **Tearing:**  
  “Rasgo” na imagem causado pela falta de sincronização entre a placa de vídeo e o monitor.  
  - Soluções: ativar **V-Sync**, **FreeSync** (AMD) ou **G-Sync** (NVIDIA).  
