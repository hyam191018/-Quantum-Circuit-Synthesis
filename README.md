# Quantum Circuit Synthesis 量子電路合成


## 動機

基於量子電路的電腦是未來的趨勢，相比於傳統1和0的位元，量子電腦所採用的quantum bit憑藉著"旋轉"這種操作，進行input與output的轉換。然而，量子電路的設計目前還沒有一個最佳的演算法的找出最小數量的quantum gate，故本程式希望藉由暴力法強行生成出一個較少gates的量子電路。

本程式實現了一個真值表到量子電路的轉換，雖然可能不是最佳解，但至少能產生出一個滿足輸出輸入的量子電路。

## 實驗結果

| - | Toffoli gate | Peres gate | Fredkin gate | OR gate | Toffoli with one negative control line gate |
|:--:|:--:|:--:|:--:|:--:|:--:|
| Target  | 15  | 14 | 17 | 17 | 15 |
| Result  | 11 | 16 | 33 | 13 | 12 |

