
# OBJETIVOS DO PROJETO 🎯

### Este projeto tem como objetivo a prática e conhecimento sobre phishing e alguns tópicos sobre redes de computadores e engenharia social.
### Este projeto é parte do curso [Cibersecurity](https://web.dio.me/track/formacao-cybersecurity) da [DIO](https://web.dio.me/home)

# FERRAMENTAS E SISTEMAS UTILIZADOS ⚙️

- ### O sistema operacional utilizado foi o *Kali Linux* instalado na Virtual Box
- ### A página escolhida para servir de isca foi o login do google
- ### Para realizar o phishing, foi utilizada a ferramenta *setoolkit* (social enginering toolkit)
  ![](https://th.bing.com/th/id/OIP.COUXZyZJUnhVjmXQOcWS3QHaIk?w=626&h=725&rs=1&pid=ImgDetMain)

# PASSO A PASSO📝

### Para realizar o phishing, eu utilizei o método *Website attack vectors* e a opção *Credential Harvester attack method*.
### Esta opção tem como objetivo coletar as informações que o próprio usuário inserir na página clonada, assim quando o usuário enviar os campos preenchidos, esta requisição POST será encaminhada para a minha máquina, e assim será realizado o ataque phishing. Considerando que a parte mais vulnerável de um sistema é o usuário, foi utilizado este tipo de ataque baseado em engenharia social. Lembrando que tudo é para fins educacionais.

# RESULTADO DO ATAQUE PHISHING📈

### Como mencionado anteriormente, a página que servirá de isca é o login de contas google. No exemplo a seguir eu inseri um email e senha fictício;
![](/img/model.png)

### Como podemos visualizar no exemplo a seguir, o email e senha inseridos pelo usuário, foi coletado e enviado para a minha máquina
![](/img/result.png)
