# 🤖 Agente de Planejamento Semanal de Dieta, Cardápio e Receitas 🥗📝

Este projeto é um agente inteligente em Python que utiliza o poder do Gemini para gerar um 
planejamento semanal completo, incluindo dieta, cardápio e receitas detalhadas. 
Ele foi desenvolvido como parte da Imersão IA da Alura.

-----

## ✨ Funcionalidades Principais

*   **Planejamento de Dieta Personalizado:** Define uma dieta com base nas suas preferências e necessidades (Ex: Semanal, Fitness, Sem Glúten).
*   **Criação de Cardápio Semanal:** Gera um cardápio detalhado para cada dia da semana, incluindo café da manhã, almoço e jantar.
*   **Geração de Lista de Compras:** Para cada item do cardápio, o agente agrupará os ingredientes necessários,somará as quantidades e motará uma lista de compras.
*   **Geração de Receitas Completas:** Para cada item do cardápio, o agente fornece a receita completa com ingredientes e modo de preparo.

-----

## 🚀 Como Funciona?

O agente opera em algumas etapas principais:

1.  **Configuração Inicial:** Define a chave da API do Google e inicializa o modelo generativo do Gemini.
2.  **Definição do Perfil:** O usuário informa o tipo de dieta desejada, restrições alimentares, preferências e outras informações relevantes.
3.  **Geração do Planejamento:** O agente envia um prompt construído com as informações do usuário para a API do Gemini.
4.  **Processamento da Resposta:** A resposta do Gemini, contendo o planejamento, é recebida e formatada.
5.  **Apresentação:** O planejamento completo (dieta, cardápio e receitas) é exibido para o usuário.

-----

## 🛠️ Bibliotecas Necessárias

Para executar este projeto, você precisará instalar as seguintes bibliotecas Python que já constam no notebook:

*   **google-genai:** Para interagir com a API do Gemini.
*   **google-adk:** Para criar agentes e executar agentes de IA.

## 🏃‍♀️ Como Usar

1.  **Clone o repositório (ou baixe o notebook).**
2.  **Abra o Notebook:** Utilize o Google Colab ou um ambiente Jupyter Notebook local.
3.  **Configure sua API Key:** No notebook, localize a seção onde a API Key do Google é configurada e insira a sua chave.
4.  **Execute as Células:** Siga as instruções do notebook, executando as células em ordem.
5.  **Interaja com o Agente:** Modifique as variáveis de entrada (calorias_diarias, preferencias e refeicoes) para personalizar seu planejamento.
6.  **Visualize o Resultado:** O planejamento será exibido no final da execução do notebook.

-----

## 📊 Exemplo de Resultado

📝 Resultado do Agente 1 (Nutricionista)

Com certeza! Aqui está um cardápio semanal de 2000 calorias, prático, econômico e variado, focado em ingredientes acessíveis e preparações que facilitam o dia a dia ou o planejamento das marmitas:


**Cardápio Semanal:**

**📆 Dia 1:**
- **Café da Manhã:**
    - Total de calorias: 350 kcal;
      - Pão integral (2 fatias - 100g) (264 kcal);
      - Ovos cozidos (2 unidades - 100g) (155 kcal);
- **Almoço:**
    - Total de calorias: 850 kcal;
      - Arroz integral cozido (150g) (172 kcal);
      - Feijão carioca cozido (1 concha - 150g) (159 kcal);
      - Peito de frango grelhado (150g) (173 kcal);
      - Brócolis cozido no vapor (1 xícara - 91g) (31 kcal);
      - Abobrinha refogada (1 xícara - 124g) (19 kcal);
      - Azeite extra virgem (1 colher de sopa - 13.5g) (120 kcal)
      - Laranja (1 unidade - 160g) (76 kcal)
- **Jantar:**
    - Total de calorias: 800 kcal;
      - Sopa de lentilha com legumes (350g) (450 kcal);
      - Pão integral (1 fatia - 50g) (132 kcal);
      - Iogurte natural integral (1 pote - 170g) (93 kcal);
      - Maçã (1 unidade média - 182g) (95 kcal);

```...```

**Observações:**
*   **Preparo em Lote:** A sopa de lentilha, o arroz integral, o feijão e o frango grelhado podem ser preparados em maior quantidade e armazenados na geladeira por até 5 dias ou congelados por até 3 meses.
*   **Marmitas:** Monte as marmitas com as porções adequadas de cada refeição para facilitar o consumo ao longo da semana.
*   **Lanches:** Se sentir fome entre as refeições, adicione uma fruta ou um punhado de castanhas como lanche.
*   **Variações:** Sinta-se à vontade para variar os legumes da salada e da sopa, utilizando aqueles que estiverem mais acessíveis e em época.
*    **Hidratação:** Beba bastante água ao longo do dia (pelo menos 2 litros) para auxiliar na digestão e no bom funcionamento do organismo.
*   **Ajustes:** Adapte as quantidades de acordo com sua necessidade individual e nível de atividade física.
*   **Consulta:** Consulte um profissional de nutrição para um plano alimentar personalizado e adequado às suas necessidades específicas.

-----

📝 Resultado do Agente 2 (Planejador de compras)

Com certeza! Aqui está a lista de compras organizada por categorias, com base no cardápio semanal fornecido:


**Lista de Compras Semanal:**

**🍓 Frutas:**
*   Laranja: 7 unidades

**🥦 Legumes:**
*   Tomate cereja: 20 unidades

**🐟 Proteínas:**
*   Peito de frango: 600g
*   Atum ao natural: 2 latas
*   Feijão carioca: 1.05 kg

```...```

-----

📝 Resultado do Agente 3 (Cozinheiro)

Com certeza! Aqui estão as receitas práticas e saudáveis para o seu cardápio semanal de 2000 calorias, focadas em ingredientes acessíveis e preparações simples para o dia a dia:

**Receitas Semanais:**

**Dia 1:**

```...```

- **🍽️ Almoço: Arroz integral com feijão, peixe assado e salada**
    - Receita original: [https://www.saboresajinomoto.com.br/receitas/peixe-assado-facil/](https://www.saboresajinomoto.com.br/receitas/peixe-assado-facil/)
    - **Ingredientes:**
        - Arroz integral cozido: 150g
        - Feijão carioca cozido: 1 concha (150g)
        - Peixe assado (tilápia, salmão, etc.): 150g
        - Alface, tomate e pepino: à vontade
        - Cenoura cozida no vapor: 100g
        - Azeite extra virgem: 1 colher de sopa (15ml)
        - Laranja: 1 unidade média (160g)
    - **Modo de Preparo:**
        1. Tempere o peixe com limão, sal e pimenta.
        2. Asse no forno até dourar.
        3. Sirva com arroz, feijão, salada e cenoura cozida.

```...```

-----
