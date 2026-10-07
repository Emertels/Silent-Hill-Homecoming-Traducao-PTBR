# 🏚️ Silent Hill 5: Homecoming — Tradução para Português do Brasil (PT-BR) 🇧🇷

![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue?style=for-the-badge)
![Idioma](https://img.shields.io/badge/Idioma-Português%20do%20Brasil-green?style=for-the-badge)
![Plataforma](https://img.shields.io/badge/Plataforma-PC-5B8DEF?style=for-the-badge)

Tradução brasileira de **Silent Hill 5: Homecoming** para PC, criada por **Emerson Teles** e revisada para esta versão. O pacote de instalação fica na seção **Releases**; esta página reúne informações do projeto, instruções e histórico.

---

## 📋 Índice

1. [Sobre o projeto](#-sobre-o-projeto)
2. [Download da versão 1.0.0](#-download-da-versão-100)
3. [Conteúdo traduzido](#-conteúdo-traduzido)
4. [Revisão da tradução](#-revisão-da-tradução)
5. [Como instalar](#-como-instalar)
6. [Como restaurar os arquivos anteriores](#-como-restaurar-os-arquivos-anteriores)
7. [Compatibilidade e escopo](#-compatibilidade-e-escopo)
8. [Referências de contexto](#-referências-de-contexto)
9. [Créditos e autoria](#-créditos-e-autoria)
10. [Sobre o autor](#-sobre-o-autor)

---

## 🌟 Sobre o projeto

Este projeto disponibiliza a tradução PT-BR de *Silent Hill: Homecoming* em um pacote ZIP pronto para ser extraído na pasta do jogo. A revisão editorial buscou melhorar clareza, concordância e consistência dos textos, preservando o estilo da tradução, a estrutura dos arquivos e as limitações da fonte usada pelo jogo.

O pacote contém apenas os arquivos localizados e a documentação. Não inclui executáveis do jogo, DLLs, instalador automático ou modificações de câmera.

---

## 📥 Download da versão 1.0.0

### [⬇️ Baixar Silent Hill 5: Homecoming PT-BR v1.0.0](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR/releases/download/v1.0.0/Silent.Hill.5.Homecoming.Traducao.PTBR.v1.0.0.zip)

[Ver notas completas da versão na página Releases](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR/releases/tag/v1.0.0).

O arquivo ZIP preserva o caminho `Engine/gameinfo/strings/` e inclui os 17 arquivos de localização PT-BR, este README e o changelog.

---

## 🎯 Conteúdo traduzido

O pacote reúne **17 arquivos `.str`** terminados em `_BRA`, usados pelo jogo para diálogos e textos de interface, objetivos, documentos e itens.

| Grupo | Arquivos |
| --- | --- |
| Diálogo geral | `gen_dialogue_BRA.str` |
| Capítulos | `m01_dialogue_BRA.str` a `m11_dialogue_BRA.str`, e `m13_dialogue_BRA.str` a `m16_dialogue_BRA.str` |
| Textos gerais | `strings_BRA.str` |

---

## ✨ Revisão da tradução

A revisão registrada em **2 de outubro de 2026** incluiu:

- Correções de ortografia, concordância, pontuação e construções literais em falas, objetivos, diários, documentos e textos de interface.
- Harmonização de termos e nomes conforme o contexto da história, incluindo **vice-xerife Wheeler** e **Juíza Holloway**, além de referências à Ordem, à Velha Fé e às famílias fundadoras de Shepherd's Glen.
- Ajustes em expressões de combate, rádio e diálogo para preservar o sentido e a voz dos personagens.
- Revisão de trechos narrativos e documentais selecionados.
- Uso de trema nas palavras que originalmente levariam til, conforme a limitação da fonte do jogo.
- Restauração do marcador de áudio `<static>` onde necessário.
- Preservação dos créditos **EMERSON TELES**, cores e espaçamentos, prompts de tecla/botão, tags, chaves e quebras de linha.
- Manutenção da chave existente `M02_Interest_DrainB2`, que distingue uma entrada duplicada no arquivo-base em inglês.

O registro resumido fica em [`CHANGELOG.md`](CHANGELOG.md). As notas detalhadas também acompanham a [release v1.0.0](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR/releases/tag/v1.0.0).

---

## 🚀 Como instalar

1. Baixe o ZIP na seção [Releases](https://github.com/Emertels/Silent-Hill-Homecoming-Traducao-PTBR/releases/latest) e feche o jogo.
2. Abra `Engine/gameinfo/strings/` na pasta de instalação e faça backup dos arquivos que serão substituídos.
3. Siga **somente** a opção correspondente à sua instalação:
   - **Com o patch Unknown Project v3.18 ou posterior (incluindo v3.20):** extraia o ZIP nessa pasta e mantenha os nomes com o sufixo `_BRA`.
   - **Jogo original, sem o patch Unknown Project:** não copie o ZIP como está. Em cada arquivo, remova `_BRA` do nome e substitua o arquivo-base em inglês correspondente. Por exemplo, `gen_dialogue_BRA.str` vira `gen_dialogue.str`, `m01_dialogue_BRA.str` vira `m01_dialogue.str` e `strings_BRA.str` vira `strings.str`.

Na versão original sem o mod, isso substitui os textos do idioma-base (inglês); o jogo não ganha uma opção de idioma PT-BR. O pacote não possui instalador automático. Preserve o backup para poder restaurar os arquivos anteriores.

---

## 🔄 Como restaurar os arquivos anteriores

Antes da instalação, guarde uma cópia dos arquivos `*_BRA.str` que já estão na pasta do jogo. Para desfazer a atualização, feche o jogo e recoloque essa cópia em `Engine/gameinfo/strings/`, substituindo os arquivos revisados.

---

## 🛡️ Compatibilidade e escopo

- O ZIP da release usa o sufixo `_BRA` e destina-se ao patch **Unknown Project v3.18 ou posterior**. O changelog do patch v3.18 registra o suporte não oficial aos sufixos `_BRA` (Português do Brasil) e `_CHI` (Chinês Simplificado); a instalação local documentada usa Update 3.20.
- No jogo original sem esse patch, o sufixo `_BRA` não é reconhecido. Para usar a tradução, é necessário retirar `_BRA` dos nomes e substituir os arquivos-base em inglês correspondentes, conforme os exemplos da instalação.
- O jogo original usa nomes-base sem código de idioma, como `gen_dialogue.str` e `strings.str` — não acrescente `_ENG`.
- Os arquivos `.str` mantêm codificação, marcadores e estrutura necessários à localização.
- A renderização de caracteres depende da fonte presente na instalação; recomenda-se conferir os textos no jogo após instalar.
- Este projeto cobre a tradução. Não inclui correção ou alteração da câmera, de controles, executáveis ou DLLs.

---

## 🔎 Referências de contexto

Para conferir nomes, relações entre personagens e contexto narrativo, a revisão consultou o [roteiro em inglês de Silent Hill Memories](https://www.silenthillmemories.net/sh5/script_en.htm) e o [manual de PC](https://www.silenthillmemories.net/sh5/versions/silent_hill_homecoming_pc_us_manual.pdf). A referência para o patch de terceiros é o [repositório Unknown Project](https://github.com/unknownproject/Silent_Hill_Homecoming); o changelog local do patch v3.18 registra a inclusão dos sufixos `_BRA` e `_CHI`.

---

## ✍️ Créditos e autoria

- **Tradução PT-BR:** Emerson Teles
- **Revisão editorial desta versão:** Emerson Teles
- **Idioma:** Português do Brasil (`pt-BR`)
- **Versão do pacote:** 1.0.0

Os créditos existentes dentro do jogo, incluindo **EMERSON TELES**, foram mantidos. *Silent Hill* é propriedade de seus respectivos titulares. Esta tradução de fã é um projeto independente e não possui afiliação ou endosso da Konami.

---

## 👤 Sobre o autor

Desenvolvido e mantido por **Emerson Teles**, conhecido na comunidade como **Emertels**.

Apaixonado por tecnologia, informática, jogos, manutenção de sistemas e tradução/localização de softwares e emuladores para Português do Brasil.

### 🛠️ Projetos e contribuições

- **Suítes de automação e utilitários:** [Suite-Emuladores](https://github.com/Emertels/Suite-Emuladores), [PSBBN-Translator](https://github.com/Emertels/PSBBN-Translator), [AI-Chat-Vault](https://github.com/Emertels/AI-Chat-Vault), [Microsoft-Photos-Fix](https://github.com/Emertels/Microsoft-Photos-Fix) e [Roccat-Syn-Pro-Air-Fix](https://github.com/Emertels/Roccat-Syn-Pro-Air-Fix).
- **Emulação e consoles:** projetos e localização para PSBBN, PCSX2, Dolphin, shadPS4, Azahar e RetroArch.
- **Softwares e utilitários:** traduções de DSX, ASUS GPU Tweak III, dnGrep e XWidget, além de ferramentas web.
- **Jogos:** tradução de *Silent Hill 5: Homecoming* e projetos em andamento para *Silent Hill 4: The Room*.

### 🌐 Conecte-se e acompanhe

<div align="left">

[![GitHub](https://img.shields.io/badge/GitHub-Emertels-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/emertels)
[![Website](https://img.shields.io/badge/Website-Emerson_Teles-0070F3?style=for-the-badge&logo=googlechrome&logoColor=white)](https://emertels.github.io)
[![Discord](https://img.shields.io/badge/Discord-Emertels%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://emertels.github.io/discord)
[![X / Twitter](https://img.shields.io/badge/X_Twitter-@emertels-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/emertels)
[![YouTube](https://img.shields.io/badge/YouTube-Emerson_Teles-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@emersonteles2379)
[![Telegram](https://img.shields.io/badge/Telegram-Aplicativos%20Mods-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/apksmodsandroid)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Apoiar%20Projeto-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/emertels)

</div>
