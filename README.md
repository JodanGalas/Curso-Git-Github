# A interface
Para o desenvolvimento do produto(aplicação desktop) do Auxílio Emergencial Positivo foram utilizados diversos recursos de Python, sendo o principal deles o Tkinter (biblioteca de interface gráfica padrão). Com o Tkinter, foram produzidas três diferentes telas, simples e funcionais, as quais se interligam por meio de botões. Outros recursos foram utilizados para funções específicas (Pandas, Messagebox, Filedialog, Datetime, Xlrd).

### Tela de início

Logo ao abrir o aplicativo, é exibida a tela de início, a qual contém um banner com o título, e botões com as opções “Começar”, “Ajuda” e “Sair”.

* Botão Começar: guia o funcionário para a tela de verificação;
* Botão Ajuda: guia o funcionário para a tela de ajuda;
* Botão Sair: fecha o aplicativo.

### Tela de Ajuda

Nesta tela são exibidas instruções em passo a passo, a fim de esclarecer qualquer dúvida que o funcionário que estiver utilizando a ferramenta possa ter. Para retornar para a Tela de Início, basta clicar no botão “Voltar”.

### Tela de Verificação
Esta é a tela em que o processo de inclusão no Auxílio Emergencial Positivo ocorre. Os botões “Verificar”, “Limpar”, “Selecionar” e “Concluir”, juntamente com os RadioButtons de situações emergenciais e a TextBox de inserção de CPF, fornecem o suporte necessário para que o processo ocorra:

* TextBox do CPF: área onde deve ser inserido o CPF da pessoa que solicitou a inclusão;
* Botão Verificar: analisa o CPF inserido e, caso este seja válido, dispara o comando de **exibição do histórico de pagamentos e do status** do respectivo consumidor;
* Botão Selecionar: abre uma tela de busca no Windows Explorer para que o documento comprobatório seja selecionado;
* RadioButtons de Situações Emergenciais: permite que o motivo da solicitação seja selecionado;
* Botão Concluir: realiza a operação de inclusão no Auxílio Emergencial Positivo caso todos os campos estejam preenchidos e o consumidor em questão seja apto;
* Botão Limpar: limpa tudo o que foi inserido para que uma nova consulta possa ser feita.

Além destas funcionalidades, há o botão “Voltar”, que retorna para a Tela de Início.

### Exibição do Histórico de Pagamentos e do Status

Feita a raspagem e análise de dados dos arquivos recebidos, é gerada uma Tabela única, a qual serve como uma Base de Dados para a aplicação. Através da consulta dessa tabela, os pagamentos a serem exibidos são selecionados e o status é definido.

# Manual de Instalação

Não é necessário nenhum recurso para executar a aplicação. Basta seguir os seguintes passos:
* Fazer o download da pasta que contém o arquivo.exe, o ícone, o arquivo.xlsx e a pasta de imagens;
* Descompactar a pasta compactada “Auxílio Emergencial Positivo.rar”;
* Entrar na pasta “Auxílio Emergencial Positivo” e clicar duas vezes no arquivo “AEP.exe”.











