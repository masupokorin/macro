# ちょっとしたマクロ置き場## fillterOutputMacro.txtエクセルデータの中から、特定のセルをフィルタで絞った後、その内容を別ファイルとして出力したいときに使えます。このソース内ではフィルタ対象のセル位置が固定になっているので、都度修正してください。## sheetnameChangeMacro.txtA5SQLを使用して複数のクエリを実行した時に、そのすべてを一つのエクセルに出力することがあります。その時にシート名が固定になっていないので、定常的に同じクエリを実行する場合は、このマクロで一括でシート名を変更できます。A5SQLでのエクセル出力時は、1,2行目に日時とクエリ内容が出るのでそれも一緒に削除します。