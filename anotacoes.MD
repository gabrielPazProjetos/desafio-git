#  Anotações sobre Git e GitHub

##  Conceitos Fundamentais

- **Git** é um sistema de controle de versões distribuído, criado por Linus Torvalds.
- **GitHub** é uma plataforma online que hospeda repositórios Git e facilita colaboração.
- Um **repositório** é onde o código e o histórico de versões são armazenados.
- **Commit** é uma “foto” do estado atual do projeto, com uma mensagem explicando a mudança.
- **Branch** é uma ramificação do projeto, usada para desenvolver funcionalidades sem afetar o código principal.

---

##  Branches

- `git branch` → Lista todas as branches.
- `git branch nome-da-branch` → Cria uma nova branch.
- `git checkout nome-da-branch` → Muda para outra branch.
- `git merge nome-da-branch` → Mescla uma branch com a atual.

---

##  Conectando ao GitHub

- `git remote add origin URL` → Conecta o repositório local ao GitHub.
- `git push -u origin main` → Envia a branch principal para o GitHub e define como padrão.

---

##  Boas Práticas

- Sempre escreva mensagens de commit claras e objetivas.
- Use branches para organizar o desenvolvimento de novas funcionalidades.
- Mantenha o `README.md` atualizado para facilitar o entendimento do projeto.
- Faça commits frequentes para registrar o progresso.

---

##  Extras

- `.gitignore` → Arquivo que define quais arquivos o Git deve