# takuma-ru's commands

## 新しいコマンドの追加方法
1. ファイルを作成する
2. 権限を付与する
    ```bash
    sudo chmod 755 ~/my-commands/ファイル名
    ```

3. 処理を書く
    ```
    #!/bin/sh
    echo "やっほー！"
    ```

    ※ 引数の受け取り方<br>
    `$1`, `$2`を書く
    ```
    #!/bin/sh
    echo $1
    ```
4. 完成！


## Templates

### 権限付与
```bash
sudo chmod 755 ~/my-commands/
```

### ファイルの中身
```bash
#!/bin/sh
```

### zshリロード
```bash
source ~/.zshrc
```