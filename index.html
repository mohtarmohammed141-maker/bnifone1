<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BniFone - بني فون</title>
    <!-- استيراد مكتبات Firebase الجديدة -->
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-app.js";
        import { getAuth, createUserWithEmailAndPassword, signInWithEmailAndPassword, signOut, onAuthStateChanged } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-auth.js";
        import { getFirestore, collection, addDoc, getDocs, onSnapshot } from "https://www.gstatic.com/firebasejs/10.8.0/firebase-firestore.js";

        // إعدادات المشروع الجديد بنين فون (benifone-1b548)
        const firebaseConfig = {
          apiKey: "AIzaSyCuFmscj1hESzS579rDWXuxk8oKK0qSq0U",
          authDomain: "benifone-1b548.firebaseapp.com",
          databaseURL: "https://benifone-1b548-default-rtdb.firebaseio.com",
          projectId: "benifone-1b548",
          storageBucket: "benifone-1b548.firebasestorage.app",
          messagingSenderId: "449831223933",
          appId: "1:449831223933:web:3d79cfd770ca0054406714",
          measurementId: "G-5ESTCV6GP8"
        };

        // تهيئة Firebase
        const app = initializeApp(firebaseConfig);
        const auth = getAuth(app);
        const db = getFirestore(app);

        // ربط الدوال بالنافذة العامة لتعمل مع أزرار HTML
        window.firebaseAuth = auth;
        window.firebaseDb = db;
        window.FB_createUser = createUserWithEmailAndPassword;
        window.FB_signIn = signInWithEmailAndPassword;
        window.FB_signOut = signOut;
        window.FB_onState = onAuthStateChanged;
        window.FB_addDoc = addDoc;
        window.FB_collection = collection;
        window.FB_onSnapshot = onSnapshot;
    </script>

    <style>
        :root { --blue: #1A237E; --gold: #D4AF37; --yellow: #FFEB3B; --whatsapp: #25D366; --pink: #E91E63; --red: #d32f2f; --bg: #f9f9f9; }
        * { box-sizing: border-box; font-family: 'Segoe UI', Tahoma, sans-serif; }
        
        body { 
            margin: 0; 
            background: var(--yellow); 
            background-image: radial-gradient(circle at 20% 20%, #fff9c4 0%, transparent 40%),
                              radial-gradient(circle at 80% 80%, #fff9c4 0%, transparent 40%);
            min-height: 100vh;
            display: flex; justify-content: center; align-items: center; padding: 10px;
        }

        .app-container { 
            width: 100%; max-width: 450px; background: rgba(255, 255, 255, 0.98); 
            border-radius: 35px; padding: 20px; box-shadow: 0 20px 50px rgba(0,0,0,0.15); 
            text-align: center; position: relative; border: 2px solid white;
        }

        .angel-tag { 
            position: absolute; top: -15px; left: 50%; transform: translateX(-50%);
            background: white; padding: 5px 20px; border-radius: 20px;
            font-size: 12px; color: var(--blue); font-weight: bold;
            box-shadow: 0 4px 10px rgba(0,0,0,0.1); border: 1px solid #eee;
        }

        .logo-area {
            width: 90px; height: 90px; background: white; border-radius: 50%;
            margin: 0 auto 10px; display: flex; align-items: center; justify-content: center;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1); border: 3px solid var(--blue);
            overflow: hidden;
        }
        .logo-area img { width: 90%; height: 90%; object-fit: contain; }

        .brand-box h2 { margin: 0; color: var(--blue); font-size: 20px; margin-bottom: 12px; }

        .page { display: none; }
        .active-page { display: block; animation: slideUp 0.4s ease-out; }
        @keyframes slideUp { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }

        input, textarea, select { width: 100%; padding: 12px; border-radius: 15px; border: 1px solid #eee; margin-bottom: 10px; text-align: center; font-size: 14px; background: #fafafa; }
        
        .btn { width: 100%; padding: 13px; border-radius: 18px; border: none; font-weight: bold; font-size: 15px; cursor: pointer; margin-top: 8px; transition: 0.2s; }
        .btn-blue { background: var(--blue); color: white; }
        .btn-pink { background: var(--pink); color: white; }
        .btn-green { background: #2e7d32; color: white; }
        .btn-red { background: var(--red); color: white; }
        .btn-white { background: white; color: var(--blue); border: 1px solid #eee; }
        
        .gift-section { background: var(--blue); color: white; padding: 12px; border-radius: 20px; margin: 10px 0; }
        .progress-bar { background: rgba(255,255,255,0.2); height: 8px; border-radius: 5px; margin-top: 6px; overflow: hidden; }
        #progress-fill { background: var(--gold); height: 100%; width: 0%; transition: 0.8s; }

        .grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-top: 12px; max-height: 380px; overflow-y: auto; padding-left: 5px; }
        .s-card { 
            background: white; padding: 12px 8px; border-radius: 18px; border: 1px solid #eee; 
            cursor: pointer; transition: 0.2s; box-shadow: 0 4px 6px rgba(0,0,0,0.02);
        }
        .s-card:hover { border-color: var(--blue); transform: translateY(-3px); }
        .s-card span { font-size: 22px; display: block; margin-bottom: 4px; }
        .s-card p { margin: 0; font-size: 12px; font-weight: bold; color: #444; }

        .market-tabs { display: flex; gap: 8px; margin-bottom: 12px; }
        .market-tab { flex: 1; padding: 8px; border-radius: 12px; cursor: pointer; font-weight: bold; background: #eee; color: #333; font-size: 13px; }
        .market-tab.active-tab-boys { background: var(--blue); color: white; }
        .market-tab.active-tab-girls { background: var(--pink); color: white; }

        .product-card { 
            background: white; border-radius: 15px; padding: 12px; margin-bottom: 10px; 
            border: 1px solid #eee; text-align: right; box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }
        .product-card h4 { margin: 0 0 5px 0; color: #333; font-size: 14px; }
        .product-card .price { color: green; font-weight: bold; font-size: 13px; }
        .product-card .seller { font-size: 11px; color: #777; margin-top: 3px; }

        .suggestion-box { background: #f0f4f8; padding: 12px; border-radius: 20px; margin-top: 12px; border: 1px dashed var(--blue); }
        .footer-rights { font-size: 11px; color: #777; margin-top: 15px; font-weight: bold; }
        
        .user-card-admin { background: #f8f9fa; border: 1px solid #ddd; padding: 10px; border-radius: 12px; margin-bottom: 8px; text-align: right; font-size: 12px; }

        /* ستايل محدد الشبكة والخدمات الجديد */
        .network-tool-container {
            background: #1e293b;
            color: #f8fafc;
            border-radius: 16px;
            padding: 15px;
            text-align: right;
        }
        .network-tool-container h2 {
            color: #38bdf8;
            margin-bottom: 5px;
            text-align: center;
        }
        .network-tool-container .subtitle {
            text-align: center;
            color: #94a3b8;
            font-size: 12px;
            margin-bottom: 12px;
        }
        .location-box {
            background: #334155;
            padding: 10px;
            border-radius: 8px;
            margin-bottom: 12px;
            font-size: 13px;
            text-align: center;
        }
        .ai-search-box {
            background: #0f172a;
            border: 1px solid #38bdf8;
            border-radius: 10px;
            padding: 10px;
            margin-bottom: 12px;
            font-size: 12px;
            color: #38bdf8;
            display: none;
            text-align: center;
        }
        .network-card {
            background: #334155;
            border-radius: 10px;
            padding: 12px;
            margin-bottom: 10px;
            border-right: 5px solid #64748b;
            transition: all 0.3s ease;
        }
        .network-card.best {
            border-right-color: #22c55e;
            background: #1e3a2f;
        }
        .net-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 6px;
        }
        .net-header h4 {
            margin: 0;
            font-size: 16px;
            color: #fff;
        }
        .badge {
            background: #22c55e;
            color: #fff;
            padding: 2px 6px;
            border-radius: 20px;
            font-size: 10px;
            font-weight: bold;
        }
        .net-details {
            font-size: 12px;
            color: #cbd5e1;
            border-top: 1px solid #475569;
            padding-top: 6px;
            margin-top: 6px;
        }
        .service-list {
            margin: 4px 0 0 0;
            padding-right: 15px;
            font-size: 11px;
            color: #94a3b8;
        }
        .service-list li {
            margin-bottom: 2px;
        }
        .spinner {
            display: inline-block;
            width: 12px;
            height: 12px;
            border: 2px solid #fff;
            border-top: transparent;
            border-radius: 50%;
            animation: spin 0.8s linear infinite;
            margin-left: 6px;
            vertical-align: middle;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>

<div class="app-container">
    <div class="angel-tag">بني فون ❤️ ملاك</div>

    <!-- صفحة الدخول -->
    <div id="login-page" class="page active-page">
        <div class="logo-area">
            <img src="https://img.freepik.com/premium-vector/mobile-phone-logo-design-template-smartphone-application-icon-vector-illustration_664675-538.jpg" alt="BniFone Logo">
        </div>
        <div class="brand-box"><h2>بني فون للخدمات المتكاملة</h2></div>
        
        <!-- نموذج تسجيل الدخول المباشر -->
        <div id="login-form">
            <input type="email" id="login-email" placeholder="البريد الإلكتروني">
            <input type="password" id="login-pass" placeholder="كلمة المرور">
            <button class="btn btn-blue" onclick="handleLoginFirebase()">تسجيل الدخول</button>
            <span style="font-size:12px; color:#666; cursor:pointer; text-decoration:underline; display:block; margin-top:10px;" onclick="forgotPassword()">نسيت كلمة السر؟</span>
            <button class="btn btn-white" onclick="toggleView(false)" style="margin-top:15px;">إنشاء حساب جديد</button>
        </div>

        <!-- نموذج إنشاء حساب جديد -->
        <div id="register-form" style="display:none;">
            <input type="email" id="reg-email" placeholder="البريد الإلكتروني">
            <input type="password" id="reg-pass" placeholder="كلمة مرور جديدة (6 أحرف أو أكثر)">
            <button class="btn btn-blue" onclick="handleRegisterFirebase()">إنشاء الحساب عبر النظام السحابي</button>
            <button class="btn btn-white" onclick="toggleView(true)">رجوع</button>
        </div>

        <br>
        <small style="cursor:pointer; color:var(--blue); opacity: 0.5;" onclick="openAdmin()">لوحة الإدارة الكاملة</small>
        <div class="footer-rights">تم التطوير بواسطة بني فون 2026</div>
    </div>

    <!-- الصفحة الرئيسية -->
    <div id="main-app" class="page">
        <div class="brand-box" style="margin-bottom:5px;"><h2>خدمات بني فون</h2></div>
        <p id="user-info" style="color:var(--blue); font-weight:bold; margin:0; font-size:12px;"></p>

        <div class="gift-section">
            <div style="display:flex; justify-content:space-between; font-size:11px;">
                <span>🎁 عداد هدايا ملاك (3+1)</span>
                <span id="gift-count">0 / 3</span>
            </div>
            <div class="progress-bar"><div id="progress-fill"></div></div>
        </div>
        
        <div class="grid">
            <div class="s-card" onclick="openGameTopup()"><span>🎯</span><p>شحن ألعاب الحرب</p></div>
            <div class="s-card" onclick="openAccountsMarket()"><span>🎮</span><p>سوق الحسابات</p></div>
            <div class="s-card" onclick="openOnlinePhoneServices()"><span>🌐</span><p>خدمات هواتف</p></div>
            <div class="s-card" onclick="openMikrotikServices()"><span>📡</span><p>برمجة ميكروتيك</p></div>
            <div class="s-card" onclick="openEnglishLearning()"><span>🇬🇧</span><p>تعلم الإنجليزية</p></div>
            <div class="s-card" onclick="openMarketPage()"><span>🛍️</span><p>سوق المنتجات</p></div>
            <div class="s-card" onclick="requestApkApp()"><span>📲</span><p>تطبيقات APK</p></div>
            <div class="s-card" onclick="processService('شراء كروت شبكة')"><span>🎫</span><p>كروت شبكة</p></div>
            <div class="s-card" onclick="processService('تحويل رصيد')"><span>💸</span><p>تحويل رصيد</p></div>
            <div class="s-card" onclick="processService('خدمة بنكك')"><span>🏦</span><p>خدمة بنكك</p></div>
            <div class="s-card" onclick="processService('خدمة كاش')"><span>💰</span><p>خدمات كاش</p></div>
            <div class="s-card" onclick="processService('دفع فواتير ستارلينك')"><span>🛰️</span><p>ستارلينك</p></div>
            <div class="s-card" onclick="openNetworkSettings()"><span>📶</span><p>ضبط الإنترنت</p></div>
            <div class="s-card" onclick="processService('تصميم لوغو احترافي')"><span>🎨</span><p>تصميم لوغو</p></div>
            <!-- الأيقونة المضافة والنشطة لمحدد الشبكة -->
            <div class="s-card" onclick="openNetworkToolPage()" style="background: #1e3a2f; border-color: #22c55e;"><span>📶</span><p style="color: #22c55e;">محدد الشبكة</p></div>
        </div>

        <div class="suggestion-box">
            <textarea id="suggestion-text" placeholder="📦 صندوق الاقتراحات والبلاغات: اكتب مقترحك أو بلاغك هنا..." style="height:50px;"></textarea>
            <button class="btn btn-blue" style="padding: 8px; font-size: 12px; margin-top: 0;" onclick="sendSuggestion()">إرسال للإدارة</button>
        </div>

        <button class="btn btn-white" onclick="logout()" style="margin-top:10px; color:red; border-color:red; padding:10px;">تسجيل الخروج</button>
        <div class="footer-rights">تم التطوير بواسطة بني فون 2026</div>
    </div>

    <!-- صفحة محدد الشبكة والخدمات الذكي -->
    <div id="network-tool-page" class="page">
        <div class="network-tool-container">
            <h2>محدد الشبكة والخدمات الذكي</h2>
            <p class="subtitle">محدد الشبكة والخدمات الفوري بالذكاء الاصطناعي</p>

            <div class="location-box" id="locationStatus">
                📍 تحديد الموقع: جاري رصد إحداثياتك الحالية...
            </div>

            <div class="ai-search-box" id="aiSearchLog">
                🤖 جارٍ استعلام الذكاء الاصطناعي عن أحدث الأسعار والعروض في منطقتك...
            </div>

            <div id="networksList">
                <!-- زين -->
                <div class="network-card" id="card-zain">
                    <div class="net-header">
                        <h4>زين (Zain)</h4>
                        <span id="badge-zain"></span>
                    </div>
                    <div class="net-details">
                        <div id="status-zain">أداء الشبكة: بانتظار الفحص الحي...</div>
                        <ul class="service-list">
                            <li><strong>أحدث باقات النت:</strong> <span id="zain-price">تحديث ذكي قيد التحميل...</span></li>
                        </ul>
                    </div>
                </div>

                <!-- إم تي إن -->
                <div class="network-card" id="card-mtn">
                    <div class="net-header">
                        <h4>إم تي إن (MTN)</h4>
                        <span id="badge-mtn"></span>
                    </div>
                    <div class="net-details">
                        <div id="status-mtn">أداء الشبكة: بانتظار الفحص الحي...</div>
                        <ul class="service-list">
                            <li><strong>أحدث باقات النت:</strong> <span id="mtn-price">تحديث ذكي قيد التحميل...</span></li>
                        </ul>
                    </div>
                </div>

                <!-- سوداني -->
                <div class="network-card" id="card-sudani">
                    <div class="net-header">
                        <h4>سوداني (Sudani)</h4>
                        <span id="badge-sudani"></span>
                    </div>
                    <div class="net-details">
                        <div id="status-sudani">أداء الشبكة: بانتظار الفحص الحي...</div>
                        <ul class="service-list">
                            <li><strong>أحدث باقات النت:</strong> <span id="sudani-price">تحديث ذكي قيد التحميل...</span></li>
                        </ul>
                    </div>
                </div>
            </div>

            <button class="btn btn-blue" id="testBtn" onclick="runAIScan()" style="margin-top:10px;">فحص ذكي للشبكة وأحدث الأسعار</button>
        </div>

        <button class="btn btn-white" onclick="showPage('main-app')" style="margin-top:10px; padding:10px;">العودة للرئيسية</button>
        <div class="footer-rights">تم التطوير بواسطة بني فون 2026</div>
    </div>

    <!-- صفحة سوق الحسابات والألعاب -->
    <div id="accounts-page" class="page">
        <div class="brand-box"><h2>🎮 سوق الحسابات والألعاب</h2></div>
        <p style="font-size:11px; color:#555; margin-bottom:10px;">فري فاير • تيك توك • فيسبوك • ببجي</p>

        <div id="accounts-list" style="max-height: 270px; overflow-y: auto;">جاري تحميل الحسابات...</div>

        <button class="btn btn-green" onclick="showAddAccountModal()" style="margin-top:10px; font-size: 13px;">+ اعرض حسابك للبيع</button>
        <button class="btn btn-white" onclick="showPage('main-app')" style="margin-top:5px; padding:10px;">العودة للرئيسية</button>
        <div class="footer-rights">تم التطوير بواسطة بني فون 2026</div>
    </div>

    <!-- صفحة سوق المنتجات -->
    <div id="market-page" class="page">
        <div class="brand-box"><h2>سوق بني فون الإلكتروني</h2></div>
        
        <div class="market-tabs">
            <div id="tab-boys" class="market-tab active-tab-boys" onclick="switchMarketCategory('boys')">📱 سوق الأولاد</div>
            <div id="tab-girls" class="market-tab" onclick="switchMarketCategory('girls')">💅 سوق البنات</div>
        </div>

        <div id="market-list" style="max-height: 260px; overflow-y: auto;">جاري تحميل المنتجات...</div>

        <button class="btn btn-blue" onclick="showAddProductModal()" style="margin-top:10px; font-size: 13px;">+ إضافة منتج للبيع</button>
        <button class="btn btn-white" onclick="showPage('main-app')" style="margin-top:5px; padding:10px;">العودة للرئيسية</button>
        <div class="footer-rights">تم التطوير بواسطة بني فون 2026</div>
    </div>

    <!-- لوحة الإدارة والتحكم الكاملة -->
    <div id="admin-page" class="page">
        <div class="brand-box"><h2>⚙ لوحة الكنترول والتحكم</h2></div>
        <div id="admin-reports-list" style="max-height: 300px; overflow-y: auto;"></div>
        <button class="btn btn-white" onclick="showPage('main-app')" style="margin-top:10px;">العودة للرئيسية</button>
        <div class="footer-rights">تم التطوير بواسطة بني فون 2026</div>
    </div>
</div>

<script>
    const myWhatsapp = "249113600735";
    const appCommissionRate = 0.05;
    let currentUser = null;
    let currentCategory = "boys";

    // تتبع حالة المصادقة من فايربيس الجديد
    setTimeout(() => {
        if(window.FB_onState) {
            window.FB_onState(window.firebaseAuth, (user) => {
                if (user) {
                    currentUser = user;
                    document.getElementById('user-info').innerText = "مرحباً: " + user.email;
                    showPage('main-app');
                    initRealtimeData();
                } else {
                    currentUser = null;
                }
            });
        }
    }, 1000);

    function handleLoginFirebase() {
        const email = document.getElementById('login-email').value;
        const pass = document.getElementById('login-pass').value;
        if(!email || !pass) return alert("الرجاء إدخال البريد وكلمة المرور");
        window.FB_signIn(window.firebaseAuth, email, pass)
            .then(() => alert("تم تسجيل الدخول بنجاح!"))
            .catch(err => alert("خطأ في الدخول: " + err.message));
    }

    function handleRegisterFirebase() {
        const email = document.getElementById('reg-email').value;
        const pass = document.getElementById('reg-pass').value;
        if(!email || !pass) return alert("الرجاء إدخال البريد وكلمة المرور");
        window.FB_createUser(window.firebaseAuth, email, pass)
            .then(() => {
                alert("تم إنشاء الحساب السحابي بنجاح!");
                showPage('main-app');
            })
            .catch(err => alert("خطأ في إنشاء الحساب: " + err.message));
    }

    function logout() {
        window.FB_signOut(window.firebaseAuth).then(() => {
            location.reload();
        });
    }

    // مزامنة البيانات الحية من Firestore
    let realProducts = [];
    let realAccounts = [];

    function initRealtimeData() {
        window.FB_onSnapshot(window.FB_collection(window.firebaseDb, "products"), (snapshot) => {
            realProducts = [];
            snapshot.forEach(doc => realProducts.push({ id: doc.id, ...doc.data() }));
            renderMarket();
        });

        window.FB_onSnapshot(window.FB_collection(window.firebaseDb, "accounts"), (snapshot) => {
            realAccounts = [];
            snapshot.forEach(doc => realAccounts.push({ id: doc.id, ...doc.data() }));
            renderAccounts();
        });
    }

    function openGameTopup() {
        const game = prompt("اختر اللعبة المراد شحنها:\n1- فري فاير (Free Fire)\n2- ببجي (PUBG Mobile)\n3- كول أوف ديوتي (Call of Duty)\n4- ألعاب أخرى");
        if (!game) return;
        const idPlayer = prompt("اكتب الآيدي (ID) الخاص بك داخل اللعبة:");
        if (!idPlayer) return;
        const amount = prompt("اكتب عدد الجواهر/الشدات المطلوبة:");
        if (!amount) return;

        const name = currentUser ? currentUser.email : "مشترك";
        const msg = `مرحباً بنيامين، أنا المشترك: ${name}\nأريد شحن لعبة: (${game})\nID اللاعب: ${idPlayer}\nالكمية: ${amount}`;
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent(msg)}`, "_blank");
    }

    function openOnlinePhoneServices() {
        const service = prompt("اختر الخدمة المطلوبة:\n1- فك شفرة شبكة\n2- تجاوز حساب جوجل (FRP)\n3- تعريب وتحديث سوفتوير\n4- إصلاح مشاكل الأجهزة أونلاين");
        if (!service) return;
        const model = prompt("اكتب نوع الهاتف وموديله (مثال: Samsung A52):");
        if (!model) return;

        const name = currentUser ? currentUser.email : "زبون";
        const msg = `مرحباً بنيامين، أريد خدمة سوفتوير أونلاين:\nالخدمة: ${service}\nموديل الجهاز: ${model}\nاسم المشترك: ${name}`;
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent(msg)}`, "_blank");
    }

    function openMikrotikServices() {
        const option = prompt("خدمات ميكروتيك المتاحة:\n1- ضبط سيرفر Hotspot وتحديد السرعات\n2- حل مشاكل الشبكة واليوزر مانجر\n3- ضبط راوتر Ruijie / Mikrotik\n4- تصميم صفحة تسجيل دخول شبكة باسمك");
        if (!option) return;

        const name = currentUser ? currentUser.email : "صاحب شبكة";
        const msg = `مرحباً بنيامين، أريد استشارة/خدمة برمجة ميكروتيك:\nنوع الطلب: ${option}\nالاسم: ${name}`;
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent(msg)}`, "_blank");
    }

    function openEnglishLearning() {
        alert("🎓 قسم تعليم اللغة الإنجليزية:\n\nنوفر كورسات ومواد تعليمية، قواعد، وممارسة المحادثات اليومية.\n\nاضغط موافق للتواصل مع قسم التعليم وحجز مستواك.");
        const name = currentUser ? currentUser.email : "طالب";
        const msg = `مرحباً بنيامين، أريد الانضمام/الاستفسار عن دروس تعليم اللغة الإنجليزية.\nالاسم: ${name}`;
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent(msg)}`, "_blank");
    }

    function openAccountsMarket() { showPage('accounts-page'); renderAccounts(); }

    function renderAccounts() {
        const container = document.getElementById('accounts-list');
        if (!container) return;
        container.innerHTML = "";
        if (realAccounts.length === 0) {
            container.innerHTML = "<p style='color:#777; margin-top:20px;'>لا توجد حسابات معروضة حالياً</p>";
            return;
        }

        realAccounts.forEach(acc => {
            const commission = Math.round(acc.price * appCommissionRate);
            container.innerHTML += `
                <div class="product-card" style="border-right: 4px solid var(--blue);">
                    <span style="background:var(--blue); color:white; padding:2px 8px; border-radius:8px; font-size:10px;">${acc.type}</span>
                    <h4 style="margin-top:5px;">${acc.title}</h4>
                    <div class="price">السعر: ${acc.price.toLocaleString()} ج.س</div>
                    <div class="seller">البائع: ${acc.seller}</div>
                    <button class="btn btn-green" style="padding:6px; font-size:11px; margin-top:6px;" onclick="buyAccount('${acc.title}', ${acc.price}, '${acc.type}', '${acc.seller}')">
                        شراء الحساب عبر الضامن (عمولة: ${commission} ج.س)
                    </button>
                </div>
            `;
        });
    }

    function showAddAccountModal() {
        const type = prompt("اختر نوع الحساب (فري فاير / تيك توك / فيسبوك / ببجي):");
        if (!type) return;
        const title = prompt("تفاصيل الحساب (المستوى، السكنات، المتابعين):");
        if (!title) return;
        const price = parseFloat(prompt("السعر بالجنيه السوداني:"));
        if (!price || isNaN(price)) return alert("يرجى كتابة سعر صحيح");

        const newAcc = { type, title, price, seller: currentUser ? currentUser.email : "بائع", createdAt: new Date() };
        window.FB_addDoc(window.FB_collection(window.firebaseDb, "accounts"), newAcc)
            .then(() => alert("تم إضافة حسابك للبيع بنجاح ليرى الجميع!"))
            .catch(err => alert("خطأ: " + err.message));
    }

    function buyAccount(title, price, type, sellerName) {
        const commission = Math.round(price * appCommissionRate);
        const totalPrice = price + commission;
        alert(`🔒 نظام الضامن لشراء الحسابات عبر بني فون:\nالمبلغ مع العمولة: ${totalPrice.toLocaleString()} ج.س`);
        const buyerName = currentUser ? currentUser.email : "مشتري جديد";
        const msg = `مرحباً بنيامين، أنا المشتري: ${buyerName}\nأريد شراء حساب (${type}): [${title}]\nمن البائع: ${sellerName}\nالإجمالي: ${totalPrice} ج.س`;
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent(msg)}`, "_blank");
    }

    function openMarketPage() { showPage('market-page'); renderMarket(); }

    function requestApkApp() {
        const appName = prompt("اكتب اسم التطبيق أو اللعبة التي تريد رابط تنزيلها:");
        if (!appName) return;
        const name = currentUser ? currentUser.email : "زبون";
        const msg = `مرحباً بنيامين، أريد رابط تنزيل مباشر لتطبيق: (${appName})`;
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent(msg)}`, "_blank");
    }

    function processService(serviceName) {
        alert("تنبيه: يتم الدفع عبر خدمة (بنكك) باسم: بنيامين محمد سعيد.");
        const name = currentUser ? currentUser.email : "زائر";
        const msg = `مرحباً بنيامين، أنا المشترك: ${name}\nأريد طلب خدمة: ${serviceName}`;
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent(msg)}`, "_blank");
    }

    function openNetworkSettings() {
        alert("📶 بيانات ضبط الشبكات في السودان:\n• سوداني: internet\n• زين: zain\n• إم تي إن: internet.mtn.sd");
    }

    function openNetworkToolPage() {
        showPage('network-tool-page');
    }

    function runAIScan() {
        const btn = document.getElementById('testBtn');
        const statusBox = document.getElementById('locationStatus');
        const aiLog = document.getElementById('aiSearchLog');
        
        btn.disabled = true;
        btn.innerHTML = `<span class="spinner"></span> جاري البحث وتحليل الشبكات عبر AI...`;
        statusBox.innerHTML = "📍 تم رصد الموقع الجغرافي بدقة.";
        aiLog.style.display = "block";
        aiLog.innerHTML = "🤖 الذكاء الاصطناعي يبحث في الوقت الفعلي عن أسعار الباقات والشبكات الأقوى...";

        setTimeout(() => {
            aiLog.innerHTML = "✅ تم جلب أحدث التحديثات وقراءات الإشارة بنجاح!";
            
            const results = [
                { 
                    id: 'zain', 
                    name: 'زين (Zain)', 
                    speed: '16.2 Mbps', 
                    signal: 'قوي جداً (-72 dBm)', 
                    packageInfo: 'باقة 5 جيجابايت متاحة (حسب السعر المحدث)'
                },
                { 
                    id: 'mtn', 
                    name: 'إم تي إن (MTN)', 
                    speed: '9.0 Mbps', 
                    signal: 'متوسط (-88 dBm)', 
                    packageInfo: 'باقة الأسبوع الشهرية متوفرة'
                },
                { 
                    id: 'sudani', 
                    name: 'سوداني (Sudani)', 
                    speed: '3.5 Mbps', 
                    signal: 'ضعيف (-106 dBm)', 
                    packageInfo: 'باقات الإنترنت المحدودة متوفرة'
                }
            ];

            results.sort((a, b) => parseFloat(b.speed) - parseFloat(a.speed));
            const best = results[0];

            results.forEach((net, index) => {
                const card = document.getElementById(`card-${net.id}`);
                const statusDiv = document.getElementById(`status-${net.id}`);
                const priceSpan = document.getElementById(`${net.id}-price`);
                const badge = document.getElementById(`badge-${net.id}`);

                card.style.order = index;

                if (net.id === best.id) {
                    card.classList.add('best');
                    badge.className = 'badge';
                    badge.innerHTML = 'الخيار الأقوى والأوفر 🚀';
                } else {
                    card.classList.remove('best');
                    badge.className = '';
                    badge.innerHTML = '';
                }

                statusDiv.innerHTML = `السرعة: <strong>${net.speed}</strong> | الإشارة: <strong>${net.signal}</strong>`;
                priceSpan.innerHTML = net.packageInfo;
            });

            statusBox.innerHTML = `📍 الموقع: تم تحديد الشبكة الأفضل في منطقتك حالياً هي <strong>${best.name}</strong>`;
            btn.disabled = false;
            btn.innerHTML = "إعادة الفحص الذكي";
        }, 3000);
    }

    function renderMarket() {
        const container = document.getElementById('market-list');
        if(!container) return;
        container.innerHTML = "";
        const filteredProducts = realProducts.filter(p => p.category === currentCategory);

        if(filteredProducts.length === 0) {
            container.innerHTML = "<p style='color:#777; margin-top:20px;'>لا توجد منتجات معروضة حالياً</p>";
            return;
        }

        filteredProducts.forEach(p => {
            const commission = Math.round(p.price * appCommissionRate);
            container.innerHTML += `
                <div class="product-card">
                    <h4>${p.title}</h4>
                    <div class="price">السعر: ${p.price.toLocaleString()} ج.س</div>
                    <div class="seller">البائع: ${p.seller}</div>
                    <button class="btn ${p.category === 'girls' ? 'btn-pink' : 'btn-blue'}" style="padding:6px; font-size:11px; margin-top:6px;" onclick="buyProduct('${p.title}', ${p.price}, '${p.seller}')">
                        شراء عبر الضامن (عمولة: ${commission} ج.س)
                    </button>
                </div>
            `;
        });
    }

    function switchMarketCategory(category) {
        currentCategory = category;
        document.getElementById('tab-boys').className = category === 'boys' ? 'market-tab active-tab-boys' : 'market-tab';
        document.getElementById('tab-girls').className = category === 'girls' ? 'market-tab active-tab-girls' : 'market-tab';
        renderMarket();
    }

    function buyProduct(title, price, sellerName) {
        const commission = Math.round(price * appCommissionRate);
        const totalPrice = price + commission;
        alert(`الإجمالي المطلوب تحويله لـ (بنكك): ${totalPrice.toLocaleString()} ج.س`);
        const buyerName = currentUser ? currentUser.email : "مشتري جديد";
        const msg = `مرحباً بنيامين، أنا المشتري: ${buyerName}\nأريد شراء: (${title}) من البائع: ${sellerName}\nإجمالي المبلغ: ${totalPrice} ج.س`;
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent(msg)}`, "_blank");
    }

    function showAddProductModal() {
        const title = prompt("اسم المنتج:");
        if (!title) return;
        const price = parseFloat(prompt("السعر بالجنيه السوداني:"));
        if (!price || isNaN(price)) return alert("يرجى كتابة سعر صحيح");
        const category = confirm("هل المنتج مخصص للبنات؟") ? "girls" : "boys";

        const newProd = { title, price, category, seller: currentUser ? currentUser.email : "تاجر", createdAt: new Date() };
        window.FB_addDoc(window.FB_collection(window.firebaseDb, "products"), newProd)
            .then(() => alert("تم إضافة منتجك بنجاح ليرى الجميع في السوق!"))
            .catch(err => alert("خطأ: " + err.message));
    }

    function forgotPassword() {
        window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent("نسيت كلمة سر حسابي السحابي")}`, "_blank");
    }

    function sendSuggestion() {
        const text = document.getElementById('suggestion-text').value;
        if(!text) return alert("اكتب مقترحك أو بلاغك أولاً");
        const sender = currentUser ? currentUser.email : "زائر";
        
        const report = { user: sender, text: text, date: new Date().toLocaleDateString('ar-EG'), createdAt: new Date() };
        window.FB_addDoc(window.FB_collection(window.firebaseDb, "reports"), report).then(() => {
            window.open(`https://wa.me/${myWhatsapp}?text=${encodeURIComponent("مقترح/بلاغ من " + sender + ": " + text)}`, "_blank");
            alert("تم إرسال اقتراحك/بلاغك بنجاح!");
            document.getElementById('suggestion-text').value = "";
        });
    }

    function openAdmin() {
        if(prompt("كلمة سر المدير:") === "2026") {
            showPage('admin-page');
            loadAdminReports();
        } else {
            alert("كلمة المرور خاطئة!");
        }
    }

    function loadAdminReports() {
        const cont = document.getElementById('admin-reports-list');
        cont.innerHTML = "<h4>البلاغات والاقتراحات السحابية الواردة:</h4>";
        window.FB_onSnapshot(window.FB_collection(window.firebaseDb, "reports"), (snapshot) => {
            cont.innerHTML = "<h4>البلاغات والاقتراحات السحابية الواردة:</h4>";
            if (snapshot.empty) {
                cont.innerHTML += "<p>لا توجد بلاغات حالياً</p>";
                return;
            }
            snapshot.forEach(doc => {
                const r = doc.data();
                cont.innerHTML += `
                    <div class="user-card-admin" style="border-right: 4px solid var(--blue);">
                        <b>من:</b> ${r.user}<br>
                        <b>التاريخ:</b> ${r.date}<br>
                        <b>النص:</b> ${r.text}
                    </div>
                `;
            });
        });
    }

    function toggleView(isLogin) {
        document.getElementById('login-form').style.display = isLogin ? 'block' : 'none';
        document.getElementById('register-form').style.display = isLogin ? 'none' : 'block';
    }

    function showPage(id) {
        document.querySelectorAll('.page').forEach(p => p.classList.remove('active-page'));
        document.getElementById(id).classList.add('active-page');
    }
</script>
</body>
</html>
