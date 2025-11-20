# focus-flight
Focus Flight 專注航班 ✈️

Focus Flight 是一款基於 Web 的沈浸式番茄鐘應用程式，透過模擬高空飛行的視覺與聽覺體驗，幫助使用者進入心流狀態，專注於當下的任務。

✨ 特色功能 (Features)

視學體驗 (Visuals)

生成式雲海引擎 (Generative Cloud Engine)：

不依賴外部圖片，使用 HTML5 Canvas 技術即時演算生成的無盡雲海。

採用粒子渲染技術 (Particle Rendering)，呈現立體、蓬鬆且層次分明的雲朵。

純淨藍天：精心調校的平流層淺藍色漸層天空，視野開闊。

擬真機窗：

高解析度的淺色機窗邊框設計，搭配細膩的玻璃刮痕與反光質感。

微震動回饋：模擬引擎運作時的物理震動，提升沈浸感。

巨幕模式：

支援全螢幕滿版顯示，最大化視覺包覆感。

完全響應式設計 (RWD)，適配桌面與行動裝置。

聽覺體驗 (Audio)

機長廣播：

起飛前會有專業的英文機長廣播 ("This is your captain speaking...")，增加儀式感。

使用 Web Speech API 合成，語調沈穩權威。

引擎白噪音：

使用 Web Audio API 即時生成的 Brown Noise（紅噪音/布朗噪音）。

經過頻率優化，音量適中 (25%)，能有效隔絕外部干擾。

擬真提示音：

起飛與降落時會有雙音階（叮—咚）的機艙服務鈴聲。

操作介面 (UI)

登機證設定頁：

擬真的頭等艙登機證介面。

可自訂「目的地」（專注事項）與「飛行時間」（5 ~ 120 分鐘）。

防誤觸機制：

客製化的 "Emergency Landing" 確認視窗，防止不小心結束專注。

🚀 如何使用 (How to use)

Boarding (登機)：

輸入您的專注目標（例如：Reading, Coding）。

拖動滑桿設定預計飛行時間。

確認 "Cabin Engine Sound" 開關已開啟。

Takeoff (起飛)：

點擊 "Boarding Now" 按鈕。

聆聽機長廣播與機艙提示音，進入飛行模式。

Cruising (巡航)：

享受窗外緩緩流動的雲海與白噪音，專注於您的任務。

HUD 面板會顯示剩餘時間與當前高度。

Landing (降落)：

時間結束或手動降落後，會有提示音通知您抵達目的地。

🛠️ 技術細節 (Tech Stack)

Core: HTML5, CSS3, JavaScript (ES6+)

Styling: Tailwind CSS (CDN)

Graphics: HTML5 Canvas API (Custom Particle System)

Audio: Web Audio API (Oscillators & Noise Buffers)

Speech: Web Speech API (Synthesis)

Font: Noto Sans TC, Share Tech Mono, Libre Barcode 39
