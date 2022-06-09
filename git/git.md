# BASE DE CONHECIMENTO

*[HOME](../README.md)** > GIT > SOBRE

## **1. SOBRE**

O Git é uma ferramenta usada para versionamento de artefatos de software, assim como SVN e CVS.

Além disso o GIT permite integração entre repositórios, o que chamamos de **repósitorios distribuídos**, possibilitando manter uma cópia de um repositorio em repósitorios remotos.

### **1.1. TIPOS DE  REPOSITÓRIOS**

- **Local**: Mantém artefatos na maquina do usuário  que realiza gerenciamento dos artefatos.

- **Remoto (Upstream)**: Mantém a cópia do repositório local. Permite também que múltiplos repositórios sincronizem informações realizando procedimento de merge(mesclagem), gerando uma versão integra de um artefato gerenciado por múltiplos usuários.

## **2. COMANDOS**

### 2.1.1 CRIAR REPOSITORIO

- Iniciar repositorio: git init
  
  ```bash
  git init
  ```

  > :bulb: **INFO:** Este comando permite também reiniciar um repositório ja existente

- Clonar a partir de repositorio remoto: git clone
  
  ```bash
  git clone [url-do-repositorio]
  ```

## **3. REFERÊNCIAS**

- [git-scm.com](https://git-scm.com)
- [git-book](https://git-scm.com/book/pt-br/v2)

**[HOME](../README.md)** > SOBRE
