---
permalink: /markdown/
title: ""
excerpt: ""
author_profile: false
layout: splash
header:
  nav: false
feature_row:
  - image_path: /about_picture.jpeg
    alt: "placeholder image 1"
    title: "Welcome to my website!"
    url: "https://tom-pesso.github.io/files/CV-TomPesso.pdf"
    btn_label: "CV"
    btn_class: "btn--primary"
    excerpt: "I am a sixth-year Ph.D candidate in Economics at Universitat Pompeu Fabra (UPF) and Barcelona School of Economics (BSE), under the supervision of [Prof. Geert Mesters](https://www.geertmesters.com/) and [Prof. Davide Debortoli](https://crei.cat/people/davide-debortoli-2/). <br/> <br/>

I am a macroeconomist interested in Fiscal Policy, Macroeconometrics and more generally Macroeconomic Policy Evaluation. <br/> <br/>

If you want to get in touch, please send me an email at [tom.pesso@upf.edu](mailto:tom.pesso@upf.edu)."
---




<div class="text-center mt-12 mb-10">
    <h1 class="text-5xl md:text-6xl font-bold text-gray-900 leading-tight">
        Tom Pesso
    </h1>
    <p class="text-lg text-gray-600 mt-2">Economics Ph.D. Candidate</p>
</div>


{% include feature_row id="feature_row" type="left" %}

<!-- Load Tailwind CSS [Working Papers](#working-papers){: .btn .btn--primary} -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Use Inter font family -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>

  /* Hide header bar on THIS page only */
.masthead,
.greedy-nav,
.site-nav {
    display: none !important;
}
    /* === GLOBAL FONT FAMILY + BASE SIZE === */
    .page__content {
        font-family: 'Inter', sans-serif;
        font-size: 0.7rem;
    }
    
    /* === SECTION TITLES === */
    .page__content h2 {
        font-size: 1.5rem;
        font-weight: 600;
        margin-bottom: 0.75rem;
    }

    /* === PAPER TITLES === */
    .page__content h3 {
        font-size: 0.95rem;
        font-weight: 600;
        margin-bottom: 0.05rem;
    }

    /* === ABSTRACT TEXT === */
    .page__content .text-sm {
        font-size: 0.8rem !important;
    }

    /* === PRESENTATIONS BOX — main size control === */
    .page__content .presentations-box {
        font-size: 0.6rem !important; /* “Presentations:” label */
    }

    /* === PRESENTATION BADGES (pills) === */
    .page__content .presentations-box .presentation-pill {
        font-size: 0.6rem !important;
        line-height: 1.1; /* looks cleaner inside pills */
    }

    /* === SMALL NOTES === */
    .presentations-text,
    .small-note {
        font-size: 0.6rem;
    }

    /* === OVERRIDE TAILWIND TEXT SIZES (PDF badge, ECB badge, etc.) === */
    .page__content .text-xs {
        font-size: 0.7rem !important;
    }

    .page__content .text-md {
        font-size: 0.7rem !important;
    }

    /* === ICON SIZE (PDF icon) === */
    .page__content .w-4 {
        width: 0.7rem !important;
    }
    .page__content .h-4 {
        height: 0.7rem !important;
    }

    /* === LINK STYLE === */
    .paper-link {
        text-decoration: none;
    }

    /* === DROPDOWN ARROW === */
    details[open] .toggle-icon {
        transform: rotate(180deg);
    }

   /* === REMOVE DEFAULT SUMMARY MARKER === */
summary {
    list-style: none;
    cursor: pointer;

    /* 👇 ADD THIS LINE */
    padding: 0 !important;
}
summary::-webkit-details-marker {
    display: none;
}

</style>



<!-- Main Content -->
<main class="max-w-4xl mx-auto py-8 md:py-12">

    <!-- Working Papers Section -->
    <section class="mb-6">
        <h2 id="working-papers" class="text-2xl font-semibold text-gray-900 border-b border-gray-200 pb-2 mb-6">
    Working Papers
        </h2>

        <!-- Paper 1 -->
<article class="mb-10 p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
    <details>
        <!-- Summary block -->
        <summary class="mb-2 cursor-pointer">

            <!-- Row 1: Title + chevron -->
            <div class="flex justify-between items-start gap-4">
                <h3 class="text-xl font-bold text-gray-900 !mb-2">
                    Fiscal Multiplier: the Size of the Shock Matters (2024)
                </h3>

                <!-- Chevron icon -->
                <span class="p-2 rounded-full hover:bg-gray-200 transition-colors inline-flex items-center justify-center">
                    <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300"
                         xmlns="http://www.w3.org/2000/svg" fill="none"
                         viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round"
                              d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                    </svg>
                </span>
            </div>

            <!-- Row 2: PDF badge -->
            <div class="mt-0.5 flex flex-wrap items-center gap-2">

                <!-- PDF (on demand) badge -->
                <span class="inline-flex items-center bg-yellow-100 text-yellow-800 text-xs font-semibold px-2.5 py-0.5 rounded-full border border-yellow-200">
                    <svg xmlns="http://www.w3.org/2000/svg"
                         viewBox="0 0 20 20"
                         fill="currentColor"
                         class="w-4 h-4 mr-1">
                        <path d="M5 2a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h10a2 2 0 0 0 2-2V7.5L11.5 2H5z" />
                        <path d="M11.5 2V7.5H17" />
                    </svg>
                    PDF (on demand)
                </span>

            </div>
        </summary>

        <!-- Content -->
        <div class="text-sm text-gray-700 leading-relaxed text-justify mb-4">
            <p class="mb-4">
                This paper studies the impact of the sign and magnitude of fiscal shocks on the fiscal multiplier.
                Through a theoretical examination, it highlights the significance of both the sign and magnitude
                of the shock in determining the multiplier. The study introduces a new empirical methodology,
                the Local Linear Local Projection, to detect complex non-linear patterns. When applied to US data,
                the methodology reveals that the degree of nonlinearity captured in the data varies with the
                identification strategy employed. Notably, zero does not appear to be a significant tipping point
                in the nonlinearity of the fiscal multiplier.
            </p>

            <!-- Presentations box -->
            <div class="presentations-box bg-gray-100 border border-gray-200 rounded-md p-2 mt-2">
                <div class="flex flex-wrap gap-1">

                    <span class="text-gray-700 font-semibold mr-1">Presentations:</span>

                    <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded-full border border-gray-300">
                        EEA 2025
                    </span>

                    <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded-full border border-gray-300">
                        IAAE 2025
                    </span>

                    <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded-full border border-gray-300">
                        European Winter Meeting of the Econometric Society (Dec. 2024)
                    </span>

                    <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded-full border border-gray-300">
                        BSE Summer Forum (2024, poster session)
                    </span>

                    <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded-full border border-gray-300">
                        CREi Internal Seminar (2023, 2022)
                    </span>

                    <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded-full border border-gray-300">
                        UPF Econometrics Internal Seminar (2023)
                    </span>

                    <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 text-xs font-semibold px-2 py-0.5 rounded-full border border-gray-300">
                        PhD Jamboree BSE (2023)
                    </span>

                </div>
            </div>

        </div>
    </details>
</article>


        <!-- Paper 2 -->
<article class="mb-10 p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
    <details>
        <!-- Visible header (clickable to open/close) -->
        <summary class="mb-2 cursor-pointer">

            <!-- Row 1: Title + chevron -->
            <div class="flex justify-between items-start gap-4">
                <h3 class="text-xl font-bold text-gray-900 mb-2">
                    Fiscal Policy and Inflation: Non-Linearities in Government Debt (2024)
                </h3>

                <!-- Chevron -->
                <span class="p-2 rounded-full hover:bg-gray-200 transition-colors inline-flex items-center justify-center">
                    <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300"
                         xmlns="http://www.w3.org/2000/svg" fill="none"
                         viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                    </svg>
                </span>
            </div>

            <!-- Row 2: ECB badge + PDF badge + coauthor (all on one line, wrapping together if needed) -->
            <div class="mt-0.5 flex flex-wrap items-center gap-2">
                <!-- Coauthor text -->
                <span class="text-md text-gray-600 italic">
                    with
                    <a href="https://www.ecb.europa.eu/pub/research/authors/profiles/cristina-checherita-westphal.en.html"
                       target="_blank"
                       class="paper-link text-indigo-600 hover:text-indigo-800 visited:text-purple-600 transition-colors">
                        C. Checherita-Westphal
                    </a>.
                </span>
                
                <!-- ECB badge -->
                <span class="inline-flex items-center bg-blue-100 text-blue-800 text-xs font-semibold px-2 py-0.5 rounded-full border border-blue-200">
                    ECB Working Paper - No. 2996
                </span>

                <!-- PDF badge -->
                <a href="https://www.ecb.europa.eu/pub/pdf/scpwps/ecb.wp2996~5e4df9c08d.en.pdf"
                   target="_blank"
                   class="inline-flex items-center bg-yellow-100 text-yellow-800 text-xs font-semibold px-2 py-0.5 rounded-full border border-yellow-200">
                    <svg xmlns="http://www.w3.org/2000/svg"
                         viewBox="0 0 20 20"
                         fill="currentColor"
                         class="w-4 h-4 mr-1">
                        <path d="M5 2a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h10a2 2 0 0 0 2-2V7.5L11.5 2H5z" />
                        <path d="M11.5 2V7.5H17" />
                    </svg>
                    PDF
                </a>

                
            </div>
        </summary>

        <!-- Collapsible Abstract -->
        <div class="mt-2 text-sm text-gray-700 leading-relaxed text-justify">
            <p>
                This paper investigates the interplay between discretionary fiscal policy and inflation in the euro area, emphasizing the role of public debt levels in modulating this relationship. It explores how fiscal expansions or contractions influence inflationary pressures, particularly under varying debt conditions. The analysis reveals that fiscal policy’s effect on inflation is non-linear, with debt levels significantly affecting the inflationary outcome of fiscal measures. High debt levels tend to amplify the inflation response to fiscal expansions, a finding that holds under multiple analytical frameworks and robustness checks. This paper contributes to the empirical literature by highlighting the critical role of fiscal policy, especially in high-debt environments, and its implications for inflation dynamics in the euro area.
            </p>
        </div>
    </details>
</article>



    </section>

    <!-- Work in Progress Section -->
    <section>
        <h2 class="text-2xl font-semibold text-gray-900 border-b border-gray-200 pb-2 mb-6">
            Work in Progress
        </h2>

        <!-- WIP Paper 1 -->
        <article class="p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
            <h3 class="text-xl font-bold text-gray-900 mb-2">
                US Presidents and the Economy: An Econometric Evaluation
            </h3>
            <div class="text-md text-gray-600 italic">
                with
                <a href="https://sites.google.com/site/regisbarnichon/"
                   target="_blank" class="paper-link text-indigo-600 hover:text-indigo-800 visited:text-purple-600 transition-colors duration-200">
                    R. Barnichon
                </a>,
                <a href="https://www.geertmesters.com/"
                   target="_blank" class="paper-link text-indigo-600 hover:text-indigo-800 visited:text-purple-600 transition-colors duration-200">
                    G. Mesters
                </a>
            </div>
        </article>

    </section>


<!-- Teaching Section -->
<section class="mt-12">
    <h2 id="teaching" class="text-2xl font-semibold text-gray-900 border-b border-gray-200 pb-2 mb-6">
        Teaching
    </h2>

    <!-- Course 1 -->
    <article class="mb-8 p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
        <details>
            <summary class="cursor-pointer">
                
                <!-- Top row: course title -->
                <div class="flex justify-between items-start gap-4">
                    <h3 class="text-xl font-bold text-gray-900 mb-2">
                        Fiscal Policy — Graduate TA
                    </h3>

                    <!-- Chevron -->
                    <span class="p-2 rounded-full hover:bg-gray-200 transition-colors inline-flex items-center justify-center">
                        <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300"
                             xmlns="http://www.w3.org/2000/svg" fill="none"
                             viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                  d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                        </svg>
                    </span>
                </div>

                <!-- Subtitle -->
                <div class="text-md text-gray-600 italic mt-0.5">
                    for Prof. Davide Debortoli — 2023/2025, Barcelona School of Economics
                </div>
            </summary>

            <!-- Details content -->
            <div class="mt-4 text-sm text-gray-700 leading-relaxed">
                Details to come.
            </div>
        </details>
    </article>

    <!-- Course 2 -->
<article class="mb-8 p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
    <details>
        <summary class="cursor-pointer">

            <!-- Top row: course title -->
            <div class="flex justify-between items-start gap-4">
                <h3 class="text-xl font-bold text-gray-900 mb-2">
                    Causal Inference & Panel Data — Graduate TA + Summer School TA
                </h3>

                <!-- Chevron -->
                <span class="p-2 rounded-full hover:bg-gray-200 transition-colors inline-flex items-center justify-center">
                    <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300"
                         xmlns="http://www.w3.org/2000/svg" fill="none"
                         viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round"
                              d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                    </svg>
                </span>
            </div>

            <!-- Subtitle -->
            <div class="text-md text-gray-600 italic mt-0.5">
                for Prof. Albrecht Glitz — 2021/2022 & 2022/2023, Barcelona School of Economics
            </div>
        </summary>

        <!-- Details content -->
        <div class="mt-4 text-sm text-gray-700 leading-relaxed">

            <!-- Document links (badges) -->
            <div class="flex flex-wrap gap-2 mb-4">
                
                <!-- Syllabus (example link, update if needed) -->
                <a href="https://tom-pesso.github.io/files/teaching/12e016-econometric-methods-ii.pdf" 
                   target="_blank"
                   class="inline-flex items-center bg-yellow-100 text-yellow-800 text-xs font-semibold px-2.5 py-0.5 rounded-full border border-yellow-200">
                    <svg xmlns="http://www.w3.org/2000/svg"
                         viewBox="0 0 20 20" fill="currentColor"
                         class="w-4 h-4 mr-1">
                        <path d="M5 2a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h10a2 2 0 0 0 2-2V7.5L11.5 2H5z" />
                        <path d="M11.5 2V7.5H17" />
                    </svg>
                    Syllabus
                </a>

                <!-- Problem Sets -->
                <a href="https://bse.eu/summer-school/microeconometrics"
                   target="_blank"
                   class="inline-flex items-center bg-green-100 text-green-800 text-xs font-semibold px-2.5 py-0.5 rounded-full border border-green-200">
                    <svg xmlns="http://www.w3.org/2000/svg"
                         viewBox="0 0 20 20" fill="currentColor"
                         class="w-4 h-4 mr-1">
                        <path d="M3 3h14v14H3z" />
                    </svg>
                    Summer School
                </a>

            </div>

            <!-- Content box (NO duplicated title) -->
            <div class="bg-gray-100 border border-gray-200 rounded-md p-4">

                <ul class="list-disc ml-6 space-y-1">
                    <li>Randomized Controlled Trials</li>
                    <li>Natural Experiments</li>
                    <li>Regression Discontinuity Designs</li>
                    <li>Selection on Observables (Regression, Matching)</li>
                    <li>Difference-in-Differences, Event Studies, Synthetic Control</li>
                </ul>

            </div>

        </div>
    </details>
</article>

</section>

</main>
