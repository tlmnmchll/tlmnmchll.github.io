半年前，ChatGPT刚刚火热起来时，我在知乎上创建了一个提问：“你在使用ChatGPT进行论文润色时的指令有哪些？”。目前，这个问题已经收到了113个答案，浏览量超过110万。而我的回答也获得了36万的阅读量和1.6万的收藏量，帮助了许多在英文论文写作上遇到困难的小伙伴。

这次，我将分享使用GPT4.0进行论文润色的指令总结，希望能继续为你的科研写作提供帮助。

---

## 1. 论文润色指令汇总

### 1.1 以往的一些指令

以下是一些常用的论文润色指令示例：

#### 模板1（润色）
plaintext
Below is a paragraph from an academic paper. Polish the writing to meet the academic style, improve the spelling, grammar, clarity, concision, and overall readability. When necessary, rewrite the whole sentence. Furthermore, list all modifications and explain the reasons to do so in a markdown table. Paragraph: XXX


#### 模板2（检查语法）
plaintext
Can you help me ensure that the grammar and the spelling is correct? Do not try to polish the text. If no mistake is found, tell me that this paragraph is good. If you find grammar or spelling mistakes, please list mistakes you find in a two-column markdown table. Put the original text in the first column, and the corrected text in the second column. Highlight the key words you fixed. Example: 
| Original sentence | Corrected sentence |
| :--- | :--- |
| How is you? | How are you? |
| Do you knows what is it? | Do you know what it is? |
Below is a paragraph from an academic paper. You need to report all grammar and spelling mistakes as the example before. Paragraph: XXX


#### 其他网友分享的指令
1. **提升学术质量**  
   plaintext
   Please reword and refine these paragraphs to improve their academic quality and grammatical structure. Ideally, the language should be similar to that found in the American Economic Review. Please note all the changes made.
   

2. **语言风格调整**  
   plaintext
   Please use the language style found in the American Economic Review to improve the grammar and language of the paragraphs.
   

3. **领域专家视角**  
   plaintext
   You are now acting as an expert in the field of XXX（领域名称）. From a professional point of view, do you think there is any need to modify the above content? Be careful not to modify the whole text. You need to point out the places that need to be modified one by one, and give revision opinions and recommended revision content.
   

4. **SCI论文润色**  
   plaintext
   You are now acting as an expert in the field of writing SCI academic papers. Below is a paragraph from an academic paper. From a professional point of view, please polish the writing to meet the academic style, improve the spelling, grammar, clarity, concision, and overall readability. Be careful not to modify the full text or add any new content, just modify the original sentence. Furthermore, list all modifications and explain the reasons to do so in a markdown table. The content as follows: XXX（待润色语段）
   

---

### 1.2 指令包含的内容总结

如何写好一个大语言模型的Prompt？可以包含以下几个方面：
- **关键词**：如修改语法、改进语序以更符合学术论文等。
- **领域说明**：明确论文所在的领域。
- **修改原因**：解释修改的原因，帮助理解。

---

## 2. 小硕总结的好用论文润色指令（珍藏版）

经过多次调试和实践，我总结了以下ChatGPT英文学术论文润色指令。如果你的英文较好，可以直接使用全英文版本；如果英文不好，可以使用中文解释版。

### 全英文版
plaintext
I am preparing my SCI paper for submission and require assistance in polishing each paragraph. Could you please refine my writing for academic rigor? I need you to correct any grammatical errors, improve sentence structure for academic suitability, and make the text more formal where necessary. For each paragraph we need to improve, you need to put all modified sentences in a Markdown table, each column contains the following: Full original sentence; Highlight the revised part of the sentence; Explain why made these changes. Finally, rewrite the full, corrected paragraph. If you understand, please reply: yes, let's get started.


### 中文解释版
plaintext
I am preparing my SCI paper for submission and require assistance in polishing each paragraph. Could you please refine my writing for academic rigor? I need you to correct any grammatical errors, improve sentence structure for academic suitability, and make the text more formal where necessary. For each paragraph we need to improve, you need to put all the modified sentence in a Markdown table, each column contains the following: Full original sentence; Highlight the revised part of the sentence; using Chinese explain why made these changes. Finally, Rewrite the full, corrected paragraph. If you understand, please reply: yes, let's get started.


---

## 3. GPT3.5和GPT4效果对比

答案显而易见：**GPT4效果更好！**

目前来看，GPT4的润色效果比GPT3.5更为出色。以下是GPT3.5和GPT4的对比案例：

- **GPT4案例效果**  
  GPT4能够准确理解提示，并提供高质量的润色结果。

- **GPT3.5案例效果**  
  GPT3.5在理解提示时存在问题，润色效果较差。

---

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)

希望这篇文章对你有所帮助！如果你有更多问题，欢迎留言交流！