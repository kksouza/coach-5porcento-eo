# Coach 5% · Shelters

Um coach de IA para preparar a ficha **Reflexões dos 5%** do Fórum da EO (Entrepreneurs' Organization).

Você fala solto, de preferência por voz, e o coach faz o papel de um par de Fórum: escuta, devolve a palavra que brilhou, pede a cena, corta o que é 90% e vai atrás do que ficou vazio. No fim, ele entrega a ficha preenchida **com as suas palavras**, pronta para imprimir.

> Projeto independente, feito por um membro para membros. **Não é material oficial da EO.** A estrutura da ficha é uma adaptação em português das worksheets de Forum Training (© Entrepreneurs' Organization).

---

## O que tem aqui

| Arquivo | Para que serve |
|---|---|
| `instrucoes-coach-5porcento.md` | As instruções do coach: postura, fases, modo questionário, fechamento. É o "cérebro" do agente. |
| `ficha-5porcento-template.html` | A ficha em branco. O coach preenche e devolve este arquivo. Abre em qualquer navegador e imprime em A4. |
| `README.md` | Este manual. |

---

## Como funciona a sessão

1. **Abertura.** O coach pede seu nome e a data do último encontro do Fórum. Depois faz uma única pergunta: *"O que está mais vivo em você?"*
2. **Garimpo.** Você fala; ele responde com **uma** pergunta por vez. Devolve a palavra carregada, pede a cena concreta, aponta quando é pensamento e não sentimento, ou quando é 90%.
3. **Varredura.** Quando o fluxo seca, ele mostra o placar da ficha (✅ preenchido / 🟡 raso / ⬜ vazio) e vai atrás dos buracos: casamento, filhos, pais, sócios, clientes, dinheiro, corpo, amizades, propósito…
4. **Manchetes e prioridade.** Ranking 1-2-3 entre Trabalho, Família e Pessoal e uma manchete de 3 a 5 palavras para cada área.
5. **Fecha a ficha.** Ele gera o arquivo `.html` preenchido e lista o que ficou raso ou vazio.

O coach **não dá conselho, não interpreta e não escreve a significância por você**. A ficha chega ao Fórum crua, para o grupo ressoar ao vivo.

### Comandos úteis

| Você digita | O que acontece |
|---|---|
| `Bora preencher minha ficha dos 5%` | Começa a sessão. |
| `Modo questionário` | Ele manda, numa mensagem só, a lista numerada do que falta. Você responde pelo número. Ótimo para quem está sem tempo. |
| `Fecha a ficha` | Gera a ficha final. |
| `Regras` | Se ele começar a interpretar ou fazer várias perguntas de uma vez, isto o coloca de volta nos trilhos. |

---

## Instalação

Escolha **um** dos caminhos. Todos usam os mesmos dois arquivos.

### Opção A — Plugin no ChatGPT (recomendada)

Precisa de plano pago do ChatGPT e uso no computador para criar (depois funciona também no celular).

1. Baixe este repositório: botão verde **Code → Download ZIP**, e descompacte.
2. No ChatGPT, vá em **Plugins → + → Criar plugin**. Abre o *Plugin Creator*.
3. Escreva: *"Crie um plugin chamado Coach 5% · Shelters, privado, para uso pessoal."*
4. Anexe os dois arquivos: `instrucoes-coach-5porcento.md` e `ficha-5porcento-template.html`. Diga: *"O .md são as instruções, use integralmente sem reescrever. O .html é o arquivo de conhecimento."*
5. Sugestões iniciais (o plugin aceita até 3): `Bora preencher minha ficha dos 5%`, `Modo questionário: me manda o que falta`, `Fecha a ficha`.
6. Confira a prévia que ele mostrar e aprove.

### Opção B — Projeto no ChatGPT ou no Claude

Funciona em qualquer plano que tenha **Projetos**.

1. Crie um projeto chamado *Coach 5% · Shelters*.
2. Cole o conteúdo de `instrucoes-coach-5porcento.md` nas **instruções do projeto**.
3. Suba `ficha-5porcento-template.html` como **arquivo do projeto**.
4. Abra um chat novo dentro do projeto a cada ficha e escreva *"Bora preencher minha ficha dos 5%"*.

### Opção C — Chat comum (sem instalar nada)

1. Abra um chat novo.
2. Anexe `ficha-5porcento-template.html`.
3. Cole todo o conteúdo de `instrucoes-coach-5porcento.md` como primeira mensagem e envie.

---

## Dicas de uso

- **Fale, não digite.** Use o **microfone do campo de texto** (ditado). A fala solta, com ida e volta, é o melhor material. Fale em blocos curtos: se despejar dez minutos de uma vez, ele escolhe um ponto e o resto se perde.
- **Evite o "modo voz" (conversa falada contínua)**, aquele em que a IA responde em áudio. Nele o coach tende a perder as regras e não gera o arquivo da ficha.
- **Um chat novo por ficha**, para não misturar uma semana com a outra.
- **Imprimir:** abra o `.html` no navegador → `Ctrl+P` / `Cmd+P` → Salvar como PDF ou imprimir. O layout já está em A4.
- Se ele devolver o código em vez do arquivo, copie o código, salve como `ficha.html` e abra no navegador.

---

## Confidencialidade

O que você fala na sessão é material de Fórum. Algumas recomendações:

- Desligue o uso das suas conversas para treinar modelos (ChatGPT: **Configurações → Controles de dados → "Melhorar o modelo para todos"**). Em plugins e GPTs há também a opção *"Use dados de conversas para aprimorar nossos modelos"* — deixe desmarcada.
- Não compartilhe o link da conversa nem a ficha preenchida fora do Fórum.
- Este repositório contém **só** as instruções e a ficha em branco. Nenhuma ficha preenchida deve ser enviada para cá.

---

## Contribuir

Sugestões de ajuste nas perguntas, nas fases ou na ficha são bem-vindas: abra uma *issue* ou um *pull request*. Mantenha o espírito: **sem conselho, sem interpretação, as palavras do membro.**
