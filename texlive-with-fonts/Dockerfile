FROM listx/texlive:2016

MAINTAINER Linus Arver <linus@ucla.edu>

# Add all known font packages on official Arch Linux repos (not AUR). This is
# more or less a hand-tuned list.
RUN \
	pacman -S --noconfirm\
		adobe-source-code-pro-fonts\
		adobe-source-han-sans-cn-fonts\
		adobe-source-han-sans-jp-fonts\
		adobe-source-han-sans-kr-fonts\
		adobe-source-han-sans-otc-fonts\
		adobe-source-han-sans-tw-fonts\
		adobe-source-sans-pro-fonts\
		adobe-source-serif-pro-fonts\
		artwiz-fonts\
		bdf-unifont\
		cantarell-fonts\
		dina-font\
		font-bh-ttf\
		font-bitstream-speedo\
		font-mathematica\
		gnu-free-fonts\
		gsfonts\
		noto-fonts\
		noto-fonts-cjk\
		noto-fonts-emoji\
		opendesktop-fonts\
		otf-fira-mono\
		otf-fira-sans\
		otf-ipafont\
		powerline-fonts\
		profont\
		tamsyn-font\
		terminus-font\
		tex-gyre-fonts\
		ttf-anonymous-pro\
		ttf-arphic-ukai\
		ttf-arphic-uming\
		ttf-baekmuk\
		ttf-bitstream-vera\
		ttf-cheapskate\
		ttf-croscore\
		ttf-dejavu\
		ttf-droid\
		ttf-fira-mono\
		ttf-fira-sans\
		ttf-freebanglafont\
		ttf-freefont\
		ttf-gentium\
		ttf-hack\
		ttf-hanazono\
		ttf-hannom\
		ttf-inconsolata\
		ttf-indic-otf\
		ttf-ionicons\
		ttf-junicode\
		ttf-khmer\
		ttf-liberation\
		ttf-linux-libertine\
		ttf-linux-libertine-g\
		ttf-mph-2b-damase\
		ttf-overpass\
		ttf-sazanami\
		ttf-symbola\
		ttf-tibetan-machine\
		ttf-tlwg\
		ttf-ubraille\
		ttf-ubuntu-font-family\
		wqy-bitmapfont\
		wqy-microhei\
		wqy-microhei-lite\
		wqy-zenhei\
		xorg-fonts-100dpi\
		xorg-fonts-75dpi\
		xorg-fonts-alias\
		xorg-fonts-cyrillic\
		xorg-fonts-encodings\
		xorg-fonts-misc\
		xorg-fonts-type1\
		minted\
		biber\
	&& yes | pacman -Scc
