## 在ZSH中设置vim key

 
  在zsh版本的bash中，默认的输入快捷键都是emacs的，通过如下设置，在zsh中也能愉快的使用vim了。
  ```shell
    #打开~/.zshrc
    vim ~/.zshrc
    #找到plugins位置
     vi-mode
    #新建 ~/.editrc文件
    touch ~/.editrc
    #增加一行
       bind -v
   ```
  重启终端，
  ![Screen Shot 2021-12-15 at 18 31 52](https://user-images.githubusercontent.com/25540464/146170393-38bd14e6-2e68-439f-a43a-18c5002eb883.png)
