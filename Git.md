git config --global user.name "Tên của bạn"
git config --global user.email "Email của bạn"

Clone repository từ Git server:
git clone https://<username>@<domain>/<username>/<repository>.git
git clone https://PAT@github.com/HungLM1/CCS_Tomishow
cd <repository>

Hoặc khởi tạo mới:
git init
git remote add origin https://<domain>/<username>/<repository>.git

Push code bằng PAT:
git add .
git commit -m "message here"

Lưu PAT trong credential store (tuỳ chọn):
git config --global credential.helper store


Kiểm tra domain repo:
git remote -v

reload nginx:
sudo systemctl reload nginx
restart nginx:
sudo systemctl restart nginx


