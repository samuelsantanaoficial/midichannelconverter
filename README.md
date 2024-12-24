# midi channel converter
Este script detecta automaticamente o diretório onde está localizado e processa todos os arquivos MIDI presentes nesse mesmo local:

## Como usar

### Linux
Instale o pynthon3
```bash
sudo apt install python3-pip
```
Instale as dependências
```bash
pip install mido
```
```bash
pip install python-rtmidi
```
Com o arquivo **midi-channel-converter.py** dentro da pasta com os arquivos midi que precisam ser editados, abra o terminal e execute:
```bash
python3 midi-channel-converter.py
```
Todos os arquivos midi dessa pasta vão ser substituidos, agora tudo no canal 10
*(faça backup dos arquivos antes)*
