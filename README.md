# Huong dan publish package npm

## B1. Bước 1: Lập tài khoản NPM
* Đăng ký tài khoản npm [tại đây](https://www.npmjs.com/signup). Đây là nơi chúng ta sẽ đẩy package và quản lý chúng.

## B2. Tạo Reposiory git
* Tạo repository tại [github](https://github.com/). Package của bạn cần nằm trong 1 reposiry dạng pulic. Đây sẽ là trang giúp chúng ta quản lý mã nguồn và tài liệu hướng dẫn sử dụng package.

## B3: Tạo thư mục package
Bạn cần tạo một thư mục là tên của package bạn muốn viết. Cấu trúc bên trong thư mục của 1 package rất đơn giản với 2 file sau:
* json: khai báo thông tin về package
* js: viết theo cấu trúc module, export các thành phần. Khi require package chính là thực hiện require file này.

## B4: Tạo package
    4.1 Tạo file package.json
    {
        "name": "tets1",
        "version": "0.1.2",
        "main": "index.js",
        "repository": "****",
        "author": "9420",
        "license": "MIT",
        "dependencies": {
            "tets1": "^0.1.0"
        }
    }