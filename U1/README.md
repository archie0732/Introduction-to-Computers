# Unit - 1(有翻譯)

## 1-1 Turing Mode

1. universal computation  device was **first** described by **Alan Turing**  (世上第一台萬用電腦模型由turing提出)  
2. alan turing proposed that all computation could be performed by a special kind of a machine ==> **turing machine**(提出所有計算都可以由一種特殊的機器來執行==>就是現在所說的**圖靈機**)

冷知識:  
>圖靈測試（英語：Turing test）是英國電腦科學家艾倫·圖靈於1950年提出的思想實驗，目的是測試機器能否表現出與人一樣的智力水準。測試時測試者透過電腦鍵盤輸入文字並透過螢幕輸出文字  
[完整內容](https://zh.wikipedia.org/zh-tw/%E5%9B%BE%E7%81%B5%E6%B5%8B%E8%AF%95)

3. general-purpose computer : A program is a set of instructions that tells the computer what to do with data(通用計算機:一組告訴電腦如何處理資料的指令。)
4. **A Universal Turing Machine(萬用圖靈機)**, a machine that can do any computation if the appropriate program is provided, was the first description of a modern computer.(給正確的程式碼，可以做任何計算)


## 1-2 nov Neumann Model 
1. nov Neumann propose program and data all store in the memory(他提出程式跟資料都存於記憶體)
2. Early electroniccomputers (1930-1950)did not store the program in memory—all were programmed externally(在那之前得電腦程式都透過硬體接線)
3. **Every computer today is based on the von Neumann Model**(**所有的電腦都是以nov model為基礎**)
   >1. four subsystem(四個子系統)
   >2. stored program concept(程式可存)
   >3. Sequential Execution of Instructions(指令依序執行)
   
**four subsystem**  
![](https://raw.githubusercontent.com/archie0732/Introduction-to-Computers/main/picture/unit/Screen-Shot-2017-04-26-at-1.08.57-PM.webp)
>* Memory– the storage area of programsand data(記憶體:儲存程式與資料)
>* ALU– arithmetic/logicoperations take place(ALU:計算與邏輯)
>* Control Unit– control Memory, ALU, and I/O(控制單元:控制記憶體、AUL與I/O)
>* I/O-input and output

## Sequential Execution of Instructions(程式依照順序執行)  
*~The instructions are executed one after another* 

  
**The control unit**  
* fetches(抓取)one instruction from memory
* interpret(解讀)it
* execute(執行)it
* **不包含**`compile`(編譯)
## Computer Components
1. software(軟體)
2. hardware(硬體)
   >* cpu(內含ALU、控制單元等)
   >* 記憶體
   >* 輸入、輸出設備(例如:傳輸線)
  
**store data**(with binary)  <br>  
Store data in the form of an electrical signal, specifically its presenceor absence.  
```
使用電子訊號儲存資料，看他是有訊號或無訊號
```
## algorithms(演算法)
1. first solve the problem in a step-by-step mannerand then(一步步的解決問題)   
2. try to find the appropriate sequenceof instructionsthat solves the problem.(正確的方式解決問題)

    
**ex:**      
![](https://github.com/archie0732/Introduction-to-Computers/blob/main/picture/unit/375px-LampFlowchart_ZhT.svg.png)  
[完整內容](https://zh.wikipedia.org/zh-tw/%E7%AE%97%E6%B3%95)  
## Languages
* Machine languages(機器語言): binary
* Assembly languages(組合語言):symbol pattern CPU dependent(與cpu相關)
* High level languages(高階語言):symbol patternCPU independent(與cpu獨立)
## 其他
[.](https://youtu.be/dQw4w9WgXcQ?si=B_DTpgtca1LjOyOw)  
