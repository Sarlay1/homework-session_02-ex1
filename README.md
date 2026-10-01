# Exercise 1 - Khởi tạo Droplet trên DigitalOcean

## 1. Mục tiêu

Khởi tạo một Droplet chạy Ubuntu Server trên DigitalOcean và
cấu hình đăng nhập bằng SSH Key thay vì mật khẩu.

## 2. Thông tin Droplet

- Provider: DigitalOcean
- OS: Ubuntu 22.04 LTS
- Region: Singapore
- Plan: Basic
- CPU: Shared CPU
- Disk: Regular SSD
- Authentication: SSH Key
- Username: root

## 3. Tạo SSH Key

Trên máy Windows, sử dụng PowerShell:

```powershell
ssh-keygen -t ed25519 -C "your_email@example.com"