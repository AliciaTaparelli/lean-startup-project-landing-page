<!DOCTYPE html>

<html class="light" lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Find Parking - Brisbane CBD Real-time Parking</title>
<link href="https://fonts.googleapis.com" rel="preconnect"/>
<link crossorigin="" href="https://fonts.gstatic.com" rel="preconnect"/>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Plus+Jakarta+Sans:wght@700;800&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<script id="tailwind-config">
      tailwind.config = {
        darkMode: "class",
        theme: {
          extend: {
            colors: {
              "on-primary": "#ffffff",
              "inverse-primary": "#9acbff",
              "surface-tint": "#00629e",
              "surface-container": "#edeef0",
              "secondary-container": "#c0ddff",
              "on-secondary-fixed-variant": "#2d4965",
              "surface-container-highest": "#e1e2e4",
              "on-primary-container": "#fcfcff",
              "surface-bright": "#f8f9fb",
              "surface-container-high": "#e7e8ea",
              "tertiary": "#745b00",
              "surface-variant": "#e1e2e4",
              "on-surface-variant": "#404751",
              "outline": "#707882",
              "on-secondary": "#ffffff",
              "surface-dim": "#d9dadc",
              "on-primary-fixed-variant": "#004a78",
              "on-tertiary-container": "#4f3e00",
              "on-error": "#ffffff",
              "on-secondary-container": "#46617e",
              "inverse-on-surface": "#f0f1f3",
              "secondary": "#45617e",
              "primary": "#00609a",
              "error-container": "#ffdad6",
              "on-tertiary": "#ffffff",
              "inverse-surface": "#2e3132",
              "secondary-fixed": "#cfe5ff",
              "on-background": "#191c1e",
              "surface-container-low": "#f3f4f6",
              "tertiary-container": "#d0a700",
              "on-tertiary-fixed": "#241a00",
              "tertiary-fixed": "#ffe08a",
              "on-primary-fixed": "#001d34",
              "on-secondary-fixed": "#001d34",
              "primary-fixed": "#cfe5ff",
              "secondary-fixed-dim": "#adc9ea",
              "on-tertiary-fixed-variant": "#574400",
              "primary-fixed-dim": "#9acbff",
              "on-error-container": "#93000a",
              "outline-variant": "#c0c7d2",
              "primary-container": "#0079c1",
              "error": "#ba1a1a",
              "on-surface": "#191c1e",
              "tertiary-fixed-dim": "#f1c100",
              "surface": "#f8f9fb",
              "surface-container-lowest": "#ffffff",
              "background": "#f8f9fb"
            },
            fontFamily: {
              "headline": ["Plus Jakarta Sans"],
              "body": ["Inter"],
              "label": ["Inter"]
            },
            borderRadius: {"DEFAULT": "1rem", "lg": "2rem", "xl": "3rem", "full": "9999px"},
          },
        },
      }
    </script>
<style type="text/tailwindcss">
      .material-symbols-outlined {
        font-variation-settings: 'FILL' 0, 'wght' 400, 'GRAD' 0, 'opsz' 24;
      }
      .glass-card {
        background: rgba(255, 255, 255, 0.85);
        backdrop-filter: blur(20px);
      }
      .hero-gradient {
        background: linear-gradient(135deg, #00609a 0%, #0079c1 100%);
      }
    </style>
</head>
<body class="bg-surface font-body text-on-surface">
<header class="fixed top-0 w-full z-50 bg-white/85 backdrop-blur-md border-b border-surface-variant/50">
<nav class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
<div class="text-xl font-black text-slate-900 tracking-tighter font-headline">
            Find Parking
        </div>
<div class="hidden md:flex items-center gap-8 font-headline text-sm font-bold tracking-tight">
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">Features</a>
<a class="text-on-surface-variant hover:text-primary transition-colors" href="#">About</a>
<a class="text-primary font-bold border-b-2 border-primary pb-1" href="#join">Join Waitlist</a>
</div>
<button class="md:hidden p-2 text-on-surface">
<span class="material-symbols-outlined">menu</span>
</button>
</nav>
</header>
<main class="pt-20">
<section class="relative overflow-hidden pt-20 pb-32 px-6">
<div class="max-w-7xl mx-auto grid lg:grid-cols-2 gap-16 items-center">
<div class="relative order-2 lg:order-1">
<div class="relative rounded-xl overflow-hidden shadow-2xl aspect-[4/5] bg-surface-container-high ring-1 ring-black/5">
<img class="w-full h-full object-cover" data-alt="Map of Brisbane CBD with parking pins" data-location="Brisbane CBD" src="https://lh3.googleusercontent.com/aida-public/AB6AXuDrZ4ULrV09shIDRROZmuQrfwIqizWy_rP3rT_ZWD64k7OkKluQs-kvqKTw05QtYAUGssIPARKNmLf2vf6YJO3PfWhaiD1utODlUFk6dGZUpJop32VN35Oc9UuGqwiLMfxL8uk6p7JtoT7Y7kJ03KUGFnpa6LagGQK6fEpUGfQGw8LkX1ckzRliOgO2stiOjfuSrnVWwvYR6cksoz8GdeJ54GsCIAEMHrxhgNKNqM_xLb00nRSoGg2Mt3Uwc-aTBiEV7poeh1tg7qI"/>
<div class="absolute inset-0 bg-black/5"></div>
<div class="absolute top-6 left-6 right-6 glass-card p-4 rounded-full flex items-center gap-3 shadow-xl">
<span class="material-symbols-outlined text-primary">search</span>
<span class="text-sm font-medium text-on-surface-variant">Queen Street Mall, Brisbane</span>
</div>
<div class="absolute top-1/2 left-1/3 glass-card px-3 py-2 rounded-full shadow-lg flex items-center gap-2">
<div class="w-2.5 h-2.5 rounded-full bg-emerald-500"></div>
<span class="text-xs font-bold">12 Spots</span>
</div>
<div class="absolute bottom-1/3 right-1/4 glass-card px-3 py-2 rounded-full shadow-lg flex items-center gap-2 opacity-90">
<div class="w-2.5 h-2.5 rounded-full bg-red-500"></div>
<span class="text-xs font-bold text-on-surface-variant">Full</span>
</div>
</div>
<div class="absolute -z-10 -bottom-10 -left-10 w-64 h-64 bg-primary-fixed-dim rounded-full blur-3xl opacity-20"></div>
</div>
<div class="z-10 order-1 lg:order-2">
<h1 class="font-headline text-5xl md:text-6xl font-extrabold text-on-surface leading-[1.1] tracking-tighter mb-6">
                    Find Parking in Brisbane Before You Arrive
                </h1>
<p class="text-xl text-on-surface-variant mb-10 max-w-xl leading-relaxed">
                    See real-time car park availability across Brisbane CBD — no more driving in circles.
                </p>
<div class="flex flex-col gap-4 max-w-lg">
<div class="flex flex-col sm:flex-row gap-2 bg-surface-container-lowest p-2 rounded-2xl sm:rounded-full shadow-lg ring-1 ring-black/5">
<input class="flex-1 h-14 px-6 bg-transparent rounded-full border-none focus:ring-0 text-on-surface" placeholder="Enter your email" type="email"/>
<button class="h-14 px-10 bg-primary text-on-primary rounded-full font-headline font-bold hover:bg-primary-container transition-all">
                            Join the Waitlist
                        </button>
</div>
<div class="mt-4 flex items-center gap-3">
<div class="flex -space-x-3">
<img class="w-8 h-8 rounded-full border-2 border-surface" data-alt="User" src="https://lh3.googleusercontent.com/aida-public/AB6AXuBnaBBgF0FWTbowruTcSITSTs2jz9LTwLLzwkbQxkgQ0wBonrk1eiUVq20BpIj5IJWrc_vNKZmiUFYh4S2WAtiGHCpfyRY-bTKZIaN1T8b16jyGID9r4XOP1EA4u2mMX4d_S-EV52bmk0ZwWxn3HP44ewkpL2r2DEVLqgIZAXYhdNLzRoDHzrjFXhFqRj4dKlNfqlNUA7oLTuUUi4loJScJhcSLvS1xm7EagkG6-oRaY0e5emCTtGpwndlt9I30uFlk83WGJdNmye4"/>
<img class="w-8 h-8 rounded-full border-2 border-surface" data-alt="User" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCI1zDR_eEqAOjhTl_HnPVHliuWyOG1BtPLy-8gzYF4LnL-KceyV8ryfIHetx1IAve9IDksiaRUXWOP7rvU1DbIya_6_GM7-ggxQJWVLqENtuM1bHwVqg7gGXBEK1eVkU5zDQVcn9R9iyEp0SoV0zX80SFehK-uzoY4Yz65jR_qol1be0jcJYeQoTJa1LzIRGZgr2DqpWxv9QjycKf5V8bt59-4vSP1np-lwvucH7_PqVAWn93HDlYwcnEl2cxsROJ7-47PKWgz2EI"/>
<img class="w-8 h-8 rounded-full border-2 border-surface" data-alt="User" src="https://lh3.googleusercontent.com/aida-public/AB6AXuAR53dRKdB_5tspRLOFG1vE3m4U_bEhGcziad9d2IwHPNTRnrsKt_1ZzzveYIl6akj1sCKcjhEcLdJ3raZhYegpMSO-WBOxLSMg-JBgEZ6PIWQF0n5nysq3fcykm99tvg3Ys6wPjUHs4KD3MD0KzVWVUI1Recc-sGnsTkyRrhnex_90Kh8k2UyEVdRAJEAB3ZZU82vWuCAvcXrOm7h0vdWXAcIxOWEeLOPsZ7M8j6kGW9QIvVL8lgawwWfHbd398-FkjNkt8JMApLQ"/>
</div>
<p class="text-sm font-medium text-on-surface-variant">Join 150+ Brisbane drivers</p>
</div>
</div>
</div>
</div>
</section>
<section class="py-24 bg-surface-container-low">
<div class="max-w-3xl mx-auto px-6">
<div class="text-center mb-16">
<h2 class="font-headline text-3xl font-bold tracking-tight mb-4 text-on-surface">Parking in Brisbane shouldn't be a gamble</h2>
<div class="h-1 w-16 bg-primary mx-auto rounded-full"></div>
</div>
<div class="space-y-6">
<div class="flex items-start gap-6 bg-surface-container-lowest p-8 rounded-2xl border border-outline-variant/30 hover:border-primary/50 transition-colors">
<div class="shrink-0 w-12 h-12 rounded-xl bg-secondary-container/50 flex items-center justify-center">
<span class="material-symbols-outlined text-primary">timer_off</span>
</div>
<div>
<h3 class="font-headline text-lg font-bold mb-1">“Circling for parking wastes time and fuel”</h3>
<p class="text-on-surface-variant leading-relaxed">Circling for parking wastes an average of 15 minutes and valuable fuel every trip.</p>
</div>
</div>
<div class="flex items-start gap-6 bg-surface-container-lowest p-8 rounded-2xl border border-outline-variant/30 hover:border-primary/50 transition-colors">
<div class="shrink-0 w-12 h-12 rounded-xl bg-secondary-container/50 flex items-center justify-center">
<span class="material-symbols-outlined text-primary">analytics</span>
</div>
<div>
<h3 class="font-headline text-lg font-bold mb-1">“CBD parking is unpredictable”</h3>
<p class="text-on-surface-variant leading-relaxed">CBD parking is highly volatile. What was empty five minutes ago is now full.</p>
</div>
</div>
<div class="flex items-start gap-6 bg-surface-container-lowest p-8 rounded-2xl border border-outline-variant/30 hover:border-primary/50 transition-colors">
<div class="shrink-0 w-12 h-12 rounded-xl bg-secondary-container/50 flex items-center justify-center">
<span class="material-symbols-outlined text-primary">warning</span>
</div>
<div>
<h3 class="font-headline text-lg font-bold mb-1">“Peak hours are stressful”</h3>
<p class="text-on-surface-variant leading-relaxed">Morning rushes and evening events turn simple commutes into stressful marathons.</p>
</div>
</div>
</div>
</div>
</section>
<section class="py-24 px-6 bg-white">
<div class="max-w-7xl mx-auto text-center mb-16">
<h2 class="font-headline text-5xl font-extrabold text-on-surface tracking-tighter mb-4">How It Works</h2>
<p class="text-xl text-on-surface-variant max-w-2xl mx-auto">Three simple steps to stress-free parking and travel in Brisbane</p>
</div>
<div class="max-w-7xl mx-auto grid md:grid-cols-3 gap-8">
<div class="relative bg-white p-10 rounded-[2.5rem] border border-surface-variant shadow-sm flex flex-col items-start text-left group hover:shadow-lg transition-shadow">
<div class="absolute top-8 right-10 text-[5rem] font-bold text-surface-container-highest/40 leading-none pointer-events-none select-none">01</div>
<div class="w-16 h-16 bg-[#0a0a1a] rounded-2xl flex items-center justify-center mb-10">
<span class="material-symbols-outlined text-white text-3xl">search</span>
</div>
<h3 class="font-headline text-2xl font-extrabold mb-4 text-on-surface">Enter Your Destination</h3>
<p class="text-on-surface-variant leading-relaxed font-medium">Tell us where you're heading in Brisbane and we'll find the best parking options nearby.</p>
</div>
<div class="relative bg-white p-10 rounded-[2.5rem] border border-surface-variant shadow-sm flex flex-col items-start text-left group hover:shadow-lg transition-shadow">
<div class="absolute top-8 right-10 text-[5rem] font-bold text-surface-container-highest/40 leading-none pointer-events-none select-none">02</div>
<div class="w-16 h-16 bg-[#0a0a1a] rounded-2xl flex items-center justify-center mb-10">
<span class="material-symbols-outlined text-white text-3xl">directions_car</span>
</div>
<h3 class="font-headline text-2xl font-extrabold mb-4 text-on-surface">Choose Your Spot</h3>
<p class="text-on-surface-variant leading-relaxed font-medium">Browse available street parking or private lots with real-time availability and pricing.</p>
</div>
<div class="relative bg-white p-10 rounded-[2.5rem] border border-surface-variant shadow-sm flex flex-col items-start text-left group hover:shadow-lg transition-shadow">
<div class="absolute top-8 right-10 text-[5rem] font-bold text-surface-container-highest/40 leading-none pointer-events-none select-none">03</div>
<div class="w-16 h-16 bg-[#0a0a1a] rounded-2xl flex items-center justify-center mb-10">
<span class="material-symbols-outlined text-white text-3xl">directions_bus</span>
</div>
<h3 class="font-headline text-2xl font-extrabold mb-4 text-on-surface">Get Transit Options</h3>
<p class="text-on-surface-variant leading-relaxed font-medium">If your parking is far from your destination, we'll suggest the fastest public transport route.</p>
</div>
</div>
</section>
<section class="py-24 px-6">
<div class="max-w-7xl mx-auto rounded-3xl overflow-hidden bg-primary relative min-h-[500px] flex items-center">
<img class="absolute inset-0 w-full h-full object-cover opacity-30 mix-blend-overlay" data-alt="Aerial city view" src="https://lh3.googleusercontent.com/aida-public/AB6AXuCKMwn2VpakgM5JgUn9zl1JfwPqYZizQIej68C_IeUBzODNqF18hp7QLM-C8zu0ZSU9JydQV1qpCvA2IO47wdMtafBPWRIjO74QheSGmoqdnW1XQcOgWyZ78ijtmRBgfz4Ev2F-S55kc-qcYyH7cuBcSovJxTwsv3EwHlj9btsELgXkZPt7ZVLRJb61HzzwIJHL2Dt9w5tVJn_QRDq6AKEiRPxvNRoMUKS762hoVAyO3qx7nPYSW_pKd6LtbK8H2MwtookGStfEijM"/>
<div class="relative z-10 p-12 md:p-20 max-w-3xl">
<h2 class="font-headline text-4xl md:text-5xl font-extrabold text-on-primary mb-10 leading-tight">
                    Our app shows real-time parking availability across Brisbane so you always know exactly where to go.
                </h2>
<div class="flex flex-wrap items-center gap-8">
<div class="flex items-center gap-3 text-on-primary/90 font-medium">
<span class="material-symbols-outlined text-tertiary-fixed">check_circle</span>
                        Live parking availability
                    </div>
<div class="flex items-center gap-3 text-on-primary/90 font-medium">
<span class="material-symbols-outlined text-tertiary-fixed">check_circle</span>
                        Navigation directions
                    </div>
</div>
</div>
</div>
</section>
<section class="py-24 bg-surface px-6">
<div class="max-w-4xl mx-auto">
<div class="text-center mb-16">
<span class="text-primary font-bold tracking-widest uppercase text-xs">Platform Features</span>
<h2 class="font-headline text-3xl font-bold mt-2">Everything you need to find a spot</h2>
</div>
<div class="grid md:grid-cols-2 gap-x-12 gap-y-10">
<div class="flex gap-5 items-start">
<span class="material-symbols-outlined text-primary text-3xl shrink-0" style="font-variation-settings: 'FILL' 1;">live_tv</span>
<div>
<h4 class="font-headline font-bold text-lg mb-1">Live parking availability</h4>
<p class="text-on-surface-variant text-sm leading-relaxed">Up-to-the-minute status of every major parking structure in the CBD.</p>
</div>
</div>
<div class="flex gap-5 items-start">
<span class="material-symbols-outlined text-primary text-3xl shrink-0" style="font-variation-settings: 'FILL' 1;">near_me</span>
<div>
<h4 class="font-headline font-bold text-lg mb-1">Directions to closest spot</h4>
<p class="text-on-surface-variant text-sm leading-relaxed">Direct turn-by-turn navigation to the specific entrance of the closest available spot.</p>
</div>
</div>
<div class="flex gap-5 items-start">
<span class="material-symbols-outlined text-primary text-3xl shrink-0" style="font-variation-settings: 'FILL' 1;">energy_savings_leaf</span>
<div>
<h4 class="font-headline font-bold text-lg mb-1">Save time and fuel</h4>
<p class="text-on-surface-variant text-sm leading-relaxed">Reduce carbon footprint and personal stress by eliminating unnecessary idling.</p>
</div>
</div>
<div class="flex gap-5 items-start">
<span class="material-symbols-outlined text-primary text-3xl shrink-0" style="font-variation-settings: 'FILL' 1;">location_city</span>
<div>
<h4 class="font-headline font-bold text-lg mb-1">Works across Brisbane CBD, Fortitude Valley, South Bank</h4>
<p class="text-on-surface-variant text-sm leading-relaxed">Active across Brisbane's most critical high-traffic parking zones.</p>
</div>
</div>
</div>
</div>
</section>
<section class="py-24 bg-surface-container px-6">
<div class="max-w-7xl mx-auto">
<div class="flex flex-col lg:flex-row items-center justify-between mb-16 gap-8 text-center lg:text-left">
<div>
<h2 class="font-headline text-4xl font-extrabold text-on-surface mb-2">Join 150+ Brisbane drivers already interested</h2>
<p class="text-on-surface-variant text-lg">Helping locals navigate the urban jungle more efficiently.</p>
</div>
</div>
<div class="grid md:grid-cols-3 gap-6">
<div class="bg-surface-container-lowest p-8 rounded-2xl shadow-sm border border-outline-variant/20 flex flex-col h-full">
<p class="italic text-on-surface-variant flex-1 mb-8">"Would use this every day for uni. QUT parking is a nightmare and knowing before I get there would change everything."</p>
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-secondary-container"></div>
<div>
<div class="font-bold text-on-surface text-sm">Sarah M.</div>
<div class="text-xs text-on-surface-variant">QUT Student</div>
</div>
</div>
</div>
<div class="bg-surface-container-lowest p-8 rounded-2xl shadow-sm border border-outline-variant/20 flex flex-col h-full">
<p class="italic text-on-surface-variant flex-1 mb-8">"Parking in the city is the worst — this would help so much with my client meetings in the CBD."</p>
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-secondary-container"></div>
<div>
<div class="font-bold text-on-surface text-sm">James R.</div>
<div class="text-xs text-on-surface-variant">Sales Executive</div>
</div>
</div>
</div>
<div class="bg-surface-container-lowest p-8 rounded-2xl shadow-sm border border-outline-variant/20 flex flex-col h-full">
<p class="italic text-on-surface-variant flex-1 mb-8">"Finally, someone is fixing the South Bank parking shuffle! Can't wait for the launch."</p>
<div class="flex items-center gap-3">
<div class="w-10 h-10 rounded-full bg-secondary-container"></div>
<div>
<div class="font-bold text-on-surface text-sm">Michael L.</div>
<div class="text-xs text-on-surface-variant">Hospitality Manager</div>
</div>
</div>
</div>
</div>
</div>
</section>
<section class="py-32 px-6" id="join">
<div class="max-w-4xl mx-auto text-center">
<div class="inline-flex items-center gap-2 px-4 py-2 bg-secondary-container text-on-secondary-container rounded-full mb-8 font-bold text-sm">
<span class="material-symbols-outlined text-[18px]">verified</span>
                Early Access Now Open
            </div>
<h2 class="font-headline text-5xl font-extrabold mb-8 tracking-tighter">Be the first to try it</h2>
<p class="text-xl text-on-surface-variant mb-12 max-w-2xl mx-auto">
                Secure your spot on the waitlist and get notified the moment we launch in the Brisbane CBD.
            </p>
<div class="bg-surface-container-lowest p-2 rounded-2xl sm:rounded-full shadow-2xl flex flex-col sm:flex-row gap-2 max-w-xl mx-auto border border-outline-variant/20">
<input class="flex-1 h-14 px-8 bg-transparent border-none focus:ring-0 text-on-surface font-medium" placeholder="Your best email" type="email"/>
<button class="h-14 px-10 bg-primary text-on-primary rounded-full font-headline font-bold hover:bg-primary-container transition-all">
                    Join Waitlist
                </button>
</div>
<p class="mt-6 text-sm text-on-surface-variant font-medium">No spam. Only important updates about our Brisbane launch.</p>
</div>
</section>
</main>
<footer class="w-full py-16 px-6 border-t border-surface-variant/30 bg-surface-container-low">
<div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center gap-8">
<div class="flex flex-col items-center md:items-start gap-2">
<span class="font-headline font-black text-xl text-on-surface">Find Parking</span>
<p class="text-sm text-on-surface-variant">© 2024 Find Parking. Proudly serving the Brisbane CBD community.</p>
</div>
<div class="flex items-center gap-8 text-sm font-medium text-on-surface-variant">
<a class="hover:text-primary transition-colors" href="#">Privacy Policy</a>
<a class="hover:text-primary transition-colors" href="#">Terms</a>
<a class="hover:text-primary transition-colors" href="#">Contact</a>
</div>
<div class="flex gap-4">
<span class="material-symbols-outlined text-on-surface-variant hover:text-primary cursor-pointer transition-colors">public</span>
<span class="material-symbols-outlined text-on-surface-variant hover:text-primary cursor-pointer transition-colors">share</span>
</div>
</div>
</footer>
</body></html>
