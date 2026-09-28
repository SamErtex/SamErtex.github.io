# SamErtex.github.io
Política de Privacidade
Claro. Para uma primeira instalação, o README pode ficar assim:

```text
OPA Auto Atendimento v1.11

A extensão automatiza a ação "Assumir próximo da fila" no sistema IXCSoft.

Funcionamento:
- AUTO OFF: não faz nada.
- AUTO ON: verifica .item[data-id="atend_aguard"] .notif1 a cada 3 segundos.
- Se o valor for maior que 0, encontra o botão nativo "Assumir próximo da fila"
  e executa o clique nativo.
- Depois de uma tentativa, AUTO volta para OFF.
- O valor "Em andamento" não é utilizado.
- O botão AUTO é inserido ao lado de "Assumir próximo da fila" quando o botão
  nativo estiver disponível.

PRIMEIRA INSTALAÇÃO:

1. Baixe e extraia o arquivo ZIP da extensão.
2. Abra o Google Chrome.
3. Acesse:
   chrome://extensions
4. Ative o "Modo do desenvolvedor", no canto superior direito.
5. Clique em "Carregar sem compactação".
6. Selecione a pasta da extensão extraída.
7. A extensão será adicionada ao Chrome.
8. Abra ou recarregue a página do suporte IXCSoft.
9. O botão AUTO aparecerá ao lado de "Assumir próximo da fila".

IMPORTANTE:
- Não é necessário remover uma versão anterior caso esta seja a primeira
  instalação.
- Se já existir uma versão anterior da OPA instalada, consulte o procedimento
  de atualização abaixo.

CONSOLE:

Ao carregar a extensão, podem aparecer mensagens como:

[OPA Auto v1.11] Carregado: ...
[OPA Auto v1.11] Botão inserido ao lado de "Assumir próximo da fila".

ATUALIZAÇÃO DE UMA VERSÃO ANTERIOR:

1. Abra:
   chrome://extensions
2. Localize a extensão OPA Auto Atendimento.
3. Remova a versão anterior.
4. Extraia o ZIP da nova versão.
5. Clique em "Carregar sem compactação".
6. Selecione a pasta da nova versão.
7. Recarregue a página do suporte IXCSoft.

OBSERVAÇÃO:

A extensão depende da estrutura atual da interface do IXCSoft.
Alterações na página podem exigir uma nova versão da extensão.
```
