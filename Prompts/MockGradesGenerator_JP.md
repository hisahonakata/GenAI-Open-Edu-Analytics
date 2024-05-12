# 学習者の性格を考慮した各履修科目の成績シミュレーション
このプロンプトは、生徒の性格を元に各履修科目の成績を生成するためのプロンプトです。

# プロンプト例
```
中学3年生の生徒に 16 peronalities の性格タイプをランダムに割り当て。1クラスに男子20名、女子20名で、1学校あたり5クラスです。100校分のCSVデータを作成。


各生徒の性格タイプを元に中学2年生の成績をシミュレーション。
履修科目は、
- Japanese Language
- Social Studies
- Mathematics
- Science
- Music
- Art
- Health and Physical Education
- Technology and Home Economics
- Foreign Language
- Moral Education
- Integrated Study Time
- Special Activies
です。成績は1,2,3,4,5 の5段階評価。1が劣、5が優。CSVファイルを作成。
```
# 出力結果
[Student_Grades_by_8th_graders.csv](/workspaces/GenAI-Open-Edu-Analytics/GeneratedEduData/Student_Grades_by_8th_graders.csv)