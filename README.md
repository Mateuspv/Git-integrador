# Git-integrador
Repositório utilizado na matéria de projeto integrador da faculdade
### Descricao do diretorio .git

>.git/config: É o arquivo de configuração que armazena as configurações específicas do usuário para o Git. Ele contém opções como o nome e email do usuário, configurações de formatação, alias, integração com ferramentas externas e outras personalizações.

>.git/description: É um arquivo de texto opcional que pode ser usado para fornecer uma descrição legível por humanos do repositório. Alguns serviços de hospedagem de código, como o GitWeb, usam esse arquivo para exibir uma descrição amigável do repositório.

>.git/HEAD: É um arquivo especial que contém uma referência para o ramo atual ou para um commit específico em que o repositório está posicionado. Ele é usado pelo Git para determinar em qual ramo ou commit o repositório está trabalhando no momento.

>.git/hooks/: É um diretório que contém uma série de arquivos de script chamados "hooks". Os hooks são scripts personalizáveis que são acionados automaticamente em resposta a eventos específicos do Git, permitindo que você personalize o comportamento do Git e automatize tarefas específicas.

>.git/index: É um arquivo binário que atua como uma área de preparação (staging area) para armazenar informações sobre os arquivos que serão incluídos no próximo commit. É usado para acompanhar as mudanças nos arquivos antes que elas sejam confirmadas.

>.git/info/: É um diretório que contém arquivos de configuração específicos do repositório. Alguns exemplos incluem exclude para especificar padrões de arquivos a serem excluídos e sparse-checkout para especificar quais arquivos e diretórios devem ser considerados no checkout.

>.git/logs/: É um diretório que armazena informações sobre as referências do repositório, como ramificações e HEAD, incluindo histórico de commits e alterações.

>.git/objects/: É um diretório que armazena os objetos do repositório Git. Os objetos são as unidades básicas de armazenamento do Git, incluindo blobs (conteúdo de arquivos), trees (estrutura de diretórios) e commits.

>.git/packed-refs: É um arquivo que armazena referências (ponteiros para commits ou objetos) em um formato compactado. É usado para otimizar o acesso a referências em repositórios grandes.

>.git/refs/: É um diretório que contém referências do repositório, como ramificações, tags e HEAD. Cada referência é armazenada em um arquivo separado dentro deste diretório.