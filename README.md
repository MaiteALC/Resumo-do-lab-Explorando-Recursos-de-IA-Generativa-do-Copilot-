# Resumo-do-lab-Explorando-Recursos-de-IA-Generativa-do-Copilot
Explorando recursos de IA Generativa do Microsoft Copilot
Foram inseridos alguns prompts no aplicativo mobile do Copilot, todos no contexto de vinculação do excel com Python. Além disso os resultados gerados foram comparados com os gerados pelo Google Gemini (a título de curiosidade) porém serão listadas as respostas apenas do Copilot.

Prompts utilizados no Microsoft Copilot:
1) como posso usar python no excel?
2) Quais bibliotecas Python são mais úteis para o Excel?
3) Me dê uma introdução sobre o openpyxl

Respostas (na mesma ordem dos Prompts):
1) Você pode usar **Python no Excel** de várias maneiras! A Microsoft integrou o Python diretamente ao Excel, permitindo que você escreva e execute código Python dentro das células. Aqui estão algumas formas de utilizá-lo:

- **Usando a função `=PY`**: Basta digitar `=PY("seu código Python")` em uma célula para executar scripts diretamente.
- **Manipulação de dados com Pandas**: Você pode importar bibliotecas como `pandas` e `numpy` para trabalhar com tabelas e cálculos avançados.
- **Criação de gráficos**: Utilize `matplotlib` e `seaborn` para gerar visualizações diretamente no Excel.
- **Automação de tarefas**: Python pode ser usado para automatizar processos repetitivos, como análise de dados e relatórios.

Se quiser um guia mais detalhado, confira este [tutorial oficial da Microsoft](https://support.microsoft.com/pt-br/office/introdu%C3%A7%C3%A3o-ao-python-no-excel-a33fbcbe-065b-41d3-82cf-23d05397f53d) ou assista a este [vídeo explicativo](https://www.youtube.com/watch?v=SKR1FrojC-k). Quer que eu te ajude com um exemplo prático? 🚀

2) Aqui estão algumas das **bibliotecas Python mais úteis para o Excel**:

- **pandas** – Ideal para manipulação e análise de dados em tabelas.
- **openpyxl** – Permite ler, escrever e modificar arquivos `.xlsx`.
- **xlrd** – Usado para ler arquivos `.xls` antigos.
- **xlwt** – Para escrever arquivos `.xls`.
- **XlsxWriter** – Gera arquivos `.xlsx` com formatação avançada.
- **xlwings** – Integra Python diretamente ao Excel, permitindo automação.
- **pywin32** – Interage com o Excel via COM para automação avançada.

Se quiser ver exemplos práticos, confira este [vídeo explicativo](https://www.youtube.com/watch?v=TtLQ6zxdHQs) sobre o uso de Python no Excel! 🚀


3) O **openpyxl** é uma biblioteca Python poderosa para manipular arquivos do Excel (`.xlsx`). Com ela, você pode **ler, escrever, modificar e automatizar** planilhas sem precisar abrir o Excel manualmente. Algumas funcionalidades incluem:

- **Criar e editar planilhas**: Adicionar, remover e modificar células e abas.
- **Manipular dados**: Ler e escrever valores, aplicar fórmulas e formatar células.
- **Automação**: Processar grandes volumes de dados e gerar relatórios automaticamente.
- **Gráficos e imagens**: Criar gráficos e inserir imagens diretamente nas planilhas.

Se quiser um guia prático, confira este [tutorial oficial](https://openpyxl.readthedocs.io/en/stable/tutorial.html) ou assista a este [vídeo completo](https://www.youtube.com/watch?v=BUigYkNU3GE) sobre automação com openpyxl! 🚀 Quer que eu te ajude com um exemplo de código?


Conclusões + comparação entre Copilot e Gemini:
O Copilot (versão Quick Response) embora mais rápido que o Gemini, dá respostas mais objetivas e curtas além de sugerir links e vídeos mo YouTube relacionados a pergunta. O Gemini (versão 2.5 flash) por outro lado se mostrou um pouco mais lento, mas com respostas mais detalhadas e sem a recomendação de vídeos. Em resumo, o Copilot se mostrou mais útil (e rápido) para perguntas cotidianas. 
Obs: Ambos apresentaram uma escrita bem humanizada e amigável.
Obs 2: Ao serem pedidos para gerar uma imagem ilustrativa sobre o tema de integração python/excel ambos geraram uma imagem relativamente simples, mas o Copilot foi mais simplificado focando apenas nos ícones, enquanto o Gemini utilizou ilustrações de ícones e janelas do excel e de um código para representar esse vínculo.
