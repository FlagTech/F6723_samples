# 旗標科技《Google Gemini API 開發手冊--GenAI SDK×Live API×Agent Skills》範例程式

## 各章範例程式

- [ch01 Colab 筆記本](https://colab.research.google.com/drive/1P42g033aDklIsFEhnwyFJ4qC-q6gJoxb?usp=sharing)
- [ch02 Colab 筆記本](https://colab.research.google.com/drive/1bPP0hHMnlmiOx2I5Fy9rE2eMUwHt6LAO?usp=sharing)
- [ch03 Colab 筆記本](https://colab.research.google.com/drive/1OsN0MOlqIGuUtjUkVkC7g1Uv_57B7NJn?usp=sharing)
- [ch04 GitHub Repo](https://github.com/FlagTech/F6723_mcp)
    - Windows 平台的環境建置： 
        - 安裝 `scoop` 的指令：
          ```
          Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
          Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
          ```
        - 安裝 `uv` 的指令：
          ```
          scoop install uv
          ```
        - 安裝 `nvm` 的指令：
          ```
          scoop install nvm
          nvm install node
          nvm use node
    - mscOS/Linux 平台的環境建置：          ```
        - 安裝 `Homenrew` 的指令：
          ```
          /bin/bash -c "$(curl -fsSL https://is.gd/kzrOjz)"
          ```
          安裝後的手動步驟：
          ```
          echo >> /Users/codemee/.zprofile
          echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> $HOME/.zprofile
          eval "$(/opt/homebrew/bin/brew shellenv zsh)"
          ```
       - 安裝 `uv`：
         ```
         brew install uv
         ```
      - 安裝 `nvm`：
        ```
        brew install nvm
        ```
        安裝後的手動步驟，首先建立專屬資料夾：
        ```
        mkdir ~/.nvm
        ```
        增加以下內容至 shell 啟始腳本檔：
        ```
        export NVM_DIR="$HOME/.nvm"
        [ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh" # This loads nvm
        [ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" # This loads nvm bash_completion
        ```
      - 安裝 nodejs：
        ```
        nvm install node
        ```
- [ch05 Colab 筆記本](https://colab.research.google.com/drive/1wJRrL5DAVusrpuNFd2bYPS599jlIWzD4?usp=sharing)
- 適用於 [Google GenAI SDK 2.x 版](https://github.com/googleapis/python-genai/releases/tag/v2.0.0) 後的 [Colab 筆記本](https://colab.research.google.com/drive/1sLkIgcCVWAX8l324Nref1aCDjSbobUnA?usp=sharing)
- [ch05 GitHub Repo](https://github.com/FlagTech/F6723_Interactions_API)
- [ch06 GitHub Repo](https://github.com/FlagTech/F6723_Live_API)
- [ch07 GitHub Repo](https://github.com/FlagTech/F6723_ucc)
