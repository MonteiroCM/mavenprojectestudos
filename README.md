# 🚀 Maven Project Estudos

[![Java](https://img.shields.io/badge/Java-11-orange?style=for-the-badge&logo=openjdk)](https://openjdk.java.net/)
[![Jakarta EE](https://img.shields.io/badge/Jakarta%20EE-10.0.0-blue?style=for-the-badge&logo=eclipse)](https://jakarta.ee/)
[![Maven](https://img.shields.io/badge/Maven-3.8.1-red?style=for-the-badge&logo=apache-maven)](https://maven.apache.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Build Status](https://img.shields.io/badge/Build-Passing-brightgreen?style=for-the-badge)]()

## 📋 Sobre o Projeto

Este é um projeto de estudos utilizando **Jakarta EE 10** com **Maven** para desenvolvimento de aplicações web modernas. O projeto demonstra a implementação de uma API REST simples usando as especificações mais recentes do Jakarta EE.

## 🛠️ Tecnologias Utilizadas

- **Java 11** - Linguagem de programação
- **Jakarta EE 10.0.0** - Plataforma de desenvolvimento empresarial
- **Maven 3.8.1** - Gerenciamento de dependências e build
- **Jakarta RESTful Web Services** - Para criação de APIs REST
- **Jakarta Servlet** - Para aplicações web

## 🚀 Como Executar

### Pré-requisitos

- Java 11 ou superior
- Maven 3.6 ou superior
- Servidor de aplicação compatível com Jakarta EE 10 (ex: Payara, WildFly, TomEE)

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/mavenprojectestudos.git
cd mavenprojectestudos
```

2. Compile o projeto:
```bash
mvn clean compile
```

3. Gere o arquivo WAR:
```bash
mvn package
```

4. Deploy o arquivo `target/mavenprojectestudos-1.0-SNAPSHOT.war` no seu servidor de aplicação

## 📡 API Endpoints

### GET /resources/jakartaee10
Retorna uma mensagem de ping para testar a API.

**Resposta:**
```
ping Jakarta EE
```

## 📁 Estrutura do Projeto

```
mavenprojectestudos/
├── src/
│   └── main/
│       ├── java/
│       │   └── br/com/claytonmonteiro/mavenprojectestudos/
│       │       ├── JakartaRestConfiguration.java
│       │       └── resources/
│       │           └── JakartaEE10Resource.java
│       ├── resources/
│       │   └── META-INF/
│       │       └── persistence.xml
│       └── webapp/
│           ├── index.html
│           └── WEB-INF/
│               ├── beans.xml
│               └── web.xml
├── pom.xml
└── README.md
```

## 🔧 Configuração

### Jakarta REST Configuration
- **Application Path:** `/resources`
- **Configuração:** `JakartaRestConfiguration.java`

### Recursos REST
- **Endpoint:** `/jakartaee10`
- **Método:** GET
- **Implementação:** `JakartaEE10Resource.java`

## 📚 Aprendizados

Este projeto demonstra:

- ✅ Configuração de um projeto Maven para Jakarta EE 10
- ✅ Implementação de uma API REST simples
- ✅ Estrutura básica de uma aplicação web Jakarta EE
- ✅ Configuração de dependências e build com Maven

## 🤝 Contribuindo

1. Faça um fork do projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 👨‍💻 Autor

**Clayton Monteiro**
- GitHub: [@seu-usuario](https://github.com/seu-usuario)
- LinkedIn: [Clayton Monteiro](https://linkedin.com/in/clayton-monteiro)

---

⭐ Se este projeto foi útil para você, considere dar uma estrela!