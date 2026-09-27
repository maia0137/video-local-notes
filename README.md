# Extrator de Notas de Mídia (Foco Acadêmico) 🎓

O **Extrator de Notas de Mídia** (antigo Extrator de Notas YT) é uma aplicação web de arquivo único (`.html`) focada em produtividade acadêmica e criação de resumos. Ele permite sincronizar anotações em texto com o tempo exato (timestamps) de vídeos ou áudios, além de oferecer suporte a transcrição por voz e formatação automática de referências bibliográficas.

Ideal para estudantes e pesquisadores, o app foi desenhado para rodar perfeitamente em celulares de hardware modesto ou nos PCs da biblioteca, sem necessidade de banco de dados, instalação ou dependências complexas (tudo roda no lado do cliente).

---

## 🚀 Novas Funcionalidades (Versão 2.0)

*   **💾 Salvamento Automático (Anti-Desastre):** Tudo o que você digita é salvo instantaneamente no armazenamento do navegador (`localStorage`). Se o celular fechar o app, a bateria acabar ou você atualizar a página acidentalmente, seu trabalho pode ser restaurado com um clique!
*   **📚 Metadados Acadêmicos e Citações:** Preencha os campos de Autor, Título e Ano. Ao exportar seu trabalho, o aplicativo gera automaticamente as referências no formato **ABNT** e **APA** no cabeçalho do documento.
*   **📺 Modo Manual (TV/Netflix):** Está assistindo a um documentário na TV? Use o "Modo Manual" para usar o celular apenas como um bloco de notas inteligente, digitando o tempo em que as coisas acontecem.
*   **📋 Copiar Fácil:** Botões dedicados para copiar trechos individuais rapidamente ou um botão "Copiar Tudo" para colar direto no Word, Notion ou WhatsApp.
*   **🎙️ Transcrição por Voz (Ditado Integrado):** 
    *   **Online (Web Speech):** Rápido, leve e usa o microfone do celular para ditar notas.
    *   **Offline (Vosk):** Para áudios/vídeos carregados do dispositivo, o app extrai e transcreve o áudio diretamente do arquivo, sem usar o microfone (zero ecos, 100% offline).
*   **🙌 Modo Mãos Livres:** Transcreva continuamente. Uma pausa de 3 segundos na voz salva a nota atual e inicia a próxima no tempo correto.
*   **📌 Layout Otimizado (Sticky):** Em celulares, a área de vídeo e digitação fica fixa no topo da tela, permitindo que você role e leia as notas antigas sem perder os controles de vista.
*   **🔄 Novo Trabalho:** Um botão seguro para limpar a área e começar uma nova sessão de estudos rapidamente.

---

## 🎥 Fontes de Mídia Suportadas

1.  **YouTube e Vimeo:** Cole o link e o app carrega o player oficial com captura de tempo automática.
2.  **Arquivos Locais:** Carregue arquivos de vídeo (`.mp4`, `.webm`) ou áudio (`.mp3`, `.wav`) direto do seu dispositivo. Excelente para gravar aulas ou usar no modo Avião.
3.  **Outros Links / Redes Sociais:** Links que não possuem player aberto (como Instagram, Facebook Reels, Netflix) podem ser anotados usando o **Modo Manual**.

---

## 💻 Como Usar

1.  **Carregue a Mídia:** Cole um link, faça upload de um arquivo ou clique em "Iniciar Sem Mídia" (Modo Manual).
2.  **Preencha os Metadados (Opcional):** Adicione Autor, Título e Ano para gerar referências.
3.  **Anotando:** 
    *   Clique em **⏳ Anotar** para capturar o tempo exato (ou digite o tempo no modo manual).
    *   Digite sua nota ou use o botão de **Microfone 🎙️** para ditar.
    *   Clique em **Salvar Nota**.
4.  **Exportação:**
    *   **⬇️ (.md):** Baixa um arquivo Markdown perfeito para Obsidian, Notion ou edição simples.
    *   **⬇️ (.json):** Baixa um backup completo da sessão. Pode ser importado de volta no app para continuar o trabalho depois.
    *   **📋 Copiar Tudo:** Envia tudo formatado para a sua Área de Transferência.

---

## ⌨️ Atalhos de Teclado (Para PC)

*   `Espaço`: Pausa/Retoma a mídia e já abre a caixa de anotação (quando não estiver digitando).
*   `Enter`: Salva a nota atual (quando estiver com foco na caixa de texto).
*   `Esc`: Cancela a edição e retoma o vídeo.

---

## 🛠️ Detalhes Técnicos

*   **Arquitetura:** `Vanilla JavaScript` (ES6+), HTML5 e CSS3.
*   **Estilo:** Design Responsivo (Mobile First) com tema Claro/Escuro automático e manual.
*   **Sem Servidor:** Todo o processamento (incluindo IA do Vosk e salvamento no LocalStorage) acontece 100% no navegador do usuário. Segurança e privacidade totais.

---

##  Contribuição

*Projeto idealizado com auxílio de IA para facilitação de rotinas acadêmicas, resumos de aulas e transcrição de pesquisas.* Sinta-se à vontade para fazer um **fork**, adaptar e melhorar!  
Se tiver sugestões ou encontrar bugs, abra uma *issue* ou envie um *pull request*.

---

##  Licença

Este projeto está sob a licença **MIT** – consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Desenvolvido por** Evandro Maia Neves – estudante de Engenharia Florestal na UEPA, Campus Castanhal.  
*Feito com 🔎 para facilitar os estudos e o trabalho de campo.*
