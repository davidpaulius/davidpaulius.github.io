---
title: "Fun Stuff 🏋️"
author: "David Paulius"
description: "This is an overview of David Paulius, Ph.D."
summary: "Random things that fascinate me that are not relevant to my own research or work. :)"
showToc: false
disableAnchoredHeadings: true
ShowReadingTime: false
hideMeta: true
hideSummary: false

---


<style>
/* ── News Tab System ── */
.news-tabs {
    margin-top: 1.5rem;
}

.news-tab-list {
    display: flex;
    flex-wrap: wrap;
    gap: 6px;
    margin-bottom: 1.25rem;
    border-bottom: 2px solid var(--border);
    padding-bottom: 10px;
}

.news-tab-btn {
    padding: 6px 16px;
    border: none;
    border-radius: var(--radius);
    cursor: pointer;
    font-size: 14px;
    font-weight: 600;
    font-family: inherit;
    transition: background 0.2s ease, color 0.2s ease, transform 0.1s ease;
    background: var(--tertiary);
    color: var(--primary);
    opacity: 0.55;
}

.news-tab-btn:hover {
    opacity: 0.8;
    transform: translateY(-1px);
}

.news-tab-btn.active {
    opacity: 1;
    transform: translateY(-1px);
    box-shadow: 0 2px 8px rgba(0,0,0,0.12);
}

/* Per-year accent colours that match the existing CSS variables */
.news-tab-btn[data-year="green"].active { background: var(--green); }
.news-tab-btn[data-year="blue"].active { background: var(--blue); }
.news-tab-panel {
    display: none;
}

.news-tab-panel.active {
    display: block;
    animation: fadeInTab 0.25s ease;
}

@keyframes fadeInTab {
    from { opacity: 0; transform: translateY(6px); }
    to   { opacity: 1; transform: translateY(0); }
}

/* Make the news tables cleaner inside tabs */
.news-tab-panel table {
    width: 100%;
    border-collapse: collapse;
    margin-bottom: 0 !important;
}

.news-tab-panel table tr td {
    border-bottom: 1px solid var(--border);
    padding: 10px 6px !important;
    vertical-align: top;
}

.news-tab-panel table tr:last-child td {
    border-bottom: none;
}
</style>

<div class="news-tabs">

  <!-- Tab buttons -->
  <div class="news-tab-list" role="tablist" aria-label="News by year">
    <button class="news-tab-btn active" data-year="green" role="tab" aria-selected="true" aria-controls="panel-likes" id="tab-likes">My Likes</button>
    <button class="news-tab-btn"        data-year="blue" role="tab" aria-selected="false" aria-controls="panel-photography" id="tab-photography">Photography 📸</button>
  </div>

  <!-- Likes -->
  <div class="news-tab-panel active" id="panel-likes" role="tabpanel" aria-labelledby="tab-likes">
  <ul>
    <li>
        <span>I am a <b>huge</b> fan of the <a href="https://en.wikipedia.org/wiki/Fire_Emblem" target="_blank">Fire Emblem</a> (FE) video game series. My website's favicon is the <a href="https://fireemblem.fandom.com/wiki/Crest" target="_blank">Crest of Riegan</a> from the Fire Emblem: Three Houses game (<a href="https://www.merriam-webster.com/slang/iykyk" target="_blank">IYKYK</a>).</span>
    </li>
    <li>
        <span>I also enjoy other series like <a href="https://en.wikipedia.org/wiki/Final_Fantasy" target="_blank">Final Fantasy</a> [I've beat 1-6, 8, 13, 15, and Tactics Advance (1 & 2); 7 (OG and remakes) is WIP], <a href="https://en.wikipedia.org/wiki/Pok%C3%A9mon" target="_blank">Pokémon</a> [in addition to console games, I love Pokémon Go], and <a href="https://en.wikipedia.org/wiki/Ace_Attorney" target="_blank">Ace Attorney</a>. I also enjoy games like Sudoku and Chess (unrated). I don't play games as often as I used to, but I still enjoy them casually.</span>
    </li>
    <li>
        <span>I love comedy shows, such as:</span>
        <ul>
            <li>! British comedy: <a href="https://en.wikipedia.org/wiki/Taskmaster_(TV_series)" target="_blank">Taskmaster</a>, <a href="https://en.wikipedia.org/wiki/Peep_Show_(British_TV_series)" target="_blank">Peep Show</a>, <a href="https://en.wikipedia.org/wiki/The_IT_Crowd" target="_blank">The IT Crowd</a>, <a href="https://en.wikipedia.org/wiki/Would_I_Lie_to_You%3F_(game_show)" target="_blank">WILTY</a>, <a href="https://en.wikipedia.org/wiki/8_Out_of_10_Cats_Does_Countdown" target="_blank">Cats Countdown</a>, and many more.</li>
            <li>Sitcoms: Seinfeld, Curb Your Enthusiasm, It's Always Sunny in Philadelphia, Frasier, The Office (both US and UK), and many more.</li>
            <li>Cartoons: South Park, Archer, American Dad.</li>
        </ul>
    </li>
    <li>
        <span>I love movies, especially non-mainstream, indie, or classic ones. I am always looking for recommendations to add to my <a href="https://letterboxd.com/davi_duck/" target="_blank">Letterboxd</a>!</span>
    </li>
    <li>
        <span>I like listening to different genres of music. What I really love are:</span>
        <ul>
            <li>Classical music, especially <a href="https://en.wikipedia.org/wiki/Romantic_music">Romantic</a> music. My favourite composers are <a href="https://en.wikipedia.org/wiki/Anton%C3%ADn_Dvo%C5%99%C3%A1k">Dvořák</a>, <a href="https://en.wikipedia.org/wiki/Sergei_Rachmaninoff">Rachmaninoff</a>, and <a href="https://en.wikipedia.org/wiki/Claude_Debussy">Debussy</a> (in no particular order).</li>
            <li>70's and 80's music (rock, pop, disco, R&B, etc).</li>
            <li><a href="https://en.wikipedia.org/wiki/Soca_music">Soca</a> and <a href="https://en.wikipedia.org/wiki/Afrobeats">Afrobeats</a>.</li>
        </ul>
    </li>
  </div>

  <!-- Photography -->
  <div class="news-tab-panel" id="panel-photography" role="tabpanel" aria-labelledby="tab-photography">
    <h4>Check out more photos <a href="https://goo.gl/photos/r7VYNbVtMnBCmvsx6" target="_blank">here.</a> 🙂</h4>
    <p>These are just a few of my favourite shots taken with my Android phones (current phone: Pixel 7; previous phones: Nexus 6P, Pixel 2, Pixel 6). Most of these have been edited to some extent, but I try to retain some realism in their colours.
    </p>

<style>
/* ── Photography Gallery ── */

.photo-gallery {
    column-count: 3;
    column-gap: 12px;
    margin: 1.5rem 0;
}

@media (max-width: 700px) {
    .photo-gallery { column-count: 2; }
}
@media (max-width: 450px) {
    .photo-gallery { column-count: 1; }
}

.photo-item {
    break-inside: avoid;
    margin-bottom: 12px;
    overflow: hidden;
    border-radius: 10px;
    cursor: zoom-in;
    position: relative;
}

.photo-item img {
    width: 100%;
    display: block;
    border-radius: 10px;
    transition: transform 0.3s ease, filter 0.3s ease;
    margin: 0 !important;
}

.photo-item:hover img {
    transform: scale(1.03);
    filter: brightness(0.85);
}

/* ── Lightbox ── */
.photo-lightbox {
    display: none;
    position: fixed;
    inset: 0;
    z-index: 9999;
    background: rgba(0, 0, 0, 0.92);
    align-items: center;
    justify-content: center;
    flex-direction: column;
    animation: lbFadeIn 0.2s ease;
}

.photo-lightbox.open {
    display: flex;
}

@keyframes lbFadeIn {
    from { opacity: 0; }
    to   { opacity: 1; }
}

.photo-lightbox img {
    max-width: 90vw;
    max-height: 85vh;
    border-radius: 10px;
    object-fit: contain;
    box-shadow: 0 8px 48px rgba(0,0,0,0.8);
    margin: 0 !important;
    transition: opacity 0.2s ease;
}

.lb-counter {
    color: rgba(255,255,255,0.6);
    font-size: 13px;
    margin-top: 12px;
    letter-spacing: 1px;
    font-family: monospace;
}

.lb-nav {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background: rgba(255,255,255,0.12);
    border: none;
    color: white;
    font-size: 28px;
    width: 50px;
    height: 50px;
    border-radius: 50%;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: background 0.2s ease;
    line-height: 1;
}

.lb-nav:hover {
    background: rgba(255,255,255,0.28);
}

.lb-prev { left: 16px; }
.lb-next { right: 16px; }

.lb-close {
    position: absolute;
    top: 14px;
    right: 18px;
    background: none;
    border: none;
    color: rgba(255,255,255,0.8);
    font-size: 32px;
    cursor: pointer;
    line-height: 1;
    padding: 4px 8px;
    border-radius: 6px;
    transition: color 0.2s ease, background 0.2s ease;
}

.lb-close:hover {
    color: white;
    background: rgba(255,255,255,0.15);
}
</style>

<!-- Masonry photo grid -->
<div class="photo-gallery" id="photoGallery"></div>

<!-- Lightbox overlay -->
<div class="photo-lightbox" id="photoLightbox" role="dialog" aria-modal="true" aria-label="Photo viewer">
    <button class="lb-close" id="lbClose" title="Close (Esc)">&times;</button>
    <button class="lb-nav lb-prev" id="lbPrev" title="Previous (←)">&#8249;</button>
    <img src="" alt="Gallery photo" id="lbImg" referrerpolicy="no-referrer" />
    <button class="lb-nav lb-next" id="lbNext" title="Next (→)">&#8250;</button>
    <div class="lb-counter" id="lbCounter"></div>
</div>

<script>
(function () {
    /* ── Photo list ── */
    var photos = [
        "https://lh3.googleusercontent.com/pw/AIL4fc_tMYbCfDA1WIMeOoq1yT555_pRWvOT1gCZ1VoGAlDZZTSlpGkQkGnroA6z3el6NdTn2yqcOMk8y15A6RGWbTNpNK5eSClXM3uwLoBvVPRCVv9lVsWtdt3rk_QzboRzaqwXyzP0_OK9uZKu6lNhc_yKsQ=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc-sBWModD1vRVk9dbr06Knsacp5UrxgNA1G7NNzuzcZYXGLnBtZcve2TC7JaTAy-dpLT_ZRti4uq2HKmmO-lpCwtskexAGhzFa7Rs-wNSf_HuCjhbU4=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc-LsXpLTXoZyQ8IJMJ1yGOOcrZA8ypaPea5VpoexIGXTh9jWybVxQFo4GijOvPBM47ACfgjZGvsj_UNWOOiFu2YYnXQSWxQ1yDTSlhpowFoqYoR4H3d=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc-jVg0Iu8p7vyFEZXBQKL5X4b_LaYTT5vymteitOyYTkJojP9dIopeZKgBqJ6w2eDAy9dgfRdJfHLFQlSddD9lW0eUoeHz7ZPSpyP3OgeMRzpzqooIa=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc8zTGOsuhwBqT9HYyN03DGmi1WuVEcW80WoD3vE_40L4SbmIj1gS98pCd0zVLqVfLrQvaQPjZ44JN6Z4n682mEQ8ZhjhRVr9JANMVw980R5UimIA-1z=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AP1GczMMXuUPmwcaqc27l-WgZ_HQqdgQ_HkoQod2yujnyPk_UdTz5DqbVNCinHHaCmTjDZJosOAbZgAJRVOU0DxMatuO0wkE5IRE-uYha22IUXM56LqmGp1swzjPDr_uvnolUZ8nC2rjmHndqsRbaV7Ic3r-xQ=w1659-h1250-s-no-gm?authuser=0",
        "https://lh3.googleusercontent.com/pw/AP1GczMXmn9PZNJG9z3jJ-j_K1FhSw0U_hBrlMtA0qWyrXfU85vjehsLNFOCiE3jJSMah2gNOkSu1QDc0rGETNHAMFjGTdCcap1LEdSJiNLg4BWnjZVi8D4-ClxHN8JKuAfa_aFK2qaV4zfYiSsto2LCflXmKg=w1659-h1250-s-no-gm?authuser=0",
        "https://lh3.googleusercontent.com/pw/AP1GczOZwVQNCbbru0I9q93OCaO_Q5k4cUpkX_A6EMMIwSBMkPzYt6G1czsiKzVPpMayLsZeW7veHobuXV6_zv5BGRDV8ty8InQF2wAgG3T3L-dTUxHdCFsc0cnFpYXE2fYutYlg8NyonSmVC_F_vFqJkWJd6g=w1659-h1250-s-no-gm?authuser=0",
        "https://lh3.googleusercontent.com/pw/AIL4fc9seNLYw2vyXBs1AkPlOU8yZV_LnWVD3SdXb_AXGMG7J6DNqcH99wsbibxk8dLRXjY1csLeuInyqoJFHr8STAe-Zvy-ORTJiqk53Nb_7fxJjCU-B_z5=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc8197Z2N34lFdJiykvYh7YLTSytmCNDtM6ElqZ9IFoE4UxVe0qjCPcwv6YpTVSYSRj4POMm2y1IRv0N9RPn8MkNDg3cXMAYJ8ETMyhQXMNh_D0Fdxe4=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc_HjrNNpQAfoxhrF3kBbnpFTXen6upxNy3ev-pytrnZeTnHsbn4K7a7Q8e7Yu5Dw9pvDhc6nS4q0K2xGw7z7rsX1oiwBa7Kzhi0O9cY_B9F6r7Cjtus=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc99QWIXNnZfxh579bDZEEpzouhEh77C4npEghnUXqnLHEMStVm8qwd4Dtm8-I3WwexLQZnA0kig16fJuHXxh1u9NAaSAffpeB72n93XR4vBBQ7LEptX=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc9vwqbwuPm6Sme61igzP5rNwIsOtnnclYNZeQj1b-BbAHEnJQB770uvj4UyRhRs55Tg9q8iDxtkcB8FmAlXKDUp0gQOSzNgXy9sOfOeodpoGZPYGhIv=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc-rKKpy3weSenRP11Qilw92aOnRhK-ATwJm9gi-WLJMkhlWYZl_t3h2pTQTyNSu-sqDGY-z9HVWv9EWZEU7BT28udS0_faZHRTN4emrPO-40S6bReng=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc9D3iCCQGvbjQ-fC-F7l5qlEAwOtIZnop3bkiyMlQEjBzWvF93qKGYxYtzQqWuk1mfOOksueaEmUJCO9okIllqzPtJsR4VtuIjvs60zWaEEpODZYRm-=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc-0I9XdbH63py7BqhazyPKEPf8syBHS7RdbQZItS18Lg58ZhNplIBc30asQyt1SVQvctd_breRVxENRkdH5Nqe3RDjtwVTgmCXiKjmp-7wIv9wI0t4D=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc8DkdFngROxKvQQEBd69tdl3LXexJ7anGXpd2dKOlpegDJ6LwokGtTvtvDmVGtoFIl8_mMRt4jILTDck5iZ36590NhNK0fHKykWcCvopUtRXTPQ1j5m=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc_K9Y2X_XTuLmm-Aje--QTIQacFWXNAfk9A6njpE8m5cgX4O-4l_mN6mwh-1996Eo5TG9Qf4ivh7bH4LGXf66EciNCkgSjJvyGOWEn738RLH1ubAf8C=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc_uXFLz4eFd63llDgPmPSWjtd9s3n55kTH_TXhSWVHMNkrXgzKEgH3KhPspmtdPqVZN2NlpNa63Vg3ByQdue-A1Pfog0C0pwfl37CkpNgiY1UAHzdco=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc8V_O_zQUaOfKp8MQXDtxx_OcXjWnNLAnFXGIZiY-1ewB8Dfc3iybS4jjhPlVWATYIiWwJLbY3mJS3nLDLLub-gPbLg25-OxkO2coFqxiL0txF5Bfoq=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc_Py_gBU_QlNr7Tbm4VcrVQz3Jk4Vpzrup0MfgJ-Hwctw5qp7Mfq2GV8Ruuyyxq6HVOw-fSaOsN9L7OOagFJa6z-Dhj2ja1dgpRi5--DzYhcY-3Luax=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc_XasmIrqid9R50Lcw31ngikZogBqzf3Rp5picNaeOZ_dQ3WUjK_I-fSwgGXisy_xlcehZEi792nfSXy-6sAGbnksyJ_0BiLMxJuZz7l1UIYL7keb7K=w1920-h1080",
        "https://lh3.googleusercontent.com/pw/AIL4fc9WQ_1Dircu9WlVMYq4xBeLgr6u3IFEyjAO366pW6zbM-Rg414tfXDMAZ23JpJyH-W2bSwZ_aEDIushnxpbqpDafWk91f0oR7gCEaasJ_-BHT8XcO9_=w1920-h1080"
    ];

    /* ── Shuffle ── */
    function shuffle(arr) {
        for (var i = arr.length - 1; i > 0; i--) {
            var j = Math.floor(Math.random() * (i + 1));
            var tmp = arr[i]; arr[i] = arr[j]; arr[j] = tmp;
        }
    }
    shuffle(photos);

    /* ── Build masonry grid ── */
    var gallery = document.getElementById('photoGallery');
    photos.forEach(function (url, idx) {
        var item = document.createElement('div');
        item.className = 'photo-item';
        item.setAttribute('data-index', idx);
        var img = document.createElement('img');
        img.src = url;
        img.alt = 'Photo ' + (idx + 1);
        img.loading = 'lazy';
        img.referrerPolicy = 'no-referrer';
        item.appendChild(img);
        item.addEventListener('click', function () { openLightbox(idx); });
        gallery.appendChild(item);
    });

    /* ── Lightbox logic ── */
    var lightbox  = document.getElementById('photoLightbox');
    var lbImg     = document.getElementById('lbImg');
    var lbCounter = document.getElementById('lbCounter');
    var current   = 0;

    function openLightbox(idx) {
        current = idx;
        showPhoto(current);
        lightbox.classList.add('open');
        document.body.style.overflow = 'hidden';
    }

    function closeLightbox() {
        lightbox.classList.remove('open');
        document.body.style.overflow = '';
    }

    function showPhoto(idx) {
        lbImg.style.opacity = '0';
        setTimeout(function () {
            lbImg.src = photos[idx];
            lbImg.style.opacity = '1';
        }, 120);
        lbCounter.textContent = (idx + 1) + ' / ' + photos.length;
    }

    function prevPhoto() {
        current = (current - 1 + photos.length) % photos.length;
        showPhoto(current);
    }

    function nextPhoto() {
        current = (current + 1) % photos.length;
        showPhoto(current);
    }

    document.getElementById('lbClose').addEventListener('click', closeLightbox);
    document.getElementById('lbPrev').addEventListener('click', prevPhoto);
    document.getElementById('lbNext').addEventListener('click', nextPhoto);

    /* Click outside image to close */
    lightbox.addEventListener('click', function (e) {
        if (e.target === lightbox) closeLightbox();
    });

    /* Keyboard navigation */
    document.addEventListener('keydown', function (e) {
        if (!lightbox.classList.contains('open')) return;
        if (e.key === 'Escape')      closeLightbox();
        if (e.key === 'ArrowLeft')   prevPhoto();
        if (e.key === 'ArrowRight')  nextPhoto();
    });
})();
</script>


  </div>

  <!-- 2021 & Earlier -->
  <div class="news-tab-panel" id="panel-2021" role="tabpanel" aria-labelledby="tab-2021">
  </div>

</div>

<script>
(function () {
    var btns   = document.querySelectorAll('.news-tab-btn');
    var panels = document.querySelectorAll('.news-tab-panel');

    btns.forEach(function (btn) {
        btn.addEventListener('click', function () {
            var target = btn.getAttribute('aria-controls');

            // Deactivate all
            btns.forEach(function (b) {
                b.classList.remove('active');
                b.setAttribute('aria-selected', 'false');
            });
            panels.forEach(function (p) {
                p.classList.remove('active');
            });

            // Activate clicked
            btn.classList.add('active');
            btn.setAttribute('aria-selected', 'true');
            var panel = document.getElementById(target);
            if (panel) panel.classList.add('active');
        });
    });
})();
</script>

