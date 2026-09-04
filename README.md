# openxray
cd to stalker_cop:

    curl -O https://raw.githubusercontent.com/redybicy/openxray/refs/heads/main/stalker_cop -O https://raw.githubusercontent.com/redybicy/openxray/refs/heads/main/stalker_cop.desktop -O https://raw.githubusercontent.com/redybicy/openxray/refs/heads/main/stalker_cop.png
make symlinks:

    mkdir -p ${HOME}/.local/bin && ln -s $(pwd)/stalker_cop ${HOME}/.local/bin/ && \
    mkdir -p ${HOME}/.local/share/applications && ln -s $(pwd)/stalker_cop.desktop ${HOME}/.local/share/applications/ && \
    mkdir -p ${HOME}/.local/share/icons/hicolor/64x64/apps && ln -s $(pwd)/stalker_cop.png ${HOME}/.local/share/icons/hicolor/64x64/apps/
cd to stalker_cs:

    curl -O https://raw.githubusercontent.com/redybicy/openxray/refs/heads/main/stalker_cs -O https://raw.githubusercontent.com/redybicy/openxray/refs/heads/main/stalker_cs.desktop -O https://raw.githubusercontent.com/redybicy/openxray/refs/heads/main/stalker_cs.png
make symlinks:

    mkdir -p ${HOME}/.local/bin && ln -s $(pwd)/stalker_cs ${HOME}/.local/bin/ && \
    mkdir -p ${HOME}/.local/share/applications && ln -s $(pwd)/stalker_cs.desktop ${HOME}/.local/share/applications/ && \
    mkdir -p ${HOME}/.local/share/icons/hicolor/64x64/apps && ln -s $(pwd)/stalker_cs.png ${HOME}/.local/share/icons/hicolor/64x64/apps/
