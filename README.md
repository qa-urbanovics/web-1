# web-1 — MkDocs сайт (Material)

Статический сайт/портфолио на **MkDocs** с темой **Material**. :contentReference[oaicite:1]{index=1}  
Прод-версия публикуется на GitHub Pages: `https://qa-urbanovics.github.io/web-1/`. :contentReference[oaicite:2]{index=2}

---

## Быстрый старт (локально)

### Требования
- Python 3.10+ (рекомендуется)
- pip
- (опционально) virtualenv/venv

### Установка и запуск dev-сервера

```bash
# 1) Клонируем репозиторий
git clone https://github.com/qa-urbanovics/web-1.git
cd web-1

# 2) Создаём и активируем виртуальное окружение
python -m venv .venv

# Linux/macOS:
source .venv/bin/activate
# Windows (PowerShell):
# .\.venv\Scripts\Activate.ps1

# 3) Ставим зависимости
pip install -r requirements.txt

# 4) Запускаем локально
mkdocs serve
