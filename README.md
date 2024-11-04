# Testing Fitnesse
Projeto da disciplina de Teste de software do Programa de Pós Graduação em Informática Aplicada (PPGIA) na Universidade Federal Rural de Pernambuco (UFRPE)
**Objetivo:** Avaliação prática da ferramenta.

**Entregáveis:**
- [](Link para o documento de inspeção)

# Tutorial de instalação e configuração no windows 11
## 0. (Pré-requisito) É necessário ter o Java SDK 11 para funcionamento
- Verifique sua versão do Java. Abra o Prompt de Comando pressionano Win + S, digite cmd e pressione Enter.
Digite o seguinte comando para verificar a versão do Java instalada:
```bash
java -version
```
- Se a versão exibida não for a 11, ou se não houver nenhuma resposta, siga para o próximo passo para instalar o Java 11.
- Acesse a [https://www.oracle.com/java/technologies/javase/jdk11-archive-downloads.html](página) para baixar o Java 11.
- Baixe o _Windows x64 Installer_ e execute o arquivo .exe, seguindo os passos para instalação. Durante a instalação, presta atenção no local onde o Java está sendo instalado (pode copiar o caminho já).
- Configure as variáveis de ambiente para essa versão do Java:
 1. Abra o menu **Iniciar**, procure por **Variáveis de Ambiente** e selecione **Editar as variáveis de ambiente** do sistema.
 2. Na janela que abrir, clique em **Variáveis de Ambiente**.
 3. Em **Variáveis do Sistema**, clique em **Novo**... e adicione:  
    a. Para **nome da variável** ```JAVA_HOME```  
    b. **Valor da variável:** o caminho para o diretório do JDK 11 (por exemplo, C:\Program Files\Java\jdk-11).
 5. Clique em **OK**.
 6. Na lista de variáveis do sistema, selecione a variável _Path_ e clique em **Editar**.
 7. Adicione uma nova entrada: ```%JAVA_HOME%\bin```.
 8. Clique em OK para salvar.

## 1. Baixando o Fitnesse
- Baixe o jar em: [https://fitnesse.org/FitNesseDownload.html](fitnesse-standalone.jar)
- O Fitnesse É um wiki web server que não precisa de configuração e a instalação. Consiste em baixar um arquivo executável .jar que inicia um servidor que dá acesso ao site do Fitnesse.

## 2. Executando o fitnesse
1. vá no prompt de comando, e acesse a pasta que fez o download.
2. Digite "java -jar fitnesse-standalone.jar":
 - Por default, o Fitnesse usa a porta 80. Caso algum outro programa esteja usando, utilize o código "java -jar fitnesse-standalone.jar -p _[digite sua porta aqui]_* para definir uma porta personalizada.
3. Acesse o navegador com localhost:[suaPorta]

# Relatório de uso
