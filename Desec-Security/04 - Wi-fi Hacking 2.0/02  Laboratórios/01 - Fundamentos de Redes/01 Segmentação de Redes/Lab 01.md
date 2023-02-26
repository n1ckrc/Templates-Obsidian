
## Lab 01 - Segmentação de Redes 

Lab ID: 792e04be494960696a655ff69dd5bde47c3d5c3e

  
Enunciado: Em uma rede de notação CIDR /25 para máscara de rede.  
Quantos endereços são possíveis por cada rede?

**R** - 


---


### Solução do Desafio

Existem diversas maneiras de descobrirmos este resultado:

1. Podemos fazer o cálculo manualmente:

```
Esse cálculo é feito tomando 2 elevado ao número de bits na máscara de rede menos 32. No caso de uma máscara de rede /25, isso seria 2^(25-32) = 128.
```

2. Podemos utilizar o ipcalc:

```bash
ipcalc 192.168.0.0/25
```

3. Podemos também utilizar uma calculadora online:

```http
https://www.iptp.net/pt_PT/iptp-tools/ip-calculator/
```

4. Outras referências:
```http
https://youtu.be/7tUEHsQR9ak 

https://brasilcloud.com.br/duvidas/o-que-e-uma-mascara-de-sub-rede-sub-mask/
```

---



>PS: Este é apenas um exemplo de como você pode registrar as soluções encontradas por você em cada um dos laboratórios. Seria interessante também que anotasse as suas dificuldades e todo passo a passo de como chegou a cada uma das soluções. Se utilizaar uma linha de comando com muitos parâmetros, descreva para que cada um deles serve. Depois faça uma breve reflexão do que foi possível aprender com o laboratório e caso tenha ficado alguma dúvida acione o suporte da Desec.