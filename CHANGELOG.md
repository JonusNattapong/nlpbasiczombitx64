# Changelog

## [0.2.1] - 2023-07-20

### เพิ่ม
- รองรับการใช้งาน PyThaiNLP เพื่อเพิ่มความสามารถขั้นสูงในการประมวลผลภาษาไทย
- ฟังก์ชันขั้นสูงสำหรับการจัดการตัวเลขไทย (thai_number_to_text, thai_text_to_number)
- ฟังก์ชันขั้นสูงสำหรับการจัดการวันที่และเวลาภาษาไทย (format_thai_date, thai_time, thai_day_to_datetime)
- ฟังก์ชันขั้นสูงสำหรับการค้นหาคำที่มีเสียงคล้ายกัน (thai_soundex)
- ฟังก์ชันขั้นสูงสำหรับการแก้ไขคำผิด (spell_correction)
- ฟังก์ชันขั้นสูงสำหรับการจัดการคำหยุดและพยางค์ภาษาไทย (get_thai_stopwords, get_thai_syllables)
- ฟังก์ชันขั้นสูงสำหรับการใช้งาน WordNet ภาษาไทย (get_thai_wordnet_synsets, get_thai_wordnet_synonyms)
- ฟังก์ชันขั้นสูงสำหรับการแปลงเลขไทยและเลขอารบิก (thai_digit_to_arabic_digit, arabic_digit_to_thai_digit)

### ปรับปรุง
- ปรับปรุงการตัดคำภาษาไทยให้รองรับหลายอัลกอริทึมจาก PyThaiNLP (newmm, longest, attacut)
- ปรับปรุงการแท็กส่วนของคำพูดให้รองรับหลายโมเดลจาก PyThaiNLP (perceptron, artagger)
- เพิ่มความสามารถในการแปลงระหว่างรูปแบบแท็กส่วนของคำพูดต่างๆ (UD, ORCHID)
- เพิ่มตัวอย่างการใช้งานฟังก์ชันขั้นสูงใน advanced_usage.py

## [0.2.0] - 2023-07-15

### เพิ่ม
- การจำแนกข้อความ (Text Classification) ด้วยวิธีการใช้คำสำคัญและ Zero-shot
- การจำแนกโทเค็น (Token Classification) สำหรับการแท็กส่วนของคำพูดและการรู้จำหน่วยงานที่มีชื่อเสียงแบบละเอียด
- การตอบคำถาม (Question Answering) สำหรับการตอบคำถามจากบริบทและตาราง
- การแปลภาษา (Translation) ระหว่างภาษาไทยและภาษาอังกฤษ
- การสกัดคุณลักษณะ (Feature Extraction) สำหรับการวิเคราะห์ข้อความภาษาไทย
- การสร้างข้อความ (Text Generation) ด้วยเทมเพลต, n-gram และรูปแบบไวยากรณ์
- การวัดความคล้ายคลึงของข้อความ (Text Similarity) ด้วยวิธีการต่างๆ
- ตัวอย่างการใช้งานขั้นสูง (Advanced Usage Examples)

### ปรับปรุง
- เพิ่มประสิทธิภาพการวิเคราะห์อารมณ์ด้วยดิกชันนารีที่ครอบคลุมมากขึ้น
- ปรับปรุงการแท็กส่วนของคำพูดให้มีความแม่นยำมากขึ้น
- เพิ่มทรัพยากรภาษาไทย (Thai Resources) สำหรับการประมวลผลภาษาธรรมชาติ

## [0.1.0] - 2023-07-01

### เพิ่ม
- การตัดคำ (Tokenization) ด้วยอัลกอริธึม Maximum Matching
- การแท็กส่วนของคำพูด (Part-of-Speech Tagging) ด้วย Hidden Markov Model
- การรู้จำหน่วยงานที่มีชื่อเสียง (Named Entity Recognition) ด้วยกฎและดิกชันนารี
- การวิเคราะห์อารมณ์ (Sentiment Analysis) ด้วยดิกชันนารีคำศัพท์
- การตรวจสอบการสะกดคำ (Spell Checking) ด้วย Edit Distance
- การสรุปข้อความ (Text Summarization) ด้วยอัลกอริธึม TextRank
- เครื่องมือช่วยเหลือ (Utilities) สำหรับการประมวลผลภาษาไทย 