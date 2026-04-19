/* --- 基礎設定與變數 --- */
:root {
  --bg-color: #0d1117; /* 深色背景，類 GitHub */
  --card-bg: #161b22;
  --accent-color: #2ea043; /* 專業感的綠色 */
  --text-primary: #e6edf3;
  --text-secondary: #8b949e;
  --border-color: #30363d;
  --font-main: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
}

body {
  background-color: var(--bg-color);
  color: var(--text-primary);
  font-family: var(--font-main);
  line-height: 1.6;
  margin: 0;
  padding: 0;
}

/* --- 頂級導航列 (體現細節) --- */
header {
  border-bottom: 1px solid var(--border-color);
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  background: rgba(13, 17, 23, 0.8);
  backdrop-filter: blur(10px);
  z-index: 100;
}

/* --- 專案卡片 (核心部分：主管最看重) --- */
.project-card {
  background-color: var(--card-bg);
  border: 1px solid var(--border-color);
  border-radius: 8px;
  padding: 24px;
  margin-bottom: 2rem;
  transition: transform 0.2s ease, border-color 0.2s ease;
  position: relative;
  overflow: hidden;
}

/* 專業感：滑過時顯示邊框亮點，而非誇張的縮放 */
.project-card:hover {
  border-color: var(--accent-color);
  transform: translateY(-4px);
}

.project-title {
  font-size: 1.5rem;
  font-weight: 700;
  color: var(--text-primary);
  margin-bottom: 8px;
}

/* --- 技術標籤 (體現專業度) --- */
.tech-stack {
  display: flex;
  gap: 8px;
  margin-top: 12px;
}

.tag {
  background: rgba(46, 160, 67, 0.1);
  color: var(--accent-color);
  border: 1px solid rgba(46, 160, 67, 0.2);
  padding: 2px 10px;
  border-radius: 12px;
  font-size: 0.75rem;
  font-weight: 600;
}

/* --- 呼應你的需求：綠色圓圈狀態指示器 --- */
.status-indicator {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 0.85rem;
  color: var(--text-secondary);
}

.status-circle {
  width: 10px;
  height: 10px;
  background-color: var(--accent-color); /* 綠色填充 */
  border-radius: 50%;
  display: inline-block;
  box-shadow: 0 0 8px var(--accent-color);
}

/* --- 行動召喚按鈕 (GitHub 連結) --- */
.btn-primary {
  background-color: #21262d;
  color: #c9d1d9;
  border: 1px solid var(--border-color);
  padding: 8px 16px;
  border-radius: 6px;
  cursor: pointer;
  text-decoration: none;
  font-size: 0.9rem;
  display: inline-flex;
  align-items: center;
  gap: 6px;
}

.btn-primary:hover {
  background-color: #30363d;
  border-color: #8b949e;
}

/* --- 區塊標題 --- */
.section-label {
  color: var(--accent-color);
  font-family: monospace;
  font-size: 0.9rem;
  margin-bottom: 0.5rem;
  display: block;
}
