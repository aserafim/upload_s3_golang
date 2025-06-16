# Upload S3 Golang

Este projeto em Go foi desenvolvido como parte do curso Full Cycle Go Expert, com o objetivo de implementar um serviço de upload de arquivos utilizando a linguagem Go.

## 📦 Objetivo

O serviço permite o upload de arquivos, possivelmente para um bucket S3 (AWS), utilizando uma arquitetura simples com boas práticas de organização e modularização de código.

## 🧱 Estrutura do Projeto

```

upload\_s3\_golang/
├── main.go               # Ponto de entrada da aplicação
├── go.mod                # Gerenciador de dependências Go
├── uploader/
│   ├── handler.go        # Controlador HTTP que lida com requisições de upload
│   └── uploader.go       # Lógica de envio dos arquivos

````

## 🚀 Tecnologias Utilizadas

- [Go](https://golang.org/)
- [net/http](https://pkg.go.dev/net/http) para criação do servidor web
- AWS SDK (presumido)
- Arquitetura modular (separação de responsabilidades em pacotes)

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/upload_s3_golang.git
   cd upload_s3_golang
````

2. Instale as dependências:

   ```bash
   go mod tidy
   ```

3. Insira as informações confidenciais:
  - user
  - senha
  - bucket

4. Inclua no diretório /tmp/ os arquivos a serem upados

5. Execute o projeto:

   ```bash
   go run main.go
   ```

## ✍️ Autor

Desenvolvido por [Seu Nome](https://github.com/seu-usuario) durante o curso **Full Cycle Go Expert**.

## 📄 Licença

Este projeto está licenciado sob a licença MIT.

