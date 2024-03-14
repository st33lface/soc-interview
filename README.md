## Security Operation Control Interview - CRDC
##### Your goal will be to protect our company while we empower our customers.
&nbsp;
![CRDC](/images/logo-rodape.png "CRDC - Central de Registro de Direitos Creditórios")

## About the test 


- First of all, remember that you can use any technology to help you solve the problems. We're here just to challenge you to think.
- Don't be afraid of finishing the test on time. Take care to explain your mindset and ask us anytime you want. 
- We won't give you the answers, but we'll help you through the path.
- Anytime you want, take a deep breath and drink a couple of sips of water
- At the end of the test, you must commit your changes and push it to our repository.

 
# Requirements
- Install Git and Github CLI
 
Linux (Ubuntu based)
```sh
sudo apt update && sudo apt install git
```
```sh
sudo apt install gh
```
Windows
```sh
winget install -e --id Git.Git
```
```sh
winget install github.cli
```
- Configure Github CLI to be able to clone our repository
```sh
gh auth login
```
select github.com and hit enter 
```sh
What account do you want to log into? GitHub.com
```
select SSH and hit enter 
```sh
What is your preferred protocol for Git operations on this host? SSH
```
hit enter
```sh
Generate a new SSH key to add to your GitHub account? Yes
```
hit enter
```sh
Enter a passphrase for your new SSH key (Optional)
```
hit enter
```sh
Title for your SSH key: GitHub CLI
```
select Login with a web browser and login to your account 
```sh
How would you like to authenticate GitHub CLI? Login with a web browser
```

- Clone the following repository

```sh
git clone https://github.com/claytonpiccinin/soc-interview && cd soc-interview
```

# Challenge 

Let's start thinking about the problem. We suffered an attack 😧, and we're trying to understand step by step what happened.
Your goal here, is to help us to understand. 

Read carefully and analyze these events: 

A - Abra o arquivo json Archive1 e analise: Falso - Positivo

 1 - Encontre a família de amostras maliciosas.
 R: PassShow

 2 - Encontre o nome do host
 R: crdcnb121

 3 - Encontre o nome de usuário.
 R: ViniciusValerio

 4 - Encontre a data (mm/dd/year). 
 R: 2024-03-07    

 5 - O que você deve fazer para realizar a contenção?
 R: Como a detecção foi marcada como "Prevented", a contenção já foi realizada com sucesso neste caso. 

 6 - O que você acha do comportamento desse evento? Isso e verdadeiro ou falso?
 R: comportamento do evento parece verdadeiro, pois mostra a detecção e prevenção de um software potencialmente indesejado.

 7 - Quais são os hashes de evidências do arquivo?
• SHA1: 73f8e5c17b49b9f2703fed59cc2be77239e904f7
• SHA256: c41216eee9756a1dcc546df4fe97defc05513eed64ce6ac05f1501b50e6f96cc


B - Abra o arquivo json Archive2 e analise: Falso - Falso 

1 - Encontre o usuário envolvido neste evento.
User: andre.oliveira@crdc.com.br

 
2 - Encontre todos os IPs e escreva sobre eles.
 
Ips:     168.196.40.82
         189.57.104.170
         200.170.138.149


3 – O que um hacker poderia fazer dentro desta rede?
R: O Hacker poderia utilizar o acesso para realizar diversos tipos de ataques cybernéticos, Violar politícas e padrões de segurança, escalar previlêngios até instalar softwares maliciosos que podem comprometer toda a operação.


4 - 4 - O que você acha do comportamento desse evento? O que poderia ter acontecido aqui? Isso e verdadeiro ou falso?
R: O comportamento do evento parece verdadeiro, pois mostra a detecção de um usuário credenciado porém em outra localidade com alguns ip's divergentes 

C - Resposta a Incidentes

1 - O que você entende por Resposta a Incidentes?
R:  É o processo que descreve como uma organização deverá lidar com um incidente de segurança seja ele: 
    *  Um ataque Cybernético 
    *  Uma violação de dados 
    *  A presença de um software malicioso como um vírus  
    
    
2 - Quais são as fases de Resposta a Incidentes?
     * Preparação
     * Detecção e Análise 
     * Contenção 
     * Investigação 
     * Comunicação   

3 - O que você entende por CSIRT (Computer Security Incident Response Team)?
R: É uma equipe responsável por lidar com incidentes de segurança cibernética em uma organização. Eles são encarregados de detectar, analisar e responder a ameaças de segurança, além de coordenar a resposta e recuperação após um incidente. 
          
4- Quais as diferenças entre dados pessoais e dados sensíveis?
R: Dados pessoais referem-se a informações que identificam ou podem identificar uma pessoa específica. Isso pode incluir coisas como nome, endereço, número de telefone, endereço de e-mail, número de identificação, etc.

R: Já os dados sensíveis são um subconjunto de dados pessoais que são considerados particularmente sensíveis ou privados.    Isso pode incluir informações como origem étnica ou racial, opiniões políticas, crenças religiosas, saúde física ou mental, informações biométricas, histórico criminal, etc.

 Em resumo, enquanto dados pessoais identificam uma pessoa, dados sensíveis são informações especialmente confidenciais ou íntimas sobre essa pessoa.

Boa sorte  :)
Valeu :)
 
