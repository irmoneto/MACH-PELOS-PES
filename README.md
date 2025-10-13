Analisador de Compatibilidade pelos Pés

Visão Geral

Este projeto é um aplicativo web interativo desenvolvido em HTML, CSS (utilizando Tailwind CSS [1]) e JavaScript puro. Ele permite aos usuários analisar a compatibilidade entre duas pessoas com base na morfologia de seus pés, seguindo uma metodologia específica de leitura de pés.

O aplicativo guia o usuário através de um processo de upload de imagens dos pés, marcação de pontos específicos para análise de formato e tamanho dos dedos, e uma etapa final para classificação do tamanho das unhas. Ao final, um relatório de compatibilidade detalhado é gerado, incluindo uma pontuação e descrições sobre os pontos fortes e desafios da relação.

Funcionalidades Principais

•
Análise de Formato do Pé: Classificação do formato do pé (Egípcio, Grego/Romano, Quadrado) com base em marcações visuais.

•
Análise de Tamanho dos Dedos: Avaliação do tamanho relativo dos dedos (Curtos, Normais, Longos) através de medições na imagem.

•
Análise de Tamanho das Unhas: Classificação do tamanho das unhas (Pouco Visíveis, Normais, Bem Visíveis) para inferir características de convicção.

•
Relatório de Compatibilidade: Geração de um relatório detalhado com base nas análises de ambos os indivíduos, incluindo uma pontuação de compatibilidade e insights relacionais.

•
Exportação para PDF: Capacidade de exportar o relatório gerado para um arquivo PDF, utilizando a biblioteca html2pdf.js [2].

•
Privacidade por Design: Todas as análises e processamento de imagens são realizados localmente no navegador do usuário. As imagens não são enviadas para servidores, garantindo a privacidade dos dados.

Tecnologias Utilizadas

•
HTML5: Estrutura e conteúdo da página.

•
Tailwind CSS: Framework CSS para estilização rápida e responsiva.

•
JavaScript (Vanilla JS): Lógica de interação, manipulação de DOM, processamento de imagens e cálculos de análise.

•
html2pdf.js: Biblioteca JavaScript para geração de PDFs a partir de conteúdo HTML.

Como Usar

Para utilizar o aplicativo, basta abrir o arquivo comparador-pes01.html em um navegador web moderno. O aplicativo irá guiá-lo através das seguintes etapas:

1.
Tela Inicial: Clique em "Começar Análise Dupla" para iniciar.

2.
Nomes: Insira os nomes das duas pessoas a serem analisadas.

3.
Upload de Imagens: Faça o upload de uma foto clara e de boa qualidade do pé de cada pessoa. A foto deve ser tirada de cima e de frente.

4.
Marcações: Siga as instruções para marcar pontos específicos nas imagens dos pés para a análise de formato e tamanho dos dedos.

5.
Classificação das Unhas: Responda a uma pergunta sobre a visibilidade das unhas.

6.
Relatório: Visualize o relatório de compatibilidade gerado e, opcionalmente, exporte-o para PDF.

Política de Privacidade e Termos de Uso

Conforme detalhado no próprio aplicativo, este projeto adere a uma rigorosa política de privacidade:

•
Coleta de Dados: Apenas os nomes são coletados para personalização do relatório e não são armazenados persistentemente.

•
Uso de Imagens: As imagens dos pés são processadas localmente no navegador do usuário e não são enviadas, armazenadas ou compartilhadas com o desenvolvedor ou terceiros. Elas são descartadas após a sessão.

•
Cookies e Rastreamento: O aplicativo não utiliza cookies de rastreamento de terceiros ou ferramentas de analytics que coletam dados pessoais.

•
Disclaimer Médico: O aplicativo não oferece diagnóstico médico, psicológico, quiroprático ou podológico. A análise é para fins de autoconhecimento e desenvolvimento pessoal.

Para os termos completos, consulte a seção "Termos Legais" dentro do aplicativo.

Aprimoramentos Futuros (Sugestões)

Com base em uma análise detalhada, algumas sugestões para aprimoramento incluem:

•
Experiência do Usuário (UX): Melhorar o feedback visual durante as marcações, validação de inputs mais robusta, e um indicador de progresso claro.

•
Performance: Otimização de imagens de exemplo e revisão do carregamento assíncrono de scripts.

•
Acessibilidade (A11y): Melhoria do contraste de cores, garantia de navegação por teclado e revisão de textos alternativos para imagens.

•
Manutenibilidade: Modularização do código JavaScript e uso de constantes para strings.

•
Novas Funcionalidades: Adição de um modo de análise individual, armazenamento local de relatórios e opções de compartilhamento direto.

Créditos
Desenvolvido por Irmo Zuccato Neto.
