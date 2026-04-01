# Simulado - Criptografia (Completo)

**Nome:** Victor Gabriel Silva
**Curso:** Engenharia de Software

---

## Bloco 1: Histórico da Criptografia (Questões 1 a 12)

**1. Qual é considerada a primeira cifra conhecida, descrita no Antigo Testamento, que substituía a primeira letra do alfabeto pela última?**

A) Cifra de César

B) Cifra de Vigenère

**C) Cifra de Atbash**

D) Cifra de Enigma

---

**2. A Cifra de César, utilizada por Júlio César para correspondência secreta, é classificada como:**

A) Uma cifra de transposição

**B) Uma cifra de substituição monoalfabética com deslocamento fixo**

C) Uma cifra polialfabética

D) Uma cifra de fluxo digital

---

**3. Qual dispositivo criptográfico da Grécia Antiga consistia em um bastão de madeira onde uma tira de pergaminho era enrolada para escrever a mensagem longitudinalmente?**

A) O Disco de Cifra de Alberti

B) A Máquina Enigma

**C) A Scytale**

D) O Quadrado de Políbio

---

**4. Qual cifra, desenvolvida na França no século XVI, utilizava uma palavra-chave e uma tabela para aplicar deslocamentos variáveis, tornando-se conhecida como "le chiffre indéchiffrable" (o cifra indecifrável)?**

A) Cifra de Playfair

B) Cifra de Hill

**C) Cifra de Vigenère**

D) Cifra de Beaufort

---

**5. A Máquina Enigma, utilizada pela Alemanha na Segunda Guerra Mundial, implementava qual tipo de cifra?**

A) Cifra de substituição monoalfabética

**B) Cifra de substituição polialfabética com rotores**

C) Cifra de transposição simples

D) Cifra de fluxo digital

---

**6. Quem liderou a equipe em Bletchley Park que conseguiu quebrar o código da Máquina Enigma durante a Segunda Guerra Mundial?**

A) Whitfield Diffie

B) Ron Rivest

**C) Alan Turing**

D) Philip Zimmerman

---

**7. Em que ano foi publicado o artigo "New Directions in Cryptography", que introduziu o conceito de criptografia de chave pública?**

A) 1945

**B) 1976**

C) 1985

D) 1991

---

**8. Quem foram os autores do artigo "New Directions in Cryptography", marco fundamental para a criptografia assimétrica?**

A) Rivest, Shamir e Adleman

**B) Diffie e Hellman**

C) Daemen e Rijmen

D) Schneier e Kelsey

---

**9. O programa PGP (Pretty Good Privacy), criado por Philip Zimmerman em 1991, foi importante porque:**

A) Foi o primeiro algoritmo de criptografia simétrica do governo dos EUA

**B) Democratizou o uso da criptografia assimétrica para o público em geral, protegendo e-mails e arquivos**

C) Foi o primeiro algoritmo de troca de chaves da história

D) Substituiu completamente o algoritmo RSA

---

**10. Qual foi o primeiro algoritmo de criptografia simétrica amplamente adotado como padrão governamental pelos EUA em 1977?**

A) AES

B) Blowfish

**C) DES (Data Encryption Standard)**

D) RC4

---

**11. Em 2001, qual algoritmo foi oficialmente adotado pelo NIST para substituir o DES, tornando-se o padrão global de criptografia simétrica?**

A) Triple-DES

B) Blowfish

C) Twofish

**D) AES (Advanced Encryption Standard)**

---

**12. Qual foi o principal motivo para a substituição do DES pelo AES?**

A) O DES era muito rápido e consumia pouca energia

**B) O DES tinha chave de 56 bits, tornando-se vulnerável a ataques de força bruta**

C) O DES não era compatível com computadores modernos

D) O DES era um algoritmo de código aberto sem suporte governamental

---

## Bloco 2: Algoritmos de Criptografia Simétrica (Questões 13 a 26)

**13. A principal característica da criptografia simétrica é:**

A) Utilizar um par de chaves: uma pública e uma privada

**B) Utilizar a mesma chave tanto para cifrar quanto para decifrar a mensagem**

C) Não utilizar chaves, apenas algoritmos de hash

D) Utilizar três chaves diferentes para cada operação

---

**14. Qual é a principal vantagem da criptografia simétrica em relação à assimétrica?**

A) Maior segurança matemática

**B) Maior eficiência computacional e velocidade para grandes volumes de dados**

C) Não requer distribuição de chaves

D) É resistente a ataques quânticos

---

**15. Como são classificadas as cifras que processam cada bit ou byte individualmente em tempo real, geralmente mais rápidas para hardware com recursos limitados?**

A) Cifras de bloco (block ciphers)

**B) Cifras de fluxo (stream ciphers)**

C) Cifras de transposição

D) Cifras de substituição

---

**16. Qual é o tamanho de bloco e o tamanho de chave do algoritmo DES (Data Encryption Standard)?**

A) Bloco 128 bits, chave 128 bits

**B) Bloco 64 bits, chave 56 bits**

C) Bloco 256 bits, chave 128 bits

D) Bloco 64 bits, chave 64 bits

---

**17. O Triple-DES (3DES) aplica o algoritmo DES três vezes. Qual é a principal vulnerabilidade que ainda o torna suscetível a ataques como o "Sweet 32"?**

A) O tamanho da chave de 56 bits

**B) O pequeno tamanho de bloco de 64 bits**

C) O uso de apenas uma rodada de criptografia

D) A ausência de suporte a hardware moderno

---

**18. Qual algoritmo simétrico foi desenvolvido por Joan Daemen e Vincent Rijmen e selecionado pelo NIST em 2001 como padrão global?**

A) DES

B) 3DES

**C) AES (Rijndael)**

D) Twofish

---

**19. Quais são os tamanhos de chave suportados pelo AES (Advanced Encryption Standard)?**

A) 56, 112 e 168 bits

B) 64, 128 e 256 bits

**C) 128, 192 e 256 bits**

D) 256, 512 e 1024 bits

---

**20. Qual cifra de fluxo, amplamente utilizada em protocolos SSL/TLS e WEP, foi considerada quebrada e não é mais considerada segura?**

A) AES-GCM

B) ChaCha20

**C) RC4**

D) Salsa20

---

**21. Qual algoritmo simétrico foi desenvolvido por Bruce Schneier em 1993 como uma substituição ao DES, mas é limitado pelo seu tamanho de bloco de 64 bits?**

A) Twofish

**B) Blowfish**

C) Serpent

D) Camellia

---

**22. Qual algoritmo, também desenvolvido por Bruce Schneier, foi finalista da competição do AES e utiliza bloco de 128 bits com chaves de até 256 bits?**

A) Blowfish

B) RC6

**C) Twofish**

D) SEED

---

**23. O algoritmo Camellia, desenvolvido no Japão, é amplamente utilizado em qual contexto?**

A) Apenas em sistemas governamentais japoneses

**B) Em protocolos IPSec e OpenPGP, sendo aprovado por diversos padrões internacionais**

C) Exclusivamente em sistemas embarcados

D) Apenas em criptomoedas

---

**24. Qual algoritmo simétrico é o padrão nacional da China, utilizado em aplicações governamentais e financeiras no país?**

A) SEED

B) ARIA

**C) SM1 / SM4**

D) Magma

---

**25. Em relação à segurança do AES-256 frente à computação quântica, qual afirmação é correta?**

A) Será completamente quebrado pelo algoritmo de Shor

**B) Manterá segurança equivalente a uma chave de 128 bits devido ao algoritmo de Grover**

C) Será mais vulnerável que o AES-128

D) Não haverá impacto algum na segurança

---

**26. Qual é o algoritmo simétrico recomendado atualmente para a maioria das aplicações que exigem alto nível de segurança?**

A) DES

B) Triple-DES

C) RC4

**D) AES-256**

---

## Bloco 3: Algoritmos de Criptografia Assimétrica (Questões 27 a 40)

**27. Qual é a principal característica da criptografia assimétrica (chave pública)?**

A) Utiliza a mesma chave para cifrar e decifrar

**B) Utiliza um par de chaves matematicamente relacionadas: uma pública e uma privada**

C) Não utiliza chaves, apenas funções hash

D) Utiliza três chaves diferentes para cada operação

---

**28. Qual foi o primeiro algoritmo de chave pública publicado, desenvolvido por Whitfield Diffie e Martin Hellman em 1976?**

A) RSA

B) DSA

**C) Diffie-Hellman**

D) ECC

---

**29. Qual é a principal função do algoritmo Diffie-Hellman?**

A) Cifrar mensagens de forma assimétrica

B) Gerar assinaturas digitais

**C) Permitir a troca segura de chaves entre duas partes em um canal inseguro**

D) Compactar dados criptografados

---

**30. Qual é a principal vulnerabilidade do algoritmo Diffie-Hellman quando utilizado isoladamente?**

A) É extremamente lento para qualquer aplicação prática

**B) É vulnerável a ataques de homem-no-meio (Man-in-the-Middle)**

C) Não suporta chaves maiores que 1024 bits

D) Foi completamente quebrado em 2010

---

**31. O algoritmo RSA, desenvolvido em 1977, tem sua segurança baseada na dificuldade de resolver qual problema matemático?**

A) Logaritmo discreto

B) Problema da mochila

**C) Fatoração de números inteiros grandes**

D) Problema dos três corpos

---

**32. Quem são os criadores do algoritmo RSA, que se tornou o padrão de fato para criptografia assimétrica?**

A) Diffie e Hellman

**B) Rivest, Shamir e Adleman**

C) Daemen e Rijmen

D) Koblitz e Miller

---

**33. Por que o RSA não é utilizado para cifrar grandes volumes de dados diretamente?**

A) Porque não é seguro para grandes volumes

**B) Porque é 10 a 1.000 vezes mais lento que algoritmos simétricos**

C) Porque não suporta chaves grandes o suficiente

D) Porque foi patenteado e não pode ser usado comercialmente

---

**34. Qual é a abordagem típica para utilizar o RSA na prática?**

A) Utilizar o RSA para cifrar todo o conteúdo da mensagem

**B) Utilizar o RSA apenas para cifrar uma chave de sessão simétrica (como AES), que então cifra o conteúdo**

C) Utilizar o RSA apenas para compressão de dados

D) Utilizar o RSA como substituto completo de algoritmos simétricos

---

**35. O DSA (Digital Signature Algorithm) foi desenvolvido para qual finalidade específica?**

A) Cifragem de mensagens

B) Troca de chaves

**C) Assinatura digital**

D) Compactação de dados

---

**36. Qual é a principal vantagem da criptografia de curvas elípticas (ECC) em relação ao RSA?**

A) É mais antiga e mais testada

**B) Oferece o mesmo nível de segurança com chaves significativamente menores e menor custo computacional**

C) É resistente a ataques de força bruta

D) Não requer distribuição de chaves

---

**37. Para oferecer segurança equivalente a uma chave RSA de 3.072 bits, qual seria o tamanho aproximado de uma chave ECC?**

A) 160-223 bits

B) 224-255 bits

**C) 256-383 bits**

D) 512+ bits

---

**38. Qual algoritmo assimétrico é amplamente utilizado em dispositivos móveis e sistemas com recursos computacionais limitados devido à sua eficiência?**

A) RSA com chave de 4096 bits

**B) ECDSA (Elliptic Curve Digital Signature Algorithm)**

C) DSA com chave de 2048 bits

D) Diffie-Hellman com chave de 1024 bits

---

**39. De acordo com a tabela de segurança equivalente, qual chave RSA oferece segurança comparável a uma chave ECC de 256-383 bits?**

A) 1.024 bits

B) 2.048 bits

C) 3.072 bits

**D) 7.680 bits**

---

**40. Qual ameaça futura representa o maior desafio para os algoritmos assimétricos atuais como RSA, ECC e Diffie-Hellman?**

A) Ataques de força bruta com computadores clássicos

**B) Desenvolvimento de computadores quânticos em larga escala com o algoritmo de Shor**

C) Aumento do custo da energia elétrica para computação

D) Patentes que impedem a adoção em larga escala

---