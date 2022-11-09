# Comandos básicos para um bom desempenho no terminal
* *Criar novo repositório:* **git init**
* *Comitar um arquivo:* **git commit**
* *Criar uma pasta:* **mkdir**

[Para saber mais...](https://gist.github.com/leocomelli/2545add34e4fec21ec16)

# Tópicos fundamentais para entender o funcionamento do Git
### SHA-1
> SHA-1 é um tipo de criptografia com função hash criptográfica. Isso significa que a cada codificação, um novo hash é gerado. Esse tipo de método de codificação também é chamado de função de dispersão criptográfica.
Dessa forma, o SHA-1 é uma forma eficiente de identificar modificações em um arquivo.

### Objetos internos do Git
* Blobs
> * Possuem metadados
> * Bloco básico de composição
> * Não guarda o nome do arquivo, só o SHA-1

* Trees
> * Armazenam blobs
> * Guarda o nome do arquivo
> * Montar a estrutura de onde está localizado o arquivo

* Commits 
> * Commit aponta para um autor, para uma mensagem, etc
> * Se alterar o SHA da blob, altera o da árvore e consequentemente no commit

### Chave SSH e Token
* **CHAVE SSH:** Forma segura e encriptada de estabelecer uma conexão entre duas máquinas
* **TOKEN:** Substitui a senha
