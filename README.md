🧠 Assistente de Meta - Projeto NLW
Este é um projeto que utiliza a API Gemini da Google para responder perguntas relacionadas a três jogos populares: League of Legends, Valorant e Counter-Strike: Global Offensive (CS:GO). O usuário pode informar sua API Key, selecionar o jogo e fazer perguntas relacionadas ao meta atual, builds, estratégias e dicas.

🔍 Funcionalidades
✅ Interface responsiva com design moderno.

✅ Integração com a API Gemini para respostas personalizadas via IA.

✅ Suporte a três jogos:

League of Legends

Valorant

Counter-Strike: Global Offensive

✅ Respostas formatadas em Markdown convertidas para HTML.

✅ Animações de carregamento e feedback visual ao usuário.

✅ Segurança básica: campo de API Key oculto.

🖥️ Tecnologias Utilizadas
HTML5

CSS3

JavaScript (Vanilla)

Showdown.js (para conversão de Markdown em HTML)

API Gemini (modelo gemini-2.5-flash)

🚀 Como Usar
1. Clone o repositório:
bash
Copiar
Editar
git clone https://github.com/seu-usuario/nlw-assistente-meta.git
2. Navegue até o diretório:
bash
Copiar
Editar
cd nlw-assistente-meta
3. Abra o arquivo index.html no navegador.
4. Preencha os campos:
🔐 API Key (obtida no Google AI Studio)

🎮 Selecione o jogo

❓ Faça uma pergunta (ex: Melhor build para Lux Mid)

📁 Estrutura de Pastas
css
Copiar
Editar
nlw-assistente-meta/
│
├── index.html
├── script.js
├── README.md
└── src/
    ├── img/
    │   └── bg.png
    │   └── logo.png
    └── styles/
        ├── reset.css
        ├── responsive.css
        └── styles.css
🛠️ Personalização
Você pode adicionar novos jogos adaptando os prompts no script.js.

Trocar o background e logo em src/img.

Adicionar melhorias visuais no CSS ou responsividade adicional.

🧪 Exemplo de Pergunta e Resposta
Pergunta: Melhor agente para iniciar no Valorant?
Resposta gerada:

markdown
Copiar
Editar
**Agente indicado para iniciantes:**  
- **Sage** — Fácil de aprender, com cura e controle de área.  
- **Phoenix** — Boa mobilidade e habilidades intuitivas.
❗ Observações
A API Gemini pode exigir ativação prévia e limites de uso.

As respostas são baseadas no meta atual e são simuladas com base em instruções precisas dentro do prompt.

📄 Licença
Este projeto é livre para uso pessoal e educacional.
