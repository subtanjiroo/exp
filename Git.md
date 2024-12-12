git config --global user.name "Tên của bạn"
git config --global user.email "Email của bạn"

Clone repository từ Git server:
git clone https://<username>@<domain>/<username>/<repository>.git
cd <repository>

Hoặc khởi tạo mới:
git init
git remote add origin https://<domain>/<username>/<repository>.git

Push code bằng PAT:
git add .
git commit -m "message here"

Lưu PAT trong credential store (tuỳ chọn):
git config --global credential.helper store


