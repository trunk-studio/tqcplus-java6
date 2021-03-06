# Java 程式語言的特色

追溯至 1990 年 12 月，Sun（昇陽電腦）公司成立 Green Team 團隊，主要成員有 Patrick Naughton、Mike Sheridan 及 James Gosling。他們開始著手一項名為「Green Project」的新專案，目標是發展一種系統架構，使程式能夠在電腦以外的消費性電子產品運作（例如手機、資訊家電等）。

Green Team 在 1992 年 9 月，發表一款名為 Star Seven（簡稱 Star 7 或 *7）的機器，它和 PDA 裝置類似，Star 7 在當時已具有先進的無線通訊功能。Java 程式語言的前身 Oak 在此時誕生，用來開發 Star 7 的軟體程式；當時 James Gosling 因為看見窗外的「橡樹（oak）」，決定將新程式語言命名為 Oak。

當 Oak 要註冊成商標時，才發現這個名字已經被別家公司註冊。由於工程師們喜歡在討論時喝咖啡，就將程式語言名稱改為 Java（一種咖啡的名稱），這個名稱就一直沿用到現在。

Java 有別於許多傳統程式語言（例如 C 語言等）：

- 許多傳統程式語言在編譯之後，會產生機器碼（machince code），然後直接在硬體上執行；
Java 在編譯後則會產生 Byte Code，並間接的在 Java Virtual Machine（JVM）上執行。這個 JVM（Java 虛擬機器）其實是一個軟體，其功用是解譯並執行 Byte Code，而 JVM 仍然是在硬體上執行。
- Java 虛擬機器（JVM）是軟體，所以 Java 程式具有跨平台的特性：只要為不同的處理器或作業系統設計其專屬的 JVM，Java 程式便可以不需改寫，就能在這些不同的處理器或作業系統上執行。這便是「Write once, runs everywhere」（一次編譯、到處執行）的由來。

Java 支援物件導向程式設計（Object-Oriented Programming），所謂「物件」的概念，可以用常見的家電作比喻。物件包含「屬性」及「方法」，例如冷氣機的「屬性」有：「開關」及「溫度」；而「方法」則有：「開機」、「關機」及「設定溫度」等。

支援物件導向的程式語言，讓程式設計師在撰寫比較複雜的程式時，可以設計比較容易幫助思考的物件，模擬、控制與應用電腦本身（如滑鼠與鍵盤等也是物件）和我們生活周遭的物件的程式，因此便有研究人員發明了支援物件導向程式設計的語言。

Java 的設計搭上了全球資訊網的順風車，原因是 Java 的設計團隊可以寫一個能夠在瀏覽器中執行的 JVM，而讓 Java Applet 程式可以透過網路下載至瀏覽器中執行。這個「網路＋物件導向」的特性讓 Java 瞬間爆紅。

除了跨平台、物件導向、可透過網路動態的載入及執行程式等功能之外，Java 還支援多執行緒、例外狀態處理與自動記憶體回收的功能：

- 多執行緒讓一個程式可以執行數個工作；
- 例外狀態處理讓處理例外的程式碼也能夠物件化；
- 自動記憶體回收則讓程式設計師免除了使用低階的指標（pointers）來設計資料結構及管理記憶體的負擔。這個特色成了 C 與 C++ 語言程式設計師的福音，因為它可以為程式設計師減少許多不容易 debug 的錯誤。
