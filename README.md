# CareKnow Robot
Robot Generative AI Berbentuk Vending Machine untuk Deteksi Awal Masalah Kesehatan

## Instruction
Berikut petunjuk atau langkah-langkah untuk menggunakan CareKnow Robot (Generative AI)

### 1. Installing Ollama
#### macOS

[Download](https://ollama.com/download/Ollama-darwin.zip)

#### Windows

[Download](https://ollama.com/download/OllamaSetup.exe)

#### Linux

```
curl -fsSL https://ollama.com/install.sh | sh
```

[Manual install instructions](https://github.com/ollama/ollama/blob/main/docs/linux.md)

#### Quickstart

To run and chat with [Llama 3.2](https://ollama.com/library/llama3.2):

```
ollama run llama3.2
```

### 2. Installing Dify
#### Quick start
The quickest way to deploy Dify locally is to run our [docker-compose.yml](https://github.com/langgenius/dify/blob/main/docker/docker-compose.yaml). Follow the instructions to start in 5 minutes.

> Before installing Dify, make sure your machine meets the following minimum system requirements:
> 
>- CPU >= 2 Core
>- RAM >= 4 GiB
>- Docker and Docker Compose Installed
</br>

Run the following command in your terminal to clone the whole repo.
```bash
git clone https://github.com/langgenius/dify.git
```
After cloning,run the following command one by one.
```bash
cd dify
cd docker
cp .env.example .env
docker compose up -d
```

### 3. Download our RAG Data and DSL File for Dify
#### RAG Data
You can download from link bellow.
```bash
git clone https://github.com/langgenius/dify.git
```

#### Our DSL File for Dify
You can download from link bellow.
```bash
git clone https://github.com/langgenius/dify.git
```

### 4. Insert RAG To Knowledge
Pada aplikasi dify masukan data yang sudah kami kumpulkan sebagai data RAG:
1. Buka Aplikasi Dify di localhost
2. Menuju Tab Knowledge
3. Pilih Create Knowledge
4. Tambahkan atau Drag drop semua file
5. Chunk settings : pilih automatic, Index mode: Economical, Top-K: 3
6. Next, kemudian finnis (setelah file 100% processing)

### 5. Import our DSL File
Pada aplikasi dify import DSL yang nanti akan menjadi webpage Robot CareKnow Bot (gambar seperti di paparan pdf):
1. Buka Aplikasi Dify di localhost
2. Menuju Tab Studio
3. Drag and Drop file
4. Create and finnish

### CareKnow Robot sudah dapat digunakan sebagai Robot Assistant dan dimanfaatkan di vanding machine
