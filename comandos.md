![Logo Git](https://media.licdn.com/dms/image/D4E12AQESXaHdHV-OMA/article-cover_image-shrink_720_1280/0/1697904028864?e=1726704000&v=beta&t=2A3lpt_6FKj8IJ9swBgycLCJWqE6X4liZs744kTQnX0)

### Inicializando o Git

- `git init` = inicializa um novo projeto com git
- `git add .` = adiciona todos os arquivos alterados para um estágio para commit
    - `git add nome_arquivo` = adiciona apenas para o arquivo específico
- `git commit -m “First Commit”` = mensagem do commit
- `git status` = mostra o status das atualizações atuais

---

### **Verifica as atualizações**

- `git log` = mostra todos os commits, log de alterações
- `git diff` = mostra a diferença entre o arquivo atual e o último commit realizado
- `git restore nome_arquivo` = restaura o estado do arquivo do último commit

---

### **Branches**

- `git branch` = mostra todas as branches e indica em qual você está
- `git checkout -b name-branch` = cria e muda para uma nova branch

---

- `git checkout master` = muda para a branch master
    - `git merge desenvolvimento` = mescla as alterações da branch desenvolvimento para a branch principal (master)

---

- `git checkout desenvolvimento`
    - `git merge master` = mescla as alterações da branch master para a branch desenvolvimento

---

### Trabalhando com repositório remoto

- `git remote add origin https://endereço.com/arquivo.git` = adiciona um repositório remoto
- `git push -u origin main` = envia as alterações locais para o repositório remoto e define a branch main como padrão para futuros pushes
- `git pull origin name-branch` = puxa as alterações do repositório remoto para a branch especificada localmente

---

- `git fetch` = sincroniza o local com o remoto, baixando todas as referências remotas, mas sem fazer merge
