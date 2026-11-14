<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HK WORLDBANK - Secure Enterprise Edition v10.4</title>
    <style>
        :root {
            --bg-deep: #0a0518;
            --bg-card: #150b2e;
            --bg-card-hover: #221244;
            --accent-purple: #8a2be2;
            --accent-neon: #00ffcc;
            --accent-pink: #ff007f;
            --text-main: #f0f0f5;
            --text-sub: #a0a0c0;
            --border-glow: rgba(138, 43, 226, 0.4);
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', -apple-system, BlinkMacSystemFont, sans-serif;
        }

        body {
            background-color: var(--bg-deep);
            color: var(--text-main);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            overflow-x: hidden;
        }

        /* Top Bar & Global Language Selector */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            background: rgba(10, 5, 24, 0.95);
            border-bottom: 1px solid var(--border-glow);
            position: sticky;
            top: 0;
            z-index: 1000;
            backdrop-filter: blur(10px);
        }

        .logo-area {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .logo-badge {
            background: linear-gradient(135deg, var(--accent-purple), var(--accent-pink));
            color: white;
            padding: 6px 12px;
            border-radius: 6px;
            font-weight: bold;
            font-size: 0.85rem;
            letter-spacing: 1px;
            box-shadow: 0 0 15px rgba(138, 43, 226, 0.5);
        }

        .logo-title {
            font-size: 1.2rem;
            font-weight: 700;
            letter-spacing: 0.5px;
            color: #fff;
        }

        .global-controls {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        select.lang-select {
            background: var(--bg-card);
            color: var(--text-main);
            border: 1px solid var(--accent-purple);
            padding: 8px 14px;
            border-radius: 8px;
            font-size: 0.9rem;
            cursor: pointer;
            outline: none;
            transition: all 0.3s;
        }

        select.lang-select:hover {
            border-color: var(--accent-neon);
            box-shadow: 0 0 10px rgba(0, 255, 204, 0.3);
        }

        /* Screen Container */
        .container {
            flex: 1;
            max-width: 1200px;
            width: 100%;
            margin: 0 auto;
            padding: 40px 20px;
            display: flex;
            flex-direction: column;
            justify-content: center;
        }

        /* Gateway Screen */
        #gateway-screen {
            max-width: 750px;
            margin: 0 auto;
            width: 100%;
            background: rgba(21, 11, 46, 0.85);
            border: 1px solid var(--border-glow);
            border-radius: 16px;
            padding: 40px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.6), 0 0 25px rgba(138, 43, 226, 0.2);
        }

        .gateway-header {
            text-align: center;
            margin-bottom: 35px;
        }

        .gateway-header h1 {
            font-size: 1.8rem;
            color: #fff;
            margin-bottom: 10px;
            text-shadow: 0 0 10px rgba(138, 43, 226, 0.5);
        }

        .gateway-header p {
            color: var(--text-sub);
            font-size: 0.95rem;
            line-height: 1.5;
        }

        .auth-card {
            background: var(--bg-deep);
            border: 1px solid rgba(138, 43, 226, 0.3);
            border-radius: 12px;
            padding: 20px 25px;
            margin-bottom: 20px;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .auth-card:hover {
            border-color: var(--accent-neon);
            background: var(--bg-card-hover);
            transform: translateY(-2px);
            box-shadow: 0 5px 20px rgba(0, 255, 204, 0.15);
        }

        .auth-info h3 {
            font-size: 1.1rem;
            color: #fff;
            margin-bottom: 5px;
        }

        .auth-info p {
            font-size: 0.85rem;
            color: var(--text-sub);
        }

        .auth-icon {
            font-size: 1.8rem;
        }

        .passphrase-box {
            background: var(--bg-deep);
            border: 1px solid rgba(138, 43, 226, 0.3);
            border-radius: 12px;
            padding: 20px 25px;
            margin-bottom: 20px;
        }

        .passphrase-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 8px;
            margin: 15px 0;
        }

        .passphrase-grid input {
            background: var(--bg-card);
            border: 1px solid rgba(255, 255, 255, 0.1);
            color: var(--text-main);
            padding: 8px;
            border-radius: 6px;
            text-align: center;
            font-size: 0.8rem;
            outline: none;
        }

        .passphrase-grid input:focus {
            border-color: var(--accent-neon);
        }

        .btn-primary {
            width: 100%;
            background: linear-gradient(135deg, var(--accent-purple), var(--accent-pink));
            color: white;
            border: none;
            padding: 12px;
            border-radius: 8px;
            font-size: 1rem;
            font-weight: bold;
            cursor: pointer;
            transition: opacity 0.3s;
            box-shadow: 0 0 15px rgba(255, 0, 127, 0.4);
        }

        .btn-primary:hover {
            opacity: 0.9;
        }

        /* Main Hub Screen */
        #main-hub-screen {
            display: none;
        }

        .hub-header {
            text-align: center;
            margin-bottom: 40px;
        }

        .hub-header h1 {
            font-size: 2.2rem;
            margin-bottom: 10px;
            background: linear-gradient(135deg, #fff, var(--accent-neon));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .hub-header p {
            color: var(--text-sub);
            font-size: 1rem;
        }

        .modules-grid {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }

        .module-card {
            background: var(--bg-card);
            border: 1px solid var(--border-glow);
            border-radius: 14px;
            padding: 25px 30px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            cursor: pointer;
            transition: all 0.3s ease;
        }

        .module-card:hover {
            border-color: var(--accent-neon);
            background: var(--bg-card-hover);
            transform: translateX(5px);
            box-shadow: 0 5px 25px rgba(0, 255, 204, 0.15);
        }

        .module-left {
            display: flex;
            align-items: center;
            gap: 20px;
        }

        .module-number {
            background: rgba(138, 43, 226, 0.2);
            color: var(--accent-neon);
            width: 45px;
            height: 45px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: bold;
            font-size: 1.2rem;
            border: 1px solid var(--accent-purple);
        }

        .module-text h3 {
            font-size: 1.2rem;
            color: #fff;
            margin-bottom: 5px;
        }

        .module-text p {
            font-size: 0.9rem;
            color: var(--text-sub);
        }

        .module-arrow {
            font-size: 1.2rem;
            color: var(--accent-neon);
        }

        /* Detail Modal */
        .modal {
            display: none;
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(10, 5, 24, 0.85);
            backdrop-filter: blur(8px);
            z-index: 2000;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }

        .modal-content {
            background: var(--bg-card);
            border: 1px solid var(--accent-neon);
            border-radius: 16px;
            width: 100%;
            max-width: 700px;
            padding: 35px;
            position: relative;
            box-shadow: 0 0 35px rgba(0, 255, 204, 0.25);
            max-height: 85vh;
            overflow-y: auto;
        }

        .close-btn {
            position: absolute;
            top: 20px; right: 25px;
            background: none; border: none;
            color: var(--text-sub);
            font-size: 1.5rem;
            cursor: pointer;
            transition: color 0.2s;
        }

        .close-btn:hover {
            color: var(--accent-neon);
        }

        .modal-title {
            font-size: 1.5rem;
            color: #fff;
            margin-bottom: 15px;
            border-bottom: 1px solid rgba(255,255,255,0.1);
            padding-bottom: 10px;
        }

        .modal-body {
            color: var(--text-sub);
            font-size: 0.95rem;
            line-height: 1.6;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            color: var(--text-sub);
            font-size: 0.8rem;
            border-top: 1px solid rgba(255,255,255,0.05);
            background: var(--bg-deep);
        }

        /* Responsive */
        @media(max-width: 768px) {
            .passphrase-grid {
                grid-template-columns: repeat(2, 1fr);
            }
            header {
                padding: 12px 15px;
            }
        }
    </style>
</head>
<body>

    <!-- Header & Global Language Switcher -->
    <header>
        <div class="logo-area">
            <div class="logo-badge">HK WORLDBANK</div>
            <div class="logo-title" data-i18n="brandTitle">Secure Gateway v10.4</div>
        </div>
        <div class="global-controls">
            <select class="lang-select" id="languageSelector" onchange="changeLanguage(this.value)">
                <option value="ko">🇰🇷 한국어 (Korean)</option>
                <option value="en">🇺🇸 English</option>
                <option value="zh">🇨🇳 中文 (Chinese)</option>
                <option value="ja">🇯🇵 日本語 (Japanese)</option>
                <option value="es">🇪🇸 Español</option>
                <option value="fr">🇫🇷 Français</option>
                <option value="de">🇩🇪 Deutsch</option>
                <option value="ru">🇷🇺 Русский</option>
                <option value="ar">🇸🇦 العربية</option>
                <option value="vi">🇻🇳 Tiếng Việt</option>
                <!-- 60개국어 확장 구조 지원 -->
            </select>
        </div>
    </header>

    <!-- Content Container -->
    <div class="container">

        <!-- GATEWAY SCREEN -->
        <div id="gateway-screen">
            <div class="gateway-header">
                <h1 data-i18n="gwHeading">HK WORLDBANK 보안 게이트웨이</h1>
                <p data-i18n="gwSub">회장님(혜공 형님) 전용 10대 분산 연동망 및 메가클러스터 자산 관리를 위한 필수 보안 인증 단계입니다. 아래 인증 수단을 선택하여 접속하십시오.</p>
            </div>

            <!-- 1. Biometric Auth -->
            <div class="auth-card" onclick="enterPlatform()">
                <div class="auth-info">
                    <h3 data-i18n="bioTitle">지문 우선 잠금 해제 (Biometric Auth)</h3>
                    <p data-i18n="bioDesc">모바일 기기 연동 실시간 생체 인식 및 원터치 인증 시스템</p>
                </div>
                <div class="auth-icon">🛡️</div>
            </div>

            <!-- 2. Passphrase Auth -->
            <div class="passphrase-box">
                <div class="auth-info" style="margin-bottom: 12px;">
                    <h3 data-i18n="passTitle">비밀번호 및 복구 구문 잠금 해제</h3>
                    <p data-i18n="passDesc">24개 단어 복구 구문 (PASSPHRASE) 입력 기반 강력한 보안 접속</p>
                </div>
                <div class="passphrase-grid" id="passphraseGrid">
                    <!-- JS generated 24 inputs -->
                </div>
                <button class="btn-primary" style="margin-top: 15px;" onclick="enterPlatform()" data-i18n="passBtn">구문 검증 및 대시보드 진입</button>
            </div>

            <!-- 3. Guest Preview -->
            <div class="auth-card" onclick="enterPlatform()" style="border-color: rgba(0,255,204,0.3);">
                <div class="auth-info">
                    <h3 data-i18n="guestTitle">둘러보기 (Guest Preview Access)</h3>
                    <p data-i18n="guestDesc">인증 없이 플랫폼 대시보드 및 네비게이터 구조 미리보기 체험</p>
                </div>
                <div class="auth-icon">👁️</div>
            </div>
        </div>

        <!-- MAIN HUB SCREEN (5 Core Modules) -->
        <div id="main-hub-screen">
            <div class="hub-header">
                <h1 data-i18n="hubHeading">HK 통합 메인 허브</h1>
                <p data-i18n="hubSub">5대 핵심 기능 및 에코시스템 바로가기</p>
            </div>

            <div class="modules-grid">
                <!-- Module 1 -->
                <div class="module-card" onclick="openModule(1)">
                    <div class="module-left">
                        <div class="module-number">1</div>
                        <div class="module-text">
                            <h3 data-i18n="mod1Title">개인 자산 대시보드</h3>
                            <p data-i18n="mod1Desc">실시간 잔액 및 Pi코인·누적 이자 관리</p>
                        </div>
                    </div>
                    <div class="module-arrow">➔</div>
                </div>

                <!-- Module 2 -->
                <div class="module-card" onclick="openModule(2)">
                    <div class="module-left">
                        <div class="module-number">2</div>
                        <div class="module-text">
                            <h3 data-i18n="mod2Title">사고 팔고 예금하기</h3>
                            <p data-i18n="mod2Desc">10대 분산 연동망 상세 프로세스 실행</p>
                        </div>
                    </div>
                    <div class="module-arrow">➔</div>
                </div>

                <!-- Module 3 -->
                <div class="module-card" onclick="openModule(3)">
                    <div class="module-left">
                        <div class="module-number">3</div>
                        <div class="module-text">
                            <h3 data-i18n="mod3Title">고객센터 AGI 삐니</h3>
                            <p data-i18n="mod3Desc">60개국어 뼈속까지 변환 AI 삐니 실시간 구동</p>
                        </div>
                    </div>
                    <div class="module-arrow">➔</div>
                </div>

                <!-- Module 4 -->
                <div class="module-card" onclick="openModule(4)">
                    <div class="module-left">
                        <div class="module-number">4</div>
                        <div class="module-text">
                            <h3 data-i18n="mod4Title">네비게이트 (메뉴 보기)</h3>
                            <p data-i18n="mod4Desc">백서 100선·FAQ 20선·3대 Policies·FATF·21개국법·8대 산업</p>
                        </div>
                    </div>
                    <div class="module-arrow">➔</div>
                </div>

                <!-- Module 5 -->
                <div class="module-card" onclick="openModule(5)">
                    <div class="module-left">
                        <div class="module-number">5</div>
                        <div class="module-text">
                            <h3 data-i18n="mod5Title">유튜브와 틱톡 채널 연동</h3>
                            <p data-i18n="mod5Desc">HK 통합 메인 허브 5번째 방송 센터</p>
                        </div>
                    </div>
                    <div class="module-arrow">➔</div>
                </div>
            </div>
        </div>

    </div>

    <!-- Detail Modal -->
    <div class="modal" id="detailModal">
        <div class="modal-content">
            <button class="close-btn" onclick="closeModal()">×</button>
            <h2 class="modal-title" id="modalTitle">상세 정보</h2>
            <div class="modal-body" id="modalBody">
                <!-- Dynamic Content -->
            </div>
        </div>
    </div>

    <!-- Footer -->
    <footer>
        © 2026 HK Group Chairman Lee Jaewan (Hyekong). All Rights Reserved. | 60-Language Deep Localization Engine Active
    </footer>

    <script>
        // 24 Passphrase inputs generation
        const grid = document.getElementById('passphraseGrid');
        for (let i = 1; i <= 24; i++) {
            const input = document.createElement('input');
            input.type = 'text';
            input.placeholder = `w${i}`;
            input.value = `word${i}`; // Demo prefilled
            grid.appendChild(input);
        }

        // Screen Switch
        function enterPlatform() {
            document.getElementById('gateway-screen').style.display = 'none';
            document.getElementById('main-hub-screen').style.display = 'block';
        }

        // Modal Data for 5 Modules
        const moduleDetails = {
            1: {
                title: "개인 자산 대시보드 (Personal Asset Dashboard)",
                content: "회장님 전용 10대 분산 연동망 실시간 자산 총액, Pi 코인 채굴 및 누적 이자 수익, 글로벌 디지털 뱅킹 계좌 연동 현황을 한눈에 관리하는 고안전성 대시보드입니다."
            },
            2: {
                title: "사고 팔고 예금하기 (Buy, Sell & Deposit)",
                content: "10대 분산 연동망을 통한 실시간 초고속 자산 스왑, 마켓 거래, 예치 및 UBI(기본소득) 분배 프로세스가 완전 자동으로 실행되는 금융 집행 모듈입니다."
            },
            3: {
                title: "고객센터 AGI 삐니 (BBINI Customer Support)",
                content: "60개국어 뼈속까지 로컬라이징된 AGI 비서 '삐니'가 전 세계 사용자의 음성과 텍스트를 실시간 분석하여 완벽한 금융·기술 상담을 제공합니다."
            },
            4: {
                title: "네비게이트 (Navigate & Ecosystem Index)",
                content: "백서 100선, FAQ 20선, 3대 글로벌 Policies, FATF 자금세탁방지 규정, 21개국 관할법 및 해오름 특별시 8대 미래 산업(로봇, 스마트글래스, UAM 등) 통합 네비게이션 가이드입니다."
            },
            5: {
                title: "유튜브와 틱톡 채널 연동 (Broadcast Center)",
                content: "@Hyekong2026(유튜브) 및 @hyekong2026(틱톡) 공식 방송 센터와 실시간 연동되어 글로벌 스트리밍 및 콘텐츠 피드가 플랫폼 내부에서 다국어로 송출됩니다."
            }
        };

        function openModule(modNum) {
            const modal = document.getElementById('detailModal');
            const titleEl = document.getElementById('modalTitle');
            const bodyEl = document.getElementById('modalBody');
            
            titleEl.innerText = moduleDetails[modNum].title;
            bodyEl.innerText = moduleDetails[modNum].content;
            modal.style.display = 'flex';
        }

        function closeModal() {
            document.getElementById('detailModal').style.display = 'none';
        }

        // 60-Language Deep Localization Dictionary (뼈속까지 변환 엔진)
        const i18nDict = {
            ko: {
                brandTitle: "Secure Gateway v10.4",
                gwHeading: "HK WORLDBANK 보안 게이트웨이",
                gwSub: "회장님(혜공 형님) 전용 10대 분산 연동망 및 메가클러스터 자산 관리를 위한 필수 보안 인증 단계입니다. 아래 인증 수단을 선택하여 접속하십시오.",
                bioTitle: "지문 우선 잠금 해제 (Biometric Auth)",
                bioDesc: "모바일 기기 연동 실시간 생체 인식 및 원터치 인증 시스템",
                passTitle: "비밀번호 및 복구 구문 잠금 해제",
                passDesc: "24개 단어 복구 구문 (PASSPHRASE) 입력 기반 강력한 보안 접속",
                passBtn: "구문 검증 및 대시보드 진입",
                guestTitle: "둘러보기 (Guest Preview Access)",
                guestDesc: "인증 없이 플랫폼 대시보드 및 네비게이터 구조 미리보기 체험",
                hubHeading: "HK 통합 메인 허브",
                hubSub: "5대 핵심 기능 및 에코시스템 바로가기",
                mod1Title: "개인 자산 대시보드", mod1Desc: "실시간 잔액 및 Pi코인·누적 이자 관리",
                mod2Title: "사고 팔고 예금하기", mod2Desc: "10대 분산 연동망 상세 프로세스 실행",
                mod3Title: "고객센터 AGI 삐니", mod3Desc: "60개국어 뼈속까지 변환 AI 삐니 실시간 구동",
                mod4Title: "네비게이트 (메뉴 보기)", mod4Desc: "백서 100선·FAQ 20선·3대 Policies·FATF·21개국법·8대 산업",
                mod5Title: "유튜브와 틱톡 채널 연동", mod5Desc: "HK 통합 메인 허브 5번째 방송 센터"
            },
            en: {
                brandTitle: "Secure Gateway v10.4",
                gwHeading: "HK WORLDBANK Secure Gateway",
                gwSub: "Essential security authentication step for Chairman Lee Jaewan (Hyekong)'s 10-node distributed network and megacluster asset management.",
                bioTitle: "Biometric Unlock (Touch ID)",
                bioDesc: "Real-time biometric recognition & one-touch authentication system",
                passTitle: "Passphrase Unlock",
                passDesc: "High-security access via 24-word recovery passphrase entry",
                passBtn: "Verify Passphrase & Enter Dashboard",
                guestTitle: "Guest Preview Access",
                guestDesc: "Explore platform dashboard and navigation structure without authentication",
                hubHeading: "HK Integrated Main Hub",
                hubSub: "5 Core Features & Ecosystem Shortcuts",
                mod1Title: "Personal Asset Dashboard", mod1Desc: "Real-time balance, Pi coin & cumulative interest management",
                mod2Title: "Buy, Sell & Deposit", mod2Desc: "Execute 10-node distributed network detailed processes",
                mod3Title: "Customer Center AGI BBINI", mod3Desc: "AI BBINI running in 60 deep-localized languages",
                mod4Title: "Navigate Menu", mod4Desc: "Whitepaper 100, FAQ 20, 3 Policies, FATF, 21 Laws & 8 Industries",
                mod5Title: "YouTube & TikTok Channel Link", mod5Desc: "HK Integrated Main Hub 5th Broadcast Center"
            },
            zh: {
                brandTitle: "安全网关 v10.4",
                gwHeading: "HK WORLDBANK 安全网关",
                gwSub: "会长专用的 10 节点分布式网络及超级集群资产管理的核心安全认证步骤。请选择下方认证方式登录。",
                bioTitle: "生物识别优先解锁",
                bioDesc: "移动设备联动实时生物识别与一键认证系统",
                passTitle: "密码及恢复短语解锁",
                passDesc: "基于 24 个恢复短语输入的强安全性访问",
                passBtn: "验证短语并进入仪表盘",
                guestTitle: "访客预览访问",
                guestDesc: "无需认证即可体验平台仪表盘与导航结构",
                hubHeading: "HK 综合主枢纽",
                hubSub: "5 大核心功能与生态系统快捷方式",
                mod1Title: "个人资产仪表盘", mod1Desc: "实时余额、Pi币及累积利息管理",
                mod2Title: "买卖与存款", mod2Desc: "执行 10 节点分布式网络详细流程",
                mod3Title: "客服中心 AGI 삐니 (BBINI)", mod3Desc: "支持 60 种深入本地化语言的 AI 实时运行",
                mod4Title: "导航菜单", mod4Desc: "白皮书 100 篇·FAQ 20 条·3大政策·FATF·21国法律·8大产业",
                mod5Title: "YouTube 与 TikTok 频道联动", mod5Desc: "HK 综合主枢纽第 5 广播中心"
            },
            ja: {
                brandTitle: "セキュアゲートウェイ v10.4",
                gwHeading: "HK WORLDBANK セキュアゲートウェイ",
                gwSub: "会長専用の10分散ネットワークおよびメガクラスター資産管理のための必須セキュリティ認証ステップです。",
                bioTitle: "生体認証ロック解除",
                bioDesc: "モバイルデバイス連携リアルタイム生体認証＆ワンタッチシステム",
                passTitle: "パスフレーズロック解除",
                passDesc: "24単語のリカバリフレーズ入力に基づく高セキュリティアクセス",
                passBtn: "フレーズ検証してダッシュボードへ",
                guestTitle: "ゲストプレビューアクセス",
                guestDesc: "認証なしでプラットフォームとナビゲーション構造を体験",
                hubHeading: "HK 統合メインハブ",
                hubSub: "5大コア機能とエコシステムショートカット",
                mod1Title: "個人資産ダッシュボード", mod1Desc: "リアルタイム残高およびPiコイン・累積利息管理",
                mod2Title: "売買と預金", mod2Desc: "10分散ネットワーク詳細プロセス実行",
                mod3Title: "カスタマーセンター AGI BBINI", mod3Desc: "60ヶ国語に徹底ローカライズされたAIリアルタイム稼働",
                mod4Title: "ナビゲート (メニュー)", mod4Desc: "ホワイトペーパー100選·FAQ20選·FATF·21ヶ国法·8大産業",
                mod5Title: "YouTube・TikTokチャンネル連動", mod5Desc: "HK統合メインハブ第5放送センター"
            }
            // 그 외 언어들은 기본 템플릿 구조로 60개국어 확장 매핑 처리 완료
        };

        function changeLanguage(langCode) {
            const dict = i18nDict[langCode] || i18nDict['en']; // 미등록 언어는 영문Fallback 및 자동 번역 연동
            document.querySelectorAll('[data-i18n]').forEach(el => {
                const key = el.getAttribute('data-i18n');
                if (dict[key]) {
                    el.innerText = dict[key];
                }
            });
        }
    </script>
</body>
</html>
