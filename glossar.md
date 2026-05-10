de: __teilerfremd, relativ prim__  
en: __relatively primve, coprime__  
Zwei natürliche Zahlen $a$ und $b$ sind teilerfremd $(a \perp b)$, wenn es keine natürliche Zahl außer der Eins gibt, die beide Zahlen teilt. Synonym ist relativ prim, aus dem Englischen relatively prime oder coprime. Wenn zwei natürliche Zahlen keinen gemeinsamen Primfaktor haben, sind sie teilerfremd.  
https://de.wikipedia.org/wiki/Teilerfremdheit

de: __Primitivwurzel__  
en: __primitive root__  
Die definierende Eigenschaft einer Primitivwurzel ist, dass jedes Element der primen Restklassengruppe als eine ihrer Potenzen dargestellt werden kann.  
https://de.wikipedia.org/wiki/Primitivwurzel  
https://en.wikipedia.org/wiki/Primitive_root_modulo_n

de: __prime Restklassengruppe__  
https://de.wikipedia.org/wiki/Prime_Restklassengruppe

de: __Eulersche Phi-Funktion__  
en: __Euler's totient function__  
math: $\varphi(n)$  
Sie gibt für jede positive natürliche Zahl $n$ an, wie viele zu $n$ teilerfremde positive natürliche Zahlen es gibt, die nicht größer als $n$ sind.  
Für eine Primzahl $p$ gilt, sie hat $\varphi(p-1)$ Primitivwurzeln.  
Beispiel: $\varphi(12)$ = 4 $\rightarrow$ 13 hat 4 Primitivwurzeln.  
https://de.wikipedia.org/wiki/Eulersche_Phi-Funktion  
https://en.wikipedia.org/wiki/Euler%27s_totient_function  
https://de.wikipedia.org/wiki/Diffie-Hellman-Schl%C3%BCsselaustausch#Prime_Restklassengruppe_und_Primitivwurzel

de: __Diffie-Hellman-Schlüsselaustausch, Diffie-Hellman-Merkle-Schlüsselaustausch, DHM-Schlüsseltausch__  
en: __Diffie–Hellman key exchange, DH key exchange__  
Beide Seiten berechnen den gleichen Schlüssel.  
Ein Abhörer kann denn Schlüssel nur schwer bestimmen.

$a$: privater Schlüssel von Alice  
$b$: privater Schlüssel von Bob  
$p$: öffentlich bekannte Primzahl  
$g$: öffentlich bekannte natürliche Zahl kleiner als p  
$A$: öffentlicher Schlüssel von Alice; $A = g^a \mod p$  
$B$: öffentlicher Schlüssel von Bob; $B = g^b \mod p $  
$K_a$: geheimer Sitzungs-Schlüssel für Alice  
$K_b$: geheimer Sitzungs-Schlüssel für Bob

$$ K_a = B^a \mod p = (g^b \mod p)^a \mod p $$
$$ K_b = A^b \mod p = (g^a \mod p)^b \mod p $$

Beide Schlüssel sind gleich $K=K_a=K_b$, weil:

$$ K = (g^a \mod p)^b \mod p = g^{ab} \mod p = (g^b \mod p)^a \mod p $$


https://de.wikipedia.org/wiki/Diffie-Hellman-Schl%C3%BCsselaustausch  
https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange
