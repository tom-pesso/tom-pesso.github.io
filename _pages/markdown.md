---
permalink: /markdown/
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
    /* Apply Inter font */
    .page-content { /* Target the theme's content wrapper if possible */
        font-family: 'Inter', sans-serif;
    }
    /* Style for the paper links */
    .paper-link {
        @apply text-indigo-600 hover:text-indigo-800 visited:text-purple-600 transition-colors duration-200;
    }
    /* Style for the dropdown icon rotation */
    .toggle-icon.rotate-180 {
        transform: rotate(180deg);
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
            <!-- Visible Header -->
            <div class="flex justify-between items-center mb-4">
                <h3 class="text-xl font-bold text-gray-900 pr-4">
                    Fiscal Multiplier: the Size of the Shock Matters (2024)
                </h3>
                <button class="abstract-toggle p-2 rounded-full hover:bg-gray-200 transition-colors" onclick="toggleAbstract(this)" aria-expanded="false" aria-label="Toggle Abstract">
                    <!-- Chevron down icon -->
                    <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                    </svg>
                </button>
            </div>
            
            <!-- Collapsible Abstract -->
            <div class="abstract-content max-h-0 opacity-0 overflow-hidden transition-all duration-500 ease-in-out">
                <p class="text-gray-700 leading-relaxed text-justify mb-4">
                    This paper studies the impact of the sign and magnitude of fiscal shocks on the fiscal multiplier. Through a theoretical examination, it highlights the significance of both the sign and magnitude of the shock in determining the multiplier. The study introduces a new empirical methodology, the Local Linear Local Projection, to detect complex non-linear patterns. When applied to US data, the methodology reveals that the degree of nonlinearity captured in the data varies with the identification strategy employed. Notably, zero does not appear to be a significant tipping point in the nonlinearity of the fiscal multiplier.
                </p>
                <!-- Presentations info moved inside the dropdown -->
                <div class="bg-gray-100 p-3 rounded-md mb-4 border border-gray-200">
                    <p class="text-sm text-gray-600">
                        <span class="font-semibold">Presentations:</span> EEA 2025, IAAE 2025, European Winter Meeting of the Econometric Society (Dec. 2024), BSE Summer Forum (2024, poster session), CREi Internal Seminar (2023, 2022), UPF Econometrics Internal Seminar (2023), PhD Jamboree BSE (2023)
                    </p>
                </div>
            </div>

            <!-- Always Visible Content -->
            <p class="text-sm font-medium text-gray-800 italic">
                Draft available on demand.
            </p>
        </article>

        <!-- Paper 2 -->
        <article class="mb-10 p-6 bg-gray-50 rounded-lg shadow-md border border-gray-200">
            <!-- Visible Header -->
            <div class="flex justify-between items-start mb-4">
                <div class="flex-1">
                    <h3 class="text-xl font-bold text-gray-900 mb-2">
                        Fiscal Policy and Inflation: Accounting for Non-Linearities in Government Debt (2024)
                    </h3>
                    <div class="text-md text-gray-600 italic">
                        with <a href="https://www.ecb.europa.eu/pub/research/authors/profiles/cristina-checherita-westphal.en.html" target="_blank" class="paper-link">C. Checherita-Westphal</a>.
                        <span class="inline-block bg-blue-100 text-blue-800 text-xs font-semibold ml-2 px-2.5 py-0.5 rounded-full not-italic">ECB Working Paper - No. 2996</span>
                        
                        <!-- PDF link moved here -->
                        <a href="https://www.ecb.europa.eu/pub/pdf/scpwps/ecb.wp2996~5e4df9c08d.en.pdf" target="_blank" class="paper-link text-sm font-medium ml-2 inline-flex items-center not-italic">
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="w-4 h-4 mr-1">
                                <path fill-rule="evenodd" d="M15.625 8.25a.75.75 0 0 1 .75.75v5.5a.75.75 0 0 1-1.5 0v-5.5a.75.75 0 0 1 .75-.75Z" clip-rule="evenodd" />
                                <path d="M10 2.25a.75.75 0 0 1 .75.75v10.19l2.47-2.47a.75.75 0 1 1 1.06 1.06l-3.75 3.75a.75.75 0 0 1-1.06 0l-3.75-3.75a.75.75 0 1 1 1.06-1.06l2.47 2.47V3a.75.75 0 0 1 .75-.75Z" />
                                <path d="M2 9.75A.75.75 0 0 1 2.75 9h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 9.75Z" />
                            </svg>
                            pdf?
                        </a>
                    </div>
                </div>
                <button class="abstract-toggle p-2 rounded-full hover:bg-gray-200 transition-colors ml-4" onclick="toggleAbstract(this)" aria-expanded="false" aria-label="Toggle Abstract">
                    <!-- Chevron down icon -->
                    <svg class="toggle-icon w-5 h-5 text-gray-600 transition-transform duration-300" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" d="m19.5 8.25-7.5 7.5-7.5-7.5" />
                    </svg>
                </button>
            </div>

            <!-- Collapsible Abstract -->
            <div class="abstract-content max-h-0 opacity-0 overflow-hidden transition-all duration-500 ease-in-out">
                <p class="text-gray-700 leading-relaxed text-justify mb-4">
                    This paper investigates the interplay between discretionary fiscal policy and inflation in the euro area, emphasizing the role of public debt levels in modulating this relationship. It explores how fiscal expansions or contractions influence inflationary pressures, particularly under varying debt conditions. The analysis reveals that fiscal policy’s effect on inflation is non-linear, with debt levels significantly affecting the inflationary outcome of fiscal measures. High debt levels tend to amplify the inflation response to fiscal expansions, a finding that holds under multiple analytical frameworks and robustness checks. This paper contributes to the empirical literature by highlighting the critical role of fiscal policy, especially in high-debt environments, and its implications for inflation dynamics in the euro area.
                </p>
            </div>
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
                with <a href="https://sites.google.com/site/regisbarnichon/" target="_blank" class="paper-link">R. Barnichon</a>, 
                <a href="https://www.geertmesters.com/" target="_blank" class="paper-link">G. Mesters</a>
            </div>
        </article>

    </section>

</main>

<script>
    function toggleAbstract(buttonElement) {
        const article = buttonElement.closest('article');
        const content = article.querySelector('.abstract-content');
        const icon = buttonElement.querySelector('.toggle-icon');
        const isExpanded = buttonElement.getAttribute('aria-expanded') === 'true';

        if (isExpanded) {
            // Close it
            buttonElement.setAttribute('aria-expanded', 'false');
            content.style.maxHeight = '0px';
            content.classList.add('opacity-0');
            icon.classList.remove('rotate-180');
        } else {
            // Open it
            buttonElement.setAttribute('aria-expanded', 'true');
            // Set max-height to scrollHeight for a smooth animation to the content's full height
            content.style.maxHeight = content.scrollHeight + 'px';
            content.classList.remove('opacity-0');
            icon.classList.add('rotate-180');
        }
    }
</script>
