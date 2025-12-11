# Linux Essentials - Estudos de Linux

Bem-vindo ao material de estudo sobre **Linux Essentials**! Este repositório contém documentação para aprender os fundamentos do Linux de forma simples e prática.

## 📚 O que você vai aprender?

- 📁 **Estrutura de diretórios** - Como o Linux organiza seus arquivos
- 💻 **Comandos essenciais** - Ferramentas que você usa todos os dias
- 🔧 **Sistema de arquivos** - Como tudo funciona nos bastidores

---

## 📁 Arquivos de Estudo

Todos os arquivos estão na pasta `lab-linux-essentials/`:

| Arquivo | Descrição |
|---------|-----------|
| `lab-linux-essentials/linux-essentials.txt` | Explicação de cada diretório Linux |
| `lab-linux-essentials/linux-comandos.txt` | Referência dos principais comandos |
| `guia_500_comandos_Linux.pdf` | Guia completo com 500 comandos explicados |

---

## 🏠 Diretórios Linux - O Essencial

Linux organiza seus arquivos em pastas. Aqui estão as principais:

### Pastas Importantes para o Sistema

```
/bin      → Programas principais que você usa
/sbin     → Programas do administrador
/etc      → Configurações do sistema
/home     → Seus arquivos pessoais
/root     → Arquivos do super usuário (admin)
/tmp      → Arquivos temporários
```

### Pastas do Sistema

```
/boot     → Arquivos para iniciar o computador
/dev      → Dispositivos (disco, mouse, teclado...)
/lib      → Bibliotecas que os programas precisam
/proc     → Informações sobre processos rodando
/var      → Arquivos que mudam (logs, emails...)
```

### Pastas de Programas

```
/usr      → Programas e dados do usuário
/opt      → Programas instalados manualmente
/mnt      → Pastas montadas temporariamente
/media    → Pen-drives, DVDs, etc
```

---

## 💡 Dica de Estudo

> **Pense em Linux como uma biblioteca:**
> - Cada pasta `/` é um corredor
> - Cada arquivo é um livro
> - O caminho completo é o "endereço" do livro

Por exemplo: `/home/usuario/documentos/carta.txt` quer dizer:
- Comece na raiz `/`
- Vá para pasta `home`
- Entre na pasta `usuario`
- Procure a pasta `documentos`
- Abra o arquivo `carta.txt`

---

## 🎯 Como Usar Este Material

### Para Iniciantes

1. Comece lendo sobre os **diretórios principais** (seção acima)
2. Abra um terminal e explore: `ls -la /`
3. Consulte `lab-linux-essentials/linux-comandos.txt` para aprender novos comandos

### Para Praticar

1. Abra `lab-linux-essentials/linux-essentials.txt` para entender os diretórios
2. Tente explorar cada diretório mencionado no seu terminal
3. Use `man comando` ou `comando --help` para mais detalhes

### Para Consultar Rápido

1. Procure em `lab-linux-essentials/linux-comandos.txt` o comando que precisa
2. Veja a explicação e o exemplo
3. Adapte para sua necessidade

---

## 📖 Tópicos Importantes

### 1️⃣ Estrutura de Diretórios
A forma como o Linux organiza os arquivos é padronizada (FHS). Todos os sistemas Linux seguem este padrão, então o que você aprende funciona em qualquer lugar.

### 2️⃣ Permissões de Arquivos
Cada arquivo tem permissões que controlam quem pode ler, escrever ou executar. Isso é fundamental para segurança.

### 3️⃣ Comandos Básicos
Você não precisa decorar todos os comandos. O importante é saber **onde procurar** e **como usar** o manual (`man`).

### 4️⃣ Terminal vs Interface Gráfica
O terminal é mais poderoso! Muitas coisas só podem ser feitas lá. Aprenda a se sentir confortável no terminal.

---

## 🚀 Primeiros Passos

Abra um terminal e tente estes comandos:

```bash
# Ver em que pasta você está
pwd

# Listar arquivos da pasta atual
ls -la

# Ver o conteúdo de um arquivo
cat /etc/hostname

# Obter ajuda sobre um comando
man ls

# Sair do manual (pressione 'q')
```

---

## 📝 Pequeno Glossário

| Termo | Significa |
|-------|-----------|
| **Terminal** | Programa para digitar comandos |
| **Shell** | Interpretador de comandos (bash, zsh...) |
| **Diretório** | Pasta que contém arquivos ou outras pastas |
| **Root** | Super usuário com permissão total |
| **Permissão** | Controle de acesso (ler, escrever, executar) |
| **Caminho** | Endereço completo de um arquivo ou pasta |

---

## ✅ Checklist de Aprendizado

Marque conforme aprende:

- [ ] Entendi a estrutura de diretórios `/bin`, `/home`, `/etc`
- [ ] Consigo navegar entre pastas com `cd`
- [ ] Sei listar arquivos com `ls`
- [ ] Entendo o que é caminho relativo e absoluto
- [ ] Consigo ler arquivos com `cat` ou `less`
- [ ] Entendo permissões de arquivos
- [ ] Consigo usar `man` para pedir ajuda
- [ ] Pratico regularmente no terminal

---

## 🎓 Próximos Passos

Depois de dominar o essencial:

1. Aprenda sobre **permissões e segurança**
2. Estude **gerenciamento de usuários**
3. Explore **scripts bash**
4. Trabalhe com **redes e conexões**
5. Configure **serviços do sistema**

---

## 📚 Referências

- **FHS Standard**: [Filesystem Hierarchy Standard](https://pt.wikipedia.org/wiki/Filesystem_Hierarchy_Standard)
- **GNU/Linux Brasil**: Material educativo em português
- **Manual oficial**: Use `man` no seu terminal!

---

## 💬 Dica Final

> O melhor jeito de aprender Linux é **praticando no terminal**.
> Não tenha medo de cometer erros - use máquinas virtuais ou ambientes de teste!

**Bom estudo! 🐧**
