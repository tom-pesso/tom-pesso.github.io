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
    /* Apply Inter font and smaller base size to this page */
    .page__content {
        font-family: 'Inter', sans-serif;
        font-size: 0.8rem; /* ≈ your old 0.9em */
    }

    /* Make section headings smaller than default Tailwind 2xl */
    .page__content h2 {
        font-size: 1rem;
        font-weight: 600;
    }

    /* Make paper titles smaller */
    .page__content h3 {
        font-size: 0.9rem;
        font-weight: 600;
    }

    /* Default text size for paragraphs, spans, links, list items */
    .page__content p,
    .page__content span,
    .page__content a,
    .page__content li {
        font-size: 0.8rem;
    }

    /* Slightly smaller text for presentations lists, notes, etc. */
    .presentations-text,
    .small-note {
        font-size: 0.7rem; /* ≈ your old 0.8em */
    }

    .paper-link {
        text-decoration: none;
    }

    /* Rotate chevron when a <details> block is open */
    details[open] .toggle-icon {
        transform: rotate(180deg);
    }

    /* Hide the default triangle marker on <summary> */
    summary {
        list-style: none;
        cursor: pointer;
    }
    summary::-webkit-details-marker {
        display: none;
    }
</style>

<!-- Main Content -->
<main class="max-w-4xl mx-auto py-8 md:py-12">

    <!-- Working Papers Section -->
    <section class="mb-12">
        <h2 class="text-2xl font-semibold text-gray-900 border-b border-gray-200 pb-2 mb-6">
            Working Papers
        </h2>

        <!-- Paper 1 -->
        <article class="mb-10 p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
            <!-- Collapsible block (title + abstract + presentations) -->
            <details>
                <summary class="flex justify-between items-start mb-2">
                    <div class="flex-1">
                        <h3 class="text-xl font-bold text-gray-900 mb-2">
                            Fiscal Multiplier: the Size of the Shock Matters (2024)
                        </h3>
                        <div class="text-md text-gray-600 italic">
                            <!-- PDF badge (on demand) -->
                            <span class="inline-flex items-center bg-yellow-100 text-yellow-800 text-xs font-semibold px-2.5 py-0.5 rounded-full border border-yellow-200">
                                <svg xmlns="http://www.w3.org/2000/svg"
                                     viewBox="0 0 20 20"
                                     fill="currentColor"
                                     class="w-4 h-4 mr-1"
                                     aria-hidden="true">
                                    <path d="M5 2a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h10a2 2 0 0 0 2-2V7.5L11.5 2H5z" />
                                    <path d="M11.5 2V7.5H17" />
                                </svg>
                                <span>PDF (on demand)</span>
                            </span>
                        </div>
                    </div>
                    <span class="p-2 rounded-full hover:bg-gray-200 transition-colors inline-flex items-center justify-center">
                        <!-- Chevron down icon -->
                        <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300"
                             xmlns="http://www.w3.org/2000/svg" fill="none"
                             viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true">
                            <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                        </svg>
                    </span>
                </summary>

                <!-- Content that appears when opened -->
                <div class="text-sm text-gray-700 leading-relaxed text-justify mb-4">
                    <p class="mb-4">
                        This paper studies the impact of the sign and magnitude of fiscal shocks on the fiscal multiplier. Through a theoretical examination, it highlights the significance of both the sign and magnitude of the shock in determining the multiplier. The study introduces a new empirical methodology, the Local Linear Local Projection, to detect complex non-linear patterns. When applied to US data, the methodology reveals that the degree of nonlinearity captured in the data varies with the identification strategy employed. Notably, zero does not appear to be a significant tipping point in the nonlinearity of the fiscal multiplier.
                    </p>
                    <div class="bg-gray-100 p-3 rounded-md mb-1 border border-gray-200">
                        <p class="presentations-text text-gray-600">
                            <span class="font-semibold">Presentations:</span> EEA 2025, IAAE 2025, European Winter Meeting of the Econometric Society (Dec. 2024), BSE Summer Forum (2024, poster session), CREi Internal Seminar (2023, 2022), UPF Econometrics Internal Seminar (2023), PhD Jamboree BSE (2023)
                        </p>
                    </div>
                </div>
            </details>

            <!-- Always Visible Content -->
            <p class="small-note text-gray-800 italic mt-2">
                Draft available on demand.
            </p>
        </article>

        <!-- Paper 2 -->
        <article class="mb-10 p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
            <details>
                <!-- Visible header (clickable to open/close) -->
                <summary class="flex justify-between items-start mb-2">
                    <div class="flex-1">
                        <h3 class="text-xl font-bold text-gray-900 mb-2">
                            Fiscal Policy and Inflation: Accounting for Non-Linearities in Government Debt (2024)
                        </h3>
                        <div class="text-md text-gray-600 italic">
                            with
                            <a href="https://www.ecb.europa.eu/pub/research/authors/profiles/cristina-checherita-westphal.en.html"
                               target="_blank" class="paper-link text-indigo-600 hover:text-indigo-800 visited:text-purple-600 transition-colors duration-200">
                                C. Checherita-Westphal
                            </a>.
                            <span class="inline-block bg-blue-100 text-blue-800 text-xs font-semibold ml-2 px-2.5 py-0.5 rounded-full not-italic">
                                ECB Working Paper - No. 2996
                            </span>

                            <!-- PDF badge as yellow button -->
                            <a href="https://www.ecb.europa.eu/pub/pdf/scpwps/ecb.wp2996~5e4df9c08d.en.pdf"
                               target="_blank"
                               class="paper-link inline-flex items-center bg-yellow-100 text-yellow-800 text-xs font-semibold ml-2 px-2.5 py-0.5 rounded-full border border-yellow-200">
                                <svg xmlns="http://www.w3.org/2000/svg"
                                     viewBox="0 0 20 20"
                                     fill="currentColor"
                                     class="w-4 h-4 mr-1"
                                     aria-hidden="true">
                                    <path d="M5 2a2 2 0 0 0-2 2v12c0 1.1.9 2 2 2h10a2 2 0 0 0 2-2V7.5L11.5 2H5z" />
                                    <path d="M11.5 2V7.5H17" />
                                </svg>
                                <span>PDF</span>
                            </a>
                        </div>
                    </div>

                    <span class="p-2 rounded-full hover:bg-gray-200 transition-colors ml-4 inline-flex items-center justify-center">
                        <!-- Chevron down icon -->
                        <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300"
                             xmlns="http://www.w3.org/2000/svg" fill="none"
                             viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" aria-hidden="true">
                            <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                        </svg>
                    </span>
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

</main>
