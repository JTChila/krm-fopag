# 🚛 Sistema de Automação Inteligente FOPAG — KRM / JR / Kipper

Sistema Web 100% client-side para automação do fechamento da Folha de Pagamento (FOPAG) dos motoristas Mensalistas e Comissionados.

## 🎯 Como Usar (Passo a Passo Rápido para a Natani)

1. **Acesse o Sistema:**
   - **Pela Internet (no computador da KRM):** Acesse o link do GitHub Pages e digite a senha de acesso (`krm2026`).
   - **No Computador Local:** Dê dois cliques em `ABRIR_SISTEMA_KRM.bat` ou abra `index.html`.
2. **Escolha a Aba da Empresa:**
   - Selecione entre `KRM MENSAL`, `KRM COMISSAO`, `JR MENSAL`, `JR COMISSAO`, `KIPPER MENSAL` ou `KIPPER COMISSAO`.
3. **Digite Somente os Valores que Vêm na Mão:**
   - **Azul (`D`, `E`, `Z`):** Garantia Mínima (use o botão `/30` ao lado se houve férias/atestado), Comissão e Adiantamento Quinzenal.
   - **Verde (`Y`):** Salário Ficha / Vale Ficha (sua meta líquida).
   - **Amarelo (`AL` até `AO`):** Farmácia, Plano de Saúde, Vale e Empréstimo CEF.
   - *Dica:* Ao digitar um valor e apertar **Enter**, o cursor desce automaticamente para o motorista de baixo na mesma coluna (igual ao Excel!).
4. **O Robô Calcula as Diárias e Horas Sozinho (Colunas Roxas):**
   - Com a opção `⚡ Auto-Completar Horas ao Digitar` marcada, o sistema calcula automaticamente `Dias Diária (F)`, `Art. 66 (I/K)`, `Adicional Noturno (M)` e `Horas Extras 50%/100% (O/S)` descontando DSR, INSS 2026 e IRRF 2026 para cravar **`AJUSTE (W) = R$ 0,00`**!
   - Quer travar uma quantidade específica de diárias e ajustar só as horas? Digite as diárias na coluna `F` e clique no botão **`🎯`** no final da linha.
5. **Baixe a Planilha Pronta para o Excel (`.xlsx`):**
   - Clique no botão verde **`📥 Baixar Excel Pronto (.xlsx)`** no topo da tela.
   - O sistema gera a planilha `.xlsx` original da KRM com todas as cores, bordas, cabeçalhos e fórmulas preservadas!

