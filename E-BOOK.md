## **DevOps Chronicles: The Chaos Quest**

---

### **Página 1: O Chamado à Aventura**  

A sala de TI era um relicário de tecnologias esquecidas: servidores com LEDs piscando descontroladamente, cabos amontoados como serpentes adormecidas, e uma estante cheia de manuais de Windows NT. Henrique, o novo gerente de TI, entrou com energia. 

"Time, atenção! Nosso objetivo é épico: migrar toda a infraestrutura do Windows Server para Kubernetes. Tudo on-prem. Sem budget. Temos 30 dias."

Marco, o técnico de suporte, ergueu a mão. "Kuber o quê? Isso é tipo um vírus?"  
Luana, a desenvolvedora, digitava nervosamente: "Posso rodar isso no Visual Studio?"  
Carlos, o analista de infraestrutura, resmungou: "Isso é modinha, não vai rodar no meu cluster de VMs."

Henrique olhou para Tatiane, a líder de TI, que apenas suspirou: "Vamos precisar de café... muito café."

> **Ilustração**: Uma sala cheia de servidores antigos, post-its espalhados e um quadro branco com a palavra "Kubernetes" cercada de interrogações e desenhos de dragões.

---

### **Página 2: A Jornada Começa**

Henrique distribuiu papéis com títulos: **Mestre do YAML** (Luana), **Guardião do Etcd** (Carlos), **Caçador de Logs** (Marco), e **Comandante de Cluster** (Tatiane). 

Luana, encarregada dos containers, exclamou: "YAML é tipo JSON com poesia? Isso aqui quebra por falta de espaço?"  

Enquanto isso, Carlos tentava instalar o Kubernetes no hardware legado. "Esse servidor tem 2 GB de RAM. Isso é suficiente?" 

Marco, no suporte, tropeçou em um cabo e desligou metade do ambiente. "Ops. Isso era importante?"

Tatiane, segurando o riso, disse: "Time, foco! Primeiro aprendemos a criar um container simples. Depois enfrentamos o monstro do cluster."

> **Ilustração**: O time ao redor de uma mesa bagunçada, com papéis de RPG e um mapa desenhado com passos como "Criar Pods", "Configurar Etcd" e "Sobreviver à Instalação".

---

### **Página 3: O Monstro do Cluster**

Carlos configurava o Etcd enquanto resmungava: "Control Plane? Parece coisa de ficção científica."

Marco, tentando rodar seu primeiro comando, gritou: "Deu erro! E agora?"  
Luana leu calmamente: "A mensagem diz: `connection refused`. Isso significa... que estamos ferrados?"  

A equipe descobriu que o servidor principal estava usando uma versão obsoleta de Linux. "Essa coisa roda com kernel 2.6!" exclamou Carlos.

Depois de uma luta épica, com comandos falhando e soluções improvisadas, finalmente um pod estava ativo. O time vibrou como se tivesse derrotado um dragão. 

> **Ilustração**: Um terminal mostrando `kubectl get pods` com o status "Running", enquanto o time ergue as mãos em comemoração.

---

### **Página 4: O Ritual do CI/CD**

"Agora precisamos automatizar tudo," disse Henrique. Luana começou a configurar o Jenkins. "Isso é tipo montar um quebra-cabeça com peças que não encaixam." 

Marco aprendia a usar o `kubectl logs`. "Gente, esse comando é o meu novo melhor amigo!"  

Carlos, por outro lado, lutava para configurar volumes persistentes. "Por que nada nesse sistema aceita meus discos RAID? É sabotagem?"

Apesar dos desafios, o time conseguiu configurar um pipeline funcional. Jenkins rodava os deploys com sucesso. Tatiane, aliviada, murmurou: "Isso está começando a parecer mágica."

> **Ilustração**: Jenkins rodando um pipeline com luzes verdes e o time brindando com café.

---

### **Página 5: O Plot Twist Épico**

No dia da apresentação final, o sistema estava estável, a aplicação rodando, e o time orgulhoso. Henrique declarou: "Vocês são verdadeiros heróis do DevOps!"  

Mas então, a porta da sala se abriu. Um estagiário entrou correndo: "A energia caiu no servidor principal!"  

Desesperados, eles correram até o data center e descobriram que o no-break não estava funcionando. Carlos apontou: "Tem uma extensão de ferro-velho ligada aqui."

Tatiane suspirou e disse: "É por isso que ninguém nunca migra tudo de uma vez."

Eles improvisaram, conectaram tudo de volta, e finalmente, o sistema foi restaurado. Henrique riu. "A moral da história? Não importa o quão avançada seja a tecnologia, um cabo velho sempre pode arruinar seu dia."

> **Ilustração**: O time no data center, rindo nervosamente enquanto reconectam cabos em meio a servidores antigos.

---

**FIM**
