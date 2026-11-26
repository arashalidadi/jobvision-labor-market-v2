# داده خام

فایل داده در این پوشه قرار می‌گیرد و به دلیل حجم (حدود ۳۷۴ مبی‌بایت / ۳۹۲ مگابایت) و محدودیت مجوز، در مخزن گیت‌هاب نگهداری نمی‌شود (در `.gitignore` است).

- مسیر مورد انتظار در پروژه: `data/JobVision_Jobposts_Dataset.csv`

## دریافت داده

- صفحه داده: <https://huggingface.co/datasets/JobVision/JobVision_Jobposts_Dataset>
- نام فایل: `JobVision_Jobposts_Dataset.csv`
- داده در بخش *Files and versions* مخزن Hugging Face در دسترس است.

در Google Colab یا هر محیط دیگری می‌توانید فایل را مستقیماً از مخزن Hugging Face دانلود کنید:

```python
from huggingface_hub import hf_hub_download

path = hf_hub_download(
    repo_id="JobVision/JobVision_Jobposts_Dataset",
    filename="JobVision_Jobposts_Dataset.csv",
    repo_type="dataset",
)
```

## مشخصات داده

| مشخصه | مقدار |
| --- | --- |
| تعداد ردیف | ۳۶۴٬۸۳۸ آگهی |
| تعداد ستون | ۴۳ |
| بازه انتشار | فروردین ۱۴۰۱ تا اسفند ۱۴۰۲ (مارس ۲۰۲۲ تا مارس ۲۰۲۴) |
| واحد حقوق | میلیون تومان در ماه (برداشت‌شده از بازه مقادیر و مقایسه با بازار) |
| مجوز | CC BY-NC 4.0 — استفاده پژوهشی و غیرتجاری با ذکر منبع |
