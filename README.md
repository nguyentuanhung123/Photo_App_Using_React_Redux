# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Mục tiêu

Xây dựng một project mini đơn giản để ứng dụng kiến thức phần Redux vào project ReactJS

- Đơn giản, không quá phức tạp
- Tập trung nhiều vào `Redux` với `Redux Toolkit`
- Sử dụng toàn bộ là `hooks`
- Học sử dụng UI lib: `Reactstrap`
- Học cách sử dụng form: `Formik`
- Học cách tổ chức API (optional)

## Project này build cái gì

`PHOTO APP`

- App đơn giản để quản lý hình ảnh yêu thích, được chọn lựa từ https://picsum.photos/
- CRUD operations
- Gồm có 2 trang
- `Home`: listing + view + delete
- `AddEdit`: dùng để tạo mới + sửa thông tin của một photo
- Mỗi photo gồm: `title` + `categoryId` + `imageUrl`
- Các chức năng:
  - Rebder danh sách photo yêu thích
  - Lọc photo theo category
  - Thêm mới một photo
  - Chỉnh sửa một photo
  - Xoá một photo
  - Persist dữ liệu khi reload browser
  - Random photo ngẫu nhiên từ https://picsum.photos/
  - Hiển thị danh sách photo từ https://picsum.photos/ để lựa chọn
