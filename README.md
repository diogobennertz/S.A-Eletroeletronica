# S.A-Eletroeletronica
 • Sistema 8 - Monitoramento de ruído:         # 🔊 Noisy - Monitoramento Inteligente de Ruído para Impressoras 3D

> Monitoramento preditivo de impressoras 3D através da análise de ruído utilizando Arduino.

![Arduino](https://img.shields.io/badge/Arduino-Uno-00979D?style=for-the-badge\&logo=arduino)
![Status](https://img.shields.io/badge/Status-Funcional-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-Educacional-blue?style=for-the-badge)

---

## 📖 Sobre o Projeto

Impressoras 3D frequentemente apresentam falhas mecânicas antes mesmo que o problema seja visível. Em muitos casos, essas falhas podem ser percebidas através de alterações no som emitido durante a impressão.

O **Noisy** foi desenvolvido para atuar como um sistema de monitoramento preventivo, analisando o ruído produzido pela impressora em tempo real.

Quando um padrão sonoro anormal é detectado, o sistema gera alertas visuais e informa o operador através de um display LCD, permitindo uma intervenção rápida antes que a peça impressa seja comprometida.

---

## 🎯 Objetivo

Detectar possíveis falhas mecânicas em impressoras 3D por meio da análise de ruído ambiente, reduzindo desperdícios de material, tempo e manutenção corretiva.

---

## ⚙️ Funcionamento

<img width="1024" height="768" alt="Beige and Pink Modern Business Process Flowchart Diagram (2)" src="https://github.com/user-attachments/assets/c1fdf1fb-4c92-4a6a-8d19-c2bc79dc63ec" />

Após o retorno ao padrão normal de operação, os alertas são removidos automaticamente.

---

## 🛠️ Hardware Utilizado

| Componente           | Conexão                 |
| -------------------- | ----------------------- |
| Arduino Uno          | Controlador principal   |
| Sensor de Ruído      | Pino Digital 2          |
| LED Vermelho         | Pino Digital 3          |
| Resistor 220 Ω       | Em série com o LED      |
| Display LCD 16x2 I2C | Endereço 0x27 (SDA/SCL) |
| Protoboard           | Montagem do circuito    |

---

## 🔌 Esquema de Ligação

Consulte o diagrama disponível em:

```text
docs/esquema.png
```

---

## 📚 Bibliotecas Necessárias

Instale as seguintes bibliotecas através da Arduino IDE:

```text
Sketch
 └── Incluir Biblioteca
      └── Gerenciar Bibliotecas
```

Bibliotecas utilizadas:

* LiquidCrystal_I2C
* Wire (já inclusa na IDE)

---

## 🚀 Como Utilizar

### 1. Monte o circuito

Siga o esquema presente em:

```text
docs/esquema.png
```

### 2. Abra o projeto

```text
src/noisy.ino
```

na Arduino IDE.

### 3. Faça o upload

Conecte o Arduino e envie o código para a placa.

### 4. Posicione o sensor

Instale o sensor próximo à impressora 3D para capturar os sons produzidos durante a impressão.

### 5. Monitore

O display indicará o estado atual do sistema:

✅ TUDO OK!

ou

⚠️ ALERTA!

🚨 DEFEITO!

---

## 📸 Demonstração

Adicione imagens do projeto na pasta:

```text
docs/images/
```

Exemplo:

```markdown
![Montagem](docs/images/montagem.jpg)

![Sistema em funcionamento](docs/images/demo.jpg)
```

---

## 💡 Aplicações

* Monitoramento preventivo de impressoras 3D
* Detecção de desgaste mecânico
* Projetos de manutenção preditiva
* Sistemas embarcados com Arduino
* Automação industrial educacional

---

## 👨‍💻 Equipe de Desenvolvimento

* Diogo Faqueti Bennertz
* Eloiza Scariotti Marcelino
* Ana Clara Carvalho
* Pedro Hoffmann

---

## 📄 Licença

Projeto desenvolvido para fins acadêmicos e educacionais.


<img width="1254" height="1254" alt="41e2ac84-652a-4433-9c1d-48714af833fb" src="https://github.com/user-attachments/assets/55ea729e-6ee1-4f0c-8dd8-475089298c30" />

<img width="4000" height="2250" alt="White Playful Education Group Project Presentation-2" src="https://github.com/user-attachments/assets/2322db75-d710-4b9e-80de-54c9f50ac01c" />
<img width="4000" height="2250" alt="White Playful Education Group Project Presentation-1" src="https://github.com/user-attachments/assets/176731b3-2f6f-4041-afd3-0c502b914546" />

