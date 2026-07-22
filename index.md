<!doctype html>
<html lang="vi">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta
      name="description"
      content="Chính sách quyền riêng tư song ngữ của ứng dụng Sổ Niệm Phật (Chanting Counter)."
    />
    <meta name="color-scheme" content="dark" />
    <meta name="theme-color" content="#0b0b0a" />
    <title>Chính sách quyền riêng tư | Privacy Policy</title>
    <style>
      :root {
        color-scheme: dark;
        --background: #080806;
        --surface: rgba(21, 18, 14, 0.94);
        --surface-soft: rgba(31, 25, 18, 0.78);
        --gold: #e1ad55;
        --gold-bright: #f5d58d;
        --text: #ead7ad;
        --muted: #aa9d87;
        --border: #5f482a;
        --shadow: rgba(0, 0, 0, 0.35);
      }

      * {
        box-sizing: border-box;
      }

      html {
        scroll-behavior: smooth;
      }

      body {
        margin: 0;
        min-height: 100vh;
        background:
          radial-gradient(circle at 50% 0%, rgba(109, 77, 35, 0.2), transparent 34rem),
          linear-gradient(180deg, #11100d 0%, var(--background) 45%, #050504 100%);
        color: var(--text);
        font-family: Georgia, "Times New Roman", serif;
        line-height: 1.65;
      }

      a {
        color: var(--gold-bright);
      }

      a:focus-visible {
        outline: 2px solid var(--gold-bright);
        outline-offset: 4px;
      }

      .page-shell {
        width: min(1120px, calc(100% - 32px));
        margin: 0 auto;
        padding: 56px 0 64px;
      }

      .hero {
        margin-bottom: 30px;
        text-align: center;
      }

      .cover {
        overflow: hidden;
        margin: 0 0 30px;
        border: 1px solid var(--border);
        border-radius: 24px;
        background: var(--surface);
        box-shadow: 0 24px 60px var(--shadow);
      }

      .cover img {
        display: block;
        width: 100%;
        height: auto;
        aspect-ratio: 16 / 9;
        object-fit: cover;
      }

      .eyebrow {
        margin: 0 0 8px;
        color: var(--gold);
        font-family: Arial, Helvetica, sans-serif;
        font-size: 0.78rem;
        font-weight: 700;
        letter-spacing: 0.18em;
        text-transform: uppercase;
      }

      h1 {
        margin: 0;
        color: var(--gold-bright);
        font-size: clamp(2rem, 5vw, 3.6rem);
        font-weight: 500;
        line-height: 1.18;
      }

      .subtitle {
        max-width: 680px;
        margin: 14px auto 0;
        color: var(--muted);
        font-family: Arial, Helvetica, sans-serif;
        font-size: 0.98rem;
      }

      .language-nav {
        display: flex;
        justify-content: center;
        gap: 10px;
        margin-top: 24px;
      }

      .language-nav a {
        min-width: 120px;
        padding: 9px 16px;
        border: 1px solid var(--border);
        border-radius: 999px;
        background: var(--surface-soft);
        color: var(--gold-bright);
        font-family: Arial, Helvetica, sans-serif;
        font-size: 0.88rem;
        font-weight: 700;
        text-decoration: none;
      }

      .language-nav a:hover {
        border-color: var(--gold);
        background: rgba(93, 66, 31, 0.42);
      }

      .policies {
        display: grid;
        grid-template-columns: 1fr;
        gap: 22px;
        align-items: start;
      }

      .policy {
        overflow: hidden;
        border: 1px solid var(--border);
        border-radius: 24px;
        background: var(--surface);
        box-shadow: 0 24px 60px var(--shadow);
      }

      .policy-header {
        padding: 26px 28px 22px;
        border-bottom: 1px solid rgba(95, 72, 42, 0.72);
        background: linear-gradient(135deg, rgba(104, 74, 33, 0.26), transparent);
      }

      .language-label {
        display: inline-block;
        margin-bottom: 8px;
        color: var(--gold);
        font-family: Arial, Helvetica, sans-serif;
        font-size: 0.75rem;
        font-weight: 800;
        letter-spacing: 0.14em;
        text-transform: uppercase;
      }

      h2 {
        margin: 0;
        color: var(--gold-bright);
        font-size: clamp(1.55rem, 3vw, 2rem);
        font-weight: 600;
        line-height: 1.25;
      }

      .updated {
        margin: 9px 0 0;
        color: var(--muted);
        font-family: Arial, Helvetica, sans-serif;
        font-size: 0.82rem;
      }

      .policy-body {
        padding: 8px 28px 28px;
      }

      .intro {
        margin: 18px 0 22px;
        font-size: 1.02rem;
      }

      .policy section {
        padding: 18px 0;
        border-top: 1px solid rgba(95, 72, 42, 0.46);
      }

      h3 {
        margin: 0 0 7px;
        color: var(--gold-bright);
        font-size: 1.08rem;
        font-weight: 700;
      }

      p {
        margin: 0;
      }

      footer {
        margin-top: 30px;
        color: var(--muted);
        font-family: Arial, Helvetica, sans-serif;
        font-size: 0.82rem;
        text-align: center;
      }

      @media (max-width: 820px) {
        .page-shell {
          padding-top: 36px;
        }

        .policies {
          grid-template-columns: 1fr;
        }
      }

      @media (max-width: 520px) {
        .page-shell {
          width: min(100% - 20px, 1120px);
          padding-top: 28px;
        }

        .language-nav {
          flex-direction: column;
          align-items: stretch;
        }

        .language-nav a {
          text-align: center;
        }

        .cover {
          margin-bottom: 20px;
          border-radius: 18px;
        }

        .policy-header,
        .policy-body {
          padding-right: 20px;
          padding-left: 20px;
        }
      }

      @media (prefers-reduced-motion: reduce) {
        html {
          scroll-behavior: auto;
        }
      }
    </style>
  </head>
  <body>
    <main class="page-shell">
      <header class="hero">
        <figure class="cover">
          <img
            src="assets/policy-cover.jpg"
            alt="MGM Studio — Ideas, Code, Play"
            width="2048"
            height="1152"
            fetchpriority="high"
            decoding="async"
          />
        </figure>

        <p class="eyebrow">Sổ Niệm Phật · Chanting Counter</p>
        <h1>Chính sách quyền riêng tư<br />Privacy Policy</h1>
        <p class="subtitle">
          Chính sách song ngữ dành cho ứng dụng Sổ Niệm Phật (Chanting Counter).
        </p>
        <nav class="language-nav" aria-label="Chọn ngôn ngữ · Choose a language">
          <a href="#tieng-viet">Tiếng Việt</a>
          <a href="#english">English</a>
        </nav>
      </header>

      <div class="policies">
        <article class="policy" id="tieng-viet" lang="vi">
          <header class="policy-header">
            <span class="language-label">Tiếng Việt</span>
            <h2>Chính sách quyền riêng tư</h2>
            <p class="updated">Cập nhật lần cuối: 21/07/2026</p>
          </header>
          <div class="policy-body">
            <p class="intro">
              Sổ Niệm Phật tôn trọng quyền riêng tư của bạn. Ứng dụng được thiết kế để
              hoạt động ngoại tuyến và không yêu cầu tài khoản.
            </p>

            <section>
              <h3>Dữ liệu lưu trên thiết bị</h3>
              <p>
                Số đếm, lịch sử thực hành, mục tiêu, tùy chọn âm thanh, ngôn ngữ và các
                cài đặt khác được lưu cục bộ trên thiết bị. Chúng tôi không truyền những
                thông tin này đến máy chủ.
              </p>
            </section>

            <section>
              <h3>Ảnh và hình nền tùy chỉnh</h3>
              <p>
                Nếu bạn chọn hình nền riêng, ảnh được sao chép vào vùng lưu trữ riêng
                của ứng dụng trên thiết bị. Sổ Niệm Phật không tải ảnh này lên mạng.
              </p>
            </section>

            <section>
              <h3>Dịch vụ bên ngoài</h3>
              <p>
                Ko-fi, PayPal và ứng dụng email được mở bên ngoài Sổ Niệm Phật. Thông
                tin bạn cung cấp cho các dịch vụ này tuân theo chính sách quyền riêng
                tư riêng của họ.
              </p>
            </section>

            <section>
              <h3>Quyền riêng tư của trẻ em</h3>
              <p>
                Sổ Niệm Phật không chủ ý thu thập thông tin cá nhân của trẻ em hoặc bất
                kỳ người dùng nào.
              </p>
            </section>

            <section>
              <h3>Thay đổi chính sách</h3>
              <p>
                Chính sách này có thể được cập nhật khi ứng dụng thay đổi. Phiên bản
                mới nhất và ngày cập nhật sẽ được hiển thị tại đây.
              </p>
            </section>

            <section>
              <h3>Liên hệ</h3>
              <p>
                Nếu có câu hỏi về quyền riêng tư, vui lòng liên hệ
                <a href="mailto:support.mgm.studio@gmail.com">support.mgm.studio@gmail.com</a>.
              </p>
            </section>
          </div>
        </article>

        <article class="policy" id="english" lang="en">
          <header class="policy-header">
            <span class="language-label">English</span>
            <h2>Privacy Policy</h2>
            <p class="updated">Last updated: July 21, 2026</p>
          </header>
          <div class="policy-body">
            <p class="intro">
              Chanting Counter respects your privacy. The app is designed to work
              offline and does not require an account.
            </p>

            <section>
              <h3>Data stored on your device</h3>
              <p>
                Your counts, practice history, goals, sound preferences, language and
                other settings are stored locally on your device. We do not transmit
                this information to our servers.
              </p>
            </section>

            <section>
              <h3>Photos and custom backgrounds</h3>
              <p>
                If you choose a custom background, the selected image is copied to the
                app’s private storage on your device. It is not uploaded by Chanting
                Counter.
              </p>
            </section>

            <section>
              <h3>External services</h3>
              <p>
                Ko-fi, PayPal and your email app open outside Chanting Counter.
                Information you provide to those services is handled under their own
                privacy policies.
              </p>
            </section>

            <section>
              <h3>Children’s privacy</h3>
              <p>
                Chanting Counter does not knowingly collect personal information from
                children or any other users.
              </p>
            </section>

            <section>
              <h3>Changes to this policy</h3>
              <p>
                We may update this policy when the app changes. The latest version and
                update date will be shown here.
              </p>
            </section>

            <section>
              <h3>Contact</h3>
              <p>
                For privacy questions, contact
                <a href="mailto:support.mgm.studio@gmail.com">support.mgm.studio@gmail.com</a>.
              </p>
            </section>
          </div>
        </article>
      </div>

      <footer>© 2026 MGM Studio</footer>
    </main>
  </body>
</html>
