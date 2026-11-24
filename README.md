# Lõi xử lý Lồng Tiếng AI

Kho này chỉ để phát hành gói lõi mà ứng dụng **Lồng Tiếng AI** tự tải ở lần mở đầu tiên (xem mục *Releases*).
Bạn không cần tải tay: ứng dụng tải, kiểm tra mã SHA-256 từng phần rồi tự cài.

Gói lõi gồm phần mềm mã nguồn mở, mỗi phần giữ giấy phép riêng:

- **pyVideoTrans** — https://github.com/jianchang512/pyvideotrans — GPL-3.0. Mã nguồn có sẵn trong gói
  (thư mục `pyvideotrans/videotrans`).
- **Python 3.10** — https://www.python.org — PSF License.
- **PyTorch, faster-whisper, CTranslate2, edge-tts** và các thư viện Python khác — giấy phép kèm trong
  `pyvideotrans/.venv/Lib/site-packages/<thư viện>.dist-info`.
- **FFmpeg** (bản build của gyan.dev) — https://ffmpeg.org — GPL-3.0.
- **uv** — https://github.com/astral-sh/uv — Apache-2.0 / MIT.

Gói không chứa key, tài khoản hay dữ liệu cá nhân nào.
