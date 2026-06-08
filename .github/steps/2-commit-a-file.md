## Step 2: ファイルを commit する

_ブランチの作成ができました！ :tada:_

ブランチを作成すると、 `main` ブランチを変更せずにプロジェクトを編集できます。ブランチができたので、次はファイルを作成して最初の commit を行いましょう！

**commit とは？**: _[commit](https://docs.github.com/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)_ は、プロジェクトのファイルやフォルダーに対する変更の集合です。commit はブランチの中に存在します。詳しくは「[About commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits)」を参照してください。

### :keyboard: アクティビティ: 最初の commit

以下の手順では、GitHub 上で変更を commit する流れを案内します。commit では、ファイルの追加・削除・リネームやファイル内容の変更など、プロジェクトへの変更を記録します。この演習では、新しいブランチに新しいファイルを追加する変更を commit します。

> [!NOTE]
> `.md` は Markdown ファイルを作成する拡張子です。Markdown については、docs の「[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)」を見るか、「[Communicating using Markdown](https://github.com/skills/communicate-using-markdown)」Skills Exercise を受講して学べます。

1. repository のヘッダーメニューにある **< > Code** タブで、新しいブランチ `my-first-branch` にいることを確認します。

2. **Add file** ドロップダウンを選択して、 **Create new file** をクリックします。

   <img width="300" alt="screenshot of the create new file option" src="https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/create-new-file-option.png?raw=true">

3. **Name your file...** フィールドに `PROFILE.md` と入力します。

4. **Enter file contents here** エリアに、次の内容をファイルへコピーします。

   ```
   Welcome to my GitHub profile!
   ```

   ![screenshot for adding the profile.md file](https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/add-profile-file.png?raw=true)

5. 内容ボックス右上の **Commit changes...** をクリックします。ダイアログが表示されます。

6. GitHub はシンプルなデフォルトメッセージを提案しますが、練習として少し変更しましょう。 **Commit message** フィールドに `Add PROFILE.md` と入力してください。
   
   - **commit message** と任意の **extended description** があると、変更内容がより明確になります。これは、commit が複数ファイルにまたがる場合に特に役立ちます。

   <img width="400" alt="screenshot of adding a new file with a commit message" src="https://github.com/hiryamada/skills-introduction-to-github/blob/main/.github/images/commit-message-dialog.png?raw=true">

6. このレッスンでは、ほかのフィールドは一旦無視して **Commit changes** をクリックします。

7. ファイルを変更したので、Mona があなたの作業確認をすでに始めているはずです。少し待って、コメントを見ていてください。進捗情報と次のレッスンが返信されます。


<details>
<summary>うまくいかない場合 🤷</summary><br/>

フィードバックが届かない場合は、次を確認してください:
- `my-first-branch` ブランチにいることを確認してください。
- `PROFILE.md` ファイルが作成され、ルートフォルダーにあることを確認してください。

</details>
