# การสร้างคำบรรยายภาพด้วยแบบจำลอง CLIP Prefix Caption บนชุดข้อมูล Traffy Fondue และการใช้ Prefix Embedding จัดกลุ่มรูปภาพ
## [ผลการทดลองจัดกลุ่มรูปภาพด้วย Prefix Embeddings](https://wandb.ai/sahaz/prefix_embed_traffyV4/reports/Weave-traffyv8-22-11-25-14-15-18---VmlldzozMDMzNDMy?accessToken=7pmmkulcigofd0acltil0zqv5rney73yowlvbra5ro70uabzzm0r53hh1y8dqu4v)
## [Example on Google Colab](https://colab.research.google.com/drive/1k87uXkK9Zz5wwxOsNpZ3d0o48v6vaMaP?usp=sharing)

## คู่มือสำหรับติดตั้งและทดลองใช้งานแบบจำลอง CLIP Prefix Caption บน Local Machine
1. ติดตั้ง Python Virtual Environment โดยจะใช้รันไทม์เวอร์ชันใดก็ได้ (ในการทดลองใช้ >=3.7.6)
2. ติดตั้ง Package ตาม requirements.txt ของ Repository นี้ (หลัก ๆ ประกอบด้วย torch 1.13.0 + CUDA, transformers, evaluate, rouge_score, wandb)
3. git clone [CLIP](https://github.com/openai/CLIP)
4. ติดตั้ง Package ตาม requirements.txt ใน CLIP ข้อ 3.
5. ดาวน์โหลด Weigths ของ CLIP Prefix Caption, CLIP Model, และตัว Tokenizer ของ GPT-2 (ดูตัวอย่างได้ใน Colab)

Disclaimer: This repository use for educational only.
Thanks to https://github.com/rmokady/CLIP_prefix_caption
