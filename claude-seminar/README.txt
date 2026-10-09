Claude Code セミナー(2026-10-09)の作業用フォルダ

このファイルがあるフォルダで claude を起動します。

起動のしかた
  Mac            ターミナルに「cd 」(cd と半角の空白)を入力し、このフォルダをターミナルの画面にドラッグして Enter を押す。続けて claude と入力する
  Windows        エクスプローラーでこのフォルダを開き、アドレスバーに powershell と入力して Enter を押す。開いた画面で claude と入力する
  Windows + WSL  エクスプローラーでこのフォルダを開き、アドレスバーに wsl と入力して Enter を押す。開いた画面で claude と入力する

起動したら
  1. フォルダを信頼するかを選ぶ画面が出たら、下向きの矢印キーで Yes, I trust this folder を選び、Enter を押す
  2. 画面の下に auto mode on と出ていることを確かめる
     出ていないときは、Shift+Tab を押して auto mode on に切り替える
     切り替えても出ないときは、claude を終了し、claude update を実行してから claude --permission-mode auto で起動する
  3. / を入力し、一覧に research-deck があることを確かめる
  4. /research-deck のあとにテーマを入力する
     例: /research-deck 日本の中小企業の事業承継の現状

入っているもの
  .claude/skills/research-deck/SKILL.md   配布した Skill(名前が . で始まるフォルダは、Mac の Finder では表示されない)
  README.txt                              このファイル

できた資料は、このフォルダの output フォルダに保存されます。
