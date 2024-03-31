# estag_experience_itau
Aqui está presente meu projeto desenvolvido para o EstagExperience (Análise de dados nos negócios) do Itaú Unibanco

![image](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/be0060a0-1f7a-4f96-995e-8b66d7016ebd)

# Modelagem do banco de dados

Inicialmente, foram fornecidas cinco planilhas com dados fictícios de clientes. Sendo assim, decidi unitizar essas bases em fato e dimensão utilizando: Python (Pandas, SQLAlchemy) e Excel 

## Diagrama
obs: consultas fictícias, as mesmas são apenas rascunhos. A aplicação de forma tácita e coerente seria feito, posteriormente durante o processo de processamento dos dados.

![image](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/498aae9c-211e-46d0-a97a-14f4916c124d)


## Antes da modelagem:

![image](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/66d11d58-f3d7-4496-bd56-f80e2b6cc741)

## Após a modelagem:

Tabela Dimensão (dClientes)
![image](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/97768056-f745-40ea-a481-3e6dd59196ce)

Tabela Fato (fPagamentos)
![image](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/122f3444-df27-473a-9fbb-de9a05c5d365)

# Início da etapa de processamento dos dados utilizando Python, SQL (Alchemy), Pandas e implementação de um algoritmo de "Árvore de decisão".
Não obtive êxito na criação do modelo de machine learning, por conta da infíma quantidade de dados disponíveis.
## Código presente neste repositório, intitulado: "EstagExperince - DataProcessing"

# Visualização dos Dados
Nesta etapa, utilizei os seguintes programas: Paint (sim), Figma, Photoshop, PowerBI e utilização da linguagem DAX presente no PowerBI.

## Página 01 (Visão Geral)

Esboço:
![Página 01](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/cbdf6266-95ef-4ae1-aaf1-f0e5383fe463)

Versão Finalizada:
<img width="1280" alt="Template #1 (1)" src="https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/665e1f3e-8fe6-49eb-9af6-11926fe2c3ac">

## Página 02 (Análise de Risco)

Esboço:
![Página 02](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/72b48bbb-6ecf-4640-8a05-1b9f9497ae69)

Versão Finalizada:
<img width="1280" alt="Template #1 (2)" src="https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/c41292fb-da72-4991-8582-0fdd84602d9f">

## Página 03 (Recomendação de produtos)

Esboço:
![Página 03](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/1094820a-3955-4f09-a0db-b02733d53a44)

Versão Finalizada:
<img width="1280" alt="Template #1 (3)" src="https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/df285089-0a80-4578-b759-5b51a1ac39e3">


# Critérios utilizados para a definição de risco

## Critério de Endividamento:

Limita o total das parcelas do empréstimo a 30-40% da renda mensal do cliente.
Garante que o cliente não fique sobrecarregado com obrigações de pagamento.

## Critério de Propriedade de Imóveis:

Utilização do imóvel como garantia para o empréstimo, se disponível.
Indica estabilidade financeira e pode aumentar o patrimônio líquido do cliente.
O banco considera se o cliente possui imóveis próprios ao avaliar o risco de empréstimo.


## Critério do Tipo de Empréstimo:

Cada tipo de empréstimo tem seus próprios critérios de avaliação.
Para empréstimos educacionais, considera-se perspectivas de emprego e histórico acadêmico.
Empréstimos habitacionais são avaliados com base na capacidade de pagamento, valor do imóvel e estabilidade no emprego.
Empréstimos automotivos levam em conta o valor do veículo, histórico de crédito e possibilidade de uso do carro como garantia.
Empréstimos pessoais são avaliados principalmente com base na renda, histórico de crédito e estabilidade financeira do cliente.

## Diagrama (Risco de crédito)

![image](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/c92be715-2100-4bfc-800f-81cfb4e7f67b)

## Replicando o diagrama no código!! (Linguagem DAX)
Aplicação extremamente simples e intuitiva. Inicialmente, queria implementar o algoritmo de aprendizado de máquina (DecisionTree), todavia como havia falado anteriormente, por conta da quantidade escassa de dados, consequentemente de variações para definição concreta dos "galhos" da árvore, decidi seguir com um algoritmo baseado em Regras.

![image](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/5e0b36fd-263e-414d-a4f0-ed769f8e008e)

## Diagrama (Recomendação de produtos)

![Diagrama de recomendação](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/87634555-0e02-4da7-9c67-217f0918e49d)

## Replicando o diagrama no código!! (Linguagem DAX)
![image](https://github.com/ronaldosilvak/estag_experience_itau/assets/124167035/4a16de0c-70cb-457b-b468-76158c3b3fe1)

# Finalização

Queria agradecer a oportunidade de participar deste incrível treinamento e, para o pessoal que deseja estudar e ver de pertinho o dashboard criado após esse árduo seguimento de etapas, o mesmo está disponível neste link: {link} 

Bons estudos, obrigado Itaú Unibanco e muito obrigado a você por estar vendo meu projeto!!











