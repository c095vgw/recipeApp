# data_fileディレクトリの中身について
保存しているファイルは以下のディレクトリの中
 - 料理毎のcsvファイル(data_file/サイト名フォルダ/*/レシピID.csv)
 - レシピサイト毎のcsvファイル(data_file/サイト名フォルダ/*.csv)
 - 全レシピをまとめたcsvファイル(data_file/all/*.csv)

レシピ名などは [recipes.csv] に、材料・分量は [ingredients.csv] に、手順は [make_list.csv] に

# 確認事項
 - 全サイトのレシピをまとめるとIDが被る
 - IDの桁を合わせるかどうか
 - タグで紐付ける場合、新たにタグテーブルを作るべきか
 - 難易度でソートする際の基準について(手順と時間で考える)