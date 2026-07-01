# 英単語学習アプリ (Next.js)

Reactで開発した英語学習アプリをNext.jsへ移植したバージョンです。

🔗 https://english-app-next.vercel.app/

## 概要

英単語学習・翻訳・AI英会話を行えるWebアプリです。

元々React(Vite)で開発したアプリをNext.jsへ移植し、
App Router環境への対応やSSRを考慮した実装を行いました。

フレームワークの違いによる実装方法の違いや、
クライアントサイドとサーバーサイドの動作の違いを学ぶことを目的として開発しました。

## 主な機能

- 英単語の登録・管理
- 辞書候補の自動取得
- 翻訳機能
- AI英会話
- 音声入力
- 音声読み上げ

## 移植時に対応した内容

- React(Vite) → Next.js(App Router)へ移植
- localStorage利用時のSSR対策
- SpeechRecognition利用時のSSR対策
- 環境変数によるAPI管理
- Vercel / Renderへのデプロイ
- クライアントコンポーネント化（"use client"）

## 使用技術

### Frontend

- Next.js
- React
- JavaScript

### Backend

- Node.js
- Express

### API

- OpenAI API
- DeepL API

### Deployment

- Vercel
- Render
