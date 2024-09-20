# Dummy Express
<a href="https://bit.ly/penpot-dummy-express">https://bit.ly/penpot-dummy-express</a>

# Repositórios
- [TODOS](https://github.com/orgs/gt-05/repositories)
- [GRUPO 01](https://github.com/gt-05/grupo-01)
- [GRUPO 02](https://github.com/gt-05/grupo-02)
- [GRUPO 03](https://github.com/gt-05/grupo-03)
- [GRUPO 04](https://github.com/gt-05/grupo-04)

# Sites para QA
- GRUPO 01 - [https://gt-05.github.io/grupo-01/](https://gt-05.github.io/grupo-01/)
- GRUPO 02 - [https://gt-05.github.io/grupo-02/](https://gt-05.github.io/grupo-02/)
- GRUPO 03 - [https://gt-05.github.io/grupo-03/](https://gt-05.github.io/grupo-03/)
- GRUPO 04 - [https://gt-05.github.io/grupo-04/](https://gt-05.github.io/grupo-04/)

# Quadros de tarefas
- GRUPO 01 - [https://github.com/orgs/gt-05/projects/17](https://github.com/orgs/gt-05/projects/17)
- GRUPO 02 - [https://github.com/orgs/gt-05/projects/14](https://github.com/orgs/gt-05/projects/14)
- GRUPO 03 - [https://github.com/orgs/gt-05/projects/19](https://github.com/orgs/gt-05/projects/19)
- GRUPO 04 - [https://github.com/orgs/gt-05/projects/16](https://github.com/orgs/gt-05/projects/16)

# Fluxo para resolver conflitos
```mermaid
graph TB
A1[Resolvendo conflito] -- Se o respositório já ta clonado --> A2[git checkout main]
A1 -- Se o repositório não ta clonado --> A3[git clone URL]
A2 --> B1[git pull]
B1 --> #1[git checkout branch-que-vai-para-main]
A3 --> #1
#1 --> C1[git merge main]
C1 -- Depois de resolver os arquivos conflitantes --> D1[git add .] 
D1 --> E1[git commit -m ''Mensagem'']
E1 --> F1((git push))
```

