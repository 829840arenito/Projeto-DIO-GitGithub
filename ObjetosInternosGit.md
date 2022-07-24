# Objetos Internos do Git #

### Blob - ###

Bloco básico de composição que armazena metadados e encapsula diretórios. Possui encriptação **SHA1**. 

### **Tree** - ###

Armazena **Blobs** e outras Trees  **além** de conter informações sobre os diretórios. Também possui encriptação. 

### Commits - ###

Armazena **Trees** com **Blobs**  e é o último objeto que guarda alterações. Carrega o nome do autor.



**SHA1** é uma encriptação de 40 caracteres gerados para cada **blob**, **tree** ou **commit** e alterações deles, tornando o Git extremamente seguro.

**Chave SSH** é uma autenticação que estabelece uma conexão segura entre 2 máquinas: servidor local e o do Git. Sempre com 2 chaves, uma local e uma pública, faz o GitHub "conhecer"  seu dispositivo.