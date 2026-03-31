### 🎯 Phishing Controlado com Kali Linux e SEToolkit

Laboratório educacional para simular um ataque de phishing em ambiente **controlado**, utilizando Kali Linux e a ferramenta SEToolkit. Projeto desenvolvido como parte de um desafio de cibersegurança da DIO.

> ⚠️ **Aviso de Responsabilidade**  
> Este projeto é estritamente para fins educacionais e de pesquisa em segurança.  
> É proibido utilizar as técnicas demonstradas aqui contra sistemas, contas ou redes de terceiros sem autorização explícita e por escrito.  
> O autor não se responsabiliza por qualquer uso indevido deste conteúdo.

## 🎯 Objetivo do Projeto

- Demonstrar, em ambiente controlado, como um ataque de phishing pode ser montado com o SEToolkit no Kali Linux.
- Documentar passo a passo o raciocínio técnico, configuração do laboratório e evidências da captura de credenciais de teste.
- Reforçar boas práticas de segurança e conscientização sobre engenharia social.

## 🛠️ Tecnologias Utilizadas

- **Kali Linux** para geração da página de phishing
- **SEToolkit (Social-Engineer Toolkit)** pré-instalado no Kali
- **Git e GitHub** para versionamento e publicação da documentação
- **Google Chrome** para simular o usuário alvo
- **VirtualBox** para execução do Kali em máquina virtual

## 🧪 Cenário de Laboratório

- Máquina atacante: Kali Linux executando o SEToolkit.
- Máquina vítima: navegador acessando o IP do Kali em rede controlada.
- Todo o teste é feito apenas em ambiente autorizado.

## 📸 Evidências (prints)

As evidências do laboratório serão organizadas na pasta `images/`, incluindo:
- Execução do SEToolkit no terminal.
- Página de phishing carregada no navegador.
- Captura de credenciais de teste no console do SET.
