# video-local-notes
Um aplicativo para tomar ajudar a transcrever videos do armazenamento local do usuário.
---
# Local Video Notes – Anotador de Vídeos Offline

**Local Video Notes** é uma ferramenta HTML puro (sem dependências externas) que permite assistir a vídeos locais e fazer anotações sincronizadas com o tempo de reprodução. Ideal para estudantes, pesquisadores e profissionais que precisam extrair informações de gravações de aulas, entrevistas, palestras ou vídeos de campo – tudo sem conexão com a internet.

---

##  Funcionalidades

-  **Seleção de vídeo local** – carregue qualquer arquivo de vídeo do seu dispositivo.
-  **Captura de timestamp** – pause o vídeo no momento exato e anote algo.
-  **Edição rápida** – escreva a anotação em um campo de texto e salve.
-  **Lista organizada** – todas as notas são exibidas em ordem cronológica com o timestamp clicável – clique no horário para voltar àquele ponto do vídeo.
-  **Exportação para Markdown** – gere um arquivo `.md` com todas as suas anotações, pronto para ser usado em editores de texto ou para compartilhar.
-  **Design minimalista e escuro** – foca no conteúdo e reduz o cansaço visual.

---

##  Como usar

1. **Abra o arquivo** `index.html` em qualquer navegador moderno (Chrome, Edge, Firefox, etc.).  
   *Nenhuma instalação ou servidor é necessário.*

2. **Clique no botão** `📂 Selecionar Vídeo` e escolha um arquivo de vídeo do seu computador.

3. O vídeo será carregado e os controles aparecerão. Assista normalmente.

4. Quando quiser fazer uma anotação:
   - Pause o vídeo (ou clique no botão **⏳ Capturar Tempo e Anotar** – ele pausa automaticamente).
   - Escreva sua nota no campo que aparecer.
   - Clique em **Salvar** – a nota será registrada com o timestamp atual.

5. Para voltar a um ponto específico, clique no timestamp (ex: `[3:45]`) na lista de notas.

6. Para exportar todas as anotações, clique em **⬇️ Exportar (.md)** – um arquivo `minhas-notas.md` será baixado.

---

##  Tecnologias utilizadas

- **HTML5** – estrutura da página.
- **CSS3** – estilização (tema escuro, responsivo).
- **JavaScript (Vanilla)** – toda a lógica de captura, armazenamento e exportação.
- **File API** – leitura de vídeos locais.
- **Blob/URL.createObjectURL** – carregamento dinâmico do vídeo.
- **Markdown** – formato de exportação (leve e universal).

Nenhuma biblioteca externa, framework ou CDN – tudo roda offline.

---

##  Estrutura do projeto

O projeto consiste em um único arquivo `index.html` que contém todo o CSS e JavaScript embutidos.  
Ideal para portabilidade: basta copiar o arquivo para qualquer dispositivo (computador, tablet, celular) e abrir.

---

##  Possíveis melhorias futuras

- [ ] Editar/excluir notas individuais.
- [ ] Importar/exportar notas em JSON para sincronização entre dispositivos.
- [ ] Atalhos de teclado (ex: `Espaço` para pausar/capturar).
- [ ] Suporte a legendas ou transcrição automática (usando Web Speech API).
- [ ] Opção de tema claro/escuro.

---

##  Contribuição

Este projeto foi desenvolvido com auxílio de IA para atender a uma necessidade pessoal. Sinta-se à vontade para fazer um **fork**, adaptar e melhorar!  
Se tiver sugestões ou encontrar bugs, abra uma *issue* ou envie um *pull request*.

---

##  Licença

Este projeto está sob a licença **MIT** – consulte o arquivo [LICENSE](LICENSE) para mais detalhes.

---

**Desenvolvido por** Evandro Maia Neves – estudante de Engenharia Florestal na UEPA, Campus Castanhal.  
*Feito com ❤️ para facilitar os estudos e o trabalho de campo.*
