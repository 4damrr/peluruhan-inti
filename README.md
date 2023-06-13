# peluruhan-inti
Peluruhan inti atom menggunakan solusi analitik umum oleh Dobromir (2002).

Pada kebanyakan _textbook_, penyelesaian persamaan peluruhan radioaktif berantai dilakukan secara analitik untuk maksimal tiga nuklida. Dobromir (2002) menawarkan solusi secara analitik yang lebih umum sebagai berikut,
$$N_i(t)=N_{10}\lambda_{i-1}\lambda_{i-2}...\lambda_1 \sum_{k=1}^{i}\dfrac{\exp{\left(-\lambda_kt\right)}}{\prod_{j=1,j\neq k}^{i}\left(\lambda_j-\lambda_k\right)}+N_{m0}\lambda_{i-1}...\lambda_m$$

Untuk penurunan yang lebih lengkap, dapat diakses pada [link berikut](https://pubs.aip.org/aapt/ajp/article-abstract/70/4/444/1042385/Short-solution-of-the-radioactive-decay-chain?redirectedFrom=fulltext).
