# Deploy lên GitHub Pages

## Bước 1: Tạo repository trên GitHub

1. Vào [github.com/new](https://github.com/new)
2. Đặt tên repo (ví dụ: `Elsa-1st-birthday` hoặc `elsa-birthday`)
3. Chọn **Public**
4. **Không** tick "Add a README" (repo local đã có code)
5. Bấm **Create repository**

## Bước 2: Đẩy code lên GitHub

Trong terminal, chạy (thay `USERNAME` và `REPO` bằng tên GitHub và tên repo của bạn):

```bash
cd /Users/tantd2/My/Elsa-1st-birthday
git remote add origin https://github.com/USERNAME/REPO.git
git branch -M main
git push -u origin main
```

Ví dụ nếu username là `tantd2` và repo là `Elsa-1st-birthday`:

```bash
git remote add origin https://github.com/tantd2/Elsa-1st-birthday.git
git push -u origin main
```

## Bước 3: Bật GitHub Pages

1. Vào repo trên GitHub → **Settings** → **Pages** (menu trái)
2. Ở **Source** chọn **Deploy from a branch**
3. **Branch**: chọn `main` → **/ (root)** → **Save**
4. Đợi 1–2 phút, trang sẽ có tại:
   - `https://USERNAME.github.io/REPO/`

Ví dụ: `https://tantd2.github.io/Elsa-1st-birthday/`
