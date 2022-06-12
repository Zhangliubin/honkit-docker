FROM honkit/honkit:latest

MAINTAINER suranyi suranyi.sysu@gmail.com

LABEL create_time=2022.6.15

RUN npm install gitbook-plugin-favicon-absolute \
                gitbook-plugin-edit-link \
                gitbook-plugin-search-plus \
                gitbook-plugin-expandable-chapters-small \
                gitbook-plugin-back-to-top-button \
                gitbook-plugin-page-toc-button \
                gitbook-plugin-katex \
                gitbook-plugin-hide-element \
                gitbook-plugin-prism gitbook-plugin-prism-themes \
                gitbook-plugin-github-buttons \
                gitbook-plugin-insert-logo-link-website \
                gitbook-plugin-code \
                gitbook-plugin-todo \
                gitbook-plugin-flexible-alerts \
                gitbook-plugin-theme-comscore \
                gitbook-plugin-language-picker \
                gitbook-plugin-pagefooter-freedom \
                gitbook-plugin-get-pdf \
                gitbook-plugin-password-pro

COPY fonts/SIMSUN.TTC /usr/share/fonts

ENTRYPOINT ["honkit"]