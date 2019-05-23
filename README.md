# git-skills
# mac提交git
   1.先进入到拷贝的目录
   cd /Users/jamesruio/Desktop/LearnGit
   2.然后按顺序分别输入:
   git add .       //文件添加到仓库（.代表提交所有文件）
   git commit -m "First Commit" //把文件提交到仓库
   git push   //上传到github 
   
 # 版本回退
   1.  查询历史对应不同版本的ID ，用于回退使用
   git log --pretty=oneline
   2. 恢复到历史版本
   git reset --hard fae6966548e3ae76cfa7f38a461c438cf75ba965
   3. 把修改推到远程服务器
   git push -f -u origin master 
   4. 重新更新就可以了
   git pull   
