# 🏚️ Silent Hill 5: Homecoming — Tradução PT-BR 🇧🇷

![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue?style=for-the-badge)
![Idioma](https://img.shields.io/badge/Idioma-Português%20do%20Brasil-green?style=for-the-badge)
![Jogo](https://img.shields.io/badge/Jogo-Silent%20Hill%3A%20Homecoming-darkred?style=for-the-badge)
![Plataforma](https://img.shields.io/badge/Plataforma-PC-blue?style=for-the-badge)

Tradução brasileira de **Silent Hill 5: Homecoming** para PC, revisada por **Emerson Teles**. Este repositório reúne somente os 17 arquivos de texto PT-BR (`*_BRA.str`), com os créditos e marcadores de interface preservados.

---

## 📥 Download — versão 1.0.0

Baixe o pacote pronto para instalação: [Silent.Hill.5.Homecoming.Traducao.PTBR.v1.0.0.zip](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR/releases/download/v1.0.0/Silent.Hill.5.Homecoming.Traducao.PTBR.v1.0.0.zip).

O ZIP preserva a estrutura `Engine/gameinfo/strings/`. Extraia o conteúdo na pasta do jogo e confirme a substituição dos arquivos após fazer backup.

## 📋 Conteúdo

Os arquivos ficam no caminho usado pelo jogo:

```text
Engine/gameinfo/strings/
├── gen_dialogue_BRA.str
├── m01_dialogue_BRA.str … m11_dialogue_BRA.str
├── m13_dialogue_BRA.str … m16_dialogue_BRA.str
└── strings_BRA.str
```

São 17 arquivos: diálogos dos capítulos disponíveis e textos gerais de interface, objetivos, documentos e itens.

## ✨ Revisão registrada

A revisão editorial de 2 de outubro de 2026 incluiu:

- ajustes de ortografia, concordância, pontuação e formulações literais;
- harmonização de termos e nomes conforme o contexto do jogo, incluindo **vice-xerife Wheeler** e **Juíza Holloway**;
- revisão de trechos narrativos, documentos, objetivos, combate, rádio e diálogos;
- uso de trema nas palavras que originalmente levariam til, conforme a limitação da fonte do jogo;
- restauração do marcador de áudio `<static>` onde necessário;
- preservação de **EMERSON TELES**, das cores e espaçamentos dos créditos, dos prompts de tecla/botão, das tags, das chaves e das quebras de linha.

O ajuste preexistente `M02_Interest_DrainB2` foi mantido para distinguir uma entrada duplicada no arquivo-base em inglês. Consulte [CHANGELOG.md](CHANGELOG.md) para o registro completo.

## 🚀 Instalação

1. Feche o jogo.
2. Abra a pasta de instalação de *Silent Hill: Homecoming*.
3. Faça uma cópia de segurança dos arquivos brasileiros atuais em `Engine/gameinfo/strings/`.
4. Copie os 17 arquivos `*_BRA.str` deste repositório para `Engine/gameinfo/strings/`, substituindo os arquivos correspondentes.
5. Inicie o jogo e selecione Português do Brasil, se a seleção de idioma estiver disponível na sua instalação.

Este pacote contém os arquivos de localização; não inclui instalador automático. Faça backup antes de substituir arquivos.

## 🔎 Referências de contexto

A revisão de termos e contexto narrativo consultou o [roteiro em inglês de Silent Hill Memories](https://www.silenthillmemories.net/sh5/script_en.htm) e o [manual de PC](https://www.silenthillmemories.net/sh5/versions/silent_hill_homecoming_pc_us_manual.pdf).

## 📝 Escopo e compatibilidade

Arquivos preparados para a estrutura da versão de PC indicada no pacote do jogo (Update 3.20). A revisão não altera executáveis, DLLs, controles ou câmera. A câmera continua fora do escopo deste projeto.

Os arquivos `.str` foram mantidos com sua codificação e estrutura de origem. Como a renderização depende do jogo e da fonte instalada, confira os caracteres no jogo após instalar.

## ✍️ Créditos

**Tradução e revisão PT-BR: Emerson Teles**

Os créditos existentes dentro do jogo, incluindo o nome **EMERSON TELES**, foram mantidos. *Silent Hill* é propriedade de seus respectivos titulares. Este projeto é uma tradução de fã independente e não é afiliado à Konami.

---

Desenvolvido e mantido por [Emerson Teles (@Emertels)](https://github.com/Emertels).
