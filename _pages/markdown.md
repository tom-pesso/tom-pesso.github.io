---
permalink: /markdown/
layout: single
title: ""
excerpt: ""
author_profile: true
---

<!-- Load Tailwind CSS -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Use Inter font family -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

<style>
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
    margin-bottom: 0.1rem;
}

/* === ABSTRACT TEXT === */
.page__content .text-sm {
    font-size: 0.8rem !important;
}

/* === PRESENTATIONS BOX === */
.page__content .presentations-box {
    font-size: 0.6rem !important; /* “Presentations:” label */
}

/* === PRESENTATION PILLS === */
.page__content .presentation-pill {
    font-size: 0.6rem !important;
    line-height: 1.1;
}

/* SMALL NOTES */
.presentations-text,
.small-note {
    font-size: 0.6rem;
}

/* PDF + ECB BADGE FONT SIZE */
.page__content .text-xs {
    font-size: 0.7rem !important;
}

/* Co-author line size */
.page__content .text-md {
    font-size: 0.7rem !important;
}

/* ICON SIZE */
.page__content .w-4 { width: 0.7rem !important; }
.page__content .h-4 { height: 0.7rem !important; }

/* LINKS */
.paper-link { text-decoration: none; }

/* DROPDOWN ARROW */
details[open] .toggle-icon { transform: rotate(180deg); }

/* REMOVE DEFAULT MARKER */
summary { list-style: none; cursor: pointer; }
summary::-webkit-details-marker { display: none; }
</style>


<!-- Main Content -->
<main class="max-w-4xl mx-auto py-8 md:py-12">

<section class="mb-12">
<h2 class="text-2xl font-semibold text-gray-900 border-b border-gray-200 pb-2 mb-6">Working Papers</h2>

<!-- Paper 1 -->
<article class="mb-10 p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
<details>

<summary class="flex justify-between items-start mb-2">

<div class="flex items-center gap-2 mb-2">
    <h3 class="text-xl font-bold text-gray-900">
        Fiscal Multiplier: the Size of the Shock Matters (2024)
    </h3>

    <!-- PDF badge -->
    <span class="inline-flex items-center bg-yellow-100 text-yellow-800 text-xs font-semibold px-2.5 py-0.5 rounded-full border border-yellow-200">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
             class="w-4 h-4 mr-1">
            <path d="M5 2a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h10a2 2 0 0 0 2-2V7.5L11.5 2H5z" />
            <path d="M11.5 2V7.5H17" />
        </svg>
        PDF (on demand)
    </span>
</div>

<span class="p-2 rounded-full hover:bg-gray-200 transition-colors inline-flex items-center justify-center">
    <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300"
         xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
    </svg>
</span>

</summary>

<!-- ABSTRACT -->
<div class="text-sm text-gray-700 leading-relaxed text-justify mb-4">
<p class="mb-4">
This paper studies the impact of the sign and magnitude of fiscal shocks on the fiscal multiplier...
</p>

<!-- PRESENTATIONS BOX -->
<div class="presentations-box bg-gray-100 border border-gray-200 rounded-md p-2 mt-2">
    <div class="flex flex-wrap gap-1">

        <span class="text-gray-700 font-semibold mr-1">Presentations:</span>

        <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 px-2 py-0.5 rounded-full border border-gray-300">
            EEA 2025
        </span>

        <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 px-2 py-0.5 rounded-full border border-gray-300">
            IAAE 2025
        </span>

        <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 px-2 py-0.5 rounded-full border border-gray-300">
            European Winter Meeting of the Econometric Society (Dec. 2024)
        </span>

        <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 px-2 py-0.5 rounded-full border border-gray-300">
            BSE Summer Forum (2024, poster session)
        </span>

        <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 px-2 py-0.5 rounded-full border border-gray-300">
            CREi Internal Seminar (2023, 2022)
        </span>

        <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 px-2 py-0.5 rounded-full border border-gray-300">
            UPF Econometrics Internal Seminar (2023)
        </span>

        <span class="presentation-pill inline-flex items-center bg-gray-200 text-gray-700 px-2 py-0.5 rounded-full border border-gray-300">
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
<summary class="flex justify-between items-start mb-2">

<div class="flex-1">

<div class="flex flex-wrap items-center gap-2 mb-1">
    <h3 class="text-xl font-bold text-gray-900">
        Fiscal Policy and Inflation: Accounting for Non-Linearities in Government Debt (2024)
    </h3>

    <span class="inline-flex items-center bg-blue-100 text-blue-800 text-xs font-semibold px-2 py-0.5 rounded-full border border-blue-200">
        ECB Working Paper - No. 2996
    </span>

    <a href="https://www.ecb.europa.eu/pub/pdf/scpwps/ecb.wp2996~5e4df9c08d.en.pdf"
       target="_blank"
       class="inline-flex items-center bg-yellow-100 text-yellow-800 text-xs font-semibold px-2 py-0.5 rounded-full border border-yellow-200">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor"
             class="w-4 h-4 mr-1">
            <path d="M5 2a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h10a2 2 0 0 0 2-2V7.5L11.5 2H5z" />
            <path d="M11.5 2V7.5H17" />
        </svg>
        PDF
    </a>
</div>

<p class="text-md text-gray-600 italic">
    with
    <a href="https://www.ecb.europa.eu/pub/research/authors/profiles/cristina-checherita-westphal.en.html"
       target="_blank"
       class="paper-link text-indigo-600 hover:text-indigo-800 visited:text-purple-600 transition-colors">
        C. Checherita-Westphal
    </a>.
</p>

</div>

<span class="p-2 rounded-full hover:bg-gray-200 transition-colors ml-4 inline-flex items-center justify-center">
    <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300"
         xmlns="http://www.w3.org/2000/svg" fill="none"
         viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
        <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
    </svg>
</span>

</summary>

<div class="mt-2 text-sm text-gray-700 leading-relaxed text-justify">
<p>
This paper investigates the interplay between discretionary fiscal policy and inflation in the euro area...
</p>
</div>

</details>
</article>

</section>

</main>
