# 🐞 Como reportar bugs no Aratiê OS

Reportar bugs é uma das formas **mais importantes** de contribuir com o Aratiê OS ❤️  
Mesmo que você não programe, sua ajuda pode evitar problemas para outras pessoas e melhorar a qualidade do sistema.

Este tutorial explica **como identificar, coletar informações e reportar um bug corretamente**.

---

## 📌 O que é um bug?

Um bug é qualquer comportamento inesperado do sistema, como por exemplo:

- Um programa que fecha sozinho
- Um comando que retorna erro sem explicação clara
- Algo que funcionava antes e parou de funcionar
- Problemas de desempenho, travamentos ou falhas gráficas
- Configurações que não são aplicadas corretamente

Se você **ficou em dúvida se é um bug**, provavelmente vale a pena reportar 😉

---

## ✅ Antes de reportar

Antes de abrir um novo relatório, verifique:

1. 🔍 **Se o bug já não foi reportado**
   - Procure nos [issues do repositório do Aratiê OS](https://github.com/aratie-os/.github/issues)
   - Veja a categoria "[Correções de bugs e problemas](categorias/bugs)" no blog

2. 🔄 **Se o sistema está atualizado (digite no menu de aplicativos)**
   ```bash
   aratie-update
   ```

3. 🧪 **Se o problema acontece novamente**
   - Reinicie o sistema
   - Repita os passos que causaram o erro

Se o problema persistir, siga para o próximo passo.

---

## 🧾 Informações importantes para incluir

Quanto mais informações você fornecer, **mais fácil será corrigir o bug**.

Tente incluir sempre:

### 📦 Informações do sistema

Digite no menu de aplicativos

```bash
aratie-report
```

---

### 🔁 Passos para reproduzir o problema

Explique **passo a passo**, por exemplo:

1. Iniciei o sistema
2. Abri o terminal
3. Executei o comando \`xyz\`
4. O erro aconteceu

Mesmo que pareça óbvio, quanto mais detalhado melhor, então escreva, pedimos que use as suas palavras, não use IA para "melhorar o texto" 😊

---

### ❌ Resultado esperado vs resultado atual

- ✅ **Resultado esperado:** o que deveria acontecer
- ❌ **Resultado atual:** o que realmente aconteceu

Exemplo:  
> Esperava que o programa abrisse normalmente, mas ele fecha imediatamente com erro.

---

### 📄 Logs e mensagens de erro

Se houver mensagens de erro, **copie e cole exatamente como aparecem**.

Comandos úteis:

```bash
journalctl -xe
dmesg
```

Se o log for grande, você pode:
- Colocar apenas a parte relevante
- Usar um serviço de paste (se indicado pela equipe)

---

## 🧠 Dicas importantes

- ❗ **Nunca esconda erros**: mensagens estranhas ajudam
- ❌ Não diga apenas “não funciona”
- 📷 Prints de tela são bem-vindos (quando aplicável)
- 🧘 Seja paciente — o projeto está em desenvolvimento ativo

---

## 📬 Onde reportar bugs

Você pode reportar bugs por:

- 🐙 [**GitHub Issues** (recomendado e gratuito)](https://github.com/aratie-os/aratie-os.github.io/issues/new)
- 💬 Comunidade / canais oficiais de suporte pago do projeto
- 📄 Posts documentados, se você for membro da equipe

👉 Sempre use um **título claro**, por exemplo:  
> “Erro ao iniciar o serviço de rede após atualização”

---

## 🏷️ Modelo simples de relatório de bug

Você pode copiar este modelo:

```
Descrição:
[Explique o problema]

Passos para reproduzir:
1.
2.
3.

Resultado esperado:
[O que deveria acontecer]

Resultado atual:
[O que acontece]

Informações do sistema:
- Aratiê OS:
- Kernel:
- Arquitetura:
- Ambiente gráfico:

Logs:
[Se houver]
```

---

## 💙 Obrigado por contribuir

Cada bug reportado ajuda o Aratiê OS a ser:

- Mais estável
- Mais acessível
- Mais confiável para todos

Mesmo pequenos problemas fazem diferença.  
Obrigado por fazer parte do projeto 🐧✨
