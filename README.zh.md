<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/images/logo-dark.svg">
    <img src="docs/images/logo.svg" alt="DeepSeek Bot" width="260">
  </picture>
</p>

# DeepSeek Bot

[English](README.md) | 涓枃

![鐗堟湰](https://img.shields.io/badge/鐗堟湰-v0.1_棰勮-blue) ![DSH](https://img.shields.io/badge/DSH-0.2.1--alpha.1-4D6BFE) ![璁稿彲](https://img.shields.io/badge/璁稿彲-Apache_2.0-green)

DeepSeek Bot锛堢畝绉?DS Bot锛夋槸涓€涓熀浜?[DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)锛堢畝绉?dsh锛夌殑 bot 鎻掍欢锛屾彃浠跺皢 dsh 鏀归€犱负 bot 褰㈠紡銆備綘鍙互涓庤嚜宸卞垱寤虹殑 bot 浜ゆ祦銆佸伐浣溿€?

![鍜?Chief 璇翠竴鍙ヨ瘽锛屽畠灏辨妸 bot 鍜岀兢鑱婂缓濂絔(docs/images/team.zh.png)

## 瀹夎

鍏堣濂?dsh锛屽苟鍦?dsh 閲岄厤濂借嚦灏戜竴涓ā鍨嬨€俤s bot 鐩存帴浣跨敤 dsh 閲岀殑妯″瀷銆?

**dsh Desktop锛圵indows銆乵acOS锛?*

1. 渚ф爮鐐?**鎻掍欢** 鈫?**娣诲姞鎻掍欢**銆?
2. **鍖呭悕鎴栧湴鍧€** 濉?`ds-bot`銆傚湪涓浗澶ч檰锛?*瀹夎婧?* 閫?**涓浗澶ч檰闀滃儚婧?*銆?
3. 鐐?**瀹夎**锛屽啀鐐?**绔嬪嵆鍚敤**銆傚鏋滄彁绀衡€滀笅娆″惎鍔ㄧ敓鏁堚€濓紝瀹屽叏閫€鍑?dsh 鍐嶆墦寮€銆?

杩炰笉涓?npm 鏃讹紝绗?2 姝ヤ篃鍙互濉?[Releases](https://github.com/Fei2411/DeepSeek-Bot/releases) 閲屼笅杞界殑 `ds-bot-0.1.2.tgz` 鐨勫畬鏁磋矾寰勶紝鎴栬€?`github:Fei2411/DeepSeek-Bot#v0.1.2&path:/ds-bot`锛堥渶瑕佽 Git锛夈€?

**dsh Web锛圵indows銆乵acOS銆丩inux锛?*

闇€瑕?Node.js `22.19` 浠ヤ笂鍜?pnpm銆?

```sh
npx @deepseek-ai/dsh@0.2.1-alpha.1 plugin --profile web add ds-bot
npx @deepseek-ai/dsh@0.2.1-alpha.1 web
```

## 閰嶇疆

鎴戝己鐑堝缓璁綘鐩存帴閫氳繃鍜?bot 瀵硅瘽鏉ラ厤缃叾浠?bot 鍜岀兢鑱娿€?

## 鍔熻兘

### Bot

浣犲彲浠ュ湪涓€涓獥鍙ｄ腑鍜屼竴涓?bot 瀹屾垚鎵€鏈夊璇濆拰宸ヤ綔锛屼綘鏃犻渶鎷呭績鑳屽悗鐨勪笂涓嬫枃闂銆備綘鍙互鍦?bot 璇︽儏椤垫煡鐪?bot 淇℃伅锛屼篃鍙互涓?bot 閫夋嫨浣犳兂浣跨敤鐨勬ā鍨嬨€備綘鍙互闅忔椂鍒囨崲妯″瀷锛屼絾鎴戜粛鐒跺缓璁綘涓轰竴涓?bot 闀挎湡淇濇寔涓€涓ā鍨嬶紝浠呭湪鐪熸蹇呰鐨勬椂鍒诲垏鎹€?

鍙﹀锛宐ot 鎷ユ湁璁板繂锛屽畠浼氳浣忎綘鐨勫枩濂藉苟鍦ㄤ笅娆＄殑宸ヤ綔涓簲鐢ㄣ€備綘鍙互鍦?bot 鐨勮鎯呴〉绠＄悊璁板繂锛屼篃鍙互鐩存帴鍜?bot 瀵硅瘽鏉ヨ繘琛岀鐞嗐€?

![bot 璇︽儏椤碉細妯″瀷銆佽蹇嗐€佺敤閲廬(docs/images/details.zh.png)

### Main bot

杩欎釜 bot 浣滀负浣犵殑 chief锛屽畠鎷ユ湁闈炲父楂樼殑鏉冮檺锛屽彲浠ョ鐞嗗叾浠?bot 鍜岀兢鑱娿€傜涓€娆¤繘鍏?ds bot 鏃讹紝榛樿浼氭湁涓€涓?main bot 鍙?Chief銆備綘鍙互鐩存帴鍜屽畠瀵硅瘽锛岃瀹冨紩瀵间綘瀹屾垚閰嶇疆銆?

鎬讳箣锛屾湁闂锛屾壘 main bot銆?

### 缇よ亰

ds bot 鎷ユ湁缇よ亰鍔熻兘銆傜兢鑱婃槸闈炲父濂界殑澶?bot 鍗忎綔鏂瑰紡锛屼絾瀹冧細甯︽潵闈炲父鏄庢樉鐨勮垂鐢ㄩ棶棰樸€俤s bot 涓烘鐗规剰鍋氫簡浼樺寲锛氬湪涓€涓兢鑱婁腑锛屼綘闇€瑕佽缃竴涓鐞嗗憳銆備綘鐨勬秷鎭粯璁ょ敱绠＄悊鍛樺洖澶嶏紝瀹冧細甯綘璋冪敤鍏朵粬 bot銆備綘涔熷彲浠ョ洿鎺?@ 浣犻渶瑕佹矡閫氱殑 bot锛屽畠浼氱洿鎺ュ洖搴斾綘锛氳緭鍏?@锛屼粠鍒楄〃閲岄€?bot 灏辫銆傛兂璁?bot 鍙傝€冨彟涓€娈靛璇濓紝鐐硅緭鍏ユ鐨?+ 鈫?寮曠敤瀵硅瘽銆?

![缇よ亰锛氱鐞嗗憳 Chief 鎶婃椿娲剧粰鍐欐墜鍜岀▼搴忓憳](docs/images/group.zh.png)

### 鐢ㄩ噺

鍦?璁剧疆 鈫?鐢ㄩ噺 閲岋紝鍙互鎸夋椂闂淬€佹寜 bot銆佹寜妯″瀷鏌ョ湅 Token 鐢ㄩ噺銆?

![鐢ㄩ噺椤礭(docs/images/usage.zh.png)

## 鏁版嵁

鎵€鏈夋暟鎹兘鍦ㄤ綘鑷繁鐨勭數鑴戜笂锛屽湪 dsh 涓荤洰褰曪紙榛樿 `~/.dsh`锛夌殑 `bot/` 鍜?`sessions/` 閲屻€傚嵏杞芥彃浠朵笉浼氬垹闄よ繖浜涙暟鎹€?

## 寮€鍙?

鎻掍欢婧愮爜鍦?[`ds-bot/`](ds-bot/)銆傞厤缃」鍜屽唴閮ㄧ粨鏋勮 [`ds-bot/README.md`](ds-bot/README.md)锛屽紑鍙戝拰娴嬭瘯瑙?[CONTRIBUTING.md](CONTRIBUTING.md)锛岀増鏈彉鍖栬 [CHANGELOG.md](CHANGELOG.md)銆?

## 鑷磋阿

- [DeepSeek Harness](https://github.com/deepseek-ai/deepseek-harness)锛歞s bot 寤哄湪 dsh 鐨勬彃浠剁郴缁熶笂銆傛瘡涓?bot 閮芥槸涓€涓?dsh 浼氳瘽锛岀敤鐨勬槸 dsh 鐨勫伐鍏峰拰妯″瀷銆?
- [esbuild](https://esbuild.github.io/)锛氱敤鏉ユ墦鍖呮彃浠剁殑鐣岄潰浠ｇ爜銆?
- 鎰熻阿涓嬮潰杩欎簺椤圭洰鍏紑鐨勮璁℃€濊矾銆俤s bot 鍙傝€冧簡瀹冧滑鐨勬€濊矾锛屾病鏈変娇鐢ㄥ畠浠殑浠ｇ爜锛?
  - [AgentMemoryRepo](https://github.com/AgentMemoryRepo/agentmemoryrepo)锛歜ot 璁板繂鐨?Markdown 鏍煎紡銆?
  - [OpenAI Codex](https://github.com/openai/codex)锛氬帇缂╂椂鎶婄敤鎴峰師璇濈暀鍦ㄦ憳瑕佹梺杈癸紝浠ュ強鎼滅储鑱婂ぉ璁板綍鐢ㄧ殑娑堟伅閿氱偣銆?
  - [OpenMausBot](https://github.com/milind-soni/OpenMausBot)锛氱兢鑱婅疆娴佸彂瑷€鍜?@ 鎺ュ姏銆?
  - [Hermes Agent](https://github.com/NousResearch/hermes-agent) 鍜?[Hermes Bot Mode](https://github.com/NousResearch/Hermes-Bot-Mode)锛氭瘡涓垚鍛樺湪姣忎釜缇ら噷涓€涓細璇濓紝浠ュ強浜ゆ帴鏃跺甫涓婄敤鎴蜂箣鍓嶇殑鍘熻瘽銆?
  - [OpenCode](https://github.com/sst/opencode)銆乕goose](https://github.com/block/goose)銆乕pi](https://github.com/badlogic/pi-mono)銆乕Gemini CLI](https://github.com/google-gemini/gemini-cli)锛氶暱瀵硅瘽浠€涔堟椂鍊欏帇缂╋紝浜ゆ帴绗旇鍐欏摢浜涘唴瀹广€?
  - [obelisk](https://github.com/tommy0103/obelisk)锛氱敤 SQLite 鍏ㄦ枃绱㈠紩鎼滅储鑱婂ぉ璁板綍銆?
- 姣忎竴浣嶈瘯鐢?ds bot銆佹彁闂銆佹姤 bug 鐨勪汉銆?

## 璁稿彲

[Apache License 2.0](LICENSE)銆傛寜鈥滃師鏍封€濇彁渚涳紝涓嶉檮甯︿换浣曟媴淇濄€傜敤鍒扮殑绗笁鏂逛唬鐮佸拰瀹冪殑璁稿彲瑙?[NOTICE](NOTICE)銆?

## 澹版槑

ds bot 鏄嫭绔嬬殑绀惧尯椤圭洰锛?*涓嶆槸 DeepSeek 瀹樻柟浜у搧**锛屼笌 DeepSeek 娌℃湁闅跺睘銆佽鍙垨璧炲姪鍏崇郴銆傗€淒eepSeek鈥濃€淒eepSeek Harness鈥濈瓑鍚嶇О鏄悇鑷墍鏈夎€呯殑鍟嗘爣锛岃繖閲屽彧鐢ㄦ潵璇存槑鏈彃浠跺拰浠€涔堜竴璧风敤銆?

bot 浼氭秷鑰椾綘鑷繁鐨勬ā鍨嬮搴︼紝涔熶細鎸変綘鐨勮姹傝鍐欐枃浠躲€佽繍琛屽懡浠ゃ€傞噸瑕佺殑鎿嶄綔璇疯嚜宸辨鏌ャ€?

