# GitHub Profile 资料填写

## 1. Bio（个人简介，显示在头像右侧）

```
AI 产品经理 ｜ 学习和探索 AI
```

## 2. Website（网站链接）

```
https://beautyliu.github.io/personal-site/
```

## 3. 头像

上传 `assets/avatar-512.png`，裁剪为圆形后保存。

## 设置路径

https://github.com/settings/profile

## 或者用命令（需要 user scope）

```bash
gh auth refresh -h github.com -s user
gh api -X PATCH user \
  -f bio="AI 产品经理 ｜ 学习和探索 AI" \
  -f blog="https://beautyliu.github.io/personal-site/"
```
