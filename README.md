# My Public CTF Challenges

This repo is for collecting all my non-trivial public CTF challenges, since I find they scatter at different positions now. And the format is partially inspired by [Law](https://github.com/l4wio/CTF-challenges-by-me).

For the `Flag Source` column I just record where I find the flag for this challenge, which is not related to the solutions and you can just ignore it.

Name | Event | Category | Difficulty | Comment | Flag Source
--- | --- | --- | --- | --- | --- |
[notfeal](https://github.com/sixstars/starctf2019/tree/master/crypto-notfeal) | *ctf 2019 | Crypto | Medium | Differential cryptanalysis of modified FEAL. This challenge is not interesting enough but rather a good practice to get into cryptanalysis details | /
[babyprng](https://github.com/sixstars/starctf2019/tree/master/crypto-babyprng) | *ctf 2019 | Crypto | Easy | Basic von Neumann extractor (notice that babyprng2 credits to zzj, not me) | /
[zer0des](https://github.com/Septyem/0ctf_tctf_2019/tree/master/zer0des) | 0CTF/TCTF 2019 Quals | Crypto | Hard | Breaking 8-round DES with differential-linear cryptanalysis. You are supposed to find more differential paths yourself. Due to heavy traffic required in test, I did not use 9-round, which makes it easier to solve | *[The Brothers Karamazov](https://en.wikipedia.org/wiki/The_Brothers_Karamazov)*
[zer0mi](https://github.com/Septyem/0ctf_tctf_2019/tree/master/zer0mi) | 0CTF/TCTF 2019 Quals | Crypto | Hard | Breaking Matsomoto-Imai cryptosystem by algebraic attack and solving linear equations | *Le Deuil des primevères*
[babysponge](https://github.com/Septyem/0ctf_tctf_2019/tree/master/babysponge) | 0CTF/TCTF 2019 Quals | Crypto | Medium Easy | Finding hash collisions by meet-in-the-middle attack for the sha-3 sponge construction with a extremely small capacity | *[Pale Fire](https://en.wikipedia.org/wiki/Pale_Fire)*
[If on a winters night a traveler](https://github.com/Septyem/0ctf_tctf_2019/tree/master/If_on_a_winter's_night_a_traveler) | 0CTF/TCTF 2019 Quals | Pwn | Medium | Pwning integer overflow in a customized encryption method for vim. I take the self-reference idea from Calvino | *[Miguel Street](https://en.wikipedia.org/wiki/Miguel_Street)*
[Proof of Work](https://github.com/Septyem/0ctf_tctf_2018/tree/master/Proof_of_Work) | 0CTF/TCTF 2018 Finals | Crypto | Hard | Implementing collision for MD5-like hash function with given prefix. As far as I know no one designed CTF challenges about MD5 collision internals before | *[The Garden of Forking Paths](https://en.wikipedia.org/wiki/The_Garden_of_Forking_Paths)*
[ibe](https://github.com/Septyem/0ctf_tctf_2018/tree/master/ibe) | 0CTF/TCTF 2018 Finals | Crypto | Medium | Using identity-based encryption (Cocks IBE scheme) but the key point is utilizing discriminator in quadratic residue. The task is not very natural but in general the idea is not bad | /
[primitive](https://github.com/sixstars/starctf2018/tree/master/crypto-primitive) | *ctf 2018 | Crypto | Medium Hard | Building any given permutations with add, rotate, xor only. Since the number of operation is limited you should also optimize your construction | /
[ssss/ssss2](https://github.com/sixstars/starctf2018/tree/master/crypto-ssss-ssss2) | *ctf 2018 | Crypto | Medium | Xor key reuse issue for AES_CTR. And the scripts imitate the process of WPA2 which have state inconsistency issue and are vulnerable to KRACK-style attack. In fact I think this challenge is not concise enough | /
[yafu](https://github.com/sixstars/starctf2018/tree/master/misc-yafu) | *ctf 2018 | Misc | Medium | Logical bugs inside yafu and I just want to show how weak our daily crypto tools can be | /
[stackoverflow](https://github.com/sixstars/starctf2018/tree/master/pwn-stackoverflow) | *ctf 2018 | Pwn | Medium | Trivial stack overflow without special chars like `\x00` | /
[rsa](https://github.com/Septyem/starctf-2017/tree/master/rsa) | *ctf 2017 | Crypto | Easy | Factoring big integer using Pollard's rho algorithm | *[Memoirs of Hadrian](https://en.wikipedia.org/wiki/Memoirs_of_Hadrian)*
[sql](https://github.com/Septyem/starctf-2017/tree/master/sql) | *ctf 2017 | Reverse | Easy | Reversing SQLite3 bytecode and recover the sql query | /
[compCipher](https://github.com/Septyem/starctf-2017/tree/master/compCipher) | *ctf 2017 | Pwn/Crypto | Easy | This challenge is for beginners and has nothing special | / |
