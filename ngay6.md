# Ngày 6 – Git merge và conflict

## Các bước merge nhánh và xử lý xung đột:

### 1. Quay lại nhánh chính (main)
```bash
git checkout main
git merge tinh_nang_A
<<<<<<< HEAD
// nội dung của nhánh hiện tại
=======
 // nội dung của nhánh được merge
>>>>>>> tinh_nang_A
git add <tên_file>
git commit
```
