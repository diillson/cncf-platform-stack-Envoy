<h1 align="center">Welcome to Cloud Native Computing Foundation Platform Stack 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-v0-blue.svg?cacheSeconds=2592000" />
  <a href="/" target="_blank">
    <img alt="Documentation" src="https://img.shields.io/badge/documentation-yes-brightgreen.svg" />
  </a>
  <a href="/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/fidelissauro" target="_blank">
    <img alt="Twitter: fidelissauro" src="https://img.shields.io/twitter/follow/fidelissauro.svg?style=social" />
  </a>
</p>

> Application Platform using only CNCF Stack

## Architecture

![dap](.github/assets/img/dap.png)

## Videos / Playlists

* [Playlist completa](https://www.youtube.com/playlist?list=PLsyPhquWMjqEBjY0neO8R7qGIRP0Kkwm3)

* [[CNCF Challenge] Cap. 1 - Intro](https://www.youtube.com/watch?v=pFstphlh5A8&list=PLsyPhquWMjqGk4yowFg-9vvpgwjZH_PBt&index=2&t=0s) - [Exemplos](https://github.com/msfidelis/cncf-platform-stack/tree/cap01_intro)

* [[CNCF Challenge] Cap. 2 - Commons](https://www.youtube.com/watch?v=rpHuIlN46zg&list=PLsyPhquWMjqFIP7jcBz52tqJpgRjuxDKo) - [Exemplos](https://github.com/msfidelis/cncf-platform-stack/tree/cap02_commons)

* [[CNCF Challenge] Cap. 3 - Harbor como Registry](https://www.youtube.com/watch?v=c-1Xw7TcrCs&list=PLsyPhquWMjqEdJHownusV1NMtCycZELEI) - [Exemplos](https://github.com/msfidelis/cncf-platform-stack/tree/cap03_harbor)

* [[CNCF Challenge] Cap. 4 - Kubernetes](https://www.youtube.com/watch?v=p4cUYARKlxA&list=PLsyPhquWMjqGKDaalHH-BAZjkLRT_hDvH) - [Exemplos](https://github.com/msfidelis/cncf-platform-stack/tree/cap04_k8s)

* [[CNCF Challenge] Cap. 5 - Contour Como Ingress Controller](https://www.youtube.com/playlist?list=PLsyPhquWMjqGN8d-ETwiw28p0xFfy9vJC) - [Exemplos](https://github.com/msfidelis/cncf-platform-stack/tree/cap05_contour)

* [[CNCF Challenge] Cap. 6 - Service Mesh com Linkerd](https://www.youtube.com/playlist?list=PLsyPhquWMjqGe0E8SiWh3Rv_B0lxwmL2O) - [Exemplos](https://github.com/msfidelis/cncf-platform-stack/tree/cap06_linkerd)

* [[CNCF Challenge] Cap. 7 - Cert-Manager no Kubernetes](https://www.youtube.com/playlist?list=PLsyPhquWMjqFlrDXS0_DUsUntOb0BADrh) - [Exemplos](https://github.com/msfidelis/cncf-platform-stack/tree/cap07_cert_manager)

* [[CNCF Challenge] Cap. 8 - Front Proxy com Envoy](https://www.youtube.com/playlist?list=PLsyPhquWMjqE7g-cebsM0vfOQaF9CJJx_) - [Exemplos](https://github.com/msfidelis/cncf-platform-stack/tree/cap08_front_proxy)

## Stack

| Component                 | Project / Technology                      |
| --------------------------|-------------------------------------------|
| Automation Tool           | [Ansible](https://www.ansible.com)        |
| Container runtime         | [Docker](https://www.docker.com)          |
| Container orchestration   | [Kubernetes](https://kubernetes.io)       |
| Registry                  | [Harbor](https://goharbor.io)             |
| Ingress Controller        | [Contour](https://projectcontour.io)      |
| Service Mesh              | [Linkerd](https://linkerd.io)             |
| HTTPS Certs Manager       | [cert-manager](https://cert-manager.io/)  |
| Front Proxy               | [Envoy Proxy](https://www.envoyproxy.io)  |

### 🏠 [Homepage](/)

### ✨ [Demo](/)

## Referencias

* O Formato deste curso é baseado totalmente na didática  do [curso de Golang](https://www.youtube.com/watch?v=WiGU_ZB-u0w&list=PLCKpcjBB_VlBsxJ9IseNxFllf-UFEXOdg) da Ellen Körbes

* [Home da CNCF](https://www.cncf.io)
* [Projetos da CNCF](https://www.cncf.io/projects)
* [Docs do Harbor](https://goharbor.io/docs/1.10/)
* [Certbot](https://certbot.eff.org/docs/)
* [Docs Clair](https://github.com/quay/clair/tree/master/Documentation)
* [Algoritmos de Load Balancing do Envoy](https://www.envoyproxy.io/docs/envoy/latest/intro/arch_overview/upstream/load_balancing/load_balancers)
* [Repositório com exemplos de uso do Envoy](https://github.com/msfidelis/envoy-proxy-examples) 

## Microserviços utilizados na aula pra testes

* [Whois Microservice](https://github.com/msfidelis/microservice-nadave-whois)
* [Faker Person Generator Microservice](https://github.com/msfidelis/microservice-nadave-fake-person)
* [Chip](https://github.com/msfidelis/chip)

## Install

```sh
git clone $
```

## Usage

### Harbor Setup 

```sh
ansible-playbook -i harbor-playbook.yml
```

### Kubernetes Setup

```sh
ansible-playbook -i kubernetes-playbook.yml
```

### Front Proxy Setup

```sh
ansible-playbook -i front-proxy-playbook.yml
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](/issues). 

## Show your support

Give a ⭐️ if this project helped you!


***