テンプレートのインストール方法(2015用)

テンプレートはウィザード形式になっていて次のファイルを所定の位置にコピーする必要があります。

  ウィザード登録用ファイル群
    * MikanProject2015.ico
    * MikanProject2015.vsdir
    * MikanProject2015.vsz

  ウィザード本体
    * Scripts
    * Templates
    * default.vcxproj

1 個人のウィザードとして追加する。
  ウィザードとして登録されます。

  ウィザード登録用のファイル群を
  C:\Users\ユーザー名\Documents\Visual Studio 2015\Wizards
  にコピーする。初めは存在しないのでフォルダを作る必要がある。
  C:\Users\ユーザー名はいわゆるマイドキュメントで、その中のドキュメントに恐らくVisual Studio 2015というフォルダがある。

2 ウィザード本体の設置
  C:\lib\MikanにMikanライブラリが設置されていると仮定する。

  C:\lib\Mikan
  にMikanProject2015というフォルダを作り、ウィザード本体をコピーする。

  それ以外の場所に設置した場合は、MikanProject.vszを開き、次の場所
  Param="ABSOLUTE_PATH = C:\lib\Mikan\MikanProject2015"
  のC:\lib\Mikan\MikanProject2015を設置した場所に書き換える。その場合絶対パスにする。

