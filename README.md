# การสร้างคำบรรยายภาพด้วยแบบจำลอง CLIP Prefix Caption บนชุดข้อมูล Traffy Fondue และการใช้ Prefix Embedding จัดกลุ่มรูปภาพ
## [ผลการทดลองจัดกลุ่มรูปภาพด้วย Prefix Embeddings](https://wandb.ai/sahaz/prefix_embed_traffyV4/reports/Weave-traffyv8-22-11-25-14-15-18---VmlldzozMDMzNDMy?accessToken=7pmmkulcigofd0acltil0zqv5rney73yowlvbra5ro70uabzzm0r53hh1y8dqu4v)
## [Example on Google Colab](https://colab.research.google.com/drive/1k87uXkK9Zz5wwxOsNpZ3d0o48v6vaMaP?usp=sharing)

คู่มือสำหรับติดตั้งและทดลองใช้งานแบบจำลอง CLIP Prefix Caption บน Local Machine
1. ติดตั้ง Python Virtual Environment โดยจะใช้รันไทม์เวอร์ชันใดก็ได้ (ในการทดลองใช้ >=3.7.6)
2. ติดตั้ง Pytorch (Stable Version) พร้อม CUDA 11.6
3. ติดตั้ง Package ตาม requirements.txt ของ Repository นี้
