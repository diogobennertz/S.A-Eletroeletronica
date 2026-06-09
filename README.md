# S.A-Eletroeletronica
 • Sistema 8 - Monitoramento de ruído:          D
 Noisy
Monitoramento preditivo de impressoras 3D via análise de ruído com Arduino.
Sobre o projeto
Impressoras 3D frequentemente apresentam falhas mecânicas que se manifestam sonoramente antes de causar danos visíveis. O Noisy monitora o áudio da impressora em tempo real e emite um alerta quando detecta um padrão fora do normal, permitindo intervenção antes que a impressão seja comprometida.
Funcionamento
O sensor de ruído lê o sinal digital do ambiente e compara com o limiar de operação normal. Em caso de anomalia, o sistema acende o LED vermelho e exibe mensagens de alerta no LCD. Voltando ao normal, o alerta é limpo automaticamente.
Sensor detecta ruído
        │
        ├── Sinal anômalo → LED acende + LCD exibe "Alerta!" por 5s, depois "Defeito!" por 15s
        │
        └── Sinal normal  → LED apagado + LCD exibe "TUDO OK!"
Hardware
ComponenteConexãoArduino Uno—Sensor de ruídoPino digital 2LED vermelhoPino digital 3Resistor 220 ΩEm série com o LEDDisplay LCD 16x2 (I2C)Endereço 0x27 via SDA/SCLProtoboard—
Dependências
Instale via Sketch > Incluir Biblioteca > Gerenciar Bibliotecas na Arduino IDE:

LiquidCrystal_I2C
Wire (inclusa por padrão)

Como usar

Monte o circuito conforme o diagrama em docs/esquema.png
Abra src/noisy.ino na Arduino IDE
Faça o upload para a placa
Posicione o sensor próximo à impressora — o display confirma quando o sistema está ativo


Desenvolvido por
Diogo Faqueti Bennertz, Eloiza Scariotti Marcelino, Ana Clara Carvalho, Pedro Hoffmann.
<img width="1024" height="768" alt="Beige and Pink Modern Business Process Flowchart Diagram (2)" src="https://github.com/user-attachments/assets/c1fdf1fb-4c92-4a6a-8d19-c2bc79dc63ec" />
<img width="1254" height="1254" alt="41e2ac84-652a-4433-9c1d-48714af833fb" src="https://github.com/user-attachments/assets/55ea729e-6ee1-4f0c-8dd8-475089298c30" />

<img width="4000" height="2250" alt="White Playful Education Group Project Presentation-2" src="https://github.com/user-attachments/assets/2322db75-d710-4b9e-80de-54c9f50ac01c" />
<img width="4000" height="2250" alt="White Playful Education Group Project Presentation-1" src="https://github.com/user-attachments/assets/176731b3-2f6f-4041-afd3-0c502b914546" />

