# Monster House (PS2) — Patch do Protótipo de 15 de Abril de 2006

**Autor:** otaviop  
**Jogo:** Monster House (PlayStation 2)  
**Data da build:** 15 de abril de 2006  
**Executável:** `SCPS_123.45`  
**Serial do jogo:** `SCPS-12345`  
**CRC no PCSX2:** `1753EB1F`

## Visão geral

Este patch restaura o desempenho do protótipo inicial de Monster House para PS2 e introduz diversas melhorias:

- Corrige a queda severa de desempenho, que fazia o jogo rodar a apenas 1–2 FPS.
- Habilita a jogabilidade a 60 FPS.
- Adiciona suporte adequado à câmera em widescreen 16:9.
- Corrige o descarte de objetos (*object culling*) para o campo de visão mais amplo.
- Desativa o desfoque de quadros (*frame blur* ou *ghosting*).
- Desativa o efeito HDR bloom.
- Desativa a saída de mensagens de depuração (`debug printf`).

O patch foi testado com o protótipo de Monster House de 15 de abril de 2006 no PCSX2.

**Importante:** Este patch foi desenvolvido especificamente para o executável do protótipo identificado acima. Ele não é compatível com a versão comercial de PS2.

## Instruções de instalação

### 1. Baixe o patch

Baixe o arquivo `.pnach` deste repositório.

### 2. Encontre a pasta de cheats do PCSX2

Abra o PCSX2 e utilize a opção para abrir o diretório de dados do emulador:

1. Abra o PCSX2.
2. Abra o menu **Tools**.
3. Selecione **Open Data Directory**.
4. Localize a pasta chamada `cheats`.

Dependendo da instalação do PCSX2, o diretório de dados pode estar em um local diferente.

### 3. Copie o arquivo do patch

Copie o arquivo `.pnach` baixado para a pasta `cheats`.

**Importante:** O nome do arquivo deve corresponder ao CRC do jogo:

`1753EB1F.pnach`

Se necessário, renomeie o arquivo baixado para utilizar exatamente esse nome.

### 4. Habilite os cheats no PCSX2

1. Abra as configurações do PCSX2.
2. Acesse **Emulation**.
3. Habilite a opção **Enable Cheats**.
4. Salve as configurações, caso solicitado.

### 5. Configure o widescreen

Para obter a apresentação pretendida em 16:9:

1. Abra **Settings > Graphics**.
2. Localize a opção **Aspect Ratio**.
3. Selecione **16:9**.

O patch ajusta o comportamento da câmera e do descarte de objetos. A proporção de tela do PCSX2 também precisa estar configurada como 16:9.

### 6. Inicie o jogo

Inicie o protótipo de Monster House de 15 de abril de 2006.

O PCSX2 deverá reconhecer automaticamente o patch quando o CRC do jogo corresponder a `1753EB1F` e os cheats estiverem habilitados.

## Solução de problemas

**O patch não está sendo reconhecido:**
- Verifique se o arquivo está dentro da pasta `cheats` do PCSX2.
- Certifique-se de que o nome do arquivo seja exatamente `1753EB1F.pnach`.
- Confirme se os cheats estão habilitados.
- Verifique se você está executando a versão correta do protótipo.

**O jogo continua apresentando lentidão:**
- Confirme se o patch está habilitado.
- Verifique se o CRC do jogo é `1753EB1F`.
- Certifique-se de que não está utilizando a versão comercial.

**A imagem não está sendo exibida corretamente em widescreen:**
- Verifique se a opção Aspect Ratio do PCSX2 está configurada como 16:9.

## Compatibilidade

| Item | Versão compatível |
|---|---|
| Jogo | Monster House (PS2) |
| Build | Protótipo de 15 de abril de 2006 |
| Executável | SCPS_123.45 |
| CRC | 1753EB1F |
| Emulador | PCSX2 |

## Créditos

**Desenvolvimento do patch:** otaviop

## Aviso legal

Este projeto tem como objetivo a preservação de jogos, pesquisa e melhoria de compatibilidade.

Este repositório não distribui o jogo original, imagens ISO, arquivos de BIOS ou conteúdos protegidos por direitos autorais. Você deve fornecer seus próprios arquivos do jogo, obtidos legalmente.

---

# English Version

# Monster House (PS2) — April 15, 2006 Prototype Patch

**Author:** otaviop  
**Game:** Monster House (PlayStation 2)  
**Build date:** April 15, 2006  
**Executable:** `SCPS_123.45`  
**Game serial:** `SCPS-12345`  
**PCSX2 CRC:** `1753EB1F`

## Overview

This patch restores the performance of the early Monster House PS2 prototype and introduces several improvements:

- Fixes the severe 1–2 FPS slowdown.
- Enables 60 FPS gameplay.
- Adds proper 16:9 widescreen camera support.
- Corrects object culling for the wider field of view.
- Disables frame blur (ghosting).
- Disables HDR bloom.
- Disables debug printf output.

The patch was tested with the April 15, 2006 prototype in PCSX2.

**Important:** This patch is designed specifically for the prototype executable identified above. It is not compatible with the commercial PS2 release.

## Installation Instructions

### 1. Download the patch

Download the `.pnach` file from this repository.

### 2. Find your PCSX2 cheats folder

Open PCSX2 and use the option to open its data directory:

1. Open PCSX2.
2. Open the **Tools** menu.
3. Select **Open Data Directory**.
4. Find the folder named `cheats`.

Depending on your PCSX2 installation, the data directory may be in a different location.

### 3. Copy the patch file

Copy the downloaded `.pnach` file into the `cheats` folder.

**Important:** The filename must match the game's CRC:

`1753EB1F.pnach`

If necessary, rename the downloaded file to this exact name.

### 4. Enable cheats in PCSX2

1. Open PCSX2 settings.
2. Go to **Emulation**.
3. Enable **Enable Cheats**.
4. Save the settings if prompted.

### 5. Configure widescreen

For the intended 16:9 presentation:

1. Open **Settings > Graphics**.
2. Find the **Aspect Ratio** setting.
3. Select **16:9**.

The patch adjusts the game's camera and culling behavior. The PCSX2 aspect ratio must also be set to 16:9.

### 6. Start the game

Start the April 15, 2006 Monster House prototype.

PCSX2 should automatically recognize the patch when the game CRC matches `1753EB1F` and cheats are enabled.

## Troubleshooting

**The patch is not being detected:**
- Check that the file is inside the PCSX2 `cheats` folder.
- Make sure the filename is exactly `1753EB1F.pnach`.
- Confirm that cheats are enabled.
- Verify that you are running the correct prototype build.

**The game still runs slowly:**
- Confirm that the patch is enabled.
- Check that the game CRC is `1753EB1F`.
- Make sure you are not using the commercial release.

**The image does not look correct in widescreen:**
- Check that PCSX2's Aspect Ratio setting is set to 16:9.

## Compatibility

| Item | Supported version |
|---|---|
| Game | Monster House (PS2) |
| Build | April 15, 2006 prototype |
| Executable | SCPS_123.45 |
| CRC | 1753EB1F |
| Emulator | PCSX2 |

## Credits

**Patch development:** otaviop

## Disclaimer

This project is intended for game preservation, research, and compatibility improvement.

This repository does not distribute the original game, ISO images, BIOS files, or copyrighted game assets. You must provide your own legally obtained game files.
