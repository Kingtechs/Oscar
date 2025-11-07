# Creative Flask Site

A prettier Flask starter featuring:
- Dark mode toggle
- Projects page fed by `data/projects.json`
- Tiny blog rendering Markdown from `posts/`
- Simple JSON API at `/api/projects`
- 404 page, responsive header, and mobile menu

## Quickstart
```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
python app.py
```
Visit http://localhost:5000

### Customize
- Add/edit projects in `data/projects.json`
- Create new posts in `posts/your-title.md` (the first `#` heading becomes the title)
- Tweak colors/styles in `static/style.css`