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
