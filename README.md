# 本项目暂不维护！！！！！！

<p align=center>
  <br>
  <a><img src="https://user-images.githubusercontent.com/75151244/222952534-d8d57fac-d30c-40e7-aae3-900d9660adc8.png"/></a>
  <br>
  Desktop cute catgirl with ChatGPT.
  <br>
  智能桌面猫娘接入ChatGPT,它可以协助你工作或扮演猫娘等。
  <br>
</p>

<p align="center">
<a href="#demo">Demo</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;<a href="#installation">Installation</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;<a href="#usage">Usage</a>
</p>


## Demo
目前有11个角色可以切换

  <a><img src="https://user-images.githubusercontent.com/75151244/222953906-b074da15-130c-4aa3-b7c5-59b7517fba74.png"/></a><a><img src="https://user-images.githubusercontent.com/75151244/222954621-13d21699-5ef2-424f-bd7f-4a5a96aeb47e.png"/></a>

## Installation

```console
# clone the repo
$ git clone https://github.com/Jeremy-ttt/Desktop-AI-CatGirl.git

# change the working directory to sherlock
$ cd Desktop-AI-CatGirl

# install the requirements
$ python3 -m pip install -r requirements.txt
```

## Usage
### Config
1.配置`config.json`中的**api_key**(你的Openai账号的api_key)和**base_prompt**(初始提示词)
2.需要梯子
### Run
```console
$ python3 DesktopPet.py
```
程序仅在托盘显示，托盘菜单可切换角色，更改透明度，关闭程序。

## 对话command
```
!help - Display this message
!rollback n - Rollback the conversation by n messages
!reset - Reset the conversation
!exit - Quit chat
```
