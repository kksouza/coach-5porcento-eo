# Política de privacidade e contribuição — Coach 5% · Shelters

> **REGRA INEGOCIÁVEL:** não publicar nem incluir neste repositório conversas individuais, transcrições de voz, fichas preenchidas, nomes identificáveis, relatos pessoais, dados sensíveis, tokens ou credenciais — nem em issues, PRs, commits, anexos, exemplos, testes ou logs.

## Antes de criar uma issue ou PR
- Converter a sugestão em descrição técnica genérica, com exemplos inteiramente fictícios.
- Remover nomes, datas específicas, locais, empresas, citações reconhecíveis e qualquer detalhe que permita reidentificação.
- Não copiar trechos literais de conversas privadas, mesmo com nomes trocados: anonimização superficial não basta.
- Solicitar revisão humana do texto antes do envio. Na dúvida, não publicar.
- Não enviar dados pessoais a Google Forms, Apps Script ou GitHub. Minimizar também metadados coletados.
- Não armazenar segredos no código; usar mecanismo seguro de secrets/propriedades e permissões mínimas.

## Se conteúdo pessoal for incluído por engano
1. **Interromper a divulgação e não reproduzir o conteúdo** em comentários, correções ou novas issues.
2. Restringir acesso e remover o material da interface do GitHub tão rapidamente quanto possível, por pessoa autorizada.
3. Se estiver em commits/histórico, seguir o procedimento apropriado de remoção de dados sensíveis do histórico e avaliar forks, caches e clones; apagar uma issue ou commit não garante eliminação de todas as cópias.
4. Avaliar necessidade de notificar envolvidos e rotacionar credenciais, quando aplicável.
5. Registrar o incidente somente com descrição técnica sem dados pessoais.

## Salvaguardas técnicas propostas
- Criar template de issue com checklist obrigatório de privacidade.
- Adicionar CONTRIBUTING.md e revisão de PR exigindo conferência humana.
- Adicionar verificações automatizadas de segredos e padrões de PII em PRs, com bloqueio de merge; reconhecer que detectores são falíveis e não substituem revisão humana.
- Evitar uploads/anexos de sessões; utilizar somente dados sintéticos nos testes.
- Manter o repositório privado durante o piloto e revisar permissões de colaboradores.

## Colaboração
As issues registram propostas e decisões aprovadas; Claude pode consultá-las e propor PRs. **Nenhuma ferramenta deve enviar conversas individuais ao repositório para criar contexto.** Toda publicação de sugestão deve passar por revisão do responsável.

Esta política é uma orientação de processo, não um filtro automático. A implementação das barreiras técnicas está pendente.
