## MODELO DE SUPOSTA SOLUÇÃO

- Aqui na solução utilizaremos a AWS, e de base vai iniciar pelo repositorio onde está a aplicação, caso tiver necessidade de criação de uma pipeline, utilizaremos o Jenkins para o CI (caso tiver alguma necessidade de criação de pipeline, fora isso, seguir normalmente).

- a AWS que dará total confiança e segurança para que a aplicação nunca seja indisponível, utilizaremos uma instância sob-demanda para utilziar apenas nas horas que utilizarão a aplicação, e sem necessidades de uso será desligada a instância para a economia.

- Implementação do nível fácil, poderá implantar de duas formas, utilizar com o Docker dentro do EC2 com toda a arquitetura da imagem com parte de segurança implementada e disponibilizar a aplicação, ou a aplicação local dentro da instância EC2 sem precisar fazer processos complexos e claro com toda a segurança conforme a imagem da arquitetura VPC, NAT GATEWAY etc...

<img src="./assets/architecture.png" style=" HEIGHT: 500px; LEFT: 400px"/>