# 🎵 班級音樂盒 Class Music Box

給音樂課用的教室大螢幕小工具箱。不用安裝 App，打開瀏覽器就能用；以教室橫式大螢幕為主，手機、平板也能看。

Ray's Classroom Lab｜Design by Ray Chen／陳耿睿

## 功能

| 頁面 | 檔案 | 內容 |
| --- | --- | --- |
| 首頁 | `index.html` | 大時鐘、今日聆聽計時、瀏覽器即時自創音樂、音樂跳動條、每日音樂小詞、會飛的音樂小精靈、精靈風鈴聲 |
| 節奏挑戰 | `rhythm.html` | 拍子練習：自動出題或拖曳排拍子，一拍打一個勾，播放有拍手聲 |
| 聆聽地圖 | `musicogram.html` | 魔法音樂圖：跟著光圈一拍畫一個動作 |
| 音階練習 | `scale.html` | 音符拖上五線譜，鋼琴鍵同步彈出；可隱藏答案讓學生搶答 |
| 節拍器 | `metronome.html` | 調速度、拍號、細分拍、音色，跟拍測速、自動加速 |
| 音樂家 | `composers.html` | 12 位作曲家的 Low Poly 頭像、小故事、點作品聽主題旋律 |

## 放上 GitHub Pages

1. 在 GitHub 建立一個新的 repository（例如 `class-music-box`）。
2. 把這個資料夾裡的所有檔案上傳到 repository 的最外層（`index.html` 要在最外層）。
3. 到 **Settings → Pages**，Source 選 **Deploy from a branch**，Branch 選 **main**、資料夾選 **/(root)**，按 Save。
4. 等一兩分鐘，網址會是 `https://你的帳號.github.io/class-music-box/`。

## 說明

- 所有聲音都是瀏覽器即時合成，沒有音檔。手機請先關閉靜音鍵；瀏覽器規定要先點一下畫面才會出聲。
- 需要連網載入 Google Fonts 與 three.js（cdnjs），小精靈的 3D 模型才會出現；載入失敗時會改用 2D 版本。
- 聆聽計時、風鈴開關等設定只存在各自裝置的瀏覽器裡。
- 音樂家頁的介紹文字與主題旋律為簡化改編，上課前建議老師先確認內容。
