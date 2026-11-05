# fronteira-elastica-v3.py
# Fronteira Elastica v3.0 - Modelo teorico-analitico A=0.07*alpha. Previsao falseavel para LiteBIRD, JWST e NanoGrav.
# Fronteira Elastica v3.0 - Cicatriz Termica na CMB
# Autor: Rogerio A. Silva - Licenca MIT
# Equacao principal: A = 0.07 * alpha

alpha = [0, 0.2, 0.4, 0.6, 0.8, 1.0]
for a in alpha:
    A = 0.07 * a
    print(f"Se alpha={a}, Assimetria A={A:.3f}")

print("---")
print("Se LiteBIRD medir A < 0.01, modelo descartado")
print("Direcao: (l,b)=(237,-10) Eixo do Mal")

# Fronteira Elástica v3.0

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.23989679.svg)](https://doi.org/10.5281/zenodo.23989679)

**DOI oficial:** https://doi.org/10.5281/zenodo.23989679
**Autor:** Rogério A. Silva - Pesquisador Independente

## Equação Principal (A Cicatriz Térmica)
A nossa predição falseável é:

**A = 0.07 * alpha**

Onde:
- **A** = Assimetria da CMB
- **alpha** = Parâmetro da fronteira elástica

## Teste Falseável (Regra de Ouro)
> Se o satélite LiteBIRD medir A < 0.01, o modelo está DESCARTADO.

## Direção no Céu
Onde procurar a cicatriz: **(l, b) = (237, -10)**

## Código
Arquivo principal: `fronteira-elastica-v3.py` / `modelo.py`
