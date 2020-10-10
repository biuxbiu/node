# Node

Git 的经常性操作命令记录

<br>
<br>


#### 安装一个nvm

有时候我们会需要用到多个 `npm` 版本，这个时候我们就需要通过使用 `nvm` 在多个 `npm` 版本中切换。

<br>

**通过curl的方式安装**


```javascript
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.1/install.sh | bash
```

<br>


**通过Wget的方式安装**

```javascript
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.33.1/install.sh | bash
```

<br>

安装好之后可以通过下方命令来检验是否安装好

```javascript
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && . "$NVM_DIR/nvm.sh" # This loads nvm


command -v nvm      //nvm
```


<br>

**查看目前有哪些版本可以使用**


```javascript
nvm ls-remote
```


<br>


**安装相对应的版本**

```javascript
nvm install v10.22.1
```


<br>

**切换到该版本**

```javascript
npm use v10.22.0
```
