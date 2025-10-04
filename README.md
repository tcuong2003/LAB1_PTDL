RULE CODE
-- Chỉ được làm và add/commit/push trên checkout branch của mình 
-- Sau khi push thì tạo pull request và thông báo trên zalo nhóm
-- Nội dung đúng khi

++ commit
    feat:	Thêm chức năng mới
    fix:	Sửa lỗi
    refactor:	Cải thiện code mà không đổi logic
    style:	Sửa giao diện / CSS / UI
    docs:	Thêm hoặc sửa tài liệu
    test:	Thêm hoặc sửa test
    chore:	Thay đổi nhỏ, dọn dẹp, config

Ex: git commit -m "feat: thêm file abc.xyz"

++ pull request
    Ex:
    Title:
        feat: thêm chức năng đăng nhập người dùng (giống commit)
    Description:
        Chi tiết nội dung thay đổi 

*** Chỉ có LEADER mới merge và branch main ***

CẤU TRÚC THƯ MỤC 

bai (ex: thong_ke_mo_ta)/
├── chuong (ex: covid)/            
│   ├── data/
|        ├── file.csv
│   ├── file.ipynb/
├── chuong (ex: ...)/ 
|   ├── data/
|        ├── file.csv
│   ├── file.ipynb/