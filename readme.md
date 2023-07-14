# Sendo aprovado para a CKA

### Overview sobre a prova

O exame Certified Kubernetes Administrator ( CKA ) testa conhecimentos, habilidades e as capacidades de um indivíduo de executar as tarefas exigidas por um administrador do Kubernetes.

### O que é e para que serve Kubernetes?

Kubernetes é uma plataforma de código aberto que permite gerenciar e orquestrar aplicativos em **contêineres** de forma eficiente, escalável e automatizada, facilitando a implantação e o gerenciamento de aplicações distribuídas.


### Pré requisitos não oficiais

- Linux é essencial, nada sofisticado ```cat, ls, rm, find, grep, awk```
- Bom, se o k8s é um gerenciador de containers, você tem que entender deles ```docker cri-o```. 
- Vim é o editor oficial do kubectl, profissionais serios não usam o nano.

### Sobre a prova

- À pontuação exigida para passar é 66.
- São entre 17 à 20 questões.
- 120 minutos de prova.
- Tem retake. 
- A prova custa: 395 dolares.
- Duas chances no simulado oficial: https://killer.sh/

### Topicos do exame: 

Você deve mostrar que entende os seguintes tópicos para passar no exame. Por trás do assunto, há uma porcentagem que indica o peso do tópico no exame.
- Armazenamento ( 10% )
- Solução de problemas ( 30% )
- Cargas de trabalho e agendamento ( 15% )
- Arquitetura, instalação e configuração de cluster ( 25% ) 
- Serviços e redes ( 20% )
- [Curriculo da Prova](https://github.com/cncf/curriculum/blob/master/CKA_Curriculum_v1.27.pdf)

### Minha preparação:

- [Curso do Mumshad](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests/)
- [Livro: Certified Kubernetes Administrator (CKA) Exam Guide](https://www.packtpub.com/product/certified-kubernetes-administrator-cka-exam-guide/9781803238265)
- [Simulados Kodekloud](https://kodekloud.com/topic/lab-cka-mock-exam-1/)
- [Documentacao Oficial](https://kubernetes.io/docs/)

O curso do Mumshad para mim é excelente, explica todos os topicos com detalhes. O livro entrou como um complemento dos assuntos que eu não entendia. O valor real veio nos simulados que acompanham o curso na kodekloud.

#### Killer.sh

Você recebe duas sessões gratuitas de simulador do Killer.sh ao comprar o exame. A cada sessão, você tem acesso de 36 horas a um cluster Kubernetes, onde precisa responder às 24 perguntas do exame.

Killer.sh afirma que o exame é mais desafiador do que o exame real. Eu concordo em partes. O nivel de dificuldade é o mesmo. A diferença é que o exame killer.sh tem 22 perguntas, enquanto no exame real, existem 17.

### Meu plano de estudos.

Comecei com o curso na udemy completei a primeira vez só assistindo e ignorando o que eu não sabia para me familiarizar com o conteudo, fiz o curso pela segunda vez e só passava para o proximo modulo quando tivesse total domininio do conteudo, usei o livro como material de apoio, nas duas vezes fiz todos os laboratorios. Quando terminei, pratiquei os exames simulados incluídos várias vezes no KodeKloud. Eu os pratiquei até conseguir 100% e terminar a tempo.

Após o curso, iniciei a primeira simulação do Killer.sh, respondi todas as perguntas, as primeiras vezes foram horriveis, mas continuei praticando até terminar o simulado a tempo e passar. A simulação Killer.sh usa quase o mesmo ambiente que o exame real. Ele também usa uma área de trabalho remota na qual você pode iniciar um terminal e um navegador.

Estudei as soluções do Killer.sh e reiterei os tópicos no curso Udemy e apostila.

Fiz o exame e passei.


### A Prova

Você faz o exame respondendo perguntas sobre cenários executados em alguns
clusters do Kubernetes. Com esta nova versão, você usa o navegador PSI seguro, que o conecta a uma área de trabalho remota com o Ubuntu.

Você executa as tarefas usando o terminal que pode iniciar através da área de trabalho remota. Você pode acessar a documentação do Kubernetes através de um navegador da web no sistema e navegar no site do Kubernetes.

Algumas pessoas relataram atraso ao usar a área de trabalho remota. Eu não tive essa experiência. A área de trabalho remota reagiu rapidamente e o uso do terminal e do navegador remoto funcionou sem problemas.

O exame é difícil? Acho que sim. Qualquer pessoa com experiência com Kubernetes deve ser capaz de responder a todas as perguntas. Você tem permissão para usar a documentação do Kubernetes.

Não posso divulgar nenhuma das perguntas por causa da NDA, mas posso dizer que se você puder responder a todas as perguntas do Killer.sh dentro de duas horas, você está em um bom lugar para o exame.

O problema é a hora. Você tem duas horas. Parece muito tempo, mas não é. Para passar neste exame, você deve ser rápido no terminal usando kubectl. Você não tem tempo suficiente para pesquisar a resposta de cada pergunta na documentação do Kubernetes.

