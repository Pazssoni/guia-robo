# BEMO - Bloco Educacional Modular Open-Source

![Logo do BEMO](https://i.ibb.co/XZg5Gctk/bemoo.png)

Bem-vindo ao repositório oficial do BEMO, um robô educacional de baixo custo, modular e de código aberto, projetado para democratizar o ensino de STEAM (Ciência, Tecnologia, Engenharia, Artes e Matemática) em escolas e ambientes de aprendizado.

Este projeto foi desenvolvido como um Trabalho de Conclusão de Curso em Engenharia de Computação no Instituto Federal Fluminense (IFF) por Bruno Alves Pesse Libardi e Maurício Santos Passoni.

**[Acesse o Guia Interativo Completo aqui!](https://guia-robo.vercel.app/)**

---

## 🎯 Sobre o Projeto

A robótica educacional é uma ferramenta poderosa, mas seu alto custo é uma barreira significativa para escolas públicas. O BEMO foi criado para ser uma solução acessível e replicável, com um custo de montagem aproximadamente 25 vezes menor que os kits comerciais de mercado.

### ✨ Principais Características
* ** baixo Custo:** Construído com componentes eletrônicos acessíveis, com um custo total estimado em menos de R$ 210,00.
* ** Modular:** Possui um sistema de módulos intercambiáveis (Sumô, Artista, Construtor LEGO) que se adaptam a diferentes atividades pedagógicas.
* ** Open-Source:** Todo o projeto, do hardware ao software, é de código aberto, permitindo que qualquer pessoa possa montar, modificar e aprimorar o BEMO.
* ** Impressão 3D:** O chassi e os módulos são projetados para serem fabricados em qualquer impressora 3D com filamento PLA, incentivando a autonomia e a cultura maker.
* ** Programação Acessível:** Utiliza a plataforma **mBlock**, baseada em blocos, que facilita o aprendizado de lógica de programação para iniciantes.

---

## 🛠️ Como Montar o seu Próprio BEMO

Para replicar o projeto, siga os passos abaixo.

### 1. Lista de Materiais (Bill of Materials)

A lista completa de componentes eletrônicos, parafusos e a bateria necessária pode ser encontrada no **[Guia de Montagem em PDF](./Guia_PDF/Guia_Montagem_BEMO.pdf)**, que está neste repositório.

### 2. Arquivos para Impressão 3D

Todas as peças do chassi e os módulos intercambiáveis estão disponíveis em formato `.STL` na pasta **`/Arquivos_Impressao_3D`** deste repositório.

* **Material Recomendado:** Filamento PLA
* **Configuração Sugerida:** Altura de camada de 0.2mm, com suportes ativados.

### 3. Guia de Montagem

A montagem do hardware é detalhada passo a passo em nossos guias:
* **Guia Interativo (Recomendado):** [https://guia-robo.vercel.app](https://guia-robo.vercel.app) - Inclui vídeos e uma experiência mais dinâmica.
* **Guia:** Disponível na pasta **`/Guia`** em PDF e video.

### 4. Configuração do Ambiente de Programação (mBlock)

1.  **Instale o mBlock:** Baixe a versão para PC no site oficial: [mblock.cc](https://mblock.cc/pages/downloads).
2.  **Adicione o Dispositivo:** Na aba "Dispositivos", procure e adicione o **"Arduino Nano"**.
3.  **Instale as Extensões:** No "Centro de Extensões", pesquise e adicione as duas extensões necessárias:
    * `Easy Motor Driver`
    * `TCRT5000 IR`
4.  **Comece a Programar!** As atividades práticas e os códigos de exemplo estão no Capítulo 7 dos guias (interativo e PDF).

---

## 📁 Estrutura do Repositório

* **/Arquivos_Impressao_3D:** Contém todos os arquivos `.STL` para imprimir o BEMO.
* **/Guia_PDF:** Contém a versão em PDF do guia completo de montagem e programação.
* **index.html:** Código-fonte do guia interativo online.
* **README.md:** Este arquivo que você está lendo.

---

## 📜 Citação

Se você utilizar este projeto em seu trabalho, por favor, cite-o da seguinte forma:

LIBARDI, B. A. P.; PASSONI, M. S. **BEMO (Bloco Educacional Modular Open-Source): um robô educacional de baixo custo para o ensino de STEAM.** Trabalho de Conclusão de Curso (Graduação em Engenharia de Computação) – Instituto Federal Fluminense, Bom Jesus do Itabapoana, 2025.

---

## 👨‍💻 Autores

* **Bruno Alves Pesse Libardi**
* **Maurício Santos Passoni**

Agradecemos o apoio dos nossos orientadores, Ianne Lima Nogueira e Anderson de Souza Lima.
