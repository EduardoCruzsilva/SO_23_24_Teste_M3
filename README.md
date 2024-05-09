# Teste de Sistemas Operativos - Módulo 3

Faz *fork* do repositório para teres a tua cópia.

Preenche o ficheiro README diretamente no GitHub. A partir da página principal do repositório, clica em "Edit File" (ícone representando um lápis).

Escreve as respostas dentro dos blocos correspondentes. Substitui as reticências pelo que é pedido em cada pergunta. Não desformates o documento.

Quando acabares, carrega no botão "Commit Changes".

## Informação do aluno

    Nome: Eduardo Fernandes

## P1 - Para as seguintes questões, assinala a opção correta: (2.5v)

  1. Qual das seguintes afirmações caracteriza melhor um SO servidor?

    a) Projetado para computação de uso geral
    b) Otimizado para alta disponibilidade e confiabilidade
    c) Destinado a usuários individuais
    d) Usado principalmente para jogos
    
    Resposta: B

  2. Das seguintes, qual é a função mais apropriada para um SO servidor?

    a) Executar aplicações de desktop
    b) Desenvolver aplicações móveis
    c) Fornecer software de entretenimento
    d) Gerir recursos e serviços de rede
    
    Resposta: D
   
  3. Qual dos seguintes é um sistema operativo servidor popular?

    a) Windows 11
    b) macOS Big Sur
    c) Ubuntu Server
    d) Android
    
    Resposta: c

  4. Qual é o papel de um servidor num modelo cliente-servidor?

    a) Consumir recursos fornecidos pelos clientes
    b) Fornecer recursos e serviços aos clientes
    c) Atuar como uma estação de trabalho independente
    d) Facilitar a comunicação ponto a ponto
    
    Resposta: B

  5. Qual dos seguintes protocolos é mais usado para aceder remotamente a servidores?

    a) FTP
    b) HTTP
    c) SSH
    d) SMTP
    
    Resposta: A

## P2 - Indica, sequencialmnente, os comandos para realizar as seguintes instruções: (7.5v)

  1. Cria um diretório com o nome "ex1", entra no mesmo, e cria 3 ficheiros vazios com os nomes "f1", "f2", "f3". No fim, lista os conteúdos do diretório atual.

    Resposta:
  mkdir ex1
  cd ex1
 touch f1 f2 f3
   ls
  2. Assumindo que estás no diretório "ex1", renomeia os ficheiros "f1" e "f2" para que acabem com "_antigo", e cria cópias dos mesmos.

    Resposta:
   mv f1 f1_antigo 
   mv f2 f2_antigo 
   cp f2_antigo
   cp f1_antigo 

  3. Assumindo que estás no diretório "ex1", cria o diretório "ex2", e move os ficheiros copiados no exercício anterior para o novo diretório. Seguidamente, apaga os ficheiros originais.

    Resposta:
    mkdir ex2
    mv f1 f2 ex2/
    rm f1_antigo f2_antigo

  4. Atualiza os repositórios de *packages* para garantir acesso às *packages* mais recentes, e instala o serviço **htop**.

    Resposta:
sudo apt update
sudo apt install htop 

  5. Cria um novo utilizador com o teu primeiro nome, e com o diretório "/home/nome_de_utilizador". Mostra a informação (ID) do utilizador criado.

    Resposta:
    

## P3 - Realiza os seguintes exercícios, com respostas detalhadas: (6v)

  1. Indica alguns aspetos que diferenciam um SO cliente de um SO servidor.

    Resposta:
   recursos e capacidade :
   cliente: suporte a multimidia e uma ampla gama de perifericos foco na experiencia do cliente final 
   servidor: otimizado para alta carga de trabalho com suporte a grades quantidades de memoria, armazenamento e processamento
   Segurança:
   cliente: medidas de seguranças basicas focadas na proteçao contra malwere e acessos nao autorizados 
   servidor: segurana robusta com firewalls, sistemas de detecção de intrusao e politicas de restrito acesso 
     
  2. Explica a importância de otimizar um sistema operativo servidor, com exemplos de técnicas para otimização.

    Resposta:
  a otmizaçao de um sistema operacional de servidor e essencial para melhorar a eficiencia, o desempnho e a segurança alem de garantir o uso eficaz dos recursos de hardware

  3. Descreve o processo de instalar e configurar um servidor web num SO servidor, incluindo as etapas necessárias.

    Resposta:

## P4 - Indica os comandos **git** para realizar as seguintes operações: (4v)

  1. Considera que estás no ramo 'master' de um repositório git criado localmente. Associa este repositório ao repositório remoto contido no url 'https://github.com/SO/OMeuRepositorioRemoto'. Altera o nome do ramo atual para 'main', e envia os *commits* já feitos localmente para o repositório remoto.

    Resposta:git romote add master https://github.com/SO/OMeuRepositorioRemoto
        git branch mester main
        

  2. Considera que estás na pasta raiz do teu repositório local, onde atualizaste um ficheiro de nome 'index.html'. Envia **apenas** esta atualização para o teu repositório remoto, com uma mensagem de commit apropriada.

    Resposta:
    git add index.html
    git commit -m Atualizção de ficheiro 
