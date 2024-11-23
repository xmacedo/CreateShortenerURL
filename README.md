# CreateShortenerURL


Um projeto para encurtar URLs de maneira eficiente, utilizando tecnologias avançadas da AWS, como API Gateway, S3, Lambda e Java.

---

## 🌐 Sobre o Projeto | About the Project

### 🇧🇷 
O **CreateShortenerURL** é uma aplicação de encurtamento de URLs criada no resultado do curso Gratuito da RocketSeat.  
Com este projeto, você pode:
- Transformar URLs longas em links curtos.
- Integrar com outras aplicações via API RESTfull.

### 🇺🇸 Description in English
**CreateShortenerURL** is a URL shortening application created on the RocketSeat course results.   
With this project, you can:
- Convert long URLs into short links.
- Integrate with other applications via a RESTfull API.

---

## 🛠️ Tecnologias Utilizadas | Technologies Used

<div>
  <img src="https://d1.awsstatic.com/logos/aws-lambda-2.svg" alt="AWS Lambda" width="100"/>
  <img src="https://d1.awsstatic.com/logos/aws-api-gateway.svg" alt="AWS API Gateway" width="100"/>
  <img src="https://d1.awsstatic.com/logos/aws-s3.svg" alt="AWS S3" width="100"/>
  <img src="https://www.vectorlogo.zone/logos/java/java-ar21.svg" alt="Java" width="100"/>
</div>

Este projeto utiliza os seguintes serviços e tecnologias:
- **AWS API Gateway**: Para criação e gerenciamento de endpoints RESTful.
- **AWS Lambda**: Para execução de funções serverless e processamento das URLs.
- **AWS S3**: Para armazenamento de dados estáticos e logs.
- **Java**: Linguagem principal utilizada no desenvolvimento das funções.

---

## 🚀 Como Usar | How to Use

### 🇧🇷 Passos para usar
1. Clone o repositório:
   ```bash
   git clone https://github.com/xmacedo/CreateShortenerURL.git
   cd CreateShortenerURL
   ```
2. Implemente o código em sua infraestrutura AWS.
3. Acesse o endpoint gerado pelo API Gateway para começar a encurtar URLs.

### 🇺🇸 Steps to use
1. Clone the repository:
   ```bash
   git clone https://github.com/xmacedo/CreateShortenerURL.git
   cd CreateShortenerURL
   ```
2. Deploy the code to your AWS infrastructure.
3. Access the API Gateway endpoint to start shortening URLs.

---

## 📚 Documentação da API | API Documentation

### Endpoints
- `POST /shorten`: Cria uma nova URL curta.
    - **Parâmetros**:
      ```json
      {
        "url": "https://example.com"
      }
      ```
    - **Resposta**:
      ```json
      {
        "shortenedUrl": "https://short.ly/abc123"
      }
      ```

- `GET /{id}`: Redireciona para a URL original.

---

## 🤝 Contribuindo | Contributing

Contribuições são bem-vindas! Siga os passos abaixo para colaborar:
1. Faça um fork do projeto.
2. Crie uma branch para sua feature ou correção: `git checkout -b minha-feature`.
3. Faça o commit: `git commit -m "Adicionei minha nova feature"`.
4. Envie sua branch: `git push origin minha-feature`.
5. Abra um pull request.

---

## 📄 Licença | License

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.

---

**Autor**: [Seu Nome](https://github.com/xmacedo)  
🎯 _Encurtando URLs com escalabilidade e eficiência!_
