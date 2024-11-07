# Teste A/B - PraCêAndo

## Integrantes
- Guilherme
- Fernanda

## Objetivo
Comparar duas versões da interface do aplicativo PraCêAndo — V1 (oficial) e V2 (nova) — para avaliar a eficácia das mudanças no design e na experiência do usuário.

## Metodologia
Foi criado um formulário para coletar dados de 30 participantes, divididos igualmente entre as duas versões (15 para V1 e 15 para V2). Os participantes foram avaliados quanto ao tempo médio gasto na tela "Home" de cada versão, além de responderem perguntas sobre facilidade de uso, organização visual e satisfação geral.

## Análise Estatística
Utilizamos o **Teste t-Student** para comparar a média de tempo gasto na tela "Home" entre as duas versões.

- **Estatística t**: 0.733
- **Valor p**: 0.470

Com um valor p superior a 0.05, concluímos que não há uma diferença estatisticamente significativa entre as duas versões em relação ao tempo de uso.

## Resultados
Os resultados sugerem que ambas as interfaces (V1 e V2) têm desempenho equivalente em termos de tempo gasto na tela "Home". A nova interface (V2) não apresentou melhorias significativas.

## Recomendações
- Avaliar outras métricas, como facilidade de uso e satisfação do usuário, para melhor entendimento da experiência.
- Considerar ajustes no design da V2 para melhorar a usabilidade e o engajamento.

## Como Executar
1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/teste-ab-praceando.git
   cd teste-ab-praceando
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute o script de análise:
   ```bash
   python teste_ab_analise.py
   ```

Para mais informações, entre em contato com os membros da equipe de dados:
- [Fernanda Leão](https://github.com/fernandaleaoleita)
- [Guilherme Barbosa](https://github.com/guii-barbosa)
