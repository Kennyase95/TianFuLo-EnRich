<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>添富羅 (ThinKin) 投資組合前瞻報告 - 系統性風險校準版</title>
    <style>
        :root {
            --bg-color: #0b0c10;
            --card-bg: #14161d;
            --accent-gold: #c9a054;
            --text-main: #e6ebf4;
            --text-muted: #8a99ad;
            --profit-red: #ea4335;  /* 台灣標準：紅代表獲利 */
            --loss-green: #34a853;  /* 台灣標準：綠代表虧損 */
            --warning-orange: #ff9800;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Arial, sans-serif; }
        body { background-color: var(--bg-color); color: var(--text-main); padding: 2rem; line-height: 1.6; }
        .container { max-width: 1200px; margin: 0 auto; }
        
        /* Header */
        header { border-bottom: 2px solid var(--accent-gold); padding-bottom: 1.5rem; margin-bottom: 1.5rem; display: flex; justify-content: space-between; align-items: flex-end; }
        h1 { color: var(--accent-gold); font-size: 2.2rem; font-weight: 700; letter-spacing: 1px; }
        .subtitle { color: var(--text-muted); font-size: 0.95rem; margin-top: 0.3rem; }
        .meta-info { text-align: right; color: var(--text-muted); font-size: 0.9rem; }

        /* Black Swan Alert Board */
        .alert-board { background: rgba(234, 67, 53, 0.08); border: 1px solid var(--profit-red); border-radius: 6px; padding: 1rem; margin-bottom: 2rem; display: flex; justify-content: space-between; align-items: center; }
        .alert-title { color: var(--profit-red); font-weight: bold; font-size: 1.1rem; display: flex; align-items: center; gap: 0.5rem; }
        .alert-details { font-size: 0.9rem; color: var(--text-main); }

        /* Grid Layout */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(320px, 1fr)); gap: 1.5rem; margin-bottom: 2.5rem; }
        .card { background-color: var(--card-bg); border-radius: 8px; padding: 1.5rem; border: 1px solid #222531; transition: transform 0.2s; }
        .card:hover { transform: translateY(-3px); border-color: var(--accent-gold); }
        .card-title { color: var(--accent-gold); font-size: 1.25rem; font-weight: 600; margin-bottom: 1rem; border-left: 3px solid var(--accent-gold); padding-left: 0.5rem; }
        
        /* Table Style */
        table { width: 100%; border-collapse: collapse; margin-top: 0.5rem; font-size: 0.95rem; }
        th, td { padding: 0.75rem; text-align: left; border-bottom: 1px solid #222531; }
        th { color: var(--text-muted); font-weight: 500; }
        .highlight-red { color: var(--profit-red); font-weight: bold; }
        .highlight-green { color: var(--loss-green); font-weight: bold; }
        
        /* Badge */
        .badge { background: #222531; color: var(--accent-gold); padding: 0.2rem 0.6rem; border-radius: 4px; font-size: 0.8rem; font-weight: bold; display: inline-block; }
        .badge-alert { background: rgba(234, 67, 53, 0.15); color: var(--profit-red); }
        .badge-warning { background: rgba(255, 152, 0, 0.15); color: var(--warning-orange); }

        /* Footer Callout */
        .callout { background: rgba(201, 160, 84, 0.04); border: 1px dashed var(--accent-gold); border-radius: 8px; padding: 1.5rem; margin-top: 2rem; }
        .callout h3 { color: var(--accent-gold); margin-bottom: 0.5rem; }
        .callout p { color: var(--text-muted); font-size: 0.95rem; margin-bottom: 0.5rem; }
    </style>
</head>
<body>

<div class="container">
    <header>
        <div>
            <h1>添富羅 (ThinKin) 主動式防禦投資組合</h1>
            <p class="subtitle">2026 系統性洗盤風暴與核心資產重估報告</p>
        </div>
        <div class="meta-info">
            <p>主動戰略：70% 定海神針 / 30% 機動突擊</p>
            <p>校準基準日：2026 年 6 月 7 日 (開盤前夕)</p>
        </div>
    </header>

    <div class="alert-board">
        <div class="alert-title">⚠️ 系統性黑天鵝風暴警示</div>
        <div class="alert-details">
            上週五大盤現貨重挫 600 點，<strong>台指期夜盤崩跌 3,006 點 (收 42,220 點)</strong>。美股費半大跌 10.26%，明日開盤將面臨歷史級斷崖式補跌壓力。
        </div>
    </div>

    <div class="grid">
        <div class="card" style="grid-column: span 2;">
            <div class="card-title">美光科技 (Micron, MU) 跨維度風險與轉型校準</div>
            <table>
                <thead>
                    <tr>
                        <th style="width: 25%;">檢視維度</th>
                        <th>核心量化指標與突發市況調整</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td><strong>獲利爆發性</strong></td>
                        <td>HBM4 長期定價權未變。短線受美光失守千元大關、產業年中見頂雜音重擊，遠期本益比 (Forward PE) 遭非理性壓縮。</td>
                    </tr>
                    <tr>
                        <td><strong>經營效益比</strong></td>
                        <td>2026 全年 HBM 產能仍售罄，30% 長約保障率提供基本獲利護墊。去循環化結構在風暴中將展現防禦韌性。</td>
                    </tr>
                    <tr>
                        <td><strong>籌碼風控度</strong></td>
                        <td>短線將面臨 6/12 <strong>SpaceX 歷史級 IPO (1.78兆美元)</strong> 招股引起的資金排擠。美股科技股寬幅震盪加速汰弱留強。</td>
                    </tr>
                </tbody>
            </table>
        </div>

        <div class="card">
            <div class="card-title">美光 (MU) 估值防線校準</div>
            <div style="margin-bottom: 1rem;">
                <p style="font-size: 0.85rem; color: var(--text-muted);">📈 2026 上半年區間</p>
                <p style="font-size: 1.5rem; color: var(--accent-gold); font-weight: bold;">$950 ~ $1,050 美元</p>
            </div>
            <div>
                <p style="font-size: 0.85rem; color: var(--text-muted);">📉 2026 下半年鐵壁支撐</p>
                <p style="font-size: 1.5rem; color: var(--profit-red); font-weight: bold;">$800 美元防線</p>
            </div>
        </div>
    </div>

    <div class="card" style="margin-bottom: 1.5rem;">
        <div class="card-title">台股半導體核心鏈數據重估表 (週五收盤基準)</div>
        <table>
            <thead>
                <tr>
                    <th>股票代號</th>
                    <th>資產名稱</th>
                    <th>6/5 收盤價</th>
                    <th>2026(E) EPS</th>
                    <th>前瞻 PE</th>
                    <th>明日(6/8) 開盤實戰操作對策</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>2330</td>
                    <td><strong>台積電</strong></td>
                    <td class="highlight-green">-- 元</td>
                    <td>51.5 元</td>
                    <td>-- 倍</td>
                    <td><span class="badge">定海神針</span> 先進製程源頭，不急於早盤攤平，靜待現貨爆量止穩。</td>
                </tr>
                <tr>
                    <td>3711</td>
                    <td><strong>日月光投控</strong></td>
                    <td class="highlight-green">577.00 元</td>
                    <td>16.0 元</td>
                    <td>12.3 倍</td>
                    <td><span class="badge badge-alert">595元特戰單持倉</span> 系統性重挫不恐慌。開盤預期跳空跌破560元。</td>
                </tr>
                <tr>
                    <td>2454</td>
                    <td><strong>聯發科</strong></td>
                    <td class="highlight-green">-- 元</td>
                    <td>85.0 元</td>
                    <td>-- 倍</td>
                    <td><span class="badge">定海神針</span> 邊緣 AI 護城河，開高走低長黑後，待其測試季線支撐。</td>
                </tr>
                <tr>
                    <td>3231</td>
                    <td><strong>緯創</strong></td>
                    <td class="highlight-green">174.00 元</td>
                    <td>13.95 元</td>
                    <td>12.4 倍</td>
                    <td><span class="badge badge-warning">超導代工</span> 大摩喊買鎖漲停。明日嚴禁盲目追高，防系統性多殺多。</td>
                </tr>
                <tr>
                    <td>6515</td>
                    <td><strong>穎崴</strong></td>
                    <td>-- 元</td>
                    <td>48.0 元</td>
                    <td>-- 倍</td>
                    <td><span class="badge">超導設備</span> 高 Beta 高彈性，盤中禁止左側摸底，看戲不接刀。</td>
                </tr>
                <tr>
                    <td>7769</td>
                    <td><strong>鴻勁</strong></td>
                    <td>-- 元</td>
                    <td>36.5 元</td>
                    <td>-- 倍</td>
                    <td><span class="badge">超導設備</span> 營收動能雖強，但在恐慌盤中需等待量縮不破低。</td>
                </tr>
            </tbody>
        </table>
    </div>

    <div class="callout">
        <h3>🧭 添富羅明日(6/8) 現股當沖與存股雙軌實戰鐵律</h3>
        <p>1. <strong>現股當沖 (多沖戰術)</strong>：開盤全市場融資斷頭湧出。若日月光急殺砸向 <strong>520~530 元</strong> (逼近月線/接近跌停)，當沖空手者可現股先買，午盤彈回 545~550 元即刻後賣獲利了結，<strong>嚴禁早盤追空</strong>。</p>
        <p>2. <strong>存股加碼防線</strong>：若您原本手握 595 元持倉，明天即便成本跌破也切勿殺低。空手者或欲加碼者，最佳「左側低吸埋伏區」修正至 <strong>550 ~ 560 元 (5日線附近)</strong>，利用 30% 閒置資金分批零股推進。</p>
        <p>3. <strong>時效風控紀律</strong>：當沖交易與長線存股帳戶必須嚴格分流。明日當沖多單務必於 <strong>11:30 以前</strong> 結束戰局，不將當沖單因套牢被動轉為波段存股。</p>
        <p style="margin-top: 0.7rem; font-style: italic; color: var(--accent-gold);">「小滿美學：非理性震盪帶來的估值留白，正是為我們下一次財富重新『灌漿』的甜美起點。」</p>
    </div>
</div>

</body>
</html>
