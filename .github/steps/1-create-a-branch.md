## Step 1: ブランチを作成する

_「Introduction to GitHub」へようこそ！ :wave:_

**GitHub とは？**: GitHub は、バージョン管理に _[Git](https://docs.github.com/get-started/quickstart/github-glossary#git)_ を使うコラボレーションプラットフォームです。
GitHub は [open-source](https://docs.github.com/get-started/quickstart/github-glossary#open-source) ソフトウェアを共有・貢献するための人気の場所です。

:tv: [Video: What is GitHub?](https://www.youtube.com/watch?v=pBy1zgt0XPc)

**repository とは？**: _[repository](https://docs.github.com/get-started/quickstart/github-glossary#repository)_ は、ファイルとフォルダーを含むプロジェクトです。
repository はファイルとフォルダーのバージョンを追跡します。詳しくは、GitHub Docs の
「[About repositories](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)」を参照してください。

**ブランチとは？**: _[ブランチ](https://docs.github.com/en/get-started/quickstart/github-glossary#branch)_ は、repository の並行バージョンです。
デフォルトでは、repository には `main` という名前のブランチが 1 つあり、これが決定版のブランチとみなされます。
追加のブランチを作成すると、repository の `main` ブランチをコピーして、メインプロジェクトを壊さずに安全に変更できます。
多くの人は、プロジェクトのほかの部分に影響を与えずに特定の機能に取り組むためにブランチを使います。

ブランチを使うことで、作業を `main` ブランチから分離できます。
つまり、あなたが貢献している間も、みんなの作業は安全に保たれます。
詳しくは「[About branches](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches)」を参照してください。

**profile README とは？**: _[profile README](https://docs.github.com/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)_
は、GitHub.com のコミュニティに自分の情報を共有できる、GitHub プロフィール上の「About me」セクションのようなものです。
GitHub はプロフィールページの先頭に profile README を表示します。詳しくは「[Managing your profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)」を参照してください。

![screenshot showing an example profile readme](https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/example-profile-readme.png?raw=true)

### :keyboard: アクティビティ: 最初のブランチ

1. 新しいブラウザータブを開いて、作成した repository（この演習のコピー）に移動します。このタブの手順を読みながら、もう一方のタブで作業してください。

2. repository のヘッダーメニューにある **< > Code** タブに移動します。

   ![screenshot highlighting the code tab](https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/code-tab-highlight.png?raw=true)

3. **main** ブランチのドロップダウンをクリックします。

   <img width="300" alt="screenshot highlighting the branch selection" src="https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/branch-selection-dropdown.png?raw=true">

4. テキストボックス **Find or create a branch...** に `my-first-branch` と入力します。
   
   > **Note:** これは次のステップへ進むためのチェック対象です。 :wink: 

5. **Create branch: `my-first-branch` from main** というテキストをクリックして、ブランチを作成します。

   <img width="300" alt="screenshot highlighting the create branch prompt" src="https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/create-branch-prompt.png?raw=true">

   - ブランチは自動的に、今作成したものへ切り替わります。
   - **main** ブランチのドロップダウンメニューに、新しいブランチ名が表示されます。

6. ブランチが GitHub に push されたので、Mona があなたの作業確認をすでに始めているはずです。少し待って、コメントを見ていてください。進捗情報と次のレッスンが返信されます。


<details>
<summary>うまくいかない場合 🤷</summary><br/>

フィードバックが届かない場合は、次を確認してください:
- 作成したブランチ名が正確に `my-first-branch` になっていることを確認してください。接頭辞や接尾辞は不要です。

</details>
