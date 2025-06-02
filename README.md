```
docker compose donw -v
docker compose up -d --pull always 
```

```
-v 清除舊版本與資料。

-d 以背景模式執行，不會卡住終端機。

--pull <policy> 
  missing: 預設值，只有在本地沒有 image 時才會去拉遠端的 image。
  never: 永遠 不拉取 image（即使本地沒有，也不會嘗試下載）。
  always: 每次執行都強制重新拉取 image，確保是 registry 上的最新版。
```