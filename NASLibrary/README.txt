配置先
DAServer/NASLibrary/

構成
NASLibrary/index.html
NASLibrary/tracks.json
NASLibrary/music/各楽曲ファイル

公開URL
https://serenium34.github.io/DAServer/NASLibrary/

手順
1. DAServerのmainブランチ直下にNASLibraryフォルダを作成します。
2. NASLibraryへindex.htmlとtracks.jsonを配置します。
3. NASLibrary内にmusicフォルダを作成します。
4. tracks.jsonに記載された21曲をmusicフォルダへ配置します。
5. GitHub Pagesの公開元がmainブランチのrootであることを確認します。
6. 公開URLを開いて動作を確認します。

tracks.jsonはfile、title、artistを個別に保持します。
そのため、曲名またはアーティスト名にアンダースコアが含まれても正しく表示できます。
楽曲を追加するときはtracks.jsonへ同じ形式の項目を追加してください。
