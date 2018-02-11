# 公開鍵と秘密鍵ってこんな関係性ですよっていうのを適当にしゃべる

---

## 発表する人
- [Anorlondo448(あのーるろんど)](https://wiki.infra-workshop.tech/user/Anorlondo448)


---

## 前提条件
- 公開鍵／秘密鍵が全くわからんって人

---

## やらないこと
- 公開鍵／秘密鍵の詳細
- SSLや電子署名などへの応用の仕方

---

## これだけは覚えて帰ってくれれば良いです
- 公開鍵で暗号化したものは、秘密鍵でしか復号化できません
- 秘密鍵で暗号化したものは、公開鍵でしか復号化できません

---
## こんなイメージ
![01](https://raw.githubusercontent.com/Anorlondo448/infrastructure-workshop-rsa-base/master/img/rsa_01.png "01")

---

## 公開鍵と秘密鍵って？
- なんか数学的に関係した２つの素数の組らしい
---

## 公開鍵
- 公開鍵で暗号化したものは、秘密鍵でしか復号化できません

---

## 秘密鍵
- 秘密鍵で暗号化したものは、公開鍵でしか復号化できません

---
## こんなイメージ(公開鍵)

![01](https://raw.githubusercontent.com/Anorlondo448/infrastructure-workshop-rsa-base/master/img/rsa_01.png "01")

---
## こんなイメージ(秘密鍵)

![02](https://raw.githubusercontent.com/Anorlondo448/infrastructure-workshop-rsa-base/master/img/rsa_02.png "02")

---

## 公開鍵と秘密鍵の差
- 秘密鍵から公開鍵は生成できる
- 公開鍵からは秘密鍵は生成できない
- つまり、秘密鍵が漏れるとやばい

---
