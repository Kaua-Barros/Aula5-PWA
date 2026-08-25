"# Aula5-PWA" 

Produto desenvolvido na Curricularização obrigatória da Extensão em Neuroanatomia — Medicina/UEM — 2026
# Neurobolinhas

**Serious game educativo e acessível de estimulação cognitiva em Neuroanatomia**

O **Neurobolinhas** é um serious game desenvolvido no contexto da **Curricularização obrigatória da Extensão em Neuroanatomia** do curso de Medicina da Universidade Estadual de Maringá (UEM), em 2026. A proposta utiliza uma dinâmica de jogo para associar conteúdos de Neuroanatomia a atividades de atenção, coordenação motora e raciocínio.

## 1. Objetivo educacional

O game tem como objetivos:

* favorecer o **conhecimento sobre partes do córtex cerebral**;
* estimular a **coordenação motora**;
* exercitar o **pensamento lógico**;
* promover uma atividade de estimulação cognitiva associada a conteúdos de Neuroanatomia.

A abordagem procura traduzir conteúdos acadêmicos para uma linguagem interativa e acessível ao público da atividade extensionista.

## 2. Contexto acadêmico

O Neurobolinhas foi desenvolvido como produto da **Curricularização obrigatória da Extensão em Neuroanatomia**, vinculada ao curso de **Medicina da Universidade Estadual de Maringá (UEM)**, durante o ano de **2026**.

A atividade integra a formação acadêmica dos estudantes e a produção de um recurso digital destinado à interação com o público da extensão.

## 3. Público da atividade extensionista

O software foi desenvolvido para utilização com o **público 60+**, considerando a necessidade de uma interface simples, responsiva e acompanhada de recursos de acessibilidade.

## 4. Tecnologias e estrutura

O Neurobolinhas é uma **aplicação web no formato de serious game**, estruturada a partir de arquivos de código e recursos multimídia.

A estrutura do projeto inclui:

* arquivos HTML para a estrutura da aplicação;
* arquivos CSS para apresentação e responsividade;
* arquivos JavaScript para a lógica e funcionamento do jogo;
* `manifest.json` e recursos relacionados à instalação como aplicação web progressiva (PWA);
* `sw.js` para o funcionamento relacionado ao PWA;
* pasta `assets/` para organização de imagens, sons e demais recursos utilizados pela aplicação;
* subpastas destinadas a recursos de áudio e imagens.

Os arquivos de áudio são referenciados a partir de `assets/audio`, enquanto os recursos visuais utilizados pelo jogo são organizados na estrutura de `assets`.

## 5. Recursos do software

O Neurobolinhas possui recursos voltados à acessibilidade e à adaptação da experiência de uso, incluindo:

* **Responsividade:** a interface e a área de jogo são adaptadas a diferentes dimensões de tela. O código também realiza redimensionamento dinâmico da área de jogo.
* **Áudio:** o jogo utiliza sons para diferentes eventos, como cliques, disparos, acertos, erros e conclusão da atividade.
* **TTS/narração por voz:** utiliza a API de síntese de voz do navegador (`SpeechSynthesis`) para realizar narrações em português brasileiro.
* **Libras:** integração com o **VLibras**, disponibilizada diretamente na interface da aplicação.
* **Contraste/modo escuro:** existe controle para alternância do tema visual, incluindo modo escuro.
* **Fonte ampliada:** o tamanho da fonte pode ser ajustado pelo usuário, com persistência da configuração.
* **Redução de movimento:** há suporte à redução de animações/movimento, inclusive considerando a preferência `prefers-reduced-motion` do dispositivo.
* **Controles acessíveis:** os controles de áudio e voz possuem estados identificáveis por atributos `aria-pressed`, além de regiões destinadas a anúncios de informações ao usuário.
* **Instalação como PWA:** o software possui mecanismo para instalação como aplicação web progressiva quando disponibilizado pelo navegador.

## 6. Trajetória de desenvolvimento

O desenvolvimento do Neurobolinhas ocorreu a partir das seguintes etapas:

**Estudo do conteúdo científico → tradução do conteúdo para a linguagem de jogo → construção dos códigos → organização de imagens e sons na pasta `assets` → testes → disponibilização no Google Sites → realização de correções → publicação no GitHub → apresentação ao público.**

Esse processo buscou aproximar o conteúdo acadêmico de Neuroanatomia de uma experiência interativa adequada à atividade extensionista.

## 7. Equipe discente

O desenvolvimento foi realizado coletivamente pelos seguintes estudantes:

* **Kauã Barros**
* **João Correa**
* **Vitor Hugo**
* **Armando Mazzetto**
* **Enzo Shoji Eiri**
* **Guilherme Henrique**

A autoria do projeto corresponde, portanto, ao conjunto dos integrantes que efetivamente participaram de sua construção acadêmica, não sendo atribuída exclusivamente ao proprietário da conta utilizada para hospedagem do repositório.

## 8. Docentes responsáveis

* **Profa. Dra. Sônia Trannin de Mello** — responsável pela **Neuroanatomia**.
* **Profa. Cláudia Regina Pinheiro Lopes** — responsável pela **orientação tecnológica**.

## 9. Link público do game

**Neurobolinhas — versão pública:**
[Acessar o Neurobolinhas](https://kaua-barros.github.io/Aula5-PWA/)

## 10. Repositório

**Repositório do projeto no GitHub:**
[Acessar o repositório Aula5-PWA](https://github.com/Kaua-Barros/Aula5-PWA/)

## 11. Ética e créditos

O repositório do Neurobolinhas está hospedado na conta de GitHub de um dos integrantes da equipe por uma questão de organização e publicação do projeto. **Essa hospedagem não implica autoria exclusiva do proprietário da conta.**

O software constitui uma **produção acadêmica coletiva**, desenvolvida no âmbito da Curricularização obrigatória da Extensão em Neuroanatomia da UEM. Os créditos apresentados neste documento têm como finalidade registrar os integrantes que efetivamente participaram da construção do projeto, respeitando a natureza coletiva da atividade acadêmica.


