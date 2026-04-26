<template>
  <div class="min-h-screen app">
    <div class="resume-wrapper">
      <!-- Header Section -->
      <header class="hero-section">
        <div class="hero-content">
          <div class="business-card">
            <div class="card-avatar">
              <div class="avatar-circle">
                <img src="/src/assets/3.jpg" alt="頭像" class="avatar-img" />
              </div>
            </div>
            <div class="card-info">
              <h1 class="card-name">黃愷婷</h1>
            </div>
          </div>

          <!-- 新增的資訊區塊 -->
          <div class="profile-detail-card">
            <div class="detail-header">
              <div class="detail-title-wrapper">
                <span class="detail-title-badge">Professional</span>
                <h2 class="detail-job-title">前端工程師</h2>
              </div>
            </div>
            
            <div class="detail-section intro-section">
              <div class="detail-section-header">
                <el-icon><User /></el-icon>
                <span>自我介紹</span>
              </div>
              <p class="detail-intro-text">
                擁有四年前端開發經驗，熟練使用 Vue.js 進行專案開發。個性積極主動，善於團隊協作，並樂於學習新技術以提升專業能力。期望能在未來的工作中發揮所長，為團隊創造價值並持續成長。
              </p>
            </div>

            <div class="detail-section-divider"></div>

            <div class="detail-section contact-section">
              <div class="detail-section-header">
                <el-icon><Message /></el-icon>
                <span>聯繫資訊</span>
              </div>
              <div class="contact-list">
                <div class="contact-detail-item">
                  <div class="contact-icon-box location">
                    <el-icon><Location /></el-icon>
                  </div>
                  <span>新北市中和區</span>
                </div>
                <div class="contact-detail-item">
                  <div class="contact-icon-box email">
                    <el-icon><Message /></el-icon>
                  </div>
                  <span>t141826@gmail.com</span>
                </div>
                <div class="contact-detail-item">
                  <div class="contact-icon-box phone">
                    <el-icon><Phone /></el-icon>
                  </div>
                  <span>0973-383-923</span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </header>

      <!-- Main Content -->
      <main class="main-content">


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
                      <span class="job-period">2023/9~2026/4</span>
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
                      <h4 class="text-xl font-semibold text-slate-800 mb-2">助理前端工程師</h4>
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
              <div>
                <h3 class="card-title">技能專長</h3>
                <p class="card-subtitle">Skills</p>
              </div>
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
                      <span class="skill-tag primary">PWA</span>
                    </div>
                  </div>
                </div>

                <div class="skill-category">
                  <div class="skill-category-content">
                    <h4 class="skill-category-title">後端與雲端服務 Back End & Cloud Services</h4>
                    <div class="skill-level-section">
                      <h5 class="skill-level-familiar">接觸</h5>
                      <div class="skills-list">
                        <span class="skill-tag success">Node.js</span>
                        <span class="skill-tag success">MySQL</span>
                        <span class="skill-tag success">Firebase (Firestore/FCM/Auth)</span>
                        <span class="skill-tag success">Docker</span>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="skill-category">
                  <div class="skill-category-content">
                    <h4 class="skill-category-title">開發工具 & 其他</h4>
                    <div class="skill-level-section">
                      <h5 class="skill-level-proficient">熟悉</h5>
                      <div class="skills-list">
                        <span class="skill-tag warning">OAuth 2.0 / 第三方登入 (LINE)</span>
                        <span class="skill-tag warning">sourcetree (git)</span>
                        <span class="skill-tag warning">Postman</span>
                        <span class="skill-tag warning">Vercel</span>
                        <span class="skill-tag warning">SEO</span>
                      </div>
                    </div>
                    <div class="skill-level-section">
                      <h5 class="skill-level-familiar">接觸</h5>
                      <div class="skills-list">
                        <span class="skill-tag warning">GA</span>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="skill-category">
                  <div class="skill-category-content">
                    <h4 class="skill-category-title">設計能力 Web Design</h4>
                    <div class="skill-level-section">
                      <h5 class="skill-level-familiar">接觸</h5>
                      <div class="skills-list">
                        <span class="skill-tag info">Photoshop</span>
                        <span class="skill-tag info">Figma</span>
                      </div>
                    </div>
                  </div>
                </div>

                <!-- AI 輔助工具 -->
                <div class="skill-category">
                  <div class="skill-category-content">
                    <h4 class="skill-category-title">
                      AI 輔助工具
                    </h4>
                    <div class="skill-level-section">
                      <h5 class="skill-level-proficient">熟悉</h5>
                      <div class="skills-list">
                        <span class="skill-tag brain">ChatGPT</span>
                        <span class="skill-tag brain">Copilot</span>
                        <span class="skill-tag brain">Gemini 3 Flash</span>
                        <span class="skill-tag brain">Antigravity</span>
                      </div>
                    </div>
                    <div class="skill-level-section">
                      <h5 class="skill-level-familiar">接觸</h5>
                      <div class="skills-list">
                        <span class="skill-tag brain">Claude Code</span>
                        <span class="skill-tag brain">Cursor</span>
                      </div>
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
                    <div class="project-image travel">
                      <img src="/src/assets/2.png" alt="VistaMap 縮圖" class="project-thumbnail" />
                      <div class="project-overlay">
                        <span class="project-label">個人作品 / PWA</span>
                      </div>
                    </div>
                  </div>
                  <div class="project-info">
                    <h4 class="project-title">VistaMap 旅遊規劃助手</h4>
                    <p class="project-description">專為旅遊設計的 PWA 應用程式。整合 Firebase 實現跨裝置同步與即時提醒，並針對海外旅遊優化地圖導航體驗。</p>
                    <div class="project-techs">
                      <h5 class="project-section-title">技術棧</h5>
                      <div class="tech-tags">
                        <span class="tech-tag">Antigravity (AI 輔助開發)</span>
                        <span class="tech-tag">Vue 3</span>
                        <span class="tech-tag">Firebase (Firestore/FCM)</span>
                        <span class="tech-tag">PWA</span>
                        <span class="tech-tag">Vite</span>
                        <span class="tech-tag">Tailwind CSS</span>
                      </div>
                    </div>
                    <div class="project-features">
                      <h5 class="project-section-title">主要功能</h5>
                      <ul class="feature-list">
                        <li class="feature-item">PWA 離線存取與桌面/手機端安裝</li>
                        <li class="feature-item">Firebase 實時雲端同步與多人共享行程</li>
                        <li class="feature-item">OpenStreetMap 互動式地圖嵌入</li>
                        <li class="feature-item">FCM 推播通知、景點提醒功能</li>
                        <li class="feature-item">導向第三方地圖 (Google Map) </li>
                      </ul>
                    </div>
                    <div class="project-links">
                      <div class="project-actions-bottom">
                        <el-button type="primary" @click="openLink('https://vistamap-3d2e4.web.app')" class="project-button">
                          <el-icon><View /></el-icon>
                          <span>查看專案</span>
                        </el-button>
                      </div>
                    </div>
                  </div>
                </div>

                <div class="project-card">
                  <div class="project-preview">
                    <div class="project-image ecommerce">
                      <img src="/src/assets/1.png" alt="庫存管理系統縮圖" class="project-thumbnail" />
                      <div class="project-overlay">
                        <span class="project-label">個人作品</span>
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
                        <li class="feature-item">LINE 第三方整合登入 (OAuth 2.0 授權流程實作)</li>
                        <li class="feature-item">響應式介面</li>
                        <li class="feature-item">首頁、動物醫院查詢、聯絡我們</li>
                        <li class="feature-item">會員中心（個人資料、健康存摺、毛孩護照）</li>
                        <li class="feature-item">每日簽到</li>
                        <li class="feature-item">優惠券模組、點數兌換中心</li>
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
  </div>
</template>

<script>
import {
  Download, Message, Location, Phone, InfoFilled, Briefcase,
  Star, FolderOpened, School, ShoppingCart, User, View, Link, Cpu
} from '@element-plus/icons-vue'

export default {
  name: 'App',
  components: {
    Download, Message, Location, Phone, InfoFilled, Briefcase,
    Star, FolderOpened, School, ShoppingCart, User, View, Link, Cpu
  },
  methods: {
    openLink(url) {
      window.open(url, '_blank')
    }
  }
}
</script>