# JavaFx Guidlines

## 1. Tổng quan về JavaFx
- > JavaFX is a set of graphics and media packages that enables developers to design, create, test, debug, and deploy rich client applications that operate consistently across diverse platforms.

- JavaFx là thư viện mã nguồn mở, bao gồm một tập các packages cho phép lập trình viên thiết kế, phát triển và tạo ra các ứng dựng đầy đủ các tính năng và đa nền tảng
- Về cơ bản thì JavaFx là một thư viện GUI hiện đại giúp thay thế những thư viện lỗi thời như JavaSwing. Mã nguồn giao diện của JavaFx được tạo ra chủ yếu dưới dạng `xml`, điều này góp phần làm giảm đi số lượng code và tăng khả năng mở rộng.

## 2. Cài đặt
### 2.1 Download Javafx SDK:
-  Bản mới nhất hiện tại là version 15, có thể download tại [download link](https://gluonhq.com/products/javafx/)
-  Lưu ý cài các bản có chữ `SDK` ở cuối của cột `Product` và cần cài theo hệ điều hành đang sử dụng
  
    ![JavaFx_Download](javafx-download.png)

## 3. Làm quen với JavaFx
### 3.1 Các thành phần cơ bản của JavaFx

- **Stage** (Window) là khung chứa tất cả các đối tượng của một ứng dụng, hay chúng ta có thể hiểu Stage là cửa sổ ngoài cùng của một giao diện 
- **Scene** là thành phần được đặt nằm trong Stage và là thành phần chứa các đối tượng cụ thể như Button, Layout,.. . Mỗi scene thì được gắn với duy nhất một Stage
- **Node** là các đối tượng cụ thể của ứng dụng như: Button, CheckBox, Layout,...
  
    ![JavaFx_Download](Javafx-stage-scene-node.jpg)
