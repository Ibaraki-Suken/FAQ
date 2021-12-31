# GitHub
## 導入方法
参考: [【超入門】初心者のためのGitとGitHubの使い方](https://tech-blog.rakus.co.jp/entry/20200529/git)

1. https://gitforwindows.org/ からGitをインストール
2. `git config --global user.name ユーザ名`  
   `git config --global user.email メールアドレス`
3. Git Bashを起動し、`cd プロジェクトのディレクトリのパス`を入力してプロジェクトのフォルダに移動。
4. `git init`でGitのリポジトリとして登録
5. `git branch -M main`でブランチをmasterからmainに変更。[ブランチとは?](https://backlog.com/ja/git-tutorial/stepup/01/)
6. (任意) https://github.com/github/gitignore/blob/main/Unity.gitignore などを参考に.gitignoreを配置。ここに書かれたファイルやディレクトリはGitの管理対象にならない。
7. `git add ファイル名`でファイルをGitの管理対象に追加。`git add -A`で.gitignoreに書かれたファイル以外を一括でGitに追加できる。
8. `git commit -m "[Add] index"`でコミット。""に囲まれた部分はコミットメッセージなのでなんでもいい。
9. `git remote add origin GitのURL`でリモートリポジトリを紐づけ。URLは`リポジトリのページ >> Code >> Clone >> HTTPS`から確認できる。  
   ![image](https://user-images.githubusercontent.com/35805963/147800101-94039609-9d3c-431f-b963-6bd1bc73f318.png)  
10. `git push origin main`でリモートリポジトリにローカルの内容をプッシュ
    
細かいことは追々理解すればいいです。まずは使えるように。  


## 数研リポジトリ作成方法
https://github.com/Ibaraki-Suken から New をクリック  

![image](https://user-images.githubusercontent.com/35805963/147799791-6d07f2fe-7d40-4433-963b-730a43f025f5.png)
