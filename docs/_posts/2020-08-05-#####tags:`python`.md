###### tags: `python`
# *_ 代表 可以在python被忽略的參數,屬於python idiom
例如實務上遇到要把string用=分隔成兩個參數，但卻有可能遇到分割的數目不同，這時候就可以使用 *_ 變數 ＋[None] 來處理這類問題，避免遇到Error
 key ,value, *_=string.split("=")+ [None]