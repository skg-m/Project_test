# Github Projectの使い方

## Projectは基本的にカンバン方式で進捗を管理する
- 基本的なカンバンはToDo、In Progress、Doneの3つ
- それぞれのカンバン内に項目（Note)を追加すると、それが進捗率バーに反映される
- Projectに登録されているissueは、issue画面右列のProjectsのところに、そのProject全体の進捗度合いが表示されるので、一目で進捗率がわかる。
- 各issueに対して、一つのプロジェクトを割り当てれば、各issueの進捗管理ができる。ただし、個々のissueからProjectは作れないので注意。

## 新規Projectの作成
- 上部タブからProjectsをタップ
- 既存プロジェクトがあれば、一覧が表示される。
- 新規作成する場合は、右上のNew Projectをタップ
- プロジェクト名を入力し、templateからbasic Kanbanなどを選択するとカンバンが自動生成される

### Project内のカンバンの操作
- ToDやIn Progressといったカンバンの右上の＋をクリックすると新しくCard状のNoteが作成できる
- 各Noteの右上にある・・・をクリックし、Convert to issueを選択すると、そのNoteが、issue化できる。
- In Progressカンバン内にNoteを作成すると進捗状況バーの紫部分が増えていく
- TodoやIn ProgressにあるNoteをDoneにドラッグアンドドロップすると進捗状況バーの緑色部分が増えていく

###  issueのプロジェクトへの追加
- 右欄にあるProjectsの歯車マークをクリックするとプロジェクト一覧が出てくるので、入れたいプロジェクトを選択する
- Projectタブに移動して、入れたプロジェクトを表示すると、ToDoの一番最後にさっきのissueが登録されているはず。
- Noteをドラッグして、In Progress等にドロップすれば、カンバンのステータスが変わる
- issue化されたNoteをDoneに移動すれば、issueの履歴にDoneにしたということが自動表示されるので、そのissueが終了したことがわかる。

## 注意点
- 個々のissue画面からは新規プロジェクトを作れない。
- 既存プロジェクトへの追加はできるので、プロジェクトをあらかじめ作っておいてから、
  issueを登録する。

- 逆に、Project内の項目(Note)を新規issueにすることはできる。
- 各Noteの右上の・・・からconvert to issueを選択するだけ。issueリストにも自動的に登録される。
- したがって、関連issueは一つのプロジェクトにまとめるのがよさそう。
 

