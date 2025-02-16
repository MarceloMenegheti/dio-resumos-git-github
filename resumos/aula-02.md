# Resumo aula 02

## Comandos

| Comandos Básicos   | Descrição                           |
| :---------- | :---------------------------------- |
|`$ git clone `| Cria uma cópia local de um repositório remoto.|
|`$ git branch`| Lista todos os branches do repositório.|
| `$ git pull`| Atualiza o repositório local com as mudanças mais recentes do repositório remoto.|
| `$ git remote add origin` | Adiciona um novo repositório remoto.|
| `$ git reset --soft` | Desfaz commits, mas mantém as mudanças no "staging area". |
| `$ git reset --mixed` | Desfaz commits, remove as mudanças do "staging area", mas mantém no diretório de trabalho.|
| `$ git reset --hard` | Desfaz commits e descarta todas as mudanças locais é irreversível | 
|`$ git push`| O Git assume que você quer enviar o branch atual para o branch correspondente no repositório remoto. |
| `$ git push -u origin main ` | Isso envia o branch main do seu repositório local para o branch main no repositório remoto origin. |