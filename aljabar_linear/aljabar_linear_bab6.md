# Bab 6 - Ruang Hasil Kali Dalam

## Hasil Kali Dalam

Sebelumnya telah dipelajari dot product yaitu operasi vektor yang hanya bisa digunakan di ruang $ R^n $. Ternyata operasi dot product ini bisa digenerelasikan untuk digunakan di semua ruang vektor. Operasi dot product yang digenerelasikan ini dinamakan **Hasil Kali Dalam**.

Untuk mendefinisikan suatu operasi **Hasil Kali Dalam** dari dua vektor, operasi **Hasil Kali Dalam** untuk harus memenuhi keempat aksioma ini:

$$\text{misal} \ u,\ v\ dan\ w\ \text{adalah} \ vektor\ \text{dan} \ \alpha \ \text{adalah\ skalar,\ maka}\\
1.\ \langle u+v,w\rangle =\langle u,w\rangle +\langle v,w\rangle \\
2.\ \langle \alpha v,w\rangle =\alpha \langle v,w\rangle \\
3.\ \langle v,w\rangle =\langle w,v\rangle \\
4.\ \langle v,v\rangle \geq 0\ and\ \langle v,v\rangle = 0,\ if\ and\ only\ if\ v=0\\ $$

Perhatikan bahwa $ \langle ,\rangle $ adalah tanda **Hasil Kali Dalam**.

**Ruang Hasil Kali Dalam** adalah ruang vektor yang telah didefinisikan operasi **Hasil Kali Dalam**.

### Contoh Soal

1. Tentukan Hasil Kali Dalam dari vektor $ u = (1, 2, 4) $ dan $ v = (2, 5, 7) $ jika Hasil Kali Dalam didefinisikan sebagai:

$$ \langle u,v\rangle = 4u_{1} v_{1} +2u_{2} v_{2} +7u_{3} v_{3} $$

Jawaban :

$$ \langle u,v\rangle = 4*1*2 + 2*2*5 + 7*4*7 \\
\langle u,v\rangle = 224 $$

Hasil Kali Dalam yang seperti ini dinamakan **Hasil kali dalam euclidian berbobot**. Didefinisikan seperti:

$$ \langle u,v\rangle = w_{1}u_{1} v_{1} +w_{2}u_{2} v_{2} + ... +w_{n}u_{n} v_{n} $$

## Panjang dan jarak di Ruang Hasil Kali Dalam

Jika di ruang Euclidian panjang didefinisikan sebagai:

$$ \Vert u\Vert = (u \cdot u)^{\frac{1}{2}} $$

Dan jarak antara dua vektor didefinisikan sebagai:

$$ d(u,v) = \Vert u-v\Vert = [(u-v) \cdot (u-v)]^{\frac{1}{2}} $$

Rumus ini juga berlaku di **Hasil Kali Dalam**. Definisi panjang dan jarak di ruang vektor sembarang adalah:

$$ \text{Jika} \ V\ \text{adalah\ sebuah\ ruang\ hasil\ kali\ dalam,maka\ norm\ atau\ panjang\ }\\
\text{sebuah\ vektor} \ u\ \text{di\ dalam} \ V\ \text{didefinisikan\ sebagai} :\\
\Vert u\Vert =\langle u,u\rangle ^{\frac{1}{2}} ​\ \ $$
