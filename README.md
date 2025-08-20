# Automação de Atribuição de Chamados v1.0.0

Simplifique seu fluxo de trabalho com o Dupla Tech, sua ferramenta de automação para atribuição de chamados e notificação de técnicos

## Download

Você pode baixar a versão mais recente do programa na nossa página de **[Releases](https://github.com/PHziinn/dupla-tech-cli/releases)**.

## Como Usar

1.  **Baixe o arquivo `duplatech.exe`** da última release.
2.  Crie uma pasta no seu computador para o programa.
3.  Coloque o arquivo `.exe` dentro dessa pasta.
4.  Na mesma pasta, crie um arquivo de texto chamado `.env`.
5.  Copie e cole o conteúdo abaixo no seu `.env` e preencha com suas credenciais:

    ```ini
    # Credenciais para o site Maminfo
    MAMINFO_USER=""
    MAMINFO_PASSWORD=""
    MEU_NOME_FILTRO=""

    # URL da Planilha Google Sheets (com o GID da aba correta)
    GOOGLE_SHEET_URL=""

    # --- CREDENCIAIS DO BOTCONVERSA ---
    BOTCONVERSA_URL=""
    BOTCONVERSA_USER=""
    BOTCONVERSA_PASSWORD=""
    BOTCONVERSA_BOT_ID=""

    # Seu nome para filtrar na planilha
    MEU_NOME_FILTRO=""
    MEU_NOME_FILTRO_MAMINFO=''

    ```

6.  Abra o terminal (CMD ou PowerShell) e execute o programa.
