# 轮胎检查 PWA V4 Compact OCR

V4使用Tesseract.js 7、单一SIMD LSTM Core和`eng 4.0.0_fast`，不保留node_modules、其他语言包、其他Core或npm临时文件。

## Windows一键准备
```powershell
PowerShell -ExecutionPolicy Bypass -File .\prepare-ocr-assets.ps1
```

## Git Bash
```bash
bash prepare-ocr-assets.sh
```

完成后上传项目文件夹内容到GitHub，不要上传ZIP、`.ocr-tmp`或`node_modules`。

## 本地测试
```powershell
python -m http.server 8080
```
打开 http://localhost:8080。
