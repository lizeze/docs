# Rails
  ##  环境配置
   ### 加速器

   ```
    gem sources --add https://gems.ruby-china.com/ --remove https://rubygems.org/

    bundle config mirror.https://rubygems.org https://gems.ruby-china.com
   ```
   ### 安装依赖

   ```
   gem sources --add https://gems.ruby-china.com/ --remove https://rubygems.org/
   bundle config mirror.https://rubygems.org https://gems.ruby-china.com
   ```
   ### 创建项目

   ```
  rails new --api --database=postgresql --skip-test mangosteen-1
   
   ```