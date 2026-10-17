---
layout: home
list_title: "blog list"
---

<style>
.home-intro {
  display: flex;
  align-items: flex-start;
  gap: 28px;
  margin-bottom: 32px;
}

.home-intro-text {
  flex: 1;
  min-width: 0;
}

.home-intro-photo {
  width: 180px;
  max-width: 100%;
  height: auto;
  flex-shrink: 0;
  border-radius: 12px;
  display: block;
}

@media (max-width: 600px) {
  .home-intro {
    flex-direction: column;
  }

  .home-intro-photo {
    width: 160px;
  }
}
</style>

<div class="home-intro">
  <div class="home-intro-text">
    <p>Welcome to my blog!</p>

    <p>I'm <strong>Felyne<strong>, currently a first-year master student of Shanghai top3 University, majoring in automation.</p>

    <p>Maybe my field of my study is VLA, referring to vision-language-action, a quiet popular topic recently. However, i'm a totally layman of research and not interested in it at all.</p>

    <p>-Forgiving me for not revealing the specific school, i don't want to show too much information online.</p>

    <p>For a detailed introduction about me, just click the "about me" link in the top-right corner.</p>

    <p>I write this blog just for fun, hoping everyone will enjoy it:)))))))</p>
  </div>

  <img
    class="home-intro-photo"
    src="{{ '/assets/images/photo.jpg' | relative_url }}"
    alt="My photo"
  >
</div>
