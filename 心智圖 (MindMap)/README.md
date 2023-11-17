# [Mind Map](https://mermaid.js.org/syntax/mindmap.html)

- [語法](https://mermaid.js.org/syntax/mindmap.html#syntax)
  > 透過縮排來表示相依性，但需要注意這個縮排只和前一個比較，因此即便使用雜亂的縮排數量，也會達成繪圖目標。

  - 語法範例
    ```text
      mindmap
        Root
          A
            B
            C
    ```

  - 呈現範例
    ```mermaid
      mindmap
        Root
          A
            B
            C
    ```

- [形狀](https://mermaid.js.org/syntax/mindmap.html#different-shapes)

  - 語法範例
    ```text
      mindmap
        root
          square[方形]
          rounded(圓角方形)
          circle((圓形))
          bang))爆炸((
          cloud)雲朵(
          hexagon{{六角形}}
          預設
    ```

  - 呈現範例
    ```mermaid
      mindmap
        root
          square[方形]
          rounded(圓角方形)
          circle((圓形))
          bang))爆炸((
          cloud)雲朵(
          hexagon{{六角形}}
          預設
    ```

- [圖示](https://mermaid.js.org/syntax/mindmap.html#icons)
  > 可以透過 class 設定 [fontawesome](https://fontawesome.com/v5/search?o=r&m=free) 的樣式。

  - 語法範例
    ```text
      mindmap
        Root
          A
          ::icon(fas fa-yin-yang)
          B(B)
          ::icon(fas fa-wind)
    ```

  - 呈現範例
    ```mermaid
      mindmap
        Root
          A
          ::icon(fas fa-yin-yang)
          B(B)
          ::icon(fas fa-wind)
    ```

- [Markdown](https://mermaid.js.org/syntax/mindmap.html#markdown-strings)

  - 語法範例
    ```text
      mindmap
        root
          A["`**加粗** *斜體* _斜體_ __加粗__`"]
          B[一般內容]
    ```

  - 呈現範例
    ```mermaid
      mindmap
        root
          A["`**加粗** *斜體* _斜體_ __加粗__`"]
          B[一般內容]
    ```
