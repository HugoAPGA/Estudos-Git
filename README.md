# meu-projeto

```
git init
```
- iniciar novo projeto com git

```
git add <nome-arquivo>/.
```
- add os arquivos que estão prontos para serem commitados

```
git commit -m "mensagem de commit"
```
- commit os arquivos no histórico

```
git log
```
- mostra os ultimos commit, log de alterações

```
git status
```
- como está o estado da nossa ramificação

```
git diff
```
- que mostra que foi alterado
- o que tem de alteração na ramificação

```
git merge
```
- merge de ramificações, mescla ramificações

```
git branch
```
- mostra a branch atual

```
git checkout <nome-branch>
```
- muda para essa branch

```
git branch -b <nome-da-branch>
```
- cria uma nova branch a partir do histórico da branch atual

```
git remote add <nome> <url>
```
- add um novo repositorio remoto

```
git push <nome> <nome-da-branch>
```
- manda nossas alterações locais para o repositório remoto, pra cada branch

```
git pull <nome> <nome-da-branch>
```
- pega as alterações do repositório remoto, e joga pra nossa máquina

```
git fetch
```
- atualiza o novo histórico local de acordo com o histórico salvo lá no repositório remoto
- sincronização do local com o remoto