# Cars_Detector
Repositório com o objetivo de aprender a como fazer um modelo de detecção de carros.

**OBS.**

Este projeto ainda está em desenvolvimento. O modelo ainda não consegue distinguir o que é um carro do que não é.

### Rodando Label Studio com docker

Tendo o docker instalado no computador, digite o seguinte comando no terminal:

```bash
docker-compose up -d
```

Após rodar o comando, o LabelStudio estará disponível no link http://localhost:8080.

**Login**

Para fazer login localmente, verifique as variáveis de ambientes "username" e "password" no arquivo *docker-compose.yml*.
