# My Site (GitHub Pages)

## ���J�܂ł̎菇

1. ���̃��|�W�g���� GitHub �� push ����
   ```bash
   git add .
   git commit -m "Add static site (OGP, dark mode, sitemap, etc.)"
   git push origin main
   ```
2. GitHub �̃��|�W�g���y�[�W���J��
3. Settings -> Pages �ֈړ�
4. Build and deployment �� Source �� "Deploy from a branch" �ɐݒ�
5. Branch �� `main` / `/ (root)` �ɐݒ肵�� Save
6. ���\�b?������A"Your site is live at ..." �� URL ���\��
7. �\�����ꂽ URL �փA�N�Z�X������m�F

## �@�\�ꗗ
- OGP / Twitter �J�[�h meta �^�O
- �_�[�N���[�h (�V�X�e�� + �蓮�ؑ�)
- �Ǝ� 404 �y�[�W
- �T�C�g�}�b�v (sitemap.xml) & robots.txt
- Jekyll ������ (.nojekyll)
- SVG favicon
- MIT License
- About �y�[�W (�����y�[�W�\���T���v��)

## �t�@�C���\��
```
.
���� index.html
���� about.html
���� 404.html
���� favicon.svg
���� sitemap.xml
���� robots.txt
���� .nojekyll
���� assets
��  ���� style.css
��  ���� main.js
���� LICENSE
���� README.md
```

## �J�X�^�}�C�Y�|�C���g
| ���� | ���� |
|------|------|
| �^�C�g��/���� | index.html / about.html �� <title>, meta description |
| OGP�摜 | og:image �� URL �����t�@�C���ɕύX (1200x630 ����) |
| �_�[�N���[�h�����l | main.js �̕ۑ����W�b�N�Œ����\ |
| �J���[�e�[�} | assets/style.css �̃O���f�[�V���� & �F��` |
| �y�[�W�ǉ� | �V���� .html ���쐬���i�r�Q�[�V�����փ����N�ǉ� |
| ���C�Z���X | LICENSE ��K�X�ύX |

## �ǉ��A�C�f�A
- GitHub Actions �� HTML Lint / Link Check
- �摜�œK�� (webp, avif)
- PWA (manifest.json + Service Worker)
- �A�N�Z�X��� (Analytics / Plausible / Umami)

## ���C�Z���X
MIT License
