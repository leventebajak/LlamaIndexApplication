This is a [LlamaIndex](https://www.llamaindex.ai/) project bootstrapped with [`create-llama`](https://github.com/run-llama/create-llama) v0.3.14.

## Ollama

First, download Ollama from https://ollama.com/download and run these commands to download the models used in the [.env](backend/.env) file.

```bash
ollama pull nomic-embed-text
```

```bash
ollama run llama3.2
```

## Getting Started

First, startup the backend as described in the [backend README](./backend/README.md).

Run the development server:

```shell
cd backend
python main.py
```

Second, run the development server of the frontend as described in the [frontend README](./frontend/README.md).

Run the development server:

```shell
npm run dev --prefix frontend
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.