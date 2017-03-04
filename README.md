# XC-Makefile
## 概要
XCコンパイラ用のMakefileです.  
生成されたhexファイルはMPLAB IPE等でPICに書き込めます.  
XC8では動作確認済みですが 他は動くか分かりません.
## 主な変数
### XC
xcコンパイラへのパス.  
#### 例
    XC = "/opt/microchip/xc8/v1.37/bin/xc8"

### TARGET_DEVICE
書き込む対象となるデバイス.
#### 例
    TARGET_DEVICE = 16F1938

### SRC_DIR
ソースファイルが置かれているディレクトリ.
### INCLUDE_DIR
ヘッダファイルが置かれているディレクトリ.
### OBJ_DIR
オブジェクトファイルが生成されるディレクトリ.
### TARGET_DIR
最終的にhexファイル等が生成されるディレクトリ.
