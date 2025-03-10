# FiapCap1Fase5

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto
FarmTech na era da cloud computing

## 👨‍🎓 Integrantes: 
Gustavo Beu Gomes RM:560543

## 📜 Descrição 
1. Descrição do Projeto
Título do Projeto: Previsão de Rendimento Agrícola utilizando Machine Learning
Descrição Geral: Este projeto visa fornecer insights e previsões sobre o rendimento agrícola de uma fazenda de médio porte (200 hectares). Utilizando técnicas de machine learning supervisionado e não supervisionado, o objetivo é identificar tendências de produtividade, detectar outliers e prever o rendimento com base em variáveis meteorológicas e de solo. A análise é fundamentada no conjunto de dados fornecido, com variáveis que representam condições climáticas, tipo de cultura e rendimento histórico.

Objetivo da Entrega 1
Familiarizar-se com os dados: Realizar uma análise exploratória para entender as relações entre as variáveis e os padrões observáveis.
Clusterização: Identificar padrões e tendências nos dados por meio de agrupamentos, além de destacar possíveis outliers.
Modelagem Preditiva: Construir cinco modelos de machine learning supervisionados, utilizando diferentes algoritmos, para prever o rendimento agrícola com base nos dados fornecidos.

2. Descrição da Entrega 2
Título da Entrega: Hospedagem da Solução de Machine Learning na Nuvem

Descrição Geral:
Nesta segunda entrega, o foco está na escolha de uma infraestrutura de computação em nuvem para hospedar a solução de Machine Learning desenvolvida na Entrega 1. O projeto demanda a configuração de uma máquina virtual que suporte a execução de uma API e os modelos de Machine Learning, bem como receba dados provenientes de sensores agrícolas. Essa infraestrutura será analisada com base em custos e restrições legais para armazenamento de dados.

## 🔧 Como executar o código
Parte 1: Previsão de Rendimento Agrícola utilizando Machine Learning
Esta parte do projeto foca na previsão do rendimento agrícola utilizando técnicas de Machine Learning baseadas nos dados fornecidos. Siga os passos abaixo para executar o código:

Pré-requisitos:

Python 3.9 ou superior instalado no sistema.
Bibliotecas Python necessárias instaladas:
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter (caso deseje rodar o código em um notebook).
Para instalar as bibliotecas, execute:

bash
Copiar
Editar
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
Carregar o Dataset:

Certifique-se de ter o arquivo crop_yield.csv no mesmo diretório do código.
O dataset contém as variáveis que serão usadas para treinar e testar os modelos.
Executar o Código:

Abra o arquivo pbl_fase4.ipynb no Jupyter Notebook ou rode o script Python diretamente no terminal.
Certifique-se de seguir as instruções comentadas no código para ajustar parâmetros, se necessário.
A análise envolve:
Limpeza e visualização de dados.
Criação de cinco modelos preditivos (Regressão Linear, Random Forest, etc.).
Avaliação de desempenho com métricas como MAE, MSE e R².

Parte 2: Hospedagem da Solução de Machine Learning na Nuvem
Esta parte aborda como configurar uma infraestrutura na nuvem (AWS) para hospedar a solução de Machine Learning.

Pré-requisitos:

Conta na AWS configurada e ativa.
Acesso à calculadora da AWS para estimar os custos da solução.
Familiaridade com o serviço EC2 na AWS.
Configuração da Máquina Virtual:

Acesse o painel da AWS e crie uma nova instância EC2.
Especificações da máquina virtual:
2 CPUs.
1 GiB de memória.
50 GB de armazenamento (HD).
Rede de até 5 Gigabit.
Escolha a região desejada:
São Paulo (BR) para atender a restrições legais de armazenamento.
Virgínia do Norte (EUA) para um custo menor.

## escolha:

Algumas legislações e regulamentações, como a LGPD (Lei Geral de Proteção de Dados) no Brasil, podem exigir que dados sensíveis ou críticos sejam armazenados dentro do território nacional. Escolher a região de São Paulo garante conformidade com essas exigências.
Menor Latência:

Para acessar rapidamente os dados dos sensores, é essencial ter baixa latência. Hospedar a infraestrutura na região de São Paulo, mais próxima dos sensores localizados no Brasil, reduz o tempo de resposta devido à proximidade geográfica.
Alta Disponibilidade Local:

A AWS oferece recursos robustos de redundância e disponibilidade, mesmo em uma única região, garantindo que os dados estejam acessíveis e seguros dentro do Brasil.
Custo Razoável:

Embora a região de São Paulo possa ter custos ligeiramente superiores à região da Virgínia do Norte, a escolha é justificada pela necessidade de atender a requisitos legais e operacionais prioritários.
Escalabilidade Local:

A região de São Paulo também oferece uma gama completa de serviços da AWS, permitindo que o sistema seja dimensionado conforme necessário sem a necessidade de mover dados para outra região.

