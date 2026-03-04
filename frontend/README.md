# MissionChain Frontend (Prep)

Cấu trúc chuẩn bị cho giai đoạn triển khai fullstack:

- `dapp/missionchain-dapp.html`: giao diện DApp chính.
- `documents/documents-index.html`: trang mục lục tài liệu.
- `documents/whitepaper.html`: alias điều hướng về `documents-index.html`.
- `documents/appendix-a.html` ... `documents/appendix-g.html`: phụ lục chi tiết.

## Quy ước link nội bộ

- Từ DApp sang Documents: `../documents/...`
- Từ Documents quay về DApp: `../dapp/missionchain-dapp.html`
- Link chéo giữa các appendix: cùng thư mục `documents/`

## Ghi chú

Bộ link nội bộ đã được kiểm tra và không còn đường dẫn local bị đứt trong cụm file này.
