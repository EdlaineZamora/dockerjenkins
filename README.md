# dockerjenkins
Dockerfile para construir um container com ambiente Jenkins

Versões das tecnologias:
- Ubuntu 14.04 LTS
- Oracle Java 1.8.0_11 64 bit
- Maven 3.3.9
- Jenkins 2.45
- git 1.9.1
- Nano 2.2.6-1ubuntu1

# Para construir a imagem e rodar o container:
- Entrar no diretório do arquivo dockerfile
- Executar o comando: docker build -t jenkins .
- Executar o comando: docker run -p 8080:8080 --name jenkins jenkins
- Acessar o endereço http://localhost:8080 para linux ou docker for windows ou http://ip_vm_docker:8080 para macos ou toolbox docker no windows.
