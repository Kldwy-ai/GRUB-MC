
# MC-Grub
一个Minecraft样式的Grub主题

---

# 安装方法(中文)

### 如果你是Linux（仅限基于Debian的发行版（如Ubuntu、深度或Debian本体））

> ***第一步***：下载 `mc_grub.7z`，然后直接解压到你认为不错的目录。**注意**：请直接解压文件夹，不要改名，你可以修改内部内容但不要修改文件名
> ***第二步***：执行命令 `sudo mkdir -p /boot/grub/themes/`来创建文件夹，如果已有就不必执行，如果有了还执行也没事
> ***第三步***：继续执行命令`sudo cp -r 你的解压位置 /boot/grub/themes/`
> ***第四步|关键***：修改主题文件
> > 执行`sudo nano /etc/default/grub`(当然，此处用gedit更好)，在里面修改
> > 找到开头为`GRUB_THEME`的行，如果开头有#就删掉，在=后面输入`/boot/grub/themes/mc_grub`，如果没有输错，完整的是这样的：`GRUB_THEME=/boot/grub/themes/mc_grub`
>
> ***第五步***：接下来输入`sudo update-grub`就行了
---
### 如果你是Ventoy优盘
>***第一步***：下载`ventoy.7z`，把解压出来的文件夹直接替换`VTOYEFI/grub/themes`的ventoy文件夹即可，就是这么简单

---
# How i install (English)

### If you are using Linux (Debian-based only, e.g., Ubuntu, Deepin, or Debian itself)

> ***Step 1***: Download `mc_grub.7z`, then extract it directly to any directory you like.  
> **Note**: Please extract the folder as-is, do NOT rename it. You may modify the internal contents, but do not change the folder name.
>
> ***Step 2***: Run the command `sudo mkdir -p /boot/grub/themes/` to create the themes directory. If it already exists, you can skip this; running it again won't cause any issues.
>
> ***Step 3***: Continue by running `sudo cp -r /path/to/your/extracted/folder /boot/grub/themes/`
>
> ***Step 4 | Critical***: Modify the theme configuration file.
> > Run `sudo nano /etc/default/grub` (you can use `gedit` instead if you prefer).  
> > Locate the line starting with `GRUB_THEME`. If there is a `#` at the beginning, remove it.  
> > After the `=` sign, enter `/boot/grub/themes/mc_grub`.  
> > If typed correctly, the full line should look like this:  
> > `GRUB_THEME=/boot/grub/themes/mc_grub`
>
> ***Step 5***: Finally, run `sudo update-grub` to apply the changes.

---

### If you are using a Ventoy USB drive

> ***Step 1***: Download `ventoy.7z`. Extract the folder inside, and directly replace the existing `ventoy` folder located at `VTOYEFI/grub/themes/` with the extracted one. That's it — simple and done!


---
# **中英对照：CNS-ENG comparison**
for mc_grub/theme.txt



| CNS | ENG |
|------|------|
| 快捷键: e=编辑  c=命令行 | Shortcuts: e = edit, c = command line |
| 按 F1 查看帮助 | Press F1 for help |
| 按 F2 切换主题 |Press F2 to switch themes |
| 按 F3 重启系统 | Press F3 to reboot system |
| 按 F4 关机 | Press F4 to shut down |
| UEFI 模式 | UEFI Mode |
|GRUB 2.06 | ??? |

---

made by 开朗的网友爱玩我的世界
