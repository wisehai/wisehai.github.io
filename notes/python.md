
# 技巧1
在linux中可以建立多个虚拟环境，在不同的虚拟环境中用pip安装不同的依赖

```
# 确保已安装 python3-venv 
sudo apt install python3-full python3-venv 
# 创建虚拟环境 
python3 -m venv ~/python_env 
# 激活虚拟环境 
source ~/python_env/bin/activate
```