---
title: Im Jekyll Theme
description: "An open-source Jekyll theme crafted using the Bulma CSS framework. This theme utilizes Bulma SCSS, making it incredibly easy to customize and adapt to your specific needs. With over 7 layouts and 10+ collections"
image: /assets/logos/logo.svg
layout: default
---
 <!-- 1. HEADER / NAVBAR -->
  <nav class="navbar" role="navigation" aria-label="main navigation">
        <div class="container">
            <div class="navbar-brand">
                <a class="navbar-item" href="#">
                    <strong>ghost</strong>
                </a>
                <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false">
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                    <span aria-hidden="true"></span>
                </a>
            </div>
            <div class="navbar-menu">
                <div class="navbar-start">
                    <div class="navbar-item has-dropdown is-hoverable">
                        <a class="navbar-link">Product</a>
                        <div class="navbar-dropdown">
                            <a class="navbar-item">Overview</a>
                        </div>
                    </div>
                    <a class="navbar-item">Explore</a>
                    <div class="navbar-item has-dropdown is-hoverable">
                        <a class="navbar-link">Resources</a>
                        <div class="navbar-dropdown">
                            <a class="navbar-item">Blog</a>
                        </div>
                    </div>
                    <a class="navbar-item">Pricing</a>
                </div>
                <div class="navbar-end">
                    <a class="navbar-item"><i class="fas fa-search"></i></a>
                    <a class="navbar-item">Sign in</a>
                    <div class="navbar-item">
                        <div class="buttons">
                            <a class="button is-dark get-started-btn">
                                <strong>Get Started</strong>
                                <span class="free-text">— free</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </nav>
    <!-- 2. HERO SECTION -->
    <section class="section hero-section">
        <div class="container has-text-centered">
            <h1 class="title is-1 hero-title">
                Independent technology<br>
                <span class="text-midgrey">for modern publishing.</span>
            </h1>
            <div class="placeholder placeholder-dark hero-placeholder">
                <p>Placeholder for Dashboard UI</p>
            </div>
        </div>
    </section>
    <!-- 3. INTRO TEXT SECTION -->
    <section class="section">
        <div class="container" style="max-width: 720px;">
            <p class="is-size-4 has-text-weight-medium" style="line-height: 1.5;">
                <strong>Ghost is a powerful app for professional publishers</strong> to create, share, and grow a business around their content. It comes with modern tools to build a website, publish content, send newsletters & offer paid subscriptions to members.
            </p>
            <p class="mt-5">
                <a href="#" class="is-size-5 text-link">
                    Try Ghost completely free for 14 days <i class="fa-solid fa-arrow-right ml-2"></i>
                </a>
            </p>
        </div>
    </section>
    <!-- 4. "COMPLETE CONTROL" SECTION (2-COLUMN) -->
    <section class="section section-dark control-section">
        <div class="container">
            <div class="columns is-vcentered is-variable is-8">
                <div class="column is-5">
                    <p class="eyebrow-text">Easy Site Design</p>
                    <h2 class="title is-2">Complete control over your website and branding.</h2>
                    <p class="mt-4">
                        Launch a custom website and tweak the design settings to perfectly match your brand and style. Go even further with hundreds of custom themes in our marketplace, or build your own completely custom design from scratch.
                    </p>
                    <p class="mt-5">
                        <a href="#" class="is-size-5 text-link">
                            Explore Ghost themes <i class="fa-solid fa-arrow-right ml-2"></i>
                        </a>
                    </p>
                </div>
                <div class="column is-7">
                    <div class="control-placeholder-wrapper">
                        <div class="placeholder control-placeholder-main">Site Design UI</div>
                        <div class="placeholder control-placeholder-side">Create your own brand style</div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- 5. THEME SHOWCASE GRID -->
    <section class="section section-dark theme-showcase-section">
        <div class="container">
            <div class="columns is-multiline is-centered">
                <div class="column is-one-third-desktop is-half-tablet">
                    <div class="placeholder theme-placeholder">Theme 1</div>
                </div>
                <div class="column is-one-third-desktop is-half-tablet">
                    <div class="placeholder theme-placeholder">Theme 2</div>
                </div>
                <div class="column is-one-third-desktop is-half-tablet">
                    <div class="placeholder theme-placeholder">Theme 3</div>
                </div>
                 <div class="column is-one-third-desktop is-half-tablet">
                    <div class="placeholder theme-placeholder">Theme 4</div>
                </div>
                <div class="column is-one-third-desktop is-half-tablet">
                    <div class="placeholder theme-placeholder">Theme 5</div>
                </div>
                 <div class="column is-one-third-desktop is-half-tablet">
                    <div class="placeholder theme-placeholder">Theme 6</div>
                </div>
            </div>
        </div>
    </section>
    <!-- 6. PUBLISH BY WEB & EMAIL SECTION -->
    <section class="section publish-section" style="padding: 7rem 0;">
        <div class="container has-text-centered">
            <p class="eyebrow-text" style="color: var(--color-purple);">Advanced Creator Tools</p>
            <h2 class="title is-2">Publish by web & email newsletter.</h2>
            <p class="subtitle is-5">
                An editor built from the ground-up for professionals. Calm by design, with advanced workflows by default. No more suffering through clumsy toolbars or drag & oops. Immerse yourself in the story with an interface that's invisible until you need it, and powerful when you do.
            </p>
            <div class="placeholder placeholder-light editor-placeholder">
                <p>Placeholder for Ghost Editor UI</p>
            </div>
        </div>
    </section>
    <!-- 7. RICH MEDIA & NEWSLETTERS SECTIONS -->
    <section class="section section-light-grey simple-text-section has-text-centered">
        <div class="container">
            <div class="columns is-vcentered">
                <div class="column">
                    <h3 class="title is-3">Rich media & dynamic cards.</h3>
                    <p class="subtitle is-6">Modern publishing requires more than just words. Expand your story with image galleries, gifs, video, audio, products, info boxes, and so much more.</p>
                </div>
                <div class="column">
                    <h3 class="title is-3">Newsletters built-in.</h3>
                    <p class="subtitle is-6">Deliver posts by email newsletter to your audience, so they’ll be in the loop whenever something new goes live.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- 8. TRANSFORM CLICKS SECTION (2-COLUMN with GLOW) -->
    <section class="section section-dark glow-section">
        <div class="container">
            <div class="columns is-vcentered is-variable is-8">
                <div class="column is-6">
                    <div class="email-card-bg">
                        <div class="placeholder email-card-placeholder">
                            Secure Sign In Email
                        </div>
                    </div>
                </div>
                <div class="column is-6">
                    <p class="eyebrow-text">Grow your audiences</p>
                    <h2 class="title is-2">Transform those clicks into contacts.</h2>
                    <p class="mt-4 is-size-5" style="opacity: 0.9; line-height: 1.7;">
                        Until now, building an indie publication with memberships and subscriptions has been difficult and complicated. Ghost makes it easy.
                    </p>
                    <p class="mt-4 is-size-5 has-text-weight-medium">
                        Hello, new friends.
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!-- 9. MANAGE YOUR MEMBERSHIPS SECTION -->
    <section class="section" style="padding: 7rem 0;">
        <div class="container has-text-centered">
            <p class="eyebrow-text" style="color: var(--color-purple);">Run your business</p>
            <h2 class="title is-2">Manage your memberships.</h2>
            <p class="subtitle is-5">See who's signing up, who's paying, and what they're reading, so you can get a better understanding of your core audience.</p>
            <div class="placeholder placeholder-light editor-placeholder">
                <p>Placeholder for Members List UI</p>
            </div>
        </div>
    </section>