<template>
  <div class="min-h-screen app">
    <!-- Header Section -->
    <header class="hero-section">
      <div class="hero-content">
        <div class="business-card">
          <div class="card-avatar">
            <div class="avatar-circle">
              <img src="/src/assets/apple.jpeg" alt="頭像" class="avatar-img" />
            </div>
          </div>
          <div class="card-info">
            <h1 class="card-name">黃愷婷</h1>
            <p class="card-title">前端工程師</p>
            <div class="card-contact">
              <div class="contact-item">
                <el-icon><Location /></el-icon>
                <span>新北市中和區</span>
              </div>
              <div class="contact-item">
                <el-icon><Message /></el-icon>
                <span>t141826@gmail.com</span>
              </div>
              <div class="contact-item">
                <el-icon><Phone /></el-icon>
                <span>0973-383-923</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </header>

    <!-- Main Content -->
    <main class="max-w-6xl mx-auto relative z-10 py-10 px-5 main-content">

      <!-- 自我介紹 -->
      <section class="mb-8 content-section">
        <div class="section-card">
          <div class="card-header">
            <div class="card-icon info-icon">
              <el-icon><InfoFilled /></el-icon>
            </div>
            <h3 class="card-title">自我介紹</h3>
          </div>
          <div class="card-content">
            <p>我是黃愷婷，擁有三年多前端開發經驗，熟練使用 Vue.js 進行專案開發。我個性積極主動，善於團隊協作，並樂於學習新技術以提升專業能力。期望能在未來的工作中發揮所長，為團隊創造價值並持續成長。</p>
          </div>
        </div>
      </section>

      <!-- 工作經驗 -->
      <section class="mb-8 content-section">
        <div class="section-card">
          <div class="card-header">
            <div class="card-icon work-icon">
              <el-icon><Briefcase /></el-icon>
            </div>
            <div>
              <h3 class="card-title">工作經驗</h3>
              <p class="card-subtitle">Professional Experience</p>
            </div>
          </div>
          <div class="card-content">
            <div class="relative timeline">
              <div class="timeline-item">
                <div class="timeline-dot primary"></div>
                <div class="timeline-content">
                  <div class="job-header">
                    <h4 class="text-xl font-semibold text-slate-800 mb-2">前端工程師</h4>
                    <span class="job-company">沐訊科技</span>
                    <span class="job-period">2023/9~2025</span>
                  </div>
                  <ul class="job-duties">
                    <li>擔任自家產品主要前端開發：獨立負責完整前端架構設計與實作（Vue3 + Tailwind + Scss）</li>
                    <li>跨部門協作經驗：與PM、UI/UX設計師深度討論使用者介面操作與體驗優化</li>
                    <li>全端協作開發：與後端工程師協商API規格設計，確保前後端整合效率</li>
                    <li>公部門專案維護與優化：負責既有系統功能擴充與效能提升</li>
                    <li>組件化開發：建立可重用UI組件庫，提升開發效率與程式碼品質</li>
                    <li>前端特效實作：手刻CSS動畫效果與客製化樣式，提升使用者視覺體驗</li>
                    <li>網站效能優化：實施SEO最佳化與GA數據追蹤分析</li>
                    <li>多專案技術棧：協作開發包含jQuery + Bootstrap等不同技術架構專案</li>
                  </ul>
                </div>
              </div>

              <div class="timeline-item">
                <div class="timeline-dot"></div>
                <div class="timeline-content">
                  <div class="job-header">
                    <h4 class="text-xl font-semibold text-slate-800 mb-2">前端工程師</h4>
                    <span class="job-company">愛酷智能科技</span>
                    <span class="job-period">2022/1~2023/8</span>
                  </div>
                  <ul class="job-duties">
                    <li>舊版網站維護：Vue2 + Element UI</li>
                    <li>後期重構專案：Vue3 + Element Plus + Tailwind + TypeScript + i18n</li>
                    <li>串接API及程式碼組件維護與單元測試</li>
                    <li>API 測試與資料庫管理：Postman + MySQL（查資料有無在資料庫及匯出）</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- 技能專長 -->
      <section class="mb-8 content-section">
        <div class="section-card">
          <div class="card-header">
            <div class="card-icon skills-icon">
              <el-icon><Star /></el-icon>
            </div>
            <h3 class="card-title">技能專長</h3>
          </div>
          <div class="card-content">
            <div class="skills-grid">
              <div class="skill-category">
                <div class="skill-category-content">
                  <h4 class="skill-category-title">前端開發 Front End</h4>
                  <div class="skills-list">
                    <span class="skill-tag primary">HTML</span>
                    <span class="skill-tag primary">CSS3</span>
                    <span class="skill-tag primary">JavaScript</span>
                    <span class="skill-tag primary">Vue.js 2/3</span>
                    <span class="skill-tag primary">TypeScript</span>
                    <span class="skill-tag primary">jQuery</span>
                    <span class="skill-tag primary">Vite</span>
                    <span class="skill-tag primary">Bootstrap</span>
                    <span class="skill-tag primary">Element UI</span>
                    <span class="skill-tag primary">Tailwind CSS</span>
                    <span class="skill-tag primary">Scss</span>
                    <span class="skill-tag primary">Mint UI</span>
                  </div>
                </div>
              </div>

              <div class="skill-category">
                <div class="skill-category-content">
                  <h4 class="skill-category-title">後端開發 Back End</h4>
                  <div class="skills-list">
                    <span class="skill-tag success">Node.js</span>
                    <span class="skill-tag success">MySQL</span>
                  </div>
                </div>
              </div>

              <div class="skill-category">
                <div class="skill-category-content">
                  <h4 class="skill-category-title">開發工具 & 其他</h4>
                  <div class="skills-list">
                    <span class="skill-tag warning">Git</span>
                    <span class="skill-tag warning">Docker</span>
                    <span class="skill-tag warning">Postman</span>
                    <span class="skill-tag warning">SEO</span>
                    <span class="skill-tag warning">GA</span>
                  </div>
                </div>
              </div>

              <div class="skill-category">
                <div class="skill-category-content">
                  <h4 class="skill-category-title">設計能力 Web Design</h4>
                  <div class="skills-list">
                    <span class="skill-tag info">Photoshop</span>
                    <span class="skill-tag info">Figma</span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!-- 作品集 -->
      <section class="mb-8 content-section">
        <div class="section-card">
          <div class="card-header">
            <div class="card-icon projects-icon">
              <el-icon><FolderOpened /></el-icon>
            </div>
            <div>
              <h3 class="card-title">作品集</h3>
              <p class="card-subtitle">Featured Projects & Portfolio</p>
            </div>
          </div>
          <div class="card-content">
            <div class="projects-grid">
              <div class="project-card">
                <div class="project-preview">
                  <div class="project-image ecommerce">
                    <img src="/src/assets/1.png" alt="庫存管理系統縮圖" class="project-thumbnail" />
                    <div class="project-overlay">
                      <span class="project-label">前端開發</span>
                    </div>
                  </div>
                </div>
                <div class="project-info">
                  <h4 class="project-title">庫存管理系統</h4>
                  <p class="project-description">一個基於 Vue 3 + Vite 開發的現代化庫存管理系統，提供直觀易用的界面來管理商品庫存。目前只為靜態展示。</p>
                  <div class="project-techs">
                    <h5 class="project-section-title">技術棧</h5>
                    <div class="tech-tags">
                      <span class="tech-tag">Vue 3</span>
                      <span class="tech-tag">Vite</span>
                      <span class="tech-tag">Element Plus</span>
                      <span class="tech-tag">Tailwind CSS</span>
                    </div>
                  </div>
                  <div class="project-features">
                    <h5 class="project-section-title">主要功能</h5>
                    <ul class="feature-list">
                      <li class="feature-item">使用vite + tailwind + element-plus開發，並部署於 vercel。</li>
                      <li class="feature-item">建立可操作的介面，模擬進銷存系統流程（商品新增、編輯、刪除、庫存數量調整）。</li>
                      <li class="feature-item">提供數據統整與視覺化呈現，讓使用者快速理解庫存變動與商品管理狀況。</li>
                      <li class="feature-item">著重於前端互動與使用者體驗設計，無後端 API 串接，僅做操作模擬。</li>
                    </ul>
                  </div>
                  <div class="project-links">
                    <div class="project-actions-bottom">
                      <el-button type="primary" @click="openLink('https://inventory-management-psi-beryl.vercel.app/#/')" class="project-button">
                        <el-icon><View /></el-icon>
                        <span>查看專案</span>
                      </el-button>
                      <el-button @click="openLink('https://github.com/apple333069/InventoryManagement')" class="project-button">
                        <el-icon><Link /></el-icon>
                        <span>GitHub</span>
                      </el-button>
                    </div>
                  </div>
                </div>
              </div>

              <div class="project-card">
                <div class="project-preview">
                  <div class="project-image management">
                    <el-icon class="project-icon"><Document /></el-icon>
                    <div class="project-overlay">
                      <span class="project-label">企業應用</span>
                    </div>
                  </div>
                </div>
                <div class="project-info">
                  <h4 class="project-title">寵物照護服務平台</h4>
                  <p class="project-description">參與公司專案前端開發，現已上線營運。負責整體前端架構設計與開發實作。</p>
                  <div class="project-techs">
                    <h5 class="project-section-title">技術棧</h5>
                    <div class="tech-tags">
                      <span class="tech-tag">Vue 3</span>
                      <span class="tech-tag">Scss</span>
                      <span class="tech-tag">Tailwind CSS</span>
                      <span class="tech-tag">Vite</span>
                    </div>
                  </div>
                  <div class="project-features">
                    <h5 class="project-section-title">主要功能與貢獻</h5>
                    <ul class="feature-list">
                      <li class="feature-item">動物醫院查詢</li>
                      <li class="feature-item">寵物保險指定</li>
                      <li class="feature-item">會員中心開發</li>
                      <li class="feature-item">響應式介面設計</li>
                      <li class="feature-item">最新消息、熱門活動、醫院資訊動態更新</li>
                    </ul>
                  </div>
                  <div class="project-links">
                    <div class="project-actions-bottom">
                      <el-button type="primary" @click="openLink('https://petscare.ai/')" class="project-button">
                        <el-icon><View /></el-icon>
                        <span>查看連結</span>
                      </el-button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      
    </main>
  </div>
</template>

<script>
import {
  Download, Message, Location, Phone, InfoFilled, Briefcase,
  Star, FolderOpened, School, ShoppingCart, User, View, Link
} from '@element-plus/icons-vue'

export default {
  name: 'App',
  components: {
    Download, Message, Location, Phone, InfoFilled, Briefcase,
    Star, FolderOpened, School, ShoppingCart, User, View, Link
  },
  methods: {
    openLink(url) {
      window.open(url, '_blank')
    }
  }
}
</script>