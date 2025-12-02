# 👨‍💻 Thiago Martins
> Desenvolvedor Full-Stack | Estudante de Desenvolvimento de Software Multiplataforma (FATEC) | Estudante Alpha EdTEch
>
> 📍 São José dos Campos, SP | 🎂 20 anos

Bem-vindo ao meu espaço de anotações e portfólio. Aqui eu compartilho o que estou aprendendo na Alpha Edtech e em meus projetos pessoais.

## 🔹 Sobre Mim
Sou apaixonado por tecnologia e inovação. Atualmente, atuo como Desenvolvedor Full-Stack em duas empresas.
* **Interesses:** Linux Mint, Python, Docker, HTML e Robótica (Ex-competidor FRC internacional).
* **Conquistas:** Medalhista de prata na OBA, Hackathons e participante do LALA (Latin American Leadership Academy).
* **Projetos Recentes:** *Caronna* (App de caronas universitárias), *Gaia* (Monitoramento climático).

---

# 🔹 Anotações de Estudo: Redes de Computadores

### 🔹 Conceitos Fundamentais
Uma rede de computadores permite que dispositivos se comuniquem e compartilhem recursos (arquivos, impressoras, internet).
* **Topologia:** É o "mapa" da rede.
    * *Estrela:* Conectada a um ponto central.
    * *Malha:* Alta redundância, mas complexa.
* **Protocolos:** Regras que permitem a "conversa" padronizada entre dispositivos.

### 🔹 Endereçamento IP e Sub-redes
* **IPv4:** 4 números decimais (octetos). Ex: `192.168.0.1`. (Esgotando).
    * *Classe C Privada:* `192.168.0.0` a `192.168.255.255`.
* **IPv6:** Nova geração, 128 bits, virtualmente ilimitado.
* **Máscaras de Sub-rede:** Filtro que separa a **Rede** (bits 1) dos **Dispositivos** (bits 0).
* **Portas:** Identificam serviços (1 a 65535).
    * `Porta 80`: HTTP
    * `Porta 443`: HTTPS
    * `Porta 25`: SMTP

### 🔹 Tipos de Protocolos
| Categoria | Função | Exemplos |
| :--- | :--- | :--- |
| **Rede** | Encaminhar pacotes | IP |
| **Transporte** | Gerenciar comunicação | **TCP** (Confiável, Web/Email)<br>**UDP** (Rápido, Streaming) |
| **Aplicação** | Tarefas do usuário | **HTTP** (Web), **FTP** (Arquivos) |

### 🔹 Evolução da Internet & Serviços Web
* **História:** Da ARPANET (anos 60) à Web 3.0 (Web Semântica).
* **APIs:** Regras para sistemas conversarem.
* **Arquitetura:**
    * **SOAP:** XML, rígido, corporativo.
    * **REST:** HTTP, leve, flexível (usado em apps modernos).
    * **Microsserviços:** Divide a aplicação em partes independentes.

### 🔹 Segurança e Análise
* **Diagnóstico:** `Ping` (latência) e `Traceroute` (rota dos pacotes).
* **Proteção:**
    * **SSL/TLS:** Criptografia de dados.
    * **Firewall:** Filtro de tráfego.
* **LGPD:** Lei brasileira sobre privacidade e tratamento de dados.

---

# 🔹 Git & GitHub: O Básico

Para manter este site e meus códigos organizados, utilizo Git e GitHub. Aqui estão os conceitos essenciais:

### 🔹 1. O que é o que?
* **Git:** O sistema de controle de versão que roda no meu computador (local). É a "máquina do tempo" do código.
* **GitHub:** A plataforma na nuvem que hospeda os repositórios Git e permite colaboração.

### 🔹 2. Comandos Essenciais
* `git init`: Inicia um novo repositório em uma pasta.
* `git add .`: Prepara todos os arquivos modificados para serem salvos.
* `git commit -m "mensagem"`: Salva a versão atual com um comentário explicativo.
* `git push`: Envia as alterações do computador para o GitHub.
* `git pull`: Puxa as alterações do GitHub para o computador.

### 🔹 3. Conceitos de Fluxo
* **Repository (Repositório):** A pasta do projeto.
* **Branch (Ramificação):** Uma linha do tempo paralela para testar novidades sem quebrar o código principal (`main`).
* **Merge:** O ato de fundir uma branch na outra.
* **Pull Request (PR):** Um pedido para fundir código, permitindo revisão antes da aprovação.

---
*Última atualização: Dezembro de 2025*
