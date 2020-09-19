Mudança no acesso ao comando gcloud
A chamada:

name: gcr.io/cloud-builders/gcloud
Mudou para:

name: 'gcr.io/google.com/cloudsdktool/cloud-sdk'
entrypoint: gcloud
Forma mais simples de acessar o comando Docker
Antes podíamos acessar o Docker somente por name: 'gcr.io/cloud-builders/docker', mas agora é possível acessar por name: 'docker'

​Acesso direto ao comando Docker Compose
Agora é possível invocar o comando docker-compose sem instalar uma imagem do mesmo como foi feito no curso. Basta fazer name: 'docker/compose'

Com estas mudanças você podem já adequar seus cloudbuild.yaml.

É isso aí, até a próxima.