# InkFlow — downloads

O InkFlow é uma lousa digital para Windows com aplicativo companion para tablet Android. Este repositório reúne os instaladores e os arquivos usados nas atualizações do Windows.

## Instalar no Windows

1. Abra a [versão mais recente](https://github.com/PC-Calixto/InkFlow-Releases/releases/latest) e baixe **Setup.exe**.
2. Leia e aceite os termos na etapa própria do assistente. Se ele encontrar uma versão anterior, confirme a remoção; o Setup a desinstala e continua a instalação automaticamente, preservando as lousas.
3. Confirme a autorização do Windows quando solicitada.

O arquivo `InkFlow-X.Y.Z-x64.msi` é uma alternativa para implantação administrativa. `Setup.exe.sha256` permite conferir a integridade do instalador baixado. No PowerShell, compare o valor do arquivo com o resultado de `Get-FileHash .\Setup.exe -Algorithm SHA256`.

O botão **Verificar atualizações** do InkFlow para Windows consulta as releases deste repositório. O companion Android não se atualiza pelo GitHub: a instalação de um APK compatível no tablet é manual. O APK de teste da 0.1.1 ainda não é um pacote Android de distribuição pública.

## Histórico de versões

### 0.1.2 — Setup Windows

- Termos completos em etapa exclusiva, com rolagem e aceite antes das opções.
- Opções e lista de instalações anteriores acessíveis em janelas menores, sem esconder os controles do assistente.
- Remoção confirmada da versão anterior e continuação automática da instalação.
- Limpeza segura de registros órfãos, preservando arquivos e lousas.
- Fundo translúcido do Setup integrado ao visual do InkFlow.

### 0.1.1 — correções

- A escrita no tablet apresenta o traço imediatamente e só suaviza a linha quando a caneta deixa a tela. A gravação local espera uma pausa curta entre letras para reduzir travamentos.
- A pauta ganhou mais espaço entre linhas, e a lousa do tablet aceita zoom por pinça com dois dedos.
- Caixas de texto mantêm posição, largura e altura ao sincronizar entre Windows e tablet. A edição não desenha duas cópias do texto nem reduz a caixa criada.
- No Windows, um duplo clique com o ponteiro abre a caixa de texto para edição. O texto pronto fica contido nos limites da caixa.
- No Android, o marca-texto colore o texto durante a seleção e sincroniza a marcação com o Windows.
- O instalador Windows foi reformulado para identificar instalações anteriores e oferecer a remoção com cópia de segurança das lousas guardadas na pasta antiga.

### 0.1.0 — versão inicial

- Primeira distribuição do InkFlow para Windows e do companion Android.

As alterações detalhadas da versão também constam na [descrição da release 0.1.2](https://github.com/PC-Calixto/InkFlow-Releases/releases/tag/v0.1.2).
