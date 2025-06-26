# 🎥 YouTube Video Converter - Projeto Full Stack

Este projeto é uma aplicação web para **converter vídeos do YouTube** em diferentes formatos, como MP4 ou MP3. Desenvolvido com **HTML/CSS no front-end**, e **Node.js + Python no back-end** para fazer a integração com o YouTube e conversão dos arquivos.

---

## 🗂️ Estrutura do Projeto (sugestão)

```
youtube-converter/
├── backend/
│   ├── server.js             # Servidor Node.js
│   ├── routes/
│   │   └── convert.js        # Rota de conversão
│   ├── controllers/
│   │   └── convertController.js
│   └── youtube_download.py   # Script Python para baixar vídeos
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
```

---

## 🔧 Tecnologias Utilizadas

### Front-End:
- HTML5
- CSS3
- JavaScript (Fetch API para comunicação com back-end)

### Back-End:
- Node.js + Express
- Python 3
- Biblioteca Python: `pytube`, `moviepy`, `ffmpeg`

---

## 🚀 Funcionalidades
- ✅ Inserção de URL do YouTube pelo usuário
- ✅ Comunicação front-end/back-end com Node.js
- ✅ Execução de script Python para baixar vídeo
- ✅ Opção de conversão para MP4 ou MP3
- ✅ Retorno de link para download do arquivo convertido

---

## 📌 Como Rodar o Projeto Localmente

### Requisitos:
- Node.js instalado
- Python 3 instalado

### Passos:
1. **Instale as dependências Node.js**
```bash
npm install express cors
```

2. **Instale as bibliotecas Python**
```bash
pip install pytube moviepy
```

3. **Inicie o servidor**
```bash
node server.js
```

4. **Abra o `index.html` no navegador**

---

## 📚 O Que Estudar para Este Projeto

### Front-End:
- HTML, CSS, JS básico
- Formulários e manipulação DOM
- Fetch API (requisições HTTP)

### Back-End:
- Node.js com Express
- Rotas e controle de requisições POST
- Integração com Python usando `child_process`

### Python:
- `pytube` para baixar vídeos
- `moviepy` ou `ffmpeg` para conversão de áudio/vídeo

---

## 📄 Exemplo de Uso (interface)
- Usuário cola o link do YouTube
- Escolhe o formato (MP3/MP4)
- Clica em "Converter"
- Download inicia automaticamente após o processamento

---

## 🧑‍💻 Desenvolvido por
**Lucas Mendonça Martins**

> Esse projeto é ideal para estudo de integração entre linguagens e construção de uma aplicação full stack real. Deseja que eu gere os arquivos iniciais do projeto também?
