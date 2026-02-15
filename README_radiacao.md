# Conversor de Radiação (Rs → n)

Notebook Jupyter para converter **radiação solar global diária** `Rs` (MJ/m²/dia) em **horas de sol** `n` (h),
usando a relação de **Angström–Prescott** e cálculos astronômicos diários (FAO-56).

## Como usar
1. Abra o notebook `01_Conversor_Radiacao_Rs_para_n_organizado.ipynb`.
2. Edite `INPUT_DIR` e `OUTPUT_DIR`.
3. Rode tudo (Kernel → Restart & Run All).

## Entrada
CSV com separador `;` e colunas:
- `dia;mes;ano;valor`  (valor = Rs em MJ/m²/dia)

O nome do arquivo deve conter latitude/longitude no padrão:
`..._-25.125_-49.125.csv`
