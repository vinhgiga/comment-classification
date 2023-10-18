# Comment Classification

## Nội dung

1. Cào dữ liệu với Selenium.
2. Gán nhãn dữ liệu với Label Studio.
3. Tiền xử lý dữ liệu.
4. Phân tích dữ liệu.
5. Mô hình phân loại: PhoBERT, TFITF + MultinomialNB.
6. Đánh giá mô hình: confusion matrix, accuracy, precision, recall, f1 score.

## Thiết lập

- Python 3.10.
- Cài đặt môi trường
  - Trên Windows:

  ```powershell
  $ python -m venv env
  $ .\env\Scripts\activate
  $ python -m pip install -r requirements.txt
  ```

  - Trên macOS, Linux:

  ```bash
  $ python3 -m venv env
  $ source env/bin/activate
  $ python3 -m pip install -r requirements.txt
  ```
