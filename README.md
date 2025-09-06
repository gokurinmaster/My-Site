# My Site (GitHub Pages)

## ���J�܂ł̎菇

1. ���̃��|�W�g���� GitHub �� push ����
   ```bash
   git add .
   git commit -m "Add initial static site"
   git push origin main
   ```
2. GitHub �̃��|�W�g���y�[�W���J��
3. Settings -> Pages �ֈړ�
4. Build and deployment �� Source �� "Deploy from a branch" �ɐݒ�
5. Branch �� `main` / `/ (root)` �ɐݒ肵�� Save
6. ���\�b?������A"Your site is live at ..." �� URL ���\��
7. �\�����ꂽ URL �փA�N�Z�X������m�F

## �J�X�^�}�C�Y
- `index.html` ��ҏW���ăR���e���c��ύX
- `assets/style.css` �Ńf�U�C������
- `assets/main.js` �� JavaScript ��ǉ�

## �f�B���N�g���\��
```
.
���� index.html
���� assets
   ���� style.css
   ���� main.js
```

## �ǉ� Tips
- `favicon.ico` ��u���΃u���E�U�A�C�R����ύX�\
- �J�X�^���h���C��: Settings -> Pages -> Custom domain �Őݒ� (DNS �� A / CNAME �ǉ�)
- 404 �y�[�W: `404.html` ��ǉ�����ƓƎ�404�����p�����
- Jekyll ������: ��������������ꍇ�� `.nojekyll` �t�@�C����ǉ�

## ���C�Z���X
�K�v�ɉ����� `LICENSE` ��ǉ����Ă��������B
