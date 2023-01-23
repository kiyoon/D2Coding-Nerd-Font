# D2Coding-Nerd-Font

D2Coding v1.3.2  
Nerd Font v2.3.1

생성할때 사용한 스크립트

```bash
git clone --depth 1 https://github.com/ryanoasis/nerd-fonts
git clone --depth 1 https://github.com/naver/d2codingfont
sudo apt -y install python3-fontforge
./font-patcher ../d2codingfont/D2CodingAll/D2Coding-Ver1.3.2-20180524-all.ttc --also-windows -c --careful --progressbars --fontawesome --fontawesomeextension --fontlinux --octicons --powersymbols --pomicons --powerline --powerlineextra --material --weather
```

## 하나의 TTC 파일
`D2CodingAll Nerd Font.ttc` 파일에 D2Coding, D2CodingBold, D2CodingLigature, D2CodingLigatureBold 포함됨.

## 설치

리눅스 / 맥  

```bash
mkdir -p ~/.local/share/fonts
wget https://raw.githubusercontent.com/kiyoon/D2Coding-Nerd-Font/master/D2CodingAll%20Nerd%20Font.ttc -P ~/.local/share/fonts
```

## 참고
- https://my.yirum.net/nerd-fonts-%EC%99%80-vim-devicons-%EC%84%A4%EC%B9%98/
