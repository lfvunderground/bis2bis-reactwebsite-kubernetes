# Projeto Kubernetes  HA (High Avaiability)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

![alt text for screen readers](https://github.com/jonathanbaraldi/devops/blob/master/rancher-kubernetes-producao.png?raw=true "Estrutura amazon AWS")

---
## AWS - Instâncias:
![alt text for screen readers](https://github.com/lfvunderground/bis2bis-reactwebsite-kubernetes/blob/homologation/img-grafana-outros.png?raw=true "Estrutura amazon AWS")

---
## AWS - Route53 (DNS):
![alt text for screen readers](https://github.com/lfvunderground/bis2bis-reactwebsite-kubernetes/blob/homologation/img-registros%20dns.png?raw=true "Estrutura amazon AWS")

---
## AWS - Security Groups:
![alt text for screen readers](https://github.com/lfvunderground/bis2bis-reactwebsite-kubernetes/blob/homologation/img-security%20groups.png?raw=true "Estrutura amazon AWS")

---
### Microserviço - Web (Imagem Docker):
Acesso em: https://www.homolog.vilit.com.br
Repositório GIT: https://github.com/lfvunderground/bis2bis-reactwebsite
Repositório Docker Hub: https://hub.docker.com/r/lucasvilarinof/bis2bis-reactwebsite/tags
* O projeto está configurado de uma forma em que todo commit na branch Master, dispara uma action do próprio github que cria/atualiza a imagem da aplicação direto no Docker Hub. Feito isso, uma TAG atualizada será criada em cima da imagem.

---
### Microserviço - Web (Kubernets):
Repositório: https://github.com/lfvunderground/bis2bis-reactwebsite-kubernetes
* Quando for feito uma nova versão da imagem, será necessária realizar um commit com a versão atualizada. Após esse commit, o Kubernetes irá reconhecer a alteração e aplicar no cluster.

---
### Monitoramento do Cluster Kubernetes:
![alt text for screen readers](https://github.com/lfvunderground/bis2bis-reactwebsite-kubernetes/blob/homologation/img-monitoramento-cluster.png?raw=true "Estrutura amazon AWS")

---
### Monitoramento do microserviço Web:
![alt text for screen readers](https://github.com/lfvunderground/bis2bis-reactwebsite-kubernetes/blob/homologation/img-grafana-pod1.png?raw=true "Estrutura amazon AWS")

---
### Outros tipos de monitoramentos:
![alt text for screen readers](https://github.com/lfvunderground/bis2bis-reactwebsite-kubernetes/blob/homologation/img-grafana-outros.png?raw=true "Estrutura amazon AWS")

---
## Extras:
* Cluster Rancher (3 instâncias) e Cluster Kubernetes (3 instâncias) criado em alta disponibilidade com escalabilidade na Amazon.
* Grupos de segurança criada visando reduzir riscos de ataques.
* Certbot instalado no servidor Proxy.
* Configurado auto limpeza do Cluster

 
