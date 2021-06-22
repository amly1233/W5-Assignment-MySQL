基本的 SQL 指令

● 使用 INSERT 指令新增一筆資料到 user 資料表中，這筆資料的 username 和
password 欄位必須是 ply。接著繼續新增至少 4 筆隨意的資料。

● 使用 SELECT 指令取得所有在 user 資料表中的使用者資料。

<img width="443" alt="截圖 2021-03-24 下午1 19 44" src="https://user-images.githubusercontent.com/74479902/112259645-9b6b7200-8ca3-11eb-9f25-d9e39f783d50.png">

● 使用 SELECT 指令取得 user 資料表中總共有幾筆資料。

<img width="251" alt="截圖 2021-03-24 下午1 27 49" src="https://user-images.githubusercontent.com/74479902/112260364-bc809280-8ca4-11eb-9de3-74ec5aa7cd29.png">


● 使用 SELECT 指令取得所有在 user 資料表中的使用者資料，並按照 time 欄位，由近
到遠排序。

<img width="432" alt="截圖 2021-03-24 下午1 31 44" src="https://user-images.githubusercontent.com/74479902/112260646-492b5080-8ca5-11eb-8bd7-2e1c51577d71.png">



● 使用 SELECT 指令取得 user 資料表中第 2 ~ 4 共三筆資料，並按照 time 欄位，由近
到遠排序。

<img width="458" alt="截圖 2021-03-24 下午5 46 41" src="https://user-images.githubusercontent.com/74479902/112289046-e6e44700-8cc8-11eb-928f-35bf4ff065b7.png">



● 使用 SELECT 指令取得欄位 username 是 ply 的使用者資料。

<img width="416" alt="截圖 2021-03-24 下午1 45 24" src="https://user-images.githubusercontent.com/74479902/112261610-30bc3580-8ca7-11eb-8531-8a8067f2a2fd.png">


● 使用 SELECT 指令取得欄位 username 是 ply、且欄位 password 也是 ply 的資料。

<img width="426" alt="截圖 2021-03-24 下午1 46 33" src="https://user-images.githubusercontent.com/74479902/112261727-5b0df300-8ca7-11eb-8276-d20347018955.png">



● 使用 UPDATE 指令更新欄位 username 是 ply 的使用者資料，將資料中的 name 欄位
改成【丁滿】。

<img width="444" alt="截圖 2021-03-24 下午1 49 15" src="https://user-images.githubusercontent.com/74479902/112261947-bb9d3000-8ca7-11eb-9b16-858a53ef72c1.png">


● 使用 DELETE 指令刪除所有在 user 資料表中的資料。

<img width="267" alt="截圖 2021-03-24 下午1 51 07" src="https://user-images.githubusercontent.com/74479902/112262070-fdc67180-8ca7-11eb-95cc-2d8df17f5e2b.png">





結合資料表 SQL JOIN 的操作

1. 在資料庫中，建立新資料表，取名字為message。

<img width="565" alt="截圖 2021-03-24 下午3 53 39" src="https://user-images.githubusercontent.com/74479902/112274148-1d19ca80-8cb9-11eb-9042-239bd7f09972.png">



● 使用 SELECT 搭配 JOIN 的語法，取得所有留言，資料中須包含留言會員的姓名。

<img width="423" alt="截圖 2021-03-24 下午4 46 40" src="https://user-images.githubusercontent.com/74479902/112280968-83eeb200-8cc0-11eb-9a66-162d47c539fc.png">



● 使用 SELECT 搭配 JOIN 的語法，取得 user 資料表中欄位 username 是 ply 的所有留
言，資料中須包含留言會員的姓名。

<img width="362" alt="截圖 2021-03-24 下午4 49 55" src="https://user-images.githubusercontent.com/74479902/112281399-f8295580-8cc0-11eb-8127-f4a7c3098a0f.png">


