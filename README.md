# ๐ค Transformer_Survey_Paper_Study ๐ค
![main](./img/tss_main.png)

**"A survey of Transformer"** paper study @DSBA Lab

๐ Paper : Lin, Tianyang, et al. "A Survey of Transformers." *arXiv preprint arXiv:2106.04554* (2021)  [[Link](https://arxiv.org/pdf/2106.04554.pdf)]



## 1. ์คํฐ๋ ์๊ฐ

#### 1) Members (@DSBA Lab )

๊ณ ๋ ค๋ํ๊ต ์ฐ์๊ฒฝ์๊ณตํ๊ณผ Data Science & Business Analytics Lab [[HomePage](http://dsba.korea.ac.kr/)] [[Youtube](https://www.youtube.com/channel/UCPq01cgCcEwhXl7BvcwIQyg/videos)] 

: Transformer์ NLP๋ฅผ ์ฌ๋ํ๋ ์ฐ๊ตฌ์ค ํ์๋ค๋ก ๊ตฌ์ฑ๋ ์คํฐ๋ ์๋๋ค ๐

|                 yukyung               |                 myeongsup                |              hoonsang               |                   jina                   |                   jaehyuk                   |                   subin                   |
| :------------------------------------------: | :-----------------------------------------: | :----------------------------------------: | :---------------------------------------------: | :---------------------------------------------: | :---------------------------------------------: |
| <img src="https://github.com/yukyunglee/Transformer_Survey_Study/blob/3254384e154ff2a3232a9fe723da36b1ceb92705/img/yk.jpg" width=150px> | <img src="https://github.com/yukyunglee/Transformer_Survey_Study/blob/3254384e154ff2a3232a9fe723da36b1ceb92705/img/ms.jpeg" width=150px> | <img src="https://github.com/yukyunglee/Transformer_Survey_Study/blob/3254384e154ff2a3232a9fe723da36b1ceb92705/img/hs.jpeg" width=150px> | <img src="https://github.com/yukyunglee/Transformer_Survey_Study/blob/3254384e154ff2a3232a9fe723da36b1ceb92705/img/jina.jpeg" width=150px> | <img src="https://github.com/yukyunglee/Transformer_Survey_Study/blob/3254384e154ff2a3232a9fe723da36b1ceb92705/img/jh.png" width=150px> | <img src="https://github.com/yukyunglee/Transformer_Survey_Study/blob/3254384e154ff2a3232a9fe723da36b1ceb92705/img/sb.png" width=150px> |
|                   **[Github](https://github.com/yukyunglee)**                   |                   **[Github](https://github.com/msub0310)**                   |               **[Github](https://github.com/Hoonst)**               |                   **[Github](https://github.com/jina-kim7)**                   |                   **[Github](https://github.com/TooTouch)**                   |                   **[Github](https://github.com/suubkiim)**                   |



## 2. ์คํฐ๋ ๋ชฉ์  ๋ฐ ๋ฐฉํฅ

#### 0) ์คํฐ๋ ๋ฒ์

: ์ด ์คํฐ๋๋ ์๋ฒ ์ด ๋ผ๋ฌธ์์ ๋์ค๋ ๋ชจ๋  ๋ผ๋ฌธ์ค์์ ๋ธ๋์์ผ๋ก ํ์๋ ๋ผ๋ฌธ์ ๋ค๋ฃน๋๋ค (์ด๋ก์: ์ฐ๊ตฌ์ค ์ธ๋ฏธ๋์์ ๋ค๋ฃฌ ์  ์์)

<img src="./img/paper_all.png" alt="main" style="zoom:40%;" />

#### 1) ์คํฐ๋ ๋ชฉ์ 

: ์ด ์คํฐ๋๋ ๋ผ๋ฌธ์ ๋์ค๋ ๋ชจ๋  Transformer์ ๊ตฌ์กฐ๋ฅผ ์ดํดํ๊ธฐ ์ํ ๊ฒ์ด ์๋๋ฉฐ, ๋ผ๋ฌธ์ ํตํด ๊ธฐ์กด Transformer ๋๋น Module level - Arch level, Pretrain level์์ ์ด๋ค ๋ณํ๊ฐ ์๋์ง ํ๋ฆ์ ์ดํด๋ณด๋ ๊ฒ์ ๋ชฉ์ ์ผ๋ก ํฉ๋๋ค.



#### 2) ์คํฐ๋ ๋ฐฉํฅ

- ๋ชจ๋  ์ธ์์ด ํด๋น ๋ผ๋ฌธ์ 1ํ๋ ํด์ผํฉ๋๋ค.
- ๊ฐ ์ฑํฐ๋ณ๋ก ์ธ์์ ๋ฐฐ์ ํ์ฌ ํด๋น ํํธ๋ฅผ coreํ๊ฒ ๊ณต๋ถํ  ์ฌ๋์ ์ ํ๊ณ , ๋ฐํ์๋ฃ ์ ์๊ณผ ์คํฐ๋ ๋ฐํ๋ฅผ ๋ด๋นํฉ๋๋ค.
- ๋ฐํ ์๋ฃ๋ฅผ ์ ์ํ๋ ์ด์ : ๊ณต๋ถํ ๋ด์ฉ์ ์ ๋ฆฌํ๋ ๊ณผ์ ์ ํตํด ์ดํดํ ๋ด์ฉ์ ๊ตฌ์กฐํ ํ๊ธฐ ์ํจ์๋๋ค.
- ๊ฐ ์ฑํฐ๋ณ๋ก ๋ผ๋ฌธ ๋ด์ฉ์ ์ญ ํ์ด์ค ํ ๋๋๋๊ฒ์ด ์๋๋ผ, ํด๋น ๋ถ๋ถ์์ ์ค์ํ  ๊ฒ ๊ฐ์ 'ํต์ฌ'๊ฐ๋์ ์ฐพ์ ๊ทธ ๊ฐ๋์ ์์ธํ ์ค๋ชํด์ฃผ์๋ฉด ๋ฉ๋๋ค
- ์ถํ ์์ ์ ์ฑํฐ๋ก ๋ฐํ์์์ ์ ์ํ ํ ์ฐ๊ตฌ์ค ์ ํ๋ธ์ ์๋ก๋ ํด์ผํฉ๋๋ค



#### 3) ์คํฐ๋ ๊ธฐ๊ฐ : 2021/7/7 ~ 2021/7/30

* 7/7 ~ 7/18 : ๋ผ๋ฌธ ๊ฐ์ธ ๊ณต๋ถ
* 7/19 ~ 7/29 : ์คํฐ๋ ์งํ
* 7/30 : ์คํฐ๋ ์์ ์๋ก๋ (์์ , [DSBA Youtube channel](https://www.youtube.com/channel/UCPq01cgCcEwhXl7BvcwIQyg/videos)) 



## 3. ์คํฐ๋ ์ด์ 

**00) Introduction**


<a href="https://www.youtube.com/watch?v=pOdLQIjGfl0&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-">
         <img width="300" height="160" src="https://github.com/yukyunglee/Transformer_Survey_Study/blob/main/img/tss_main.png?raw=true">
</a>

>- [์์](https://www.youtube.com/watch?v=pOdLQIjGfl0&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-) / [๋ฐํ์๋ฃ](https://github.com/yukyunglee/Transformer_Survey_Study/blob/main/Presentation/TSS_%230_intro.pdf)
>- ๋ฐํ์ : ์ด์ ๊ฒฝ ๋ฐ์ฌ๊ณผ์ 
>- ํธ์ง : ์คํ์ ์์ฌ๊ณผ์ , ํ์ฌํ ์์ฌ๊ณผ์ 


**01) Transformer basic (1~6 Page)**

<a href="https://www.youtube.com/watch?v=rjHaxK2iWX4&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=2">
         <img width="300" height="160" src="https://user-images.githubusercontent.com/37654013/128216258-3ac1ad55-0fd2-4985-872f-0bc09305a764.png">
</a>

>- [์์](https://www.youtube.com/watch?v=rjHaxK2iWX4&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=2) / [๋ฐํ์๋ฃ](https://github.com/yukyunglee/Transformer_Survey_Study/blob/main/Presentation/TSS_%231_Transformer_Basic.pdf)
>- ์ฃผ์  : Vanilla Transformer
>- ์คํฐ๋ ์งํ : 7/20
>- ๋ฐํ์ : ๊น์๋น ์์ฌ๊ณผ์ 

**02) Module-level : Attention 1 (6~11 Page)**

<a href="https://www.youtube.com/watch?v=m8rWN2-VkcU&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=4">
         <img width="300" height="160" src="https://user-images.githubusercontent.com/37654013/128216765-38610e67-28ba-4b11-99d6-27ccf1bd9d3c.png">
</a>

>- [์์](https://www.youtube.com/watch?v=m8rWN2-VkcU&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=4) / [๋ฐํ์๋ฃ](https://github.com/yukyunglee/Transformer_Survey_Study/blob/main/Presentation/TSS_%232_Sparse_Attention.pdf)
>- ์ฃผ์  : Sparse Attention
>- ์คํฐ๋ ์งํ : 7/21
>- ๋ฐํ์ : ์คํ์ ์์ฌ๊ณผ์ 

**03) Module-level : Attention 2  (11~15 Page)**

<a href="https://www.youtube.com/watch?v=FNGcX23DFLU&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=5">
         <img width="300" height="160" src="https://user-images.githubusercontent.com/37654013/128217071-705e4056-c260-42f5-9e00-e68f77041641.png">
</a>

>- [์์](https://www.youtube.com/watch?v=FNGcX23DFLU&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=5) / [๋ฐํ์๋ฃ](https://github.com/yukyunglee/Transformer_Survey_Study/blob/main/Presentation/TSS_%233_Linearized_Attention_Prototype_and_Memory_Compression.pdf)
>- ์ฃผ์  : Linearized / Prototype / Memory Compress Attention
>- ์คํฐ๋ ์งํ : 7/27
>- ๋ฐํ์ : ๊น์ง๋ ์๋ฐํตํฉ๊ณผ์ 

**04) Module-level : Attention 3  (15~20 Page)**

<a href="https://www.youtube.com/watch?v=aN1Yn2QWDHc&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=6">
         <img width="300" height="160" src="https://user-images.githubusercontent.com/37654013/128217175-d023e186-9b41-433e-9493-1a8f4a1dbf1b.png">
</a>

>- [์์](https://www.youtube.com/watch?v=aN1Yn2QWDHc&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=6) / [๋ฐํ์๋ฃ](https://github.com/yukyunglee/Transformer_Survey_Study/blob/eea1533802a9edf4c6cb2adc384900f85f38f9df/Presentation/TSS_%234_Lowrank_Prior_Improved_Attention.pdf.pdf)
>- ์ฃผ์  : LowRank SeltAttention / Attention with Prior / Improved Multi-Head Mechanism
>- ์คํฐ๋ ์งํ : 7/28
>- ๋ฐํ์ : ์ด์ ๊ฒฝ ์๋ฐํตํฉ๊ณผ์ 

**05) Module-level : Others  (20~26 Page)**

<a href="https://www.youtube.com/watch?v=9wTkdGAgT7w&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=7">
         <img width="300" height="160" src="https://user-images.githubusercontent.com/37654013/128217255-79223abd-b4e3-4352-a1ad-97ebc76a7bbd.png">
</a>

>- [์์](https://www.youtube.com/watch?v=9wTkdGAgT7w&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=7) / [๋ฐํ์๋ฃ](https://github.com/yukyunglee/Transformer_Survey_Study/blob/a2f9375ec1bcd75e33581461b89a61b7b125d7a2/Presentation/TSS_%235_Other_Module_Level_Modifications.pdf)
>- ์ฃผ์  : Position Encoding / LayerNorm / FFN
>- ์คํฐ๋ ์งํ : 7/29
>- ๋ฐํ์ : ํ์ฌํ ์์ฌ๊ณผ์ 

**06) Arch.-level ~ end  (26~33 Page)**

<a href="https://www.youtube.com/watch?v=Mtimidtm3zc&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=9">
         <img width="300" height="160" src="https://user-images.githubusercontent.com/37654013/128217328-923814e9-f56d-495a-aa86-707daab793b7.png">
</a>

>- [์์](https://www.youtube.com/watch?v=Mtimidtm3zc&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=9) / [๋ฐํ์๋ฃ](https://github.com/yukyunglee/Transformer_Survey_Study/blob/a2f9375ec1bcd75e33581461b89a61b7b125d7a2/Presentation/TTS_%236_Architectur_Level_Varient.pdf)
>- ์ฃผ์  : Architecture-level variant
>- ์คํฐ๋ ์งํ : 7/30
>- ๋ฐํ์ : ๊น๋ช์ญ ์์ฌ๊ณผ์ 

**07) Appendix : ๋น์ ์ด ๋ชจ๋ฅด๋ transformer์ 3๊ฐ์ง ์ฌ์ค**

<a href="https://www.youtube.com/watch?v=ktYuOq3lWyY&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=8">
         <img width="300" height="160" src="https://user-images.githubusercontent.com/37654013/128217455-f6da9969-4f5b-43f0-b7aa-e9fc893ac42f.png">
</a>


>- [์์](https://www.youtube.com/watch?v=ktYuOq3lWyY&list=PLetSlH8YjIfXCRQ28UHh07wxkIxdU5c7-&index=8) / [๋ฐํ์๋ฃ](https://github.com/yukyunglee/Transformer_Survey_Study/blob/main/Presentation/TTS_Appendix_Complexity_Parameters_Scaling.pdf)
>- ์ฃผ์  : [Transformer] Complexity, Parameters, and Scaling
>- ์คํฐ๋ ์งํ : 7/28
>- ๋ฐํ์ : ๊น๋ช์ญ ์์ฌ๊ณผ์ 



## 4. ์คํฐ๋ ๊ท์น

1. ์ด๋ค ์ง๋ฌธ์ด๋  ํ  ์ ์์ต๋๋ค
   - ๋ชจ๋ฅด๋ ๋ถ๋ถ์ ์ฑ์ฐ๊ธฐ ์ํด ๊ธฐ๋ณธ์ ์ด๊ณ  ์ฌ์ด ์ง๋ฌธ๋ ์ฃผ๊ณ ๋ฐ์ ์ ์์ต๋๋ค
   - ์ด๋ค ์ฌ์ด ์ง๋ฌธ์ ํ๋๋ผ๋ ์ง์งํ๊ฒ ๋ผ์ํฉ๋๋ค
2. ์ง๋ฌธ์ ๋ํ๋ ํ๋
   - ์ง๋ฌธ์ ์ต๋ํ ์์๋ฅผ ๊ฐ์ถ์ด ์ง๋ฌธํฉ๋๋ค
3. ๋ฐํ ์๋ฃ ํ๋ฆฌํฐ
   - ๋ฐํ์๋ฃ๋ ์ธ๋ฏธ๋์ฒ๋ผ ์ฑ์๋ฅผ ๋ด์ ๊ตฌ์ฑํฉ๋๋ค
   - ๋ค๋ง ๋๋ฌด ๊ธธ๊ฒ ๋ง๋ค ํ์๋ ์์ต๋๋ค
4. ์ถํ ๋ณด๊ฐ
   - ์คํฐ๋์์ ๋ผ์ํ ๋ด์ฉ์ ํด๋น ์ฑํฐ ๋ด๋น์๊ฐ ์ ๋ฆฌํ์ฌ ๊ณต์ ํฉ๋๋ค
     - ํจ๊ป ๋๋์๋ ์ง๋ฌธ ๋ฐ ๋๋ต๋ค
   - ์คํฐ๋ ์ค๊ฐ์ ๋๋ตํ์ง ๋ชปํ๋ ์ ๋ณด๋ค์ ์คํฐ๋ ์ข๋ฃ ํ ์ ๋ฆฌํ์ฌ ๊ณต์ ํฉ๋๋ค
     - ์ด ๋ํ ์์นด์ด๋น ํด์ฃผ์ธ์ !

