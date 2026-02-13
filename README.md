# React TaskBoard

React + TypeScript + Vite + Supabase で作成したタスク管理アプリです。

## 🚀 機能

- 🔐 Supabase Authentication によるログイン / ログアウト
- ✅ タスクの作成
- ✏️ タスクの更新
- 🗑 タスクの削除
- 📋 タスク一覧表示
- 🔄 リアルタイムデータ同期（Supabase）

---

## 🛠 技術スタック

- React
- TypeScript
- Vite
- Supabase
- ESLint

---

## 📂 ディレクトリ構成

src/
├── components/
│ ├── AuthForm.tsx
│ ├── TaskForm.tsx
│ └── TaskItem.tsx
├── pages/
│ ├── LoginPage.tsx
│ └── TasksPage.tsx
├── lib/
│ └── supabase.ts
├── types/
│ └── task.ts
└── main.tsx


---

## ⚙️ セットアップ方法

### 1. リポジトリをクローン

```bash
git clone git@github.com:aka60611/React-TaskBoard.git
cd React-TaskBoard

###npmをインストール
npm install

プロジェクト直下に .env ファイルを作成し、以下を記述してください。

VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_anon_key

Supabase プロジェクトは https://supabase.com
から作成できます。


###開発サーバー起動
npm run dev

