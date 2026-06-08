## Step 3: pull request を開く

_commit ができました！ :sparkles:_

プロジェクトに変更を加えて commit を作成したので、次は pull request を通じて提案する変更を共有しましょう！

**pull request とは？**: コラボレーションは _[pull request](https://docs.github.com/en/get-started/quickstart/github-glossary#pull-request)_ 上で行われます。pull request はあなたのブランチでの変更をほかの人に示し、受け入れ・拒否・追加変更の提案を可能にします。並べて比較すると、この pull request はあなたがブランチで行った変更を保持し、 `main` プロジェクトブランチへ適用することを提案します。pull request の詳細は「[About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)」を参照してください。

### :keyboard: アクティビティ: pull request を作成する

commit のあと、ブランチへの最新 push を示すメッセージと **Compare & pull request** ボタンが表示されたことに気づいたかもしれません。

![screenshot of message and button](https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/compare-pull-request-button.png?raw=true)

自動で pull request を作成するには **Compare & pull request** ボタンをクリックし、そのまま下の手順 5 に進んでください。あるいは、最初の 4 手順を使って手動作成を練習することもできます。

1. repository のヘッダーメニューで **Pull requests** タブをクリックします。
2. **New pull request** ボタンをクリックします。
3. ドロップダウンメニューで次のブランチを選択します。
   
   - **base:** `main`
   - **compare:** `my-first-branch`

   ![screenshot showing both branch selections](https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/branch-selection-comparison.png?raw=true)

4. **Create pull request** をクリックします。

5. pull request のタイトルを入力します。デフォルトではタイトルは自動的にブランチ名になります。この演習では、フィールドを `Add my first file` に編集しましょう。

6. 次のフィールドは、実施した変更の **description** を記載するためのものです。ここまでに達成した内容の短い説明を入力してください。参考として、あなたは新しいブランチの作成、ファイルの作成、commit の実施を行いました。

   ![screenshot showing pull request](https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/create-pull-request-form.png?raw=true)

7. **Create pull request** をクリックします。

8. コラボレーションの場ができたので、Mona があなたの作業確認をすでに始めているはずです。少し待って、コメントを見ていてください。進捗情報と次のレッスンが返信されます。


<details>
<summary>うまくいかない場合 🤷</summary><br/>

フィードバックが届かない場合は、次を確認してください:
- pull request のタイトルが正しいことを確認してください。
- pull request に description があることを確認してください。

</details>
