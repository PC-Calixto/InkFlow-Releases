# InkFlow — downloads

O InkFlow é uma lousa digital para Windows com aplicativo companion para tablets Android. Esta página reúne os instaladores e arquivos de atualização.

## Windows

1. Abra a [versão mais recente](https://github.com/PC-Calixto/InkFlow-Releases/releases/latest) e baixe **Setup.exe**.
2. Leia e aceite os termos no assistente. Se houver uma instalação anterior reconhecida, confirme a substituição; o Setup a remove e continua com a instalação nova, preservando as lousas.
3. Autorize a instalação quando o Windows solicitar. Ao concluir, escolha se deseja abrir o InkFlow.

O arquivo `InkFlow-X.Y.Z-x64.msi` é uma alternativa para implantação administrativa. Use `Setup.exe.sha256` para conferir a integridade do Setup.

O botão **Verificar atualizações** no aplicativo Windows consulta as releases deste repositório.

## Android

Baixe **InkFlow-0.1.5-Android.apk** na [versão mais recente](https://github.com/PC-Calixto/InkFlow-Releases/releases/latest), abra o arquivo no tablet e confirme a instalação quando o Android solicitar. A atualização do companion é manual; os dados da lousa permanecem sincronizados com o computador.

## Histórico de versões

### 0.1.5 — Windows e Android

- O leitor de PDF permite reabrir o último arquivo na página em que a leitura parou e ir diretamente a uma página pelo número.
- Imagens e páginas importadas mantêm a posição e as proporções ao sincronizar entre tablet e computador.
- O tablet ganhou controles para pausar e retomar vídeos do YouTube no computador, avançar ou voltar alguns segundos e alternar legendas.
- Ao substituir uma instalação anterior, o Setup remove a versão antiga sem abri-la antes de instalar a nova.

### 0.1.4 — Windows

- O nível de zoom é sincronizado entre o computador e o tablet.
- A sessão atual é preservada ao fechar o aplicativo, com opção de continuar o trabalho na próxima abertura.
- A edição de texto mantém a caixa selecionada ao clicar fora; um novo clique cria outra caixa e o duplo clique reabre a edição.
- No Windows, atalhos de teclado permitem copiar, recortar, colar e excluir itens da lousa.
- As miniaturas das páginas são atualizadas após mudanças no conteúdo.
- O assistente de instalação passou a ser uma janela nativa do Windows.

### 0.1.3 — instalação no Windows

- Corrigido um erro que podia interromper a instalação e abrir a ajuda do Windows Installer.
- O Setup passou a reconhecer instalações anteriores compatíveis e atualizar o InkFlow sem exigir uma remoção manual.
- A janela do instalador ganhou dimensões corretas, ícone visível, textos legíveis e botões sem cortes.
- Os termos de uso passaram a ser exibidos com títulos, negrito, listas e links formatados.

### 0.1.2 — instalação no Windows

- Os termos completos passaram a ser exibidos em uma etapa própria, com rolagem e aceite antes da instalação.
- Opções e instalações anteriores podem ser consultadas em janelas menores sem esconder os controles.
- A remoção de registros antigos preserva os arquivos e as lousas existentes.

### 0.1.1 — escrita e sincronização

- O traço no tablet aparece imediatamente e só é suavizado depois que a caneta deixa a tela.
- A pauta ganhou mais espaço entre linhas e a lousa aceita zoom por pinça.
- Caixas de texto mantêm posição e dimensões ao sincronizar entre Windows e tablet.
- O marca-texto colore o texto durante o arraste e sincroniza a marcação.

### 0.1.0 — versão inicial

- Primeira distribuição do InkFlow para Windows e Android.

Veja também o [código-fonte](https://github.com/PC-Calixto/InkFlow) e o [histórico detalhado](https://github.com/PC-Calixto/InkFlow/blob/main/CHANGELOG.md).