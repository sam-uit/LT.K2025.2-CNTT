# LT.K2025.2-CNTT

- A LT.K2025.2-CNTT Repo.

Đây là một kho/vault của https://obsidian.md/.

- Clone.
- "Open folder as vault".

## Thông báo

* Truy cập các [Thông báo](thongbao/thongbao.md).

## Kế Hoạch Đào Tạo Các Kỳ

1. [2025 - 2026: Học Kỳ 1](2025-2026-HK1.md) (Bấm để xem chi tiết)
2. 2025 - 2026: Học Kỳ 2 (Chưa bổ sung)
3. 2025 - 2026: Học Kỳ 3 (Chưa bổ sung)

## Chương Trình Đào Tạo Cử Nhân Liên Thông

- [Chương trình đào tạo Cử nhân Liên thông Đại học ngành Công nghệ thông tin – Hình thức đào tạo từ xa (Áp dụng từ khoá tuyển 2024)](https://www.citd.vn/chuong-trinh-dao-tao-cu-nhan-lien-thong-nganh-cong-nghe-thong-tin-hinh-thuc-dao-tao-tu-xa-ap-dung-tu-khoa-tuyen-2024/)
- Chi tiết ở [Khung Chương Trình Đào Tạo](thongbao/khung-chuong-trinh-dao-tao.md), hoặc dạng bảng phẳng [Khung Chương Trình Đào Tạo Liên Thông (2025)](uit/khung-chuong-trinh-dao-tao-lien-thong.md)

Mô hình:

```mermaid
---
config:
  theme: default
  look: classic
  layout: dagre
  themeVariables:
    fontFamily: Iosevka
title: Khung Chương Trình Đào Tạo (Tối thiểu 52 tín chỉ)
---
flowchart TD
 subgraph AA["CÁC MÔN HỌC ĐẠI CƯƠNG (10 TC)"]
        AAA("Toán - Tin Học - Khoa Học Tự Nhiên (10TC)")
        AA1>"Đại số tuyến tính (3 TC)"]
        AA2>"Cấu trúc rời rạc (4 TC)"]
        AA3>"Xác suất thống kê (3 TC)"]
  end
 subgraph BB["CÁC MÔN HỌC CƠ SỞ NGÀNH (>= 20 TC)"]
        BBa("Giới thiệu ngành (1 TC)")
        BBa1>"Giới thiệu ngành CNTT (1 TC)"]
        BBb("Kiến Thức Lập Trình (4 TC)")
        BBb1>"Cấu Trúc Dữ Liệu Và Giải Thuật (4 TC)"]
        BBc("Kiến Thức Phần Cứng & Hệ Điều Hành (4 TC)")
        BBc1>"Hệ Điều Hành (4 TC)"]
        BBd("Kiến Thức Nền Tảng về CNTT (15 TC)")
        BBd1>"Cơ Sở Hạ Tầng CNTT (3TC)"]
        BBd2>"Quản Lý Thông Tin (4TC)"]
        BBd3>"Nhập Môn Bảo Đảm và An Ninh Thông Tin (4 TC)"]
        BBd4>"Phân Tích Thiết Kế Phần Mềm (4 TC)"]
  end
 subgraph CC["CÁC MÔN HỌC CHUYÊN NGÀNH (>= 12 TC)"]
        CC1>"Truyền Thông Xã Hội & Web"]
        CC2>"Khoa Học Thông Tin"]
  end
 subgraph DD["TỰ CHỌN TỰ DO (max 4 TC)"]
        D>"TỰ CHỌN TỰ DO"]
  end
 subgraph EE["KIẾN THỨC TỐT NGHIỆP (10 TC)"]
        EE1>"1\. Khóa Luận Tốt Nghiệp"]
        EE2>"2\. Chuyên Dề & Đồ An"]
        EE3>"3\. Đồ An Tại Doanh Nghiệp"]
  end
    AA --> BB
    AAA --> AA1 & AA2 & AA3
    BBa --> BBa1
    BBb --> BBb1
    BBc --> BBc1
    BBd --> BBd1 & BBd2 & BBd3 & BBd4
    BB -- hoặc --> CC1 & CC2
    BB -- bổ sung --> DD
    CC -- hoặc --> EE1 & EE2 & EE3
```

Hình ảnh:

![Phân Bổ Các Khối Kiến Thức](thongbao/assets/phan-bo-khoi-kien-thuc.jpeg)

## Kế Hoạch Đào Tạo Tổng Quan

```mermaid
timeline
    title Kế Hoạch Đào Tạo
    HK1 : IE005 (Giới Thiệu Ngành CNTT)
        : IT007 (Hệ Điều Hành)
        : MA003 (Đại Số Tuyến Tính)
        : IE101 (Cơ Sở Hạ Tầng CNTT)
        : IE103 (Quản Lý Thông Tin)
    HK2 : IT003 (Cấu Trúc Dữ Liệu và Giải Thuật)
         : MA004 (Cấu Trúc Rời Rạc)
         : MA005 (Xác Suất Thống Kê)
         : IE105 (Nhập Môn Bảo Đảm và An Ninh Thông Tin)
    HK3 : Các Môn Chuyên Ngành
        : Chuyên Đề Tốt Nghiệp
    HK4 : IE505 (Khóa Luận Tốt Nghiệp)
        : IE501 (Đồ Án Tốt Nghiệp)
        : Hoặc IE502 (Đồ Án Tốt Nghiệp tại Doanh Nghiệp)
```

## Kế Hoạch Năm Học 2025 - 2026

- https://www.citd.vn/ke-hoach-nam-hoc/

![Kế Hoạch Năm Học 2025 - 2026](thongbao/assets/Ke-Hoach-Nam-Hoc-2025-2026.png)
