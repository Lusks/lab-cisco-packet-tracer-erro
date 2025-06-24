# lab-cisco-packet-tracer-erro


## 🪜 Passo a Passo

1. Adicione os dispositivos:
   - 1x **PC** (End Devices > End Devices > PC)
   - 1x **Roteador** (Network Devices > Wireless Devices > Home Router)
   - 1x **Laptop** (End Devices > End Devices > Laptop)
   - 1x **Webcam** (End Devices > Home > Webcam)

2. Tente conectar os dispositivos com um cabo.

   - Clique em "Connections" e em "Automatically Choose connection type". Agora selecione o roteador e depois clique no PC.
   - Faça o mesmo, mas dessa vez entre o roteador e a webcam.

3. Erro exibido:

> "The cable cannot be connected to that port"

## 🩹 Causa Identificada

O erro ocorreu porque eu estava tentando usar um **tipo de conexão inadequada** entre o roteador e a webcam.

## ✅ Solução Aplicada

- Troquei o tipo conexão de cabeada para **wi-fi**.

## ✅ Passo a passo da solução:

1. **Clique na Webcam**  
   - Ao abrir a janela de configurações, clique na opção **"Advanced"** (localizada no canto inferior direito da janela).

2. **Habilite a aba "I/O Config"**  
   - A aba **"I/O Config"** apareceu ao lado da aba **"Specifications"**.  
   - Dentro de **"I/O Config"**, altere a opção do **adaptador de rede** para:  
   **`PT-IOT-NM-1CE`**

3. **Realize uma nova tentativa de conexão**  
   - Ao tentar gerar uma nova conexão entre o **roteador** e a **webcam**, o **erro desaparece**.

## 🧪 Resultado Esperado

- Comunicação funcionando entre os dispositivos.


## ✅ Conclusão

Erro simples, mas que pode confundir quem está começando no Packet Tracer. Fica o aprendizado sobre a importância de escolher o cabo correto para cada tipo de conexão.

## 📚 Referência

- [Artigo original no Medium](https://medium.com/@lucasnovaestech/corrigindo-o-erro-the-cable-cannot-be-connected-to-that-port-na-aplica%C3%A7%C3%A3o-cisco-packet-tracer-ac650573a614)
- [Documentação oficial Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer)

