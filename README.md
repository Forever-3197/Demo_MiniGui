# Demo_MiniGui
## 处理github上传相关操作
> echo "# Demo_MiniGui" >> README.md<br/>
git init<br/>
git add README.md<br/>
git commit -m "first commit"<br/>
git remote add origin git@github.com:Forever-3197/Demo_MiniGui.git<br/>
git push -u origin master<br/>

## 处理minigui工程在编译过程中的执行：
> gcc -g helloworld.c -o helloworld `pkg-config minigui mgncs mgeff mgplus mgutils harfbuzz-subset chipmunk mgncs4touch --cflags --libs` -lpthread

> gcc -g helloworld.c -o helloworld -lpthread `pkg-config minigui mgplus mgutils mgncs -cflags --libs` 