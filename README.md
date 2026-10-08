☁️ Calculadora de Sobrevivência na Nuvem & FinOps Estudantil com Easter Egg

Proteção contra faturas fantasmas, simulador de risco em tempo real e modelagem visual de arquitetura para estudantes e desenvolvedores.

🌐 Acessar a Aplicação Online • Reportar Problema

📌 Sobre o Projeto

Quem está começando a estudar computação em nuvem conhece o receio clássico de cadastrar o cartão de crédito na AWS, Google Cloud ou Microsoft Azure e ser surpreendido por cobranças em dólar no fim do mês geradas por recursos esquecidos ligados.

A Calculadora de Sobrevivência na Nuvem foi desenvolvida no modo Canvas do Google Gemini para resolver essa dor. Ela atua como um simulador interativo e educacional de FinOps, ensinando boas práticas de arquitetura, limites de camadas gratuitas (Always Free / Free Tier) e como evitar as principais armadilhas de faturamento.

✨ Funcionalidades Principais (v4.5)

🧪 1. Simulador de Custos & Diagnóstico de Risco em Tempo Real

Cotação comercial ao vivo: Integração direta com API de câmbio USD/BRL.

Simulador de Dólar Cartão: Ajuste de spread bancário e IOF de cartão internacional (+6,5%).

Filtro Multi-Cloud: Navegação dinâmica entre serviços de GCP, AWS e Azure.

Simulação de Fim de Semana Ocioso: Cálculo do impacto financeiro de esquecer laboratórios ligados de sexta a domingo.

☕🍔 2. Conversor de "Custo em Moeda de Estudante"

Traduz o valor financeiro da fatura em equivalências reais do cotidiano universitário:

$0.00: Bolsa intacta! Zero risco de virar estagiário sem almoço.

Até R$ 25: Equivalente a cafezinhos expressos ou salgado da cantina.

Até R$ 75: Equivalente a refeições no Restaurante Universitário (RU) ou 1 mês de Spotify.

Acima de R$ 75: Alerta vermelho equivalente ao rancho de compras da semana!

📐 3. Diagrama de Arquitetura da Solução & Topologia

Modo Cesta Dinâmica: Renderiza visualmente o perímetro da VPC (10.0.0.0/16), separando os componentes em Borda/Ingresso, Roteamento, Computação e Banco de Dados.

Modelos de Labs de Referência: Diagramas completos de pipelines modernos (como Streaming com RabbitMQ, Kinesis, Glue e Athena).

Fluxos Técnicos Coloridos: Linhas azuis para Escrita/Ingestão e linhas verdes para Leitura/Consultas.

Exportação com 1 Clique: Botão para exportar o diagrama visual e anexar em documentações e TCCs.

🧹 4. Gerador Automático de Script de Teardown / Destruição

Gera dinamicamente scripts de terminal em Bash (aws ec2 terminate-instances, gcloud compute instances delete, az vm delete) baseados estritamente nos checkboxes marcados na tela.

Inclui rotina de liberação de IPv4 estáticos órfãos para neutralizar multas de ociosidade.

Fornece bloco padrão de destruição via Terraform (terraform destroy -auto-approve).

🔗 5. Compartilhamento por Link Único (Deep Linking)

O botão "🔗 Compartilhar Lab" codifica o estado atual da simulação na URL (#services=gcp_e2_micro,aws_nat&weekend=1).

Permite que colegas e professores abram exatamente a mesma topologia e cálculo de custos.

🏆 6. Mini-Quiz FinOps com Selo Virtual

Desafio de 3 perguntas sobre armadilhas de faturamento (IPv4 ocioso, bancos contínuos e NAT Gateways).

Explosão de confetes e desbloqueio do badge "Arquiteto FinOps Sobrevivente 🛡️" ao acertar 100%.

Botão para copiar texto pronto de comemoração formatado para postar no LinkedIn.

🔊 7. Controle Global de Áudio (Modo Silencioso)

Botão de mudo com memorização de preferência via localStorage, ideal para uso em bibliotecas ou ambientes de trabalho.

✨ 8. Sentinela Gemini IA

Auditoria inteligente da cesta de serviços com suporte a chaves gratuitas do Google AI Studio.

Arquitetura resiliente com cascata de auto-recuperação (fallback) entre modelos (gemini-3.8-flash, gemini-2.5-flash, etc.).

Modo Offline: Motor FinOps integrado com base de conhecimento local em caso de ausência de chave.

🤫 O Easter Egg: Modo de Pânico "DEFCON 1"

Para conscientizar de forma lúdica sobre os riscos de esquecer recursos ativos no fim de semana, o aplicativo possui um segredo oculto:

Acesse o aplicativo no navegador.

Dê 5 cliques rápidos no ícone da nuvem ☁️ localizado no cabeçalho superior esquerdo.

Prepare-se para o modo DEFCON 1 • COLAPSO FINANCEIRO (com sirene de alarme gerada via Web Audio API e fatura fictícia explodindo!).

Clique no botão de Teardown de Emergência para zerar a fatura e celebrar a vitória com confetes.

🛠️ Tecnologias Utilizadas

HTML5 Semântico & Moderno

Tailwind CSS (via CDN): Interface responsiva, moderna e otimizada para modo escuro (Dark Mode).

JavaScript Vanilla (ES6+): Arquitetura orientada a estados locais, sem dependências pesadas de frameworks.

Web Audio API: Síntese de áudio paramétrica no navegador (tons de alerta e bips sonoros sem arquivos externos de áudio).

Canvas Confetti: Animações de comemoração para o teardown e conquistas do quiz.

AwesomeAPI: Consulta em tempo real da cotação comercial do dólar americano (USD/BRL).

Google Gemini API: Integração com modelos generativos de IA para suporte FinOps e geração de cronogramas de estudo.

🚀 Como Executar Localmente

Como a aplicação é estruturada em arquivo único autocontido, você não precisa instalar o Node.js nem rodar gerenciadores de pacotes:

Clone o repositório:

git clone https://github.com/Anferre/calculadora-sobreviv-ncia-nuvem-.git


Navegue até o diretório do projeto:

cd calculadora-sobreviv-ncia-nuvem-


Abra o arquivo index.html em qualquer navegador:

No Linux/Ubuntu: xdg-open index.html

No Windows: start index.html

No macOS: open index.html

Ou execute com a extensão Live Server no VS Code.

🤝 Como Contribuir

Contribuições são muito bem-vindas! Sinta-se à vontade para propor novas calculadoras de serviços, modelos de diagramas ou sugestões de FinOps:

Faça um Fork do projeto;

Crie uma branch para sua funcionalidade:

git checkout -b feature/minha-melhoria


Realize o commit das alterações:

git commit -m "feat: Adiciona novo cálculo para banco serverless"


Envie as modificações para a branch:

git push origin feature/minha-melhoria


Abra um Pull Request.

📄 Licença

Este projeto está sob a licença MIT — sinta-se livre para utilizar, estudar, modificar e compartilhar com sua comunidade acadêmica.
