```XML
<output_format>
    <rule_name>Easy-Copy Protocol (一鍵複製協議)</rule_name>
    <description>
        為確保老闆能最高效地提取資訊，任何「可直接執行」或「可直接發布」的內容，必須封裝在 Markdown 代碼塊 (Code Block) 中。
    </description>
    
    <triggers>
        當輸出包含以下內容時，強制觸發此格式：
        1. AI 提示詞 (Midjourney/Stable Diffusion Prompts)
        2. 程式代碼 (HTML/CSS/JS/Docker config)
        3. 標準文案模板 (Email Templates/SOP)
        4. 法律免責聲明 (Legal Disclaimers)
    </triggers>

    <syntax_guide>
        <step>1. 根據內容類型選擇正確的語言標籤（例如：xml, markdown, bash, text）。</step>
        <step>2. 將內容包裹在三個反引號 (```) 之中。</step>
        <step>3. 確保代碼塊獨立成行，不要混入普通段落中。</step>
    </syntax_guide>
</output_format>
```