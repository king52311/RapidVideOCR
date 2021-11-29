# VideoOCR
- Forked from [videocr](https://github.com/apm1467/videocr)
- The part of OCR is accepted the [RapidOCR](https://github.com/RapidAI/RapidOCR).

#### Want to do
- [ ] Refactor the project code.
- [ ] Less time to process the video.
- [x] Refer[ClipVideo](https://github.com/SWHL/ClipVideo).~~Combined with video editing, given a text field, the program can automatically clip the correspoding video segment.~~~

#### Use
1. Install the rapidocr package by the following:
   ```shell
   pip install https://github.com/RapidAI/RapidOCR/raw/main/release/python_sdk/sdk_rapidocr_v1.0.0/rapidocr-1.0.0-py3-none-any.whl
   ```
3. Download the models and character dict of the RapidOCR by the link [Extract code: drf1](https://pan.baidu.com/s/103kx0ABtU7Lif57cv397oQ) or [Google Drive](https://drive.google.com/drive/folders/1cjfawIhIP0Yq7_HjX4wtr_obcz7VTFtg?usp=sharing)
4. Put the models in the `resources/models`
5. `python example.py`
   ```text
    Extract: 100%|██████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████████| 304/304 [01:30<00:00,  3.35it/s]
    0
    00:00:00,583 --> 00:00:04,375
    我要去杂货店买点东西要我帮你买点牛奶吗？
    Im going grocery shopping.Youwant some milk？
    1
    00:00:08,000 --> 00:00:08,541
    个还是两个？是两个
    对吧？
    Onequart ortwo？It'stwo，right？
   ```
