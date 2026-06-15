<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>MUNverse â€” Model United Nations Training Simulator</title>
    <meta name="description"
        content="MUNverse is an interactive MUN training simulator with AI mentors, gamification, speech evaluation, and a full simulated conference experience for students." />
    <meta name="keywords" content="MUN, Model United Nations, training, simulator, debate, diplomacy, education" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
        href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;500;600;700;800;900&family=Inter:wght@300;400;500;600;700&display=swap"
        rel="stylesheet" />
    <style>
        /* ================================================
   MUNVERSE â€” MAIN DESIGN SYSTEM
   ================================================ */

        /* === COLOR TOKENS === */
        :root {
            --bg-base: #030914;
            --bg-surface: #0a1020;
            --bg-elevated: #111827;
            --bg-glass: rgba(255, 255, 255, 0.04);
            --bg-glass-hover: rgba(255, 255, 255, 0.08);
            --bg-glass-active: rgba(212, 175, 55, 0.08);

            --gold: #D4AF37;
            --gold-light: #F0D060;
            --gold-dark: #9A7C1A;
            --gold-glow: rgba(212, 175, 55, 0.4);
            --blue: #4FC3F7;
            --blue-dark: #0288D1;
            --emerald: #00C896;
            --emerald-dark: #00956E;
            --purple: #845EF7;
            --coral: #FF6348;
            --rose: #FF6B9D;
            --amber: #FCC419;

            --text-primary: #EEF0FF;
            --text-secondary: #8A93B8;
            --text-muted: #525878;
            --text-gold: #D4AF37;

            --border: rgba(255, 255, 255, 0.07);
            --border-subtle: rgba(255, 255, 255, 0.04);
            --border-gold: rgba(212, 175, 55, 0.3);
            --border-active: rgba(212, 175, 55, 0.7);
            --border-blue: rgba(79, 195, 247, 0.3);
            --border-emerald: rgba(0, 200, 150, 0.3);

            --grad-gold: linear-gradient(135deg, #D4AF37 0%, #F0D060 50%, #A08020 100%);
            --grad-gold-h: linear-gradient(90deg, #D4AF37, #F0D060);
            --grad-blue: linear-gradient(135deg, #4FC3F7, #0288D1);
            --grad-emerald: linear-gradient(135deg, #00C896, #00956E);
            --grad-purple: linear-gradient(135deg, #845EF7, #5C3DC4);
            --grad-coral: linear-gradient(135deg, #FF6348, #CC3010);
            --grad-surface: linear-gradient(180deg, #0a1020 0%, #030914 100%);
            --grad-card: linear-gradient(135deg, rgba(255, 255, 255, 0.06) 0%, rgba(255, 255, 255, 0.02) 100%);

            --shadow-sm: 0 2px 8px rgba(0, 0, 0, 0.4);
            --shadow-md: 0 4px 20px rgba(0, 0, 0, 0.5);
            --shadow-lg: 0 8px 40px rgba(0, 0, 0, 0.6);
            --shadow-gold: 0 0 40px rgba(212, 175, 55, 0.25);
            --shadow-blue: 0 0 40px rgba(79, 195, 247, 0.2);
            --shadow-inset: inset 0 1px 0 rgba(255, 255, 255, 0.06);

            --space-xs: 4px;
            --space-sm: 8px;
            --space-md: 16px;
            --space-lg: 24px;
            --space-xl: 32px;
            --space-2xl: 48px;
            --space-3xl: 64px;
            --space-4xl: 96px;

            --radius-sm: 6px;
            --radius-md: 12px;
            --radius-lg: 18px;
            --radius-xl: 24px;
            --radius-2xl: 32px;
            --radius-full: 9999px;

            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            --transition-fast: all 0.15s ease;
            --transition-slow: all 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            --transition-bounce: all 0.4s cubic-bezier(0.34, 1.56, 0.64, 1);

            --z-base: 0;
            --z-above: 10;
            --z-modal: 100;
            --z-nav: 200;
            --z-toast: 300;
            --z-loading: 400;
        }

        /* === RESET === */
        *,
        *::before,
        *::after {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        html {
            font-size: 16px;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Inter', sans-serif;
            background-color: var(--bg-base);
            color: var(--text-primary);
            line-height: 1.6;
            min-height: 100vh;
            overflow-x: hidden;
        }

        /* Ambient background mesh */
        body::before {
            content: '';
            position: fixed;
            inset: 0;
            background:
                radial-gradient(ellipse 60% 40% at 15% 60%, rgba(79, 195, 247, 0.07) 0%, transparent 70%),
                radial-gradient(ellipse 50% 50% at 85% 15%, rgba(212, 175, 55, 0.07) 0%, transparent 70%),
                radial-gradient(ellipse 40% 40% at 50% 90%, rgba(132, 94, 247, 0.05) 0%, transparent 70%);
            pointer-events: none;
            z-index: 0;
        }

        /* Stars effect */
        body::after {
            content: '';
            position: fixed;
            inset: 0;
            background-image:
                radial-gradient(1px 1px at 20% 30%, rgba(255, 255, 255, 0.15) 0%, transparent 100%),
                radial-gradient(1px 1px at 40% 70%, rgba(255, 255, 255, 0.1) 0%, transparent 100%),
                radial-gradient(1px 1px at 60% 20%, rgba(255, 255, 255, 0.12) 0%, transparent 100%),
                radial-gradient(1px 1px at 80% 50%, rgba(255, 255, 255, 0.08) 0%, transparent 100%),
                radial-gradient(1px 1px at 10% 80%, rgba(255, 255, 255, 0.1) 0%, transparent 100%),
                radial-gradient(1px 1px at 90% 90%, rgba(255, 255, 255, 0.08) 0%, transparent 100%),
                radial-gradient(1px 1px at 30% 10%, rgba(255, 255, 255, 0.12) 0%, transparent 100%),
                radial-gradient(1px 1px at 70% 40%, rgba(255, 255, 255, 0.1) 0%, transparent 100%);
            pointer-events: none;
            z-index: 0;
        }

        /* === TYPOGRAPHY === */
        h1,
        h2,
        h3,
        h4,
        h5,
        h6 {
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            line-height: 1.2;
        }

        h1 {
            font-size: clamp(2rem, 5vw, 3.5rem);
        }

        h2 {
            font-size: clamp(1.5rem, 3vw, 2.5rem);
        }

        h3 {
            font-size: clamp(1.1rem, 2vw, 1.6rem);
        }

        h4 {
            font-size: 1.1rem;
        }

        p {
            line-height: 1.7;
            color: var(--text-secondary);
        }

        .text-gold {
            background: var(--grad-gold);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .text-blue {
            color: var(--blue);
        }

        .text-emerald {
            color: var(--emerald);
        }

        .text-purple {
            color: var(--purple);
        }

        .text-coral {
            color: var(--coral);
        }

        .text-primary {
            color: var(--text-primary);
        }

        .text-secondary {
            color: var(--text-secondary);
        }

        .text-center {
            text-align: center;
        }

        .text-sm {
            font-size: 0.875rem;
        }

        .text-xs {
            font-size: 0.75rem;
        }

        .font-bold {
            font-weight: 700;
        }

        .font-outfit {
            font-family: 'Outfit', sans-serif;
        }

        /* === LAYOUT === */
        #app {
            position: relative;
            z-index: 1;
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 var(--space-lg);
        }

        .page {
            min-height: 100vh;
            padding: 90px var(--space-lg) var(--space-4xl);
            animation: fadeSlideIn 0.4s ease;
        }

        .page-narrow {
            max-width: 800px;
            margin: 0 auto;
        }

        .page-title {
            text-align: center;
            margin-bottom: var(--space-2xl);
        }

        .page-title h2 {
            background: var(--grad-gold);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            margin-bottom: var(--space-sm);
        }

        .page-title p {
            color: var(--text-secondary);
            font-size: 1.05rem;
            max-width: 600px;
            margin: 0 auto;
        }

        .page-header {
            display: flex;
            align-items: center;
            gap: var(--space-md);
            margin-bottom: var(--space-xl);
        }

        /* Grids */
        .grid-2 {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: var(--space-lg);
        }

        .grid-3 {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: var(--space-lg);
        }

        .grid-auto {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: var(--space-lg);
        }

        @media (max-width: 900px) {
            .grid-3 {
                grid-template-columns: repeat(2, 1fr);
            }
        }

        @media (max-width: 600px) {

            .grid-2,
            .grid-3,
            .grid-auto {
                grid-template-columns: 1fr;
            }

            .page {
                padding: 80px var(--space-md) var(--space-3xl);
            }
        }

        /* Flex */
        .flex {
            display: flex;
        }

        .flex-center {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .flex-between {
            display: flex;
            align-items: center;
            justify-content: space-between;
        }

        .flex-col {
            display: flex;
            flex-direction: column;
        }

        .flex-wrap {
            flex-wrap: wrap;
        }

        .align-center {
            align-items: center;
        }

        .gap-xs {
            gap: var(--space-xs);
        }

        .gap-sm {
            gap: var(--space-sm);
        }

        .gap-md {
            gap: var(--space-md);
        }

        .gap-lg {
            gap: var(--space-lg);
        }

        /* Spacing utilities */
        .mb-sm {
            margin-bottom: var(--space-sm);
        }

        .mb-md {
            margin-bottom: var(--space-md);
        }

        .mb-lg {
            margin-bottom: var(--space-lg);
        }

        .mb-xl {
            margin-bottom: var(--space-xl);
        }

        .mt-md {
            margin-top: var(--space-md);
        }

        .mt-lg {
            margin-top: var(--space-lg);
        }

        /* === SCROLLBAR === */
        ::-webkit-scrollbar {
            width: 5px;
        }

        ::-webkit-scrollbar-track {
            background: transparent;
        }

        ::-webkit-scrollbar-thumb {
            background: var(--border);
            border-radius: var(--radius-full);
        }

        ::-webkit-scrollbar-thumb:hover {
            background: var(--text-muted);
        }

        /* === LOADING SCREEN === */
        #loading-screen {
            position: fixed;
            inset: 0;
            background: var(--bg-base);
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            z-index: var(--z-loading);
            transition: opacity 0.6s ease, visibility 0.6s ease;
        }

        #loading-screen.hidden {
            opacity: 0;
            visibility: hidden;
            pointer-events: none;
        }

        .loading-globe {
            font-size: 5rem;
            animation: globeFloat 2s ease-in-out infinite, globeSpin 8s linear infinite;
            margin-bottom: var(--space-xl);
            filter: drop-shadow(0 0 20px rgba(79, 195, 247, 0.4));
        }

        .loading-title {
            font-family: 'Outfit', sans-serif;
            font-size: 3rem;
            font-weight: 900;
            background: var(--grad-gold);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            letter-spacing: 0.02em;
            margin-bottom: var(--space-xs);
        }

        .loading-subtitle {
            color: var(--text-secondary);
            font-size: 0.9rem;
            letter-spacing: 0.1em;
            text-transform: uppercase;
            margin-bottom: var(--space-2xl);
        }

        .loading-bar {
            width: 240px;
            height: 3px;
            background: var(--bg-elevated);
            border-radius: var(--radius-full);
            overflow: hidden;
            margin-bottom: var(--space-md);
        }

        .loading-progress {
            height: 100%;
            width: 0%;
            background: var(--grad-gold);
            border-radius: var(--radius-full);
            transition: width 0.3s ease;
        }

        .loading-tip {
            color: var(--text-muted);
            font-size: 0.8rem;
            font-style: italic;
        }

        /* === TOP NAV === */
        #top-nav {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: var(--z-nav);
            padding: 12px var(--space-xl);
            background: rgba(3, 9, 20, 0.85);
            backdrop-filter: blur(24px);
            -webkit-backdrop-filter: blur(24px);
            border-bottom: 1px solid var(--border);
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: var(--shadow-sm);
        }

        #top-nav.hidden {
            display: none;
        }

        .nav-logo {
            font-family: 'Outfit', sans-serif;
            font-size: 1.3rem;
            font-weight: 800;
            background: var(--grad-gold);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            cursor: pointer;
            text-decoration: none;
            letter-spacing: 0.02em;
        }

        .nav-center {
            display: flex;
            align-items: center;
            gap: var(--space-xs);
        }

        .nav-breadcrumb {
            color: var(--text-muted);
            font-size: 0.8rem;
        }

        .nav-right {
            display: flex;
            align-items: center;
            gap: var(--space-sm);
        }

        .nav-xp-pill {
            display: flex;
            align-items: center;
            gap: 6px;
            padding: 6px 16px;
            background: rgba(212, 175, 55, 0.1);
            border: 1px solid var(--border-gold);
            border-radius: var(--radius-full);
            font-size: 0.85rem;
            font-weight: 700;
            color: var(--gold);
            font-family: 'Outfit', sans-serif;
        }

        .nav-level-tag {
            font-size: 0.7rem;
            font-weight: 600;
            color: var(--text-muted);
            text-transform: uppercase;
            letter-spacing: 0.08em;
        }

        .nav-icon-btn {
            width: 36px;
            height: 36px;
            background: var(--bg-glass);
            border: 1px solid var(--border);
            border-radius: var(--radius-full);
            cursor: pointer;
            font-size: 1rem;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: var(--transition);
            color: var(--text-secondary);
            text-decoration: none;
        }

        .nav-icon-btn:hover {
            background: var(--bg-glass-hover);
            border-color: var(--border-gold);
            color: var(--gold);
            transform: translateY(-1px);
        }

        /* === NOTIFICATION TOAST === */
        #notification-container {
            position: fixed;
            top: 80px;
            right: var(--space-lg);
            z-index: var(--z-toast);
            display: flex;
            flex-direction: column;
            gap: var(--space-sm);
            max-width: 320px;
        }

        .toast {
            padding: var(--space-md) var(--space-lg);
            background: var(--bg-elevated);
            border: 1px solid var(--border);
            border-radius: var(--radius-md);
            box-shadow: var(--shadow-md);
            animation: slideInRight 0.35s cubic-bezier(0.34, 1.56, 0.64, 1);
            cursor: pointer;
        }

        .toast.xp {
            border-color: var(--gold);
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.15);
        }

        .toast.badge {
            border-color: var(--purple);
            box-shadow: 0 0 20px rgba(132, 94, 247, 0.15);
        }

        .toast.success {
            border-color: var(--emerald);
        }

        .toast.info {
            border-color: var(--blue);
        }

        .toast-header {
            display: flex;
            align-items: center;
            gap: var(--space-sm);
            margin-bottom: 4px;
            font-weight: 700;
            font-size: 0.9rem;
        }

        .toast-body {
            font-size: 0.82rem;
            color: var(--text-secondary);
        }

        .toast.hide {
            animation: slideOutRight 0.3s ease forwards;
        }

        /* ================================================
   MUNVERSE â€” COMPONENT STYLES
   ================================================ */

        /* === BUTTONS === */
        .btn {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: var(--space-sm);
            padding: 12px 28px;
            border-radius: var(--radius-full);
            font-family: 'Outfit', sans-serif;
            font-weight: 600;
            font-size: 0.95rem;
            cursor: pointer;
            border: none;
            outline: none;
            transition: var(--transition-bounce);
            text-decoration: none;
            letter-spacing: 0.02em;
            white-space: nowrap;
        }

        .btn:active {
            transform: scale(0.97);
        }

        .btn-gold {
            background: var(--grad-gold);
            color: #0a0800;
            box-shadow: 0 4px 20px rgba(212, 175, 55, 0.4);
        }

        .btn-gold:hover {
            box-shadow: 0 6px 30px rgba(212, 175, 55, 0.6);
            transform: translateY(-2px);
        }

        .btn-outline-gold {
            background: transparent;
            color: var(--gold);
            border: 1px solid var(--border-gold);
        }

        .btn-outline-gold:hover {
            background: rgba(212, 175, 55, 0.1);
            border-color: var(--gold);
            box-shadow: var(--shadow-gold);
            transform: translateY(-2px);
        }

        .btn-glass {
            background: var(--bg-glass);
            color: var(--text-primary);
            border: 1px solid var(--border);
            backdrop-filter: blur(10px);
        }

        .btn-glass:hover {
            background: var(--bg-glass-hover);
            border-color: var(--border-gold);
            transform: translateY(-2px);
        }

        .btn-blue {
            background: var(--grad-blue);
            color: #fff;
            box-shadow: 0 4px 20px rgba(79, 195, 247, 0.3);
        }

        .btn-blue:hover {
            box-shadow: 0 6px 30px rgba(79, 195, 247, 0.5);
            transform: translateY(-2px);
        }

        .btn-emerald {
            background: var(--grad-emerald);
            color: #fff;
            box-shadow: 0 4px 20px rgba(0, 200, 150, 0.3);
        }

        .btn-emerald:hover {
            box-shadow: 0 6px 30px rgba(0, 200, 150, 0.5);
            transform: translateY(-2px);
        }

        .btn-danger {
            background: var(--grad-coral);
            color: #fff;
            box-shadow: 0 4px 20px rgba(255, 99, 72, 0.3);
        }

        .btn-danger:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 30px rgba(255, 99, 72, 0.5);
        }

        .btn-sm {
            padding: 8px 18px;
            font-size: 0.85rem;
        }

        .btn-lg {
            padding: 16px 40px;
            font-size: 1.1rem;
        }

        .btn-full {
            width: 100%;
        }

        .btn:disabled {
            opacity: 0.4;
            cursor: not-allowed;
            transform: none !important;
            box-shadow: none !important;
        }

        /* === GLASS CARD === */
        .card {
            background: var(--grad-card);
            border: 1px solid var(--border);
            border-radius: var(--radius-lg);
            padding: var(--space-lg);
            transition: var(--transition);
            position: relative;
            overflow: hidden;
            box-shadow: var(--shadow-sm);
        }

        .card::before {
            content: '';
            position: absolute;
            inset: 0;
            background: var(--shadow-inset);
            pointer-events: none;
        }

        .card:hover {
            border-color: rgba(255, 255, 255, 0.12);
            box-shadow: var(--shadow-md);
            transform: translateY(-3px);
        }

        .card-selectable {
            cursor: pointer;
        }

        .card-selectable:hover {
            border-color: var(--border-gold);
            box-shadow: var(--shadow-gold);
            transform: translateY(-4px);
        }

        .card-selectable.selected {
            border-color: var(--gold);
            background: rgba(212, 175, 55, 0.06);
            box-shadow: var(--shadow-gold);
        }

        .card-glow-blue:hover {
            border-color: var(--border-blue);
            box-shadow: var(--shadow-blue);
        }

        .card-glow-emerald:hover {
            border-color: var(--border-emerald);
            box-shadow: 0 0 30px rgba(0, 200, 150, 0.2);
        }

        /* === BADGE / CHIP === */
        .badge {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            padding: 4px 12px;
            border-radius: var(--radius-full);
            font-size: 0.75rem;
            font-weight: 600;
            font-family: 'Outfit', sans-serif;
            letter-spacing: 0.04em;
        }

        .badge-gold {
            background: rgba(212, 175, 55, 0.15);
            color: var(--gold);
            border: 1px solid var(--border-gold);
        }

        .badge-blue {
            background: rgba(79, 195, 247, 0.1);
            color: var(--blue);
            border: 1px solid var(--border-blue);
        }

        .badge-emerald {
            background: rgba(0, 200, 150, 0.1);
            color: var(--emerald);
            border: 1px solid var(--border-emerald);
        }

        .badge-purple {
            background: rgba(132, 94, 247, 0.1);
            color: var(--purple);
            border: 1px solid rgba(132, 94, 247, 0.3);
        }

        .badge-coral {
            background: rgba(255, 99, 72, 0.1);
            color: var(--coral);
            border: 1px solid rgba(255, 99, 72, 0.3);
        }

        .badge-gray {
            background: rgba(255, 255, 255, 0.06);
            color: var(--text-secondary);
            border: 1px solid var(--border);
        }

        /* === XP BAR === */
        .xp-bar-container {
            display: flex;
            align-items: center;
            gap: var(--space-md);
        }

        .xp-bar {
            flex: 1;
            height: 8px;
            background: var(--bg-elevated);
            border-radius: var(--radius-full);
            overflow: hidden;
            position: relative;
        }

        .xp-bar-fill {
            height: 100%;
            background: var(--grad-gold);
            border-radius: var(--radius-full);
            transition: width 0.8s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
        }

        .xp-bar-fill::after {
            content: '';
            position: absolute;
            top: 0;
            right: 0;
            width: 20px;
            height: 100%;
            background: rgba(255, 255, 255, 0.3);
            border-radius: var(--radius-full);
            animation: shimmer 2s ease infinite;
        }

        .xp-label {
            font-family: 'Outfit', sans-serif;
            font-size: 0.8rem;
            color: var(--text-secondary);
            white-space: nowrap;
        }

        /* === SCORE CIRCLE === */
        .score-circle {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            border: 3px solid;
            font-family: 'Outfit', sans-serif;
        }

        .score-circle .score-val {
            font-size: 1.4rem;
            font-weight: 800;
        }

        .score-circle .score-lbl {
            font-size: 0.6rem;
            text-transform: uppercase;
            letter-spacing: 0.06em;
        }

        .score-circle.gold {
            border-color: var(--gold);
            color: var(--gold);
        }

        .score-circle.blue {
            border-color: var(--blue);
            color: var(--blue);
        }

        .score-circle.emerald {
            border-color: var(--emerald);
            color: var(--emerald);
        }

        .score-circle.purple {
            border-color: var(--purple);
            color: var(--purple);
        }

        /* === TABS === */
        .tab-list {
            display: flex;
            gap: 4px;
            background: var(--bg-elevated);
            border-radius: var(--radius-lg);
            padding: 4px;
            margin-bottom: var(--space-xl);
            overflow-x: auto;
        }

        .tab-btn {
            flex: 1;
            min-width: fit-content;
            padding: 10px 20px;
            background: transparent;
            border: none;
            border-radius: var(--radius-md);
            color: var(--text-secondary);
            font-family: 'Outfit', sans-serif;
            font-weight: 600;
            font-size: 0.9rem;
            cursor: pointer;
            transition: var(--transition);
            white-space: nowrap;
        }

        .tab-btn.active {
            background: var(--bg-glass-active);
            color: var(--gold);
            border: 1px solid var(--border-gold);
        }

        .tab-btn:hover:not(.active) {
            color: var(--text-primary);
            background: var(--bg-glass);
        }

        .tab-panel {
            display: none;
            animation: fadeSlideIn 0.3s ease;
        }

        .tab-panel.active {
            display: block;
        }

        /* === STEPPER / WIZARD === */
        .stepper {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 0;
            margin-bottom: var(--space-2xl);
            overflow-x: auto;
            padding: var(--space-sm);
        }

        .step-item {
            display: flex;
            align-items: center;
        }

        .step-circle {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            font-size: 0.9rem;
            border: 2px solid var(--border);
            background: var(--bg-elevated);
            color: var(--text-muted);
            transition: var(--transition);
            flex-shrink: 0;
            position: relative;
            z-index: 1;
        }

        .step-item.done .step-circle {
            background: var(--grad-emerald);
            border-color: var(--emerald);
            color: #fff;
        }

        .step-item.active .step-circle {
            background: var(--grad-gold);
            border-color: var(--gold);
            color: #0a0800;
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.4);
        }

        .step-label {
            font-size: 0.7rem;
            color: var(--text-muted);
            text-align: center;
            margin-top: 4px;
            max-width: 70px;
            line-height: 1.2;
        }

        .step-item.active .step-label,
        .step-item.done .step-label {
            color: var(--text-secondary);
        }

        .step-connector {
            height: 2px;
            width: 40px;
            background: var(--border);
            flex-shrink: 0;
        }

        .step-connector.done {
            background: var(--grad-gold);
        }

        .step-inner {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        /* === CHAT INTERFACE === */
        .chat-container {
            display: flex;
            flex-direction: column;
            height: 450px;
            background: var(--bg-elevated);
            border: 1px solid var(--border);
            border-radius: var(--radius-lg);
            overflow: hidden;
        }

        .chat-messages {
            flex: 1;
            overflow-y: auto;
            padding: var(--space-lg);
            display: flex;
            flex-direction: column;
            gap: var(--space-md);
        }

        .chat-msg {
            display: flex;
            gap: var(--space-sm);
            animation: fadeSlideIn 0.3s ease;
        }

        .chat-msg.user {
            flex-direction: row-reverse;
        }

        .chat-avatar {
            width: 36px;
            height: 36px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
            flex-shrink: 0;
            background: var(--bg-elevated);
            border: 1px solid var(--border);
        }

        .chat-bubble {
            max-width: 80%;
            padding: 10px 16px;
            border-radius: var(--radius-md);
            font-size: 0.9rem;
            line-height: 1.6;
            color: var(--text-primary);
        }

        .chat-msg.bot .chat-bubble {
            background: rgba(79, 195, 247, 0.08);
            border: 1px solid var(--border-blue);
            border-top-left-radius: 4px;
        }

        .chat-msg.user .chat-bubble {
            background: rgba(212, 175, 55, 0.08);
            border: 1px solid var(--border-gold);
            border-top-right-radius: 4px;
        }

        .chat-input-row {
            display: flex;
            gap: var(--space-sm);
            padding: var(--space-md);
            border-top: 1px solid var(--border);
            background: var(--bg-surface);
        }

        .chat-input {
            flex: 1;
            background: var(--bg-elevated);
            border: 1px solid var(--border);
            border-radius: var(--radius-full);
            padding: 10px 20px;
            color: var(--text-primary);
            font-family: 'Inter', sans-serif;
            font-size: 0.9rem;
            outline: none;
            transition: var(--transition);
        }

        .chat-input:focus {
            border-color: var(--border-blue);
            box-shadow: 0 0 15px rgba(79, 195, 247, 0.1);
        }

        .chat-input::placeholder {
            color: var(--text-muted);
        }

        .chat-quick-btns {
            display: flex;
            flex-wrap: wrap;
            gap: var(--space-sm);
            padding: 0 var(--space-md) var(--space-md);
        }

        .quick-btn {
            padding: 6px 14px;
            background: var(--bg-glass);
            border: 1px solid var(--border);
            border-radius: var(--radius-full);
            color: var(--text-secondary);
            font-size: 0.8rem;
            cursor: pointer;
            transition: var(--transition);
        }

        .quick-btn:hover {
            border-color: var(--border-blue);
            color: var(--blue);
        }

        /* === TEXTAREA === */
        .textarea {
            width: 100%;
            background: var(--bg-elevated);
            border: 1px solid var(--border);
            border-radius: var(--radius-md);
            padding: var(--space-md);
            color: var(--text-primary);
            font-family: 'Inter', sans-serif;
            font-size: 0.92rem;
            line-height: 1.7;
            resize: vertical;
            outline: none;
            transition: var(--transition);
            min-height: 120px;
        }

        .textarea:focus {
            border-color: var(--border-gold);
            box-shadow: 0 0 15px rgba(212, 175, 55, 0.1);
        }

        .textarea::placeholder {
            color: var(--text-muted);
        }

        .input-field {
            width: 100%;
            background: var(--bg-elevated);
            border: 1px solid var(--border);
            border-radius: var(--radius-md);
            padding: 12px var(--space-md);
            color: var(--text-primary);
            font-family: 'Inter', sans-serif;
            font-size: 0.95rem;
            outline: none;
            transition: var(--transition);
        }

        .input-field:focus {
            border-color: var(--border-gold);
        }

        .input-field::placeholder {
            color: var(--text-muted);
        }

        /* === FEEDBACK BOX === */
        .feedback-item {
            display: flex;
            align-items: flex-start;
            gap: var(--space-sm);
            padding: 12px 16px;
            border-radius: var(--radius-md);
            margin-bottom: var(--space-sm);
            font-size: 0.9rem;
        }

        .feedback-item.good {
            background: rgba(0, 200, 150, 0.08);
            border: 1px solid rgba(0, 200, 150, 0.2);
            color: var(--emerald);
        }

        .feedback-item.warn {
            background: rgba(252, 196, 25, 0.08);
            border: 1px solid rgba(252, 196, 25, 0.2);
            color: var(--amber);
        }

        .feedback-item.bad {
            background: rgba(255, 99, 72, 0.08);
            border: 1px solid rgba(255, 99, 72, 0.2);
            color: var(--coral);
        }

        /* === AVATAR DISPLAY === */
        .avatar-display {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 3rem;
            border: 3px solid var(--border-gold);
            background: var(--bg-elevated);
            box-shadow: var(--shadow-gold);
            position: relative;
            flex-shrink: 0;
        }

        .avatar-display.lg {
            width: 120px;
            height: 120px;
            font-size: 4rem;
        }

        .avatar-badge-small {
            position: absolute;
            bottom: 0;
            right: 0;
            width: 28px;
            height: 28px;
            border-radius: 50%;
            background: var(--grad-gold);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 0.75rem;
            border: 2px solid var(--bg-base);
        }

        .avatar-option {
            cursor: pointer;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            border: 2px solid var(--border);
            background: var(--bg-elevated);
            transition: var(--transition-bounce);
        }

        .avatar-option:hover {
            transform: scale(1.15);
            border-color: var(--border-gold);
        }

        .avatar-option.selected {
            border-color: var(--gold);
            background: rgba(212, 175, 55, 0.1);
            box-shadow: 0 0 15px rgba(212, 175, 55, 0.3);
            transform: scale(1.1);
        }

        /* Color picker */
        .color-option {
            width: 36px;
            height: 36px;
            border-radius: 50%;
            cursor: pointer;
            border: 3px solid transparent;
            transition: var(--transition-bounce);
        }

        .color-option:hover {
            transform: scale(1.2);
        }

        .color-option.selected {
            border-color: white;
            transform: scale(1.1);
            box-shadow: 0 0 12px rgba(255, 255, 255, 0.3);
        }

        /* === COUNCIL CARD === */
        .council-card {
            cursor: pointer;
            padding: var(--space-xl);
            border-radius: var(--radius-xl);
            border: 1px solid var(--border);
            background: var(--grad-card);
            transition: var(--transition-bounce);
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        .council-card::before {
            content: '';
            position: absolute;
            inset: 0;
            opacity: 0;
            transition: opacity 0.3s;
        }

        .council-card:hover {
            transform: translateY(-6px);
        }

        .council-card:hover::before {
            opacity: 1;
        }

        .council-card.selected {
            border-width: 2px;
        }

        .council-emoji {
            font-size: 3rem;
            margin-bottom: var(--space-md);
            display: block;
        }

        .council-name {
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            font-size: 1rem;
            margin-bottom: var(--space-xs);
        }

        .council-short {
            font-size: 0.75rem;
            font-weight: 600;
            letter-spacing: 0.08em;
            margin-bottom: var(--space-sm);
        }

        .council-desc {
            font-size: 0.82rem;
            color: var(--text-muted);
            line-height: 1.5;
        }

        .council-diff {
            margin-top: var(--space-md);
            font-size: 0.75rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.06em;
        }

        /* === COUNTRY CARD === */
        .country-card {
            cursor: pointer;
            display: flex;
            align-items: center;
            gap: var(--space-md);
            padding: var(--space-md) var(--space-lg);
            border-radius: var(--radius-lg);
            border: 1px solid var(--border);
            background: var(--grad-card);
            transition: var(--transition-bounce);
        }

        .country-card:hover {
            transform: translateY(-3px);
            border-color: var(--border-gold);
            box-shadow: var(--shadow-gold);
        }

        .country-card.selected {
            border-color: var(--gold);
            background: rgba(212, 175, 55, 0.06);
        }

        .country-flag {
            font-size: 2.5rem;
        }

        .country-info {
            flex: 1;
        }

        .country-name {
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            font-size: 1rem;
        }

        .country-region {
            font-size: 0.78rem;
            color: var(--text-muted);
        }

        .country-stars {
            color: var(--gold);
            font-size: 0.9rem;
        }

        /* === TOPIC CARD === */
        .topic-card {
            cursor: pointer;
            padding: var(--space-xl);
            border-radius: var(--radius-xl);
            border: 1px solid var(--border);
            background: var(--grad-card);
            transition: var(--transition-bounce);
            position: relative;
            overflow: hidden;
        }

        .topic-card:hover {
            transform: translateY(-5px);
        }

        .topic-card.selected {
            border-width: 2px;
        }

        .topic-emoji {
            font-size: 2.5rem;
            margin-bottom: var(--space-md);
        }

        .topic-name {
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            font-size: 1.1rem;
            margin-bottom: var(--space-sm);
        }

        .topic-desc {
            font-size: 0.85rem;
            color: var(--text-muted);
            line-height: 1.5;
        }

        .topic-accent {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 3px;
            border-radius: var(--radius-xl) var(--radius-xl) 0 0;
        }

        /* === PHASE BANNER === */
        .phase-banner {
            display: flex;
            align-items: center;
            gap: var(--space-md);
            padding: var(--space-md) var(--space-xl);
            background: rgba(212, 175, 55, 0.06);
            border: 1px solid var(--border-gold);
            border-radius: var(--radius-xl);
            margin-bottom: var(--space-xl);
        }

        .phase-number {
            width: 48px;
            height: 48px;
            border-radius: 50%;
            background: var(--grad-gold);
            display: flex;
            align-items: center;
            justify-content: center;
            font-family: 'Outfit', sans-serif;
            font-weight: 800;
            font-size: 1.1rem;
            color: #0a0800;
            flex-shrink: 0;
        }

        .phase-info {
            flex: 1;
        }

        .phase-title {
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            font-size: 1rem;
            color: var(--gold);
        }

        .phase-sub {
            font-size: 0.82rem;
            color: var(--text-secondary);
        }

        .phase-xp {
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            color: var(--gold);
            font-size: 0.9rem;
        }

        /* === QUIZ COMPONENT === */
        .quiz-question {
            font-family: 'Outfit', sans-serif;
            font-size: 1.2rem;
            font-weight: 600;
            color: var(--text-primary);
            margin-bottom: var(--space-xl);
            line-height: 1.4;
        }

        .quiz-option {
            width: 100%;
            display: flex;
            align-items: center;
            gap: var(--space-md);
            padding: var(--space-md) var(--space-lg);
            background: var(--bg-elevated);
            border: 1px solid var(--border);
            border-radius: var(--radius-md);
            cursor: pointer;
            transition: var(--transition);
            margin-bottom: var(--space-sm);
            text-align: left;
            color: var(--text-primary);
            font-size: 0.95rem;
        }

        .quiz-option:hover {
            border-color: var(--border-blue);
            background: rgba(79, 195, 247, 0.06);
        }

        .quiz-option.correct {
            border-color: var(--emerald);
            background: rgba(0, 200, 150, 0.1);
            color: var(--emerald);
        }

        .quiz-option.wrong {
            border-color: var(--coral);
            background: rgba(255, 99, 72, 0.1);
            color: var(--coral);
        }

        .quiz-option:disabled {
            cursor: not-allowed;
        }

        .quiz-letter {
            width: 32px;
            height: 32px;
            border-radius: 50%;
            background: var(--bg-glass);
            border: 1px solid var(--border);
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 700;
            font-size: 0.85rem;
            flex-shrink: 0;
            font-family: 'Outfit', sans-serif;
        }

        /* === SPEECH EVAL BARS === */
        .eval-category {
            margin-bottom: var(--space-md);
        }

        .eval-label {
            display: flex;
            justify-content: space-between;
            margin-bottom: 6px;
            font-size: 0.85rem;
            font-weight: 600;
        }

        .eval-bar {
            height: 10px;
            background: var(--bg-elevated);
            border-radius: var(--radius-full);
            overflow: hidden;
        }

        .eval-fill {
            height: 100%;
            border-radius: var(--radius-full);
            transition: width 1s cubic-bezier(0.4, 0, 0.2, 1);
        }

        /* === VOTE BUTTON === */
        .vote-btn {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            gap: var(--space-sm);
            padding: var(--space-xl);
            border-radius: var(--radius-xl);
            cursor: pointer;
            border: 2px solid;
            background: transparent;
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            font-size: 1rem;
            transition: var(--transition-bounce);
            min-width: 140px;
        }

        .vote-btn.yes {
            border-color: var(--emerald);
            color: var(--emerald);
        }

        .vote-btn.yes:hover {
            background: rgba(0, 200, 150, 0.12);
            transform: translateY(-4px) scale(1.02);
            box-shadow: 0 8px 30px rgba(0, 200, 150, 0.3);
        }

        .vote-btn.no {
            border-color: var(--coral);
            color: var(--coral);
        }

        .vote-btn.no:hover {
            background: rgba(255, 99, 72, 0.12);
            transform: translateY(-4px) scale(1.02);
            box-shadow: 0 8px 30px rgba(255, 99, 72, 0.3);
        }

        .vote-btn.abstain {
            border-color: var(--text-muted);
            color: var(--text-muted);
        }

        .vote-btn.abstain:hover {
            background: rgba(255, 255, 255, 0.04);
            transform: translateY(-4px) scale(1.02);
        }

        .vote-btn-icon {
            font-size: 2rem;
        }

        /* === VOTE RESULT BAR === */
        .vote-result-row {
            display: flex;
            align-items: center;
            gap: var(--space-md);
            margin-bottom: var(--space-sm);
        }

        .vote-result-label {
            width: 80px;
            font-size: 0.85rem;
            font-weight: 600;
            text-align: right;
        }

        .vote-result-bar-wrap {
            flex: 1;
            height: 12px;
            background: var(--bg-elevated);
            border-radius: var(--radius-full);
            overflow: hidden;
        }

        .vote-result-fill {
            height: 100%;
            border-radius: var(--radius-full);
            transition: width 1.2s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .vote-result-count {
            width: 40px;
            font-size: 0.85rem;
            font-weight: 700;
        }

        /* === AWARD CARD === */
        .award-card {
            text-align: center;
            padding: var(--space-xl);
            border-radius: var(--radius-xl);
            border: 1px solid var(--border);
            background: var(--grad-card);
            animation: awardAppear 0.6s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
            opacity: 0;
            transform: scale(0.8);
        }

        .award-medal {
            font-size: 3.5rem;
            margin-bottom: var(--space-md);
            animation: medalBounce 0.8s ease;
        }

        .award-title {
            font-family: 'Outfit', sans-serif;
            font-size: 1rem;
            font-weight: 800;
            margin-bottom: var(--space-xs);
        }

        .award-winner {
            font-size: 0.85rem;
            color: var(--text-secondary);
        }

        /* === ACHIEVEMENT BADGE DISPLAY === */
        .achievement-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(120px, 1fr));
            gap: var(--space-md);
        }

        .achievement-item {
            text-align: center;
            padding: var(--space-md);
            border-radius: var(--radius-lg);
            border: 1px solid var(--border);
            background: var(--grad-card);
            transition: var(--transition);
        }

        .achievement-item.unlocked {
            border-color: var(--border-gold);
        }

        .achievement-item.locked {
            opacity: 0.4;
            filter: grayscale(1);
        }

        .achievement-emoji {
            font-size: 2rem;
            margin-bottom: var(--space-sm);
        }

        .achievement-name {
            font-size: 0.75rem;
            font-weight: 700;
            color: var(--text-primary);
        }

        .achievement-xp {
            font-size: 0.65rem;
            color: var(--gold);
            font-weight: 600;
        }

        /* === LEADERBOARD TABLE === */
        .leaderboard-table {
            width: 100%;
            border-collapse: collapse;
        }

        .leaderboard-table th {
            padding: 12px var(--space-md);
            text-align: left;
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 0.08em;
            color: var(--text-muted);
            border-bottom: 1px solid var(--border);
            font-family: 'Outfit', sans-serif;
        }

        .leaderboard-table td {
            padding: 14px var(--space-md);
            border-bottom: 1px solid var(--border-subtle);
            font-size: 0.9rem;
            vertical-align: middle;
        }

        .leaderboard-table tr:hover td {
            background: var(--bg-glass);
        }

        .leaderboard-table tr.player-row td {
            background: rgba(212, 175, 55, 0.05);
        }

        .lb-rank {
            font-family: 'Outfit', sans-serif;
            font-weight: 800;
            font-size: 1.1rem;
        }

        .lb-rank.gold {
            color: #FFD700;
        }

        .lb-rank.silver {
            color: #C0C0C0;
        }

        .lb-rank.bronze {
            color: #CD7F32;
        }

        .lb-name-cell {
            display: flex;
            align-items: center;
            gap: var(--space-sm);
        }

        .lb-avatar {
            width: 36px;
            height: 36px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.2rem;
            background: var(--bg-elevated);
            border: 1px solid var(--border);
            flex-shrink: 0;
        }

        .lb-xp {
            color: var(--gold);
            font-weight: 700;
            font-family: 'Outfit', sans-serif;
        }

        /* === ANALYTICS SVG CHART === */
        .analytics-radar {
            margin: 0 auto;
            display: block;
        }

        .analytics-bar-row {
            display: flex;
            align-items: center;
            gap: var(--space-md);
            margin-bottom: var(--space-sm);
        }

        .analytics-bar-label {
            width: 120px;
            font-size: 0.82rem;
            color: var(--text-secondary);
            text-align: right;
            flex-shrink: 0;
        }

        .analytics-bar-track {
            flex: 1;
            height: 12px;
            background: var(--bg-elevated);
            border-radius: var(--radius-full);
            overflow: hidden;
        }

        .analytics-bar-fill {
            height: 100%;
            border-radius: var(--radius-full);
            transition: width 1s ease;
        }

        .analytics-bar-val {
            width: 45px;
            font-size: 0.82rem;
            font-weight: 700;
            font-family: 'Outfit', sans-serif;
        }

        /* === NPC CHAIR === */
        .npc-chair {
            display: flex;
            align-items: flex-end;
            gap: var(--space-lg);
            margin-bottom: var(--space-xl);
        }

        .npc-avatar {
            font-size: 4rem;
            width: 90px;
            height: 90px;
            border-radius: var(--radius-lg);
            background: var(--bg-elevated);
            border: 2px solid var(--border-gold);
            display: flex;
            align-items: center;
            justify-content: center;
            flex-shrink: 0;
            box-shadow: var(--shadow-gold);
        }

        .npc-speech-bubble {
            flex: 1;
            background: rgba(79, 195, 247, 0.06);
            border: 1px solid var(--border-blue);
            border-radius: var(--radius-lg) var(--radius-lg) var(--radius-lg) 4px;
            padding: var(--space-lg);
            position: relative;
            font-size: 0.95rem;
            line-height: 1.7;
            color: var(--text-primary);
            font-style: italic;
        }

        .npc-speech-bubble::before {
            content: '"';
            font-size: 3rem;
            color: var(--blue);
            opacity: 0.3;
            position: absolute;
            top: 0;
            left: 10px;
            font-family: serif;
            line-height: 1;
        }

        .npc-name {
            font-size: 0.78rem;
            font-weight: 700;
            color: var(--blue);
            text-transform: uppercase;
            letter-spacing: 0.08em;
            margin-top: var(--space-sm);
        }

        /* === CLAUSE BUILDER === */
        .clause-pool {
            display: flex;
            flex-wrap: wrap;
            gap: var(--space-sm);
            padding: var(--space-md);
            background: var(--bg-elevated);
            border-radius: var(--radius-md);
            border: 1px dashed var(--border);
            min-height: 80px;
        }

        .clause-chip {
            padding: 6px 14px;
            background: var(--bg-glass);
            border: 1px solid var(--border);
            border-radius: var(--radius-full);
            font-size: 0.8rem;
            cursor: grab;
            transition: var(--transition);
            color: var(--text-secondary);
            user-select: none;
        }

        .clause-chip:hover {
            border-color: var(--border-gold);
            color: var(--gold);
            transform: scale(1.05);
        }

        .clause-chip.dragging {
            opacity: 0.4;
        }

        .clause-drop-zone {
            min-height: 200px;
            padding: var(--space-md);
            background: rgba(212, 175, 55, 0.03);
            border: 2px dashed var(--border-gold);
            border-radius: var(--radius-md);
            display: flex;
            flex-direction: column;
            gap: var(--space-sm);
        }

        .clause-drop-zone.drag-over {
            background: rgba(212, 175, 55, 0.08);
            border-color: var(--gold);
        }

        .clause-drop-placeholder {
            text-align: center;
            color: var(--text-muted);
            font-size: 0.85rem;
            padding: var(--space-xl);
        }

        .clause-item {
            display: flex;
            align-items: flex-start;
            gap: var(--space-sm);
            padding: 10px 14px;
            background: var(--bg-elevated);
            border: 1px solid var(--border);
            border-radius: var(--radius-md);
            animation: fadeSlideIn 0.2s ease;
        }

        .clause-number {
            font-weight: 700;
            color: var(--gold);
            font-size: 0.85rem;
            flex-shrink: 0;
        }

        .clause-word {
            color: var(--gold);
            font-weight: 600;
            font-size: 0.85rem;
            flex-shrink: 0;
        }

        .clause-text {
            flex: 1;
            font-size: 0.85rem;
            color: var(--text-secondary);
            line-height: 1.4;
        }

        .clause-remove {
            cursor: pointer;
            color: var(--text-muted);
            font-size: 0.85rem;
            flex-shrink: 0;
            transition: var(--transition);
        }

        .clause-remove:hover {
            color: var(--coral);
        }

        /* === HOME SCREEN === */
        .home-hero {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: var(--space-2xl);
            align-items: center;
            padding: var(--space-3xl) 0;
            min-height: calc(100vh - 80px);
        }

        @media (max-width: 768px) {
            .home-hero {
                grid-template-columns: 1fr;
                padding: var(--space-xl) 0;
            }
        }

        .hero-tagline {
            font-size: 0.85rem;
            font-weight: 600;
            letter-spacing: 0.15em;
            text-transform: uppercase;
            color: var(--gold);
            margin-bottom: var(--space-md);
        }

        .hero-title {
            font-family: 'Outfit', sans-serif;
            font-size: clamp(2.5rem, 5vw, 4rem);
            font-weight: 900;
            line-height: 1.1;
            margin-bottom: var(--space-lg);
        }

        .hero-desc {
            font-size: 1.05rem;
            color: var(--text-secondary);
            margin-bottom: var(--space-2xl);
            line-height: 1.8;
        }

        .hero-stats {
            display: flex;
            gap: var(--space-xl);
            margin-bottom: var(--space-2xl);
        }

        .hero-stat {
            text-align: center;
        }

        .hero-stat-val {
            font-family: 'Outfit', sans-serif;
            font-size: 1.8rem;
            font-weight: 800;
            color: var(--text-primary);
        }

        .hero-stat-lbl {
            font-size: 0.75rem;
            color: var(--text-muted);
            text-transform: uppercase;
            letter-spacing: 0.08em;
        }

        .hero-visual {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .globe-container {
            position: relative;
            width: 300px;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .globe-emoji {
            font-size: 10rem;
            animation: globeFloat 3s ease-in-out infinite;
            filter: drop-shadow(0 0 40px rgba(79, 195, 247, 0.4));
        }

        .globe-ring {
            position: absolute;
            border-radius: 50%;
            border: 1px solid;
            animation: ringExpand 3s ease-in-out infinite;
        }

        .globe-ring-1 {
            width: 200px;
            height: 200px;
            border-color: rgba(212, 175, 55, 0.2);
            animation-delay: 0s;
        }

        .globe-ring-2 {
            width: 260px;
            height: 260px;
            border-color: rgba(79, 195, 247, 0.15);
            animation-delay: 0.5s;
        }

        .globe-ring-3 {
            width: 300px;
            height: 300px;
            border-color: rgba(132, 94, 247, 0.1);
            animation-delay: 1s;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: var(--space-lg);
        }

        @media (max-width: 600px) {
            .menu-grid {
                grid-template-columns: 1fr;
            }
        }

        .menu-card {
            cursor: pointer;
            padding: var(--space-xl);
            border-radius: var(--radius-xl);
            border: 1px solid var(--border);
            background: var(--grad-card);
            transition: var(--transition-bounce);
            display: flex;
            align-items: center;
            gap: var(--space-lg);
        }

        .menu-card:hover {
            border-color: var(--border-gold);
            transform: translateY(-4px);
            box-shadow: var(--shadow-gold);
        }

        .menu-card-icon {
            font-size: 2rem;
        }

        .menu-card h3 {
            font-family: 'Outfit', sans-serif;
            font-size: 1rem;
            font-weight: 700;
            margin-bottom: 4px;
            color: var(--text-primary);
        }

        .menu-card p {
            font-size: 0.8rem;
            color: var(--text-muted);
            line-height: 1.4;
        }

        /* === SECTION DIVIDER === */
        .section-divider {
            display: flex;
            align-items: center;
            gap: var(--space-md);
            margin: var(--space-xl) 0;
        }

        .section-divider::before,
        .section-divider::after {
            content: '';
            flex: 1;
            height: 1px;
            background: var(--border);
        }

        .section-divider span {
            font-size: 0.78rem;
            color: var(--text-muted);
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            white-space: nowrap;
        }

        /* === DIFFICULTY SECTION === */
        .diff-section {
            margin-bottom: var(--space-2xl);
        }

        .diff-label {
            display: flex;
            align-items: center;
            gap: var(--space-md);
            margin-bottom: var(--space-md);
        }

        .diff-stars {
            font-size: 1rem;
        }

        .diff-title {
            font-family: 'Outfit', sans-serif;
            font-weight: 700;
            font-size: 1rem;
            color: var(--text-secondary);
        }

        /* === BLOC MAP === */
        .bloc-map {
            position: relative;
            width: 100%;
            height: 400px;
            background: var(--bg-elevated);
            border-radius: var(--radius-xl);
            border: 1px solid var(--border);
            overflow: hidden;
        }

        .bloc-map::before {
            content: 'WORLD MAP';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-family: 'Outfit', sans-serif;
            font-size: 8rem;
            font-weight: 900;
            color: rgba(255, 255, 255, 0.02);
            pointer-events: none;
            user-select: none;
        }

        .bloc-node {
            position: absolute;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 4px;
            cursor: pointer;
            transition: var(--transition-bounce);
        }

        .bloc-node:hover {
            transform: scale(1.2);
            z-index: 10;
        }

        .bloc-node-flag {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 1.8rem;
            background: var(--bg-surface);
            border: 2px solid var(--border);
            box-shadow: var(--shadow-sm);
            transition: var(--transition);
        }

        .bloc-node.allied .bloc-node-flag {
            border-color: var(--emerald);
            box-shadow: 0 0 15px rgba(0, 200, 150, 0.4);
        }

        .bloc-node.player .bloc-node-flag {
            border-color: var(--gold);
            box-shadow: 0 0 20px rgba(212, 175, 55, 0.5);
            transform: scale(1.2);
        }

        .bloc-node.rejected .bloc-node-flag {
            border-color: var(--coral);
            opacity: 0.5;
        }

        .bloc-node-name {
            font-size: 0.7rem;
            font-weight: 600;
            color: var(--text-secondary);
            text-align: center;
            max-width: 60px;
            line-height: 1.2;
        }

        .bloc-line {
            position: absolute;
            background: var(--grad-emerald);
            height: 2px;
            transform-origin: left center;
            opacity: 0.4;
            pointer-events: none;
        }

        /* === DEBATE CHALLENGE === */
        .debate-challenge {
            padding: var(--space-xl);
            background: rgba(255, 99, 72, 0.06);
            border: 1px solid rgba(255, 99, 72, 0.25);
            border-radius: var(--radius-lg);
            margin-bottom: var(--space-xl);
        }

        .debate-challenge-label {
            font-size: 0.75rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            color: var(--coral);
            margin-bottom: var(--space-sm);
        }

        .debate-challenge-text {
            font-family: 'Outfit', sans-serif;
            font-size: 1.05rem;
            font-weight: 600;
            color: var(--text-primary);
            line-height: 1.5;
            font-style: italic;
        }

        .debate-country {
            font-size: 0.82rem;
            color: var(--text-muted);
            margin-top: var(--space-sm);
        }

        /* ================================================
   MUNVERSE â€” ANIMATIONS & KEYFRAMES
   ================================================ */

        /* === PAGE TRANSITIONS === */
        @keyframes fadeSlideIn {
            from {
                opacity: 0;
                transform: translateY(16px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }

            to {
                opacity: 1;
            }
        }

        @keyframes slideInRight {
            from {
                opacity: 0;
                transform: translateX(30px);
            }

            to {
                opacity: 1;
                transform: translateX(0);
            }
        }

        @keyframes slideOutRight {
            from {
                opacity: 1;
                transform: translateX(0);
            }

            to {
                opacity: 0;
                transform: translateX(30px);
            }
        }

        @keyframes slideInUp {
            from {
                opacity: 0;
                transform: translateY(30px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        @keyframes fadeSlideOut {
            from {
                opacity: 1;
                transform: translateY(0);
            }

            to {
                opacity: 0;
                transform: translateY(-20px);
            }
        }

        /* === GLOBE ANIMATIONS === */
        @keyframes globeFloat {

            0%,
            100% {
                transform: translateY(0px);
            }

            50% {
                transform: translateY(-12px);
            }
        }

        @keyframes globeSpin {
            from {
                transform: rotate(0deg);
            }

            to {
                transform: rotate(360deg);
            }
        }

        @keyframes ringExpand {
            0% {
                transform: scale(0.9);
                opacity: 0.3;
            }

            50% {
                transform: scale(1.05);
                opacity: 0.6;
            }

            100% {
                transform: scale(0.9);
                opacity: 0.3;
            }
        }

        /* === LOADING === */
        @keyframes loadingBar {
            from {
                width: 0%;
            }

            to {
                width: 100%;
            }
        }

        /* === SHIMMER === */
        @keyframes shimmer {
            0% {
                opacity: 0.4;
                transform: translateX(-30px);
            }

            100% {
                opacity: 0;
                transform: translateX(30px);
            }
        }

        /* === PULSE & GLOW === */
        @keyframes pulse {

            0%,
            100% {
                opacity: 1;
            }

            50% {
                opacity: 0.5;
            }
        }

        @keyframes glowPulse {

            0%,
            100% {
                box-shadow: 0 0 20px rgba(212, 175, 55, 0.3);
            }

            50% {
                box-shadow: 0 0 40px rgba(212, 175, 55, 0.6);
            }
        }

        @keyframes goldGlow {

            0%,
            100% {
                text-shadow: 0 0 10px rgba(212, 175, 55, 0.3);
            }

            50% {
                text-shadow: 0 0 30px rgba(212, 175, 55, 0.8);
            }
        }

        /* === XP GAIN === */
        @keyframes xpFloat {
            0% {
                opacity: 1;
                transform: translateY(0) scale(1);
            }

            100% {
                opacity: 0;
                transform: translateY(-60px) scale(1.3);
            }
        }

        .xp-float {
            position: fixed;
            font-family: 'Outfit', sans-serif;
            font-size: 1.4rem;
            font-weight: 800;
            color: var(--gold);
            pointer-events: none;
            z-index: 9000;
            animation: xpFloat 1.2s ease-out forwards;
            text-shadow: 0 0 20px rgba(212, 175, 55, 0.6);
        }

        /* === TYPEWRITER === */
        @keyframes blink {

            0%,
            100% {
                opacity: 1;
            }

            50% {
                opacity: 0;
            }
        }

        .typewriter-cursor {
            display: inline-block;
            width: 2px;
            height: 1em;
            background: var(--blue);
            margin-left: 2px;
            animation: blink 0.8s ease infinite;
            vertical-align: text-bottom;
        }

        /* === CARD HOVER LIFT (applied via class) === */
        .hover-lift {
            transition: var(--transition-bounce);
        }

        .hover-lift:hover {
            transform: translateY(-6px);
        }

        /* === VOTE RIPPLE === */
        @keyframes voteRipple {
            from {
                transform: scale(0);
                opacity: 0.8;
            }

            to {
                transform: scale(4);
                opacity: 0;
            }
        }

        .vote-ripple {
            position: absolute;
            width: 60px;
            height: 60px;
            border-radius: 50%;
            animation: voteRipple 0.6s ease-out forwards;
            pointer-events: none;
        }

        /* === AWARDS === */
        @keyframes awardAppear {
            from {
                opacity: 0;
                transform: scale(0.5) translateY(30px);
            }

            to {
                opacity: 1;
                transform: scale(1) translateY(0);
            }
        }

        @keyframes medalBounce {
            0% {
                transform: scale(0) rotate(-20deg);
            }

            60% {
                transform: scale(1.3) rotate(5deg);
            }

            80% {
                transform: scale(0.9) rotate(-2deg);
            }

            100% {
                transform: scale(1) rotate(0deg);
            }
        }

        @keyframes confettiFall {
            0% {
                transform: translateY(-10px) rotate(0deg);
                opacity: 1;
            }

            100% {
                transform: translateY(100vh) rotate(720deg);
                opacity: 0;
            }
        }

        /* === STAGGER ANIMATION FOR CHILDREN === */
        .stagger>* {
            opacity: 0;
            animation: fadeSlideIn 0.4s ease forwards;
        }

        .stagger>*:nth-child(1) {
            animation-delay: 0.05s;
        }

        .stagger>*:nth-child(2) {
            animation-delay: 0.10s;
        }

        .stagger>*:nth-child(3) {
            animation-delay: 0.15s;
        }

        .stagger>*:nth-child(4) {
            animation-delay: 0.20s;
        }

        .stagger>*:nth-child(5) {
            animation-delay: 0.25s;
        }

        .stagger>*:nth-child(6) {
            animation-delay: 0.30s;
        }

        .stagger>*:nth-child(7) {
            animation-delay: 0.35s;
        }

        .stagger>*:nth-child(8) {
            animation-delay: 0.40s;
        }

        .stagger>*:nth-child(9) {
            animation-delay: 0.45s;
        }

        /* === GAVEL STRIKE === */
        @keyframes gavelStrike {
            0% {
                transform: rotate(-45deg) translateX(10px);
            }

            40% {
                transform: rotate(15deg) translateX(-5px);
            }

            60% {
                transform: rotate(-5deg);
            }

            100% {
                transform: rotate(0deg);
            }
        }

        .gavel-animate {
            animation: gavelStrike 0.5s cubic-bezier(0.34, 1.56, 0.64, 1);
        }

        /* === SPIN === */
        @keyframes spin {
            from {
                transform: rotate(0deg);
            }

            to {
                transform: rotate(360deg);
            }
        }

        .spin {
            animation: spin 1s linear infinite;
        }

        /* === BOUNCE IN === */
        @keyframes bounceIn {
            0% {
                opacity: 0;
                transform: scale(0.3);
            }

            50% {
                opacity: 1;
                transform: scale(1.15);
            }

            70% {
                transform: scale(0.9);
            }

            100% {
                opacity: 1;
                transform: scale(1);
            }
        }

        .bounce-in {
            animation: bounceIn 0.6s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
        }

        /* === SCORE REVEAL === */
        @keyframes scoreReveal {
            from {
                opacity: 0;
                transform: scale(0) rotate(-180deg);
            }

            to {
                opacity: 1;
                transform: scale(1) rotate(0deg);
            }
        }

        .score-reveal {
            animation: scoreReveal 0.7s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
        }

        .score-reveal:nth-child(1) {
            animation-delay: 0.1s;
            opacity: 0;
        }

        .score-reveal:nth-child(2) {
            animation-delay: 0.25s;
            opacity: 0;
        }

        .score-reveal:nth-child(3) {
            animation-delay: 0.4s;
            opacity: 0;
        }

        .score-reveal:nth-child(4) {
            animation-delay: 0.55s;
            opacity: 0;
        }

        /* === VOTE COUNTRY ANIMATION === */
        @keyframes voteCountry {
            0% {
                opacity: 0;
                transform: translateY(20px) scale(0.8);
            }

            60% {
                transform: translateY(-5px) scale(1.05);
            }

            100% {
                opacity: 1;
                transform: translateY(0) scale(1);
            }
        }

        .vote-country-anim {
            animation: voteCountry 0.4s cubic-bezier(0.34, 1.56, 0.64, 1) forwards;
            opacity: 0;
        }

        /* === CHART LINE ANIMATION === */
        @keyframes drawLine {
            from {
                stroke-dashoffset: 1000;
            }

            to {
                stroke-dashoffset: 0;
            }
        }

        .chart-line {
            stroke-dasharray: 1000;
            animation: drawLine 1.5s ease forwards;
        }

        /* === CRISIS ALERT === */
        @keyframes alertPulse {

            0%,
            100% {
                border-color: rgba(255, 99, 72, 0.4);
                box-shadow: 0 0 20px rgba(255, 99, 72, 0.2);
            }

            50% {
                border-color: rgba(255, 99, 72, 0.8);
                box-shadow: 0 0 40px rgba(255, 99, 72, 0.4);
            }
        }

        .crisis-alert {
            animation: alertPulse 1.5s ease infinite;
        }

        /* === TYPING INDICATOR === */
        .typing-dot {
            display: inline-block;
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background: var(--blue);
            animation: typingBounce 1.2s ease infinite;
        }

        .typing-dot:nth-child(2) {
            animation-delay: 0.2s;
        }

        .typing-dot:nth-child(3) {
            animation-delay: 0.4s;
        }

        @keyframes typingBounce {

            0%,
            80%,
            100% {
                transform: scale(0.7);
                opacity: 0.4;
            }

            40% {
                transform: scale(1);
                opacity: 1;
            }
        }
    </style>
</head>

<body>

    <!-- Loading Screen -->
    <div id="loading-screen">
        <div class="loading-globe">ðŸŒ</div>
        <div class="loading-title">MUNverse</div>
        <div class="loading-subtitle">Model United Nations Training Simulator</div>
        <div class="loading-bar">
            <div class="loading-progress" id="loading-progress"></div>
        </div>
        <div class="loading-tip" id="loading-tip">Preparing the conference hall...</div>
    </div>

    <!-- Top Navigation -->
    <nav id="top-nav" class="hidden">
        <a class="nav-logo" onclick="navigate('home')" id="nav-logo">ðŸŒ MUNverse</a>
        <div class="nav-right">
            <div class="nav-xp" id="nav-xp">
                <span>â­</span>
                <span id="nav-xp-value">0 XP</span>
            </div>
            <div class="nav-level" id="nav-level-badge"></div>
            <button class="nav-icon-btn" onclick="navigate('leaderboard')" title="Leaderboard">ðŸ†</button>
            <button class="nav-icon-btn" onclick="navigate('analytics')" title="Analytics">ðŸ“Š</button>
        </div>
    </nav>

    <!-- Main App Container -->
    <div id="app"></div>

    <!-- Notification Container -->
    <div id="notification-container"></div>

    <!-- Confetti Canvas -->
    <canvas id="confetti-canvas"
        style="position:fixed;top:0;left:0;width:100%;height:100%;pointer-events:none;z-index:9999;display:none;"></canvas>

    <!-- Scripts -->
    <script>
        /* ================================================
           MUNVERSE â€” GAME DATA
           ================================================ */

        const COUNCILS = [
            { id: 'unsc', name: 'UN Security Council', short: 'UNSC', emoji: 'ðŸ›¡ï¸', color: '#4FC3F7', diff: 'Advanced', desc: 'The primary UN organ responsible for international peace and security. Decisions are legally binding on all member states.' },
            { id: 'unhrc', name: 'UN Human Rights Council', short: 'UNHRC', emoji: 'âš–ï¸', color: '#00C896', diff: 'Intermediate', desc: 'Responsible for promoting and protecting human rights globally through dialogue, reporting, and resolutions.' },
            { id: 'who', name: 'World Health Organization', short: 'WHO', emoji: 'ðŸ¥', color: '#FF6B9D', diff: 'Beginner', desc: 'The directing and coordinating authority on international public health within the United Nations system.' },
            { id: 'unep', name: 'UN Environment Programme', short: 'UNEP', emoji: 'ðŸŒ¿', color: '#69DB7C', diff: 'Beginner', desc: 'The leading global environmental authority setting the global environmental agenda and promoting implementation.' },
            { id: 'historical', name: 'Historical Council', short: 'HISTORICAL', emoji: 'ðŸ“œ', color: '#FCC419', diff: 'Intermediate', desc: 'Simulate pivotal moments in history. Reshape key decisions that defined the modern world order.' },
            { id: 'crisis', name: 'Crisis Committee', short: 'CRISIS', emoji: 'ðŸš¨', color: '#FF6348', diff: 'Advanced', desc: 'Fast-paced dynamic committee responding to rapidly evolving global crises. Every second counts.' }
        ];

        const COUNTRIES = [
            {
                id: 'indonesia', name: 'Indonesia', flag: 'ðŸ‡®ðŸ‡©', region: 'Southeast Asia', diff: 1, bio: 'The world\'s largest archipelagic state and fourth most populous country. Indonesia plays a key role in ASEAN and promotes multilateralism and South-South cooperation.', allies: ['malaysia', 'singapore'], rivals: [], color: '#FF6348',
                policies: {
                    'climate-change': 'Indonesia supports the Paris Agreement and commits to reducing emissions by 29% by 2030. Emphasizes the right to development for emerging economies and requires climate finance from developed nations.',
                    'human-trafficking': 'Indonesia is a source, transit, and destination country. The government has strengthened legislation with Law No. 21/2007 and works with IOM on victim identification and protection.',
                    'refugee-crisis': 'Indonesia is not a signatory to the 1951 Refugee Convention but cooperates with UNHCR, providing temporary protection to Rohingya and Afghan refugees.',
                    'cyber-security': 'Indonesia supports the development of an international cyber security framework and has established BSSN (National Cyber and Encryption Agency) to coordinate national cyber defense.',
                    'ai-governance': 'Indonesia has adopted a National AI Strategy 2020-2045 and supports inclusive AI governance that considers developing nations\' unique needs and digital divides.',
                    'food-security': 'Indonesia prioritizes food sovereignty and has programs to boost rice production. Strongly supports FAO initiatives for smallholder farmers and sustainable agriculture.'
                }
            },
            {
                id: 'malaysia', name: 'Malaysia', flag: 'ðŸ‡²ðŸ‡¾', region: 'Southeast Asia', diff: 1, bio: 'A rapidly developing nation in Southeast Asia, Malaysia plays an active role in ASEAN and promotes South-South cooperation and a New International Economic Order.', allies: ['indonesia', 'singapore'], rivals: [], color: '#FFD43B',
                policies: {
                    'climate-change': 'Malaysia supports climate action but insists on CBDR principle and financial support. Emphasizes green technology transfer from developed to developing nations.',
                    'human-trafficking': 'Malaysia has the Anti-Trafficking in Persons Act 2007 and works with NGOs for victim support. Faces criticism over labor migration management.',
                    'refugee-crisis': 'Malaysia hosts over 177,000 UNHCR-registered refugees, primarily Rohingya, though not a 1951 Convention signatory. Seeks burden-sharing from international community.',
                    'cyber-security': 'Malaysia has established CyberSecurity Malaysia and supports international cooperation frameworks including regional ASEAN cyber capacity building.',
                    'ai-governance': 'Malaysia\'s National AI Roadmap aims to make Malaysia an AI hub in Southeast Asia, with focus on inclusive governance that benefits SMEs.',
                    'food-security': 'Malaysia supports sustainable agriculture, has specific programs for palm oil industry sustainability, and advocates for fair agricultural trade rules.'
                }
            },
            {
                id: 'singapore', name: 'Singapore', flag: 'ðŸ‡¸ðŸ‡¬', region: 'Southeast Asia', diff: 1, bio: 'A global financial hub and city-state, Singapore leverages its strategic location to engage in pragmatic multilateral diplomacy, trade, and technology leadership.', allies: ['malaysia', 'usa'], rivals: [], color: '#F06595',
                policies: {
                    'climate-change': 'Singapore committed to net-zero by 2050 and implemented a carbon tax. Advocates for multilateral climate solutions and is a test-bed for green finance.',
                    'human-trafficking': 'Singapore has strong anti-trafficking laws, prosecution records, and works with regional partners to dismantle trafficking networks.',
                    'refugee-crisis': 'Singapore provides substantial humanitarian contributions but does not accept refugees citing land and resource constraints.',
                    'cyber-security': 'Singapore is a global cyber security policy leader, home to the Global Forum on Cyber Expertise, and co-sponsors international capacity building frameworks.',
                    'ai-governance': 'Singapore published the Model AI Governance Framework 2.0 and is a leader in responsible AI deployment for financial and public services.',
                    'food-security': 'Singapore aims for 30% local food production by 2030 (30by30 goal) despite limited land, using vertical farming and aquaculture innovation.'
                }
            },
            {
                id: 'china', name: 'China', flag: 'ðŸ‡¨ðŸ‡³', region: 'East Asia', diff: 2, bio: 'A permanent member of the UN Security Council and the world\'s second-largest economy. China plays a central role in global governance and champions Global South development.', allies: ['russia'], rivals: ['usa', 'uk'], color: '#FF6348',
                policies: {
                    'climate-change': 'China is the world\'s largest emitter but committed to carbon neutrality by 2060. Opposes developed nations imposing emission standards and emphasizes historical responsibility.',
                    'human-trafficking': 'China has laws against trafficking but faces international criticism for treatment of North Korean refugees and labor transfer programs.',
                    'refugee-crisis': 'China provides bilateral refugee assistance but strongly opposes international intervention in sovereign matters under the Westphalian principle.',
                    'cyber-security': 'China advocates for national sovereignty in cyberspace (cyber sovereignty doctrine) and actively opposes Western-dominated cyber norms frameworks.',
                    'ai-governance': 'China is a leading AI power with national AI regulations focusing on safety, national security, and algorithmic transparency with Chinese characteristics.',
                    'food-security': 'China prioritizes food self-sufficiency with the "18 Hundred Million Mu" red line and has invested heavily in agricultural technology and vertical farming.'
                }
            },
            {
                id: 'russia', name: 'Russia', flag: 'ðŸ‡·ðŸ‡º', region: 'Eastern Europe', diff: 2, bio: 'A permanent UNSC member with vast territory and significant geopolitical influence. Russia maintains strong stances on sovereignty, non-interference, and multipolarity.', allies: ['china'], rivals: ['usa', 'uk'], color: '#4FC3F7',
                policies: {
                    'climate-change': 'Russia joined the Paris Agreement but has been slow on implementation. Emphasizes economic impacts of rapid decarbonization on its fossil fuel-dependent economy.',
                    'human-trafficking': 'Russia is a source, transit, and destination country for trafficking. Has anti-trafficking laws but enforcement is inconsistent and victim protection inadequate.',
                    'refugee-crisis': 'Russia emphasizes national sovereignty over international refugee protection mechanisms and provides selective assistance aligned with geopolitical interests.',
                    'cyber-security': 'Russia advocates for a UN-led internet governance regime under ITU jurisdiction and national control over cyberspace, rejecting Budapest Convention as one-sided.',
                    'ai-governance': 'Russia supports AI development for national security and economic development. Participates in international AI forums while opposing perceived Western dominance.',
                    'food-security': 'Russia is a major grain exporter and uses food diplomacy strategically. Participates in FAO initiatives while maintaining food sovereignty as a national security matter.'
                }
            },
            {
                id: 'france', name: 'France', flag: 'ðŸ‡«ðŸ‡·', region: 'Western Europe', diff: 2, bio: 'A founding EU member and UNSC permanent member. France champions multilateralism, human rights, and European values while maintaining significant global diplomatic influence.', allies: ['uk', 'usa'], rivals: ['russia', 'china'], color: '#845EF7',
                policies: {
                    'climate-change': 'France championed the Paris Agreement and targets carbon neutrality by 2050. Supports carbon border adjustment mechanisms and Just Energy Transition Partnerships.',
                    'human-trafficking': 'France has robust anti-trafficking legislation (Sapin II law), and provides significant international funding for victim support and survivor programs.',
                    'refugee-crisis': 'France has committed to EU refugee quotas and supports international protection standards. Faces domestic political pressure on migration management.',
                    'cyber-security': 'France leads the Paris Call for Trust and Security in Cyberspace and actively champions EU cyber regulations like NIS2 and Cyber Resilience Act.',
                    'ai-governance': 'France supports the EU AI Act as the global gold standard and advocates for human-centric, rights-based AI governance at the international level.',
                    'food-security': 'France promotes sustainable agriculture under the EU Common Agricultural Policy and funds FAO programs for food system transformation.'
                }
            },
            {
                id: 'usa', name: 'United States', flag: 'ðŸ‡ºðŸ‡¸', region: 'North America', diff: 3, bio: 'The world\'s largest economy and a permanent UNSC member. The US plays a leading role in global security, trade, technology, and governance while pursuing national interests.', allies: ['uk', 'france', 'israel'], rivals: ['russia', 'china'], color: '#4FC3F7',
                policies: {
                    'climate-change': 'The US rejoined the Paris Agreement and committed to 50-52% emissions reduction by 2030. Leads the Inflation Reduction Act as the largest climate investment in US history.',
                    'human-trafficking': 'The US leads globally through the Trafficking Victims Protection Act (TVPA) and the annual TIP Report which grades other countries\' anti-trafficking efforts.',
                    'refugee-crisis': 'The US is historically the world\'s largest refugee resettlement country, accepting up to 125,000 refugees annually and funding UNHCR as its largest donor.',
                    'cyber-security': 'The US leads international cyber norms through the Budapest Convention and bilateral agreements. Advocates for an open, interoperable, secure global internet.',
                    'ai-governance': 'The US issued an Executive Order on AI safety (2023) and leads OECD AI Principles. Promotes innovation-first governance that avoids over-regulation.',
                    'food-security': 'The US is the world\'s largest food aid donor through USAID programs and advocates for open agricultural trade and science-based food standards.'
                }
            },
            {
                id: 'uk', name: 'United Kingdom', flag: 'ðŸ‡¬ðŸ‡§', region: 'Western Europe', diff: 3, bio: 'A permanent UNSC member and global diplomatic power. Post-Brexit UK maintains extensive international commitments across security, development, and Commonwealth relations.', allies: ['usa', 'france'], rivals: ['russia'], color: '#00C896',
                policies: {
                    'climate-change': 'The UK achieved net-zero by 2050 legislation, hosted COP26 in Glasgow, and champions ambitious global targets through its climate leadership.',
                    'human-trafficking': 'UK has the landmark Modern Slavery Act 2015 and provides significant DFID international funding for anti-trafficking programs globally.',
                    'refugee-crisis': 'UK has resettlement programs including the Afghan Citizens Resettlement Scheme, though faces criticism over its Rwanda offshore processing policy.',
                    'cyber-security': 'UK is a founding Five Eyes member and active in international cyber governance. Home to the National Cyber Security Centre (NCSC).',
                    'ai-governance': 'UK hosted the first global AI Safety Summit at Bletchley Park (2023) and leads international AI safety research through the Alan Turing Institute.',
                    'food-security': 'UK supports food security through ODA programs and advocates for sustainable food systems transformation in international forums.'
                }
            },
            {
                id: 'israel', name: 'Israel', flag: 'ðŸ‡®ðŸ‡±', region: 'Middle East', diff: 3, bio: 'A technologically advanced nation with significant security challenges. Israel plays a complex role in multilateral forums and leverages strong bilateral relationships.', allies: ['usa'], rivals: ['iran'], color: '#FCC419',
                policies: {
                    'climate-change': 'Israel supports climate action and has innovative clean-tech sector. Committed to 30% renewable energy by 2030 and carbon neutrality by 2050.',
                    'human-trafficking': 'Israel has anti-trafficking laws and prosecution records but faces criticism for treatment of labor migrants and inconsistent victim identification.',
                    'refugee-crisis': 'Israel handles asylum claims through a complex legal framework and faces international criticism for deportation policies and offshore processing arrangements.',
                    'cyber-security': 'Israel is a global cyber security leader, exporting expertise from Unit 8200 veterans. Active in international cyber partnerships and the Budapest Convention.',
                    'ai-governance': 'Israel has a robust national AI plan and strong AI industry. Supports responsible AI development frameworks while protecting innovation ecosystems.',
                    'food-security': 'Israel is an agricultural innovation leader sharing drip irrigation, precision agriculture, and water management technologies through international cooperation programs.'
                }
            }
        ];

        const TOPICS = [
            {
                id: 'climate-change', name: 'Climate Change', emoji: 'ðŸŒ¡ï¸', color: '#FF6348',
                desc: 'Addressing the global climate crisis and transitioning to sustainable energy systems.',
                background: 'Climate change represents one of the most critical challenges facing humanity. Global temperatures have risen approximately 1.1Â°C above pre-industrial levels, causing widespread disruption to weather patterns, sea levels, and ecosystems worldwide. The IPCC\'s Sixth Assessment Report confirms that human activities are unequivocally responsible.',
                causes: ['Greenhouse gas emissions from fossil fuel combustion', 'Deforestation and land use change', 'Industrial agriculture and livestock production', 'Industrial manufacturing processes', 'Methane emissions from waste and energy sectors'],
                impacts: ['Rising sea levels threatening 1+ billion coastal residents', 'Extreme weather events becoming more frequent and intense', 'Food and water security disruption affecting billions', 'Climate-induced migration creating new refugee flows', 'Catastrophic biodiversity loss and ecosystem collapse'],
                keyTerms: [
                    { term: 'IPCC', def: 'Intergovernmental Panel on Climate Change â€” UN body for climate science assessment and policy guidance' },
                    { term: 'Paris Agreement', def: 'International treaty to limit global warming to 1.5Â°C above pre-industrial levels, signed 2015' },
                    { term: 'CBDR', def: 'Common But Differentiated Responsibilities â€” principle that developed nations bear greater historical responsibility for climate change' },
                    { term: 'NDC', def: 'Nationally Determined Contribution â€” each country\'s climate action plan and emissions target under the Paris Agreement' },
                    { term: 'Carbon Neutrality', def: 'Achieving net-zero carbon dioxide emissions by balancing emissions with removal or offset' },
                    { term: 'Just Transition', def: 'Framework ensuring the shift to clean energy benefits all workers and communities, especially those in fossil fuel industries' }
                ],
                sources: ['IPCC Sixth Assessment Report (2021-2022)', 'UNFCCC COP28 Dubai Agreement (2023)', 'UN Climate Action Summit Outcomes 2019', 'World Meteorological Organization Annual Climate Report 2023'],
                quizzes: [
                    { q: 'What is the main temperature target of the Paris Agreement?', opts: ['1.5Â°C above pre-industrial levels', '2.0Â°C above 1990 levels', '0.5Â°C below current levels', '3Â°C ceiling globally'], ans: 0, exp: 'The Paris Agreement aims to limit global warming to well below 2Â°C, preferably 1.5Â°C, compared to pre-industrial levels.' },
                    { q: 'What does CBDR stand for in climate negotiations?', opts: ['Carbon Basis Development Regime', 'Common But Differentiated Responsibilities', 'Climate Budget and Development Rights', 'Carbon Balance and Diverse Reductions'], ans: 1, exp: 'CBDR recognizes that while all nations share climate responsibility, developed nations bear greater historical responsibility due to cumulative emissions.' },
                    { q: 'Which sector is the largest contributor to global greenhouse gas emissions?', opts: ['Agriculture', 'Transport', 'Energy production (electricity/heat)', 'Manufacturing'], ans: 2, exp: 'Energy production accounts for approximately 34% of global greenhouse gas emissions, making it the largest single sector.' },
                    { q: 'What is a "Nationally Determined Contribution" (NDC)?', opts: ['A national climate law', 'A country\'s climate action plan under Paris Agreement', 'A UN climate fund contribution', 'National carbon tax policy'], ans: 1, exp: 'NDCs are each country\'s self-determined commitments to reduce emissions and adapt to climate impacts under the Paris Agreement.' },
                    { q: 'By how much has global average temperature increased above pre-industrial levels as of 2023?', opts: ['0.5Â°C', '1.1Â°C', '2.0Â°C', '3.2Â°C'], ans: 1, exp: 'Global temperatures have risen approximately 1.1-1.2Â°C above pre-industrial levels, with 2023 being the hottest year on record.' }
                ]
            },
            {
                id: 'human-trafficking', name: 'Human Trafficking', emoji: 'ðŸ”—', color: '#845EF7',
                desc: 'Combating modern slavery and protecting vulnerable populations from exploitation.',
                background: 'Human trafficking is a grave violation of human rights affecting an estimated 40.3 million people worldwide. It encompasses forced labor, sexual exploitation, forced marriage, and other forms of servitude that deny victims their fundamental freedoms and dignity. It is the second-largest criminal enterprise globally.',
                causes: ['Poverty and extreme economic inequality', 'Political instability, conflict, and displacement', 'Lack of education and economic opportunities', 'Gender discrimination and marginalization of vulnerable groups', 'Corruption and weak law enforcement institutions'],
                impacts: ['Severe psychological and physical trauma to victims', 'Undermining of rule of law and governance institutions', 'Estimated $150 billion USD in annual profits for criminals', 'Public health implications including disease transmission', 'Erosion of social trust and community cohesion'],
                keyTerms: [
                    { term: 'Palermo Protocol', def: 'UN Protocol to Prevent, Suppress and Punish Trafficking in Persons (2000) â€” the primary international legal framework' },
                    { term: '3P Framework', def: 'Prevention, Protection, and Prosecution â€” the core approach to comprehensive anti-trafficking policy' },
                    { term: 'Forced Labor', def: 'Work performed under threat, coercion, or deception without the worker\'s free consent or fair compensation' },
                    { term: 'ILO', def: 'International Labour Organization â€” UN agency setting and monitoring international labor standards' },
                    { term: 'Victim Identification', def: 'Process of formally identifying trafficking victims among migrant and vulnerable populations for protection' }
                ],
                sources: ['UNODC Global Report on Trafficking in Persons 2022', 'ILO Global Estimates of Modern Slavery 2022', 'UN Special Rapporteur Reports on Trafficking in Persons', 'Walk Free Foundation Global Slavery Index 2023'],
                quizzes: [
                    { q: 'How many people are estimated to be in modern slavery worldwide?', opts: ['10 million', '20 million', '40 million', '100 million'], ans: 2, exp: 'Approximately 40.3 million people are victims of modern slavery including forced labor and forced marriage globally.' },
                    { q: 'What is the Palermo Protocol?', opts: ['An EU migration agreement', 'UN Protocol on trafficking in persons (2000)', 'A peace treaty for trafficking victims', 'Italian immigration law'], ans: 1, exp: 'The Palermo Protocol (2000) is the cornerstone international legal framework to prevent and punish trafficking in persons.' },
                    { q: 'What does the "3P Framework" in anti-trafficking refer to?', opts: ['Policy, Procedure, Protocol', 'Prevention, Protection, Prosecution', 'Public, Private, Partnership', 'Peace, Progress, People'], ans: 1, exp: 'The 3P Framework focuses on Preventing trafficking, Protecting victims, and Prosecuting traffickers â€” the comprehensive response approach.' },
                    { q: 'Which region has the highest absolute number of people in modern slavery?', opts: ['Africa', 'Asia-Pacific', 'Europe', 'Americas'], ans: 1, exp: 'The Asia-Pacific region has the highest number of people in modern slavery due to its large population and significant economic disparities.' },
                    { q: 'What is the most common form of human trafficking globally?', opts: ['Sex trafficking', 'Forced labor', 'Organ trafficking', 'Child soldier recruitment'], ans: 1, exp: 'Forced labor accounts for the majority of human trafficking cases globally, affecting workers in agriculture, construction, domestic work, and manufacturing.' }
                ]
            },
            {
                id: 'refugee-crisis', name: 'Refugee Crisis', emoji: 'ðŸ•ï¸', color: '#FCC419',
                desc: 'Addressing forced displacement and protecting the rights of refugees and asylum seekers globally.',
                background: 'The world is experiencing an unprecedented refugee crisis, with over 108 million forcibly displaced people globally as of 2023 â€” the highest number ever recorded. Conflicts, persecution, climate disasters, and economic collapse are driving displacement at rates unseen since World War II.',
                causes: ['Armed conflicts and civil wars (Syria, Sudan, Ukraine, Myanmar)', 'Political persecution and human rights violations', 'Climate change and natural disasters creating environmental refugees', 'Economic collapse and acute food insecurity', 'Ethnic, religious, and political persecution'],
                impacts: ['Overwhelming strain on host country resources and public services', 'Humanitarian crises in overcrowded refugee camps', 'Loss of human capital and talent for countries of origin', 'Social tensions and integration challenges in host communities', 'Generational poverty, statelessness, and lost futures'],
                keyTerms: [
                    { term: '1951 Refugee Convention', def: 'International agreement defining who qualifies as a refugee and establishing their rights and host country obligations' },
                    { term: 'UNHCR', def: 'UN High Commissioner for Refugees â€” UN agency with mandate to protect and support refugees globally' },
                    { term: 'Non-refoulement', def: 'Core principle prohibiting the return of refugees or asylum seekers to places where they face serious threats to life or freedom' },
                    { term: 'IDP', def: 'Internally Displaced Person â€” someone displaced within their own country who does not qualify for refugee status' },
                    { term: 'Asylum Seeker', def: 'A person who has left their home country seeking refugee status and is awaiting official determination of their claim' }
                ],
                sources: ['UNHCR Global Trends Report 2023', '1951 Refugee Convention and 1967 Protocol', 'Global Compact on Refugees (2018)', 'IDMC Global Report on Internal Displacement 2023'],
                quizzes: [
                    { q: 'How many people are forcibly displaced globally as of 2023?', opts: ['50 million', '80 million', '108 million', '200 million'], ans: 2, exp: 'Over 108 million people are forcibly displaced globally as of 2023, the highest number ever recorded in human history.' },
                    { q: 'What is the principle of "non-refoulement"?', opts: ['Mandatory refugee quotas for all states', 'Prohibition on returning refugees to places of danger', 'Right of refugees to free movement globally', 'Obligation to provide refugee economic rights'], ans: 1, exp: 'Non-refoulement prohibits countries from returning refugees or asylum seekers to territories where they face persecution or serious harm.' },
                    { q: 'What distinguishes a refugee from an IDP?', opts: ['Economic status difference', 'Age classification', 'Crossing an international border vs. displaced within own country', 'Legal vs. illegal status'], ans: 2, exp: 'Refugees cross international borders while IDPs (Internally Displaced Persons) are displaced within their own country and cannot access refugee protections.' },
                    { q: 'Which country currently hosts the most refugees?', opts: ['Germany', 'Turkey', 'Jordan', 'United States'], ans: 1, exp: 'Turkey hosts approximately 3.6 million refugees, primarily from Syria, making it the world\'s largest refugee hosting country.' },
                    { q: 'The 1951 Refugee Convention was primarily created in response to which event?', opts: ['Vietnam War displacement', 'World War II mass displacement', 'Korean War refugees', 'Decolonization in Africa'], ans: 1, exp: 'The 1951 Refugee Convention was created to address the massive displacement of people caused by World War II and establish a legal framework for protection.' }
                ]
            },
            {
                id: 'cyber-security', name: 'Cyber Security', emoji: 'ðŸ”', color: '#4FC3F7',
                desc: 'Establishing international norms and cooperation frameworks for responsible behavior in cyberspace.',
                background: 'Cyberspace has become a critical domain of international conflict and cooperation. State-sponsored cyber attacks, ransomware campaigns, and information operations increasingly threaten critical infrastructure, democratic processes, financial systems, and international security. The challenge is creating binding international norms in a rapidly evolving, technically complex domain.',
                causes: ['Absence of binding international cyber law', 'Rapid digital transformation outpacing security capabilities', 'State-sponsored offensive cyber programs operated by major powers', 'Transnational criminal cyber networks exploiting jurisdictional gaps', 'Widening digital divides creating systemic vulnerabilities'],
                impacts: ['Critical infrastructure attacks (power grids, hospitals, water)', 'Election interference and mass disinformation campaigns', 'Annual global economic losses exceeding $8 trillion USD', 'Erosion of privacy, civil liberties, and digital rights', 'Escalating international tensions and risk of armed conflict'],
                keyTerms: [
                    { term: 'Budapest Convention', def: 'The Council of Europe\'s Convention on Cybercrime (2001) â€” first international treaty on cybercrime investigation and cooperation' },
                    { term: 'UN GGE/OEWG', def: 'UN Group of Governmental Experts and Open-Ended Working Group â€” primary UN bodies developing international cyber norms' },
                    { term: 'APT', def: 'Advanced Persistent Threat â€” sophisticated, long-term cyber attacks typically attributed to state-sponsored actors' },
                    { term: 'Critical Infrastructure', def: 'Systems essential to national security, public health, safety, and economic function (energy, water, finance, communications)' },
                    { term: 'Cyber Sovereignty', def: 'Doctrine holding that states have the right to control internet access and content within their borders' }
                ],
                sources: ['UN GGE Report on Developments in ICT (2021)', 'Budapest Convention on Cybercrime and its Additional Protocol', 'OEWG Final Report on ICT Security (2021)', 'Tallinn Manual 2.0 on International Law in Cyberspace'],
                quizzes: [
                    { q: 'What is the Budapest Convention?', opts: ['EU-Russia climate agreement', 'First international treaty on cybercrime (2001)', 'NATO cyber defense pact', 'UN charter on internet rights'], ans: 1, exp: 'The Budapest Convention (2001) is the first international treaty on cybercrime, establishing a framework for cross-border law enforcement cooperation.' },
                    { q: 'What does APT stand for in cybersecurity?', opts: ['Automated Protection Tool', 'Advanced Persistent Threat', 'Application Protocol Transfer', 'Anti-Phishing Technology'], ans: 1, exp: 'APT (Advanced Persistent Threat) refers to sophisticated, long-duration cyber attacks typically conducted by or on behalf of nation-states.' },
                    { q: 'Which UN body primarily leads international cyber security discussions?', opts: ['IAEA', 'ITU', 'UN GGE and OEWG', 'UNHCR'], ans: 2, exp: 'The UN Group of Governmental Experts (GGE) and the Open-Ended Working Group (OEWG) are the primary UN forums for developing international cyber norms.' },
                    { q: 'What is the fundamental geopolitical debate in cyber governance?', opts: ['Cost of cybersecurity implementation', 'Western open internet vs. cyber sovereignty doctrine', 'Technical standards disagreements', 'Who controls DNS root servers'], ans: 1, exp: 'The core debate is between Western states advocating an open, decentralized internet and states like Russia and China supporting national cyber sovereignty.' },
                    { q: 'The annual global economic cost of cybercrime is estimated at:', opts: ['$100 billion', '$1 trillion', '$8 trillion', '$50 trillion'], ans: 2, exp: 'Global cybercrime costs are estimated at over $8 trillion USD annually as of 2023, projected to reach $10.5 trillion by 2025.' }
                ]
            },
            {
                id: 'ai-governance', name: 'AI Governance', emoji: 'ðŸ¤–', color: '#845EF7',
                desc: 'Developing global frameworks for responsible artificial intelligence development, deployment, and oversight.',
                background: 'Artificial intelligence is transforming every sector of human activity at unprecedented speed. Without proper governance frameworks, AI poses serious risks: algorithmic bias perpetuating discrimination, autonomous weapons reducing human oversight of lethal force, mass surveillance threatening civil liberties, and potentially existential risks from advanced AI systems misaligned with human values.',
                causes: ['AI capabilities advancing far faster than regulatory frameworks', 'No international consensus on priority risks or governance mechanisms', 'Commercial pressures prioritizing deployment speed over safety testing', 'Intense geopolitical AI competition between the US, China, and EU', 'Limited AI technical literacy among most policymakers worldwide'],
                impacts: ['Algorithmic bias systematically disadvantaging marginalized communities', 'Autonomous weapons eroding meaningful human control over lethal force', 'Mass surveillance threatening democracy and individual freedoms', 'Economic disruption and structural unemployment across many sectors', 'Potential existential risks from highly capable future AI systems'],
                keyTerms: [
                    { term: 'AI Safety', def: 'Research and engineering practices ensuring AI systems behave as intended without harmful, unintended, or catastrophic side effects' },
                    { term: 'LAWS', def: 'Lethal Autonomous Weapons Systems â€” weapons that can select and engage targets without meaningful human control' },
                    { term: 'Algorithmic Bias', def: 'Systematic discrimination in AI decision-making arising from biased training data, flawed design, or proxy discrimination' },
                    { term: 'EU AI Act', def: 'European Union regulation (2024) creating a risk-based regulatory framework for AI development and deployment' },
                    { term: 'AGI', def: 'Artificial General Intelligence â€” hypothetical AI with human-level or greater cognitive abilities across all domains' }
                ],
                sources: ['UN Secretary-General\'s Roadmap for Digital Cooperation', 'OECD AI Principles (2019) â€” first intergovernmental AI standards', 'EU AI Act (2024) â€” world\'s first comprehensive AI regulation', 'Bletchley Park Declaration on AI Safety (2023)'],
                quizzes: [
                    { q: 'What is the primary concern of "AI Safety" research?', opts: ['Preventing AI from causing job losses', 'Ensuring AI behaves as intended without harmful side effects', 'Cybersecurity protection for AI systems', 'AI hardware physical protection'], ans: 1, exp: 'AI Safety research focuses on ensuring AI systems are reliably beneficial, aligned with human values, and free from catastrophic or unintended failure modes.' },
                    { q: 'What are Lethal Autonomous Weapons Systems (LAWS)?', opts: ['AI-powered cybersecurity tools', 'Weapons that select and engage targets without human control', 'Self-maintaining military equipment', 'Advanced drone surveillance systems'], ans: 1, exp: 'LAWS are weapons systems capable of identifying, selecting, and engaging targets without meaningful human oversight or control in the decision loop.' },
                    { q: 'Which event produced the first international declaration on AI safety risks?', opts: ['G20 Osaka Summit 2019', 'Bletchley Park AI Safety Summit 2023', 'OECD Forum 2021', 'WEF Davos 2024'], ans: 1, exp: 'The UK\'s Bletchley Park AI Safety Summit (November 2023) produced the first international declaration by 28 countries acknowledging frontier AI safety risks.' },
                    { q: 'What is "algorithmic bias"?', opts: ['Computer processing speed imbalances', 'Systematic discrimination in AI decisions from flawed data or design', 'Programmer\'s personal opinions in code', 'Mathematical calculation errors'], ans: 1, exp: 'Algorithmic bias occurs when AI systems produce systematically discriminatory outcomes due to biased training data, proxy discrimination, or flawed design choices.' },
                    { q: 'How does the EU AI Act primarily categorize AI applications?', opts: ['By country of origin', 'By risk level to fundamental rights and safety', 'By technology type (ML, deep learning, etc.)', 'By company size and revenue'], ans: 1, exp: 'The EU AI Act uses a risk-based approach, categorizing AI from unacceptable risk (banned) to high-risk (strictly regulated) to limited/minimal risk (lighter requirements).' }
                ]
            },
            {
                id: 'food-security', name: 'Food Security', emoji: 'ðŸŒ¾', color: '#00C896',
                desc: 'Ensuring global access to sufficient, safe, nutritious, and culturally appropriate food for all people.',
                background: 'Despite sufficient global food production capacity, 735 million people face chronic hunger and 2.4 billion face moderate or severe food insecurity. The climate crisis, armed conflicts, and economic inequality are driving a worsening food security emergency that threatens SDG 2: Zero Hunger by 2030.',
                causes: ['Climate change disrupting agricultural systems and crop yields', 'Armed conflicts deliberately targeting food systems and supply chains', 'Extreme economic inequality and poverty limiting food access', 'Massive food waste (one-third of all food produced is lost or wasted)', 'Biodiversity loss, soil degradation, and water scarcity'],
                impacts: ['Malnutrition, stunting, and cognitive impairment in 149 million children', 'Annual economic losses of $695 billion from lost productivity', 'Social instability and conflict driven by food price volatility', 'Forced migration from food-insecure to food-secure regions', 'Public health crises linked to both hunger and ultra-processed food overconsumption'],
                keyTerms: [
                    { term: 'FAO', def: 'Food and Agriculture Organization â€” UN specialized agency leading international food security, agriculture, and nutrition efforts' },
                    { term: 'WFP', def: 'World Food Programme â€” UN\'s food assistance agency and world\'s largest humanitarian organization, 2020 Nobel Peace Prize laureate' },
                    { term: 'SDG 2', def: 'Sustainable Development Goal 2: Zero Hunger â€” the UN\'s commitment to end hunger, achieve food security, and promote sustainable agriculture by 2030' },
                    { term: 'Food Sovereignty', def: 'The right of peoples and nations to define their own food, agriculture, and trade policies, protecting smallholder farmers' },
                    { term: 'Smallholder Farmers', def: 'Small-scale farmers, often subsistence-oriented, who collectively produce ~70% of global food consumed while facing the greatest vulnerability' }
                ],
                sources: ['FAO State of Food Security and Nutrition in the World 2023', 'WFP Global Report on Food Crises 2023', 'UN 2030 Agenda for Sustainable Development â€” SDG 2', 'CGIAR Research Programs on Food Systems and Food Security'],
                quizzes: [
                    { q: 'How many people face chronic hunger globally according to FAO 2023?', opts: ['100 million', '400 million', '735 million', '1.5 billion'], ans: 2, exp: 'Approximately 735 million people face chronic hunger globally, with numbers rising due to compounding climate, conflict, and economic shocks.' },
                    { q: 'What is SDG 2?', opts: ['Clean Water for All', 'Zero Hunger by 2030', 'Quality Education', 'Good Health and Well-being'], ans: 1, exp: 'SDG 2 (Zero Hunger) is the UN\'s Sustainable Development Goal to end hunger, achieve food security, improve nutrition, and promote sustainable agriculture by 2030.' },
                    { q: 'Which UN agency is the world\'s largest humanitarian organization?', opts: ['UNICEF', 'WHO', 'WFP', 'UNDP'], ans: 2, exp: 'The World Food Programme (WFP) is the UN\'s food assistance agency, the world\'s largest humanitarian organization, and 2020 Nobel Peace Prize laureate.' },
                    { q: 'What percentage of global food is produced by smallholder farmers?', opts: ['10%', '30%', '70%', '90%'], ans: 2, exp: 'Smallholder farmers produce approximately 70% of the food consumed globally, making support for small-scale agriculture central to food security.' },
                    { q: 'What proportion of all food produced globally is lost or wasted?', opts: ['One tenth', 'One quarter', 'One third', 'One half'], ans: 2, exp: 'Approximately one-third of all food produced globally â€” about 1.3 billion tons â€” is lost or wasted annually, representing a massive inefficiency in the food system.' }
                ]
            }
        ];

        const ACHIEVEMENTS = [
            { id: 'first-speech', name: 'First Speech', emoji: 'ðŸŽ¤', desc: 'Delivered your first speech in committee', xp: 100 },
            { id: 'resolution-author', name: 'Resolution Author', emoji: 'ðŸ“„', desc: 'Drafted your first working paper', xp: 150 },
            { id: 'master-negotiator', name: 'Master Negotiator', emoji: 'ðŸ¤', desc: 'Formed a bloc with 2+ allied nations', xp: 200 },
            { id: 'best-delegate', name: 'Best Delegate', emoji: 'ðŸ†', desc: 'Scored 90+ overall in a simulation', xp: 500 },
            { id: 'crisis-survivor', name: 'Crisis Survivor', emoji: 'ðŸš¨', desc: 'Successfully navigated a crisis event', xp: 300 },
            { id: 'research-ace', name: 'Research Ace', emoji: 'ðŸ“š', desc: 'Scored 100% on a research quiz', xp: 200 },
            { id: 'veteran-diplomat', name: 'Veteran Diplomat', emoji: 'ðŸŽ–ï¸', desc: 'Completed 3 full conference simulations', xp: 400 },
            { id: 'policy-expert', name: 'Policy Expert', emoji: 'âœï¸', desc: 'Completed a position paper with AI approval', xp: 150 },
            { id: 'first-steps', name: 'First Steps', emoji: 'ðŸ‘£', desc: 'Completed avatar creation', xp: 50 },
            { id: 'globe-trotter', name: 'Globe Trotter', emoji: 'ðŸŒ', desc: 'Represented 3 different countries', xp: 250 }
        ];

        const CRISES = [
            { id: 'pandemic', name: 'Pandemic Outbreak', emoji: 'ðŸ¦ ', urgency: 'CRITICAL', desc: 'A novel pathogen with pandemic potential has been detected in 12 countries simultaneously. The WHO has declared a Public Health Emergency of International Concern (PHEIC). Healthcare systems in affected nations are overwhelmed.', challenge: 'Draft an emergency resolution addressing international response coordination, equitable vaccine access, travel protocols, and healthcare system support within 48 hours.', options: ['Activate WHO Emergency Fund ($2B)', 'Establish International Task Force', 'Impose Coordinated Travel Restrictions', 'Launch Global Vaccine Solidarity Initiative'], best: 3 },
            { id: 'cyber-attack', name: 'Massive Cyber Attack', emoji: 'ðŸ’»', urgency: 'CRITICAL', desc: 'Critical infrastructure of 8 UN member states has been simultaneously attacked. Power grids, water treatment facilities, hospital networks, and financial systems are compromised. Attribution remains disputed.', challenge: 'Establish emergency cyber incident response protocols, determine collective countermeasures, and draft a framework for state responsibility in cyberspace.', options: ['Formally Attribute the Attack', 'Activate Cyber Defense Coalition', 'Impose Targeted Sanctions', 'Convene Emergency UNSC Session'], best: 1 },
            { id: 'refugee-surge', name: 'Mass Refugee Emergency', emoji: 'ðŸ•ï¸', urgency: 'HIGH', desc: 'A sudden escalation of conflict has displaced 2.5 million people within 72 hours. Neighboring countries are overwhelmed, UNHCR warehouses are depleted, and conditions in makeshift camps are deteriorating rapidly.', challenge: 'Coordinate immediate humanitarian response, establish burden-sharing mechanisms, and negotiate access for humanitarian organizations.', options: ['Emergency UNHCR Funding ($500M)', 'Mandatory Resettlement Quotas', 'Establish Protected Safe Zones', 'Negotiate Immediate Ceasefire'], best: 0 }
        ];

        const PREAMBULATORY_CLAUSES = [
            'Affirming', 'Alarmed by', 'Aware of', 'Bearing in mind', 'Believing',
            'Cognizant of', 'Concerned', 'Conscious of', 'Convinced', 'Declaring',
            'Deeply concerned', 'Deeply conscious', 'Deeply disturbed', 'Desiring',
            'Emphasizing', 'Expecting', 'Fully aware', 'Guided by', 'Having adopted',
            'Having considered', 'Keeping in mind', 'Mindful of', 'Noting',
            'Noting with deep concern', 'Observing', 'Reaffirming', 'Realizing',
            'Recalling', 'Recognizing', 'Seeking', 'Taking into account',
            'Taking into consideration', 'Welcoming'
        ];

        const OPERATIVE_CLAUSES = [
            'Accepts', 'Affirms', 'Approves', 'Authorizes', 'Calls upon',
            'Condemns', 'Confirms', 'Decides', 'Declares', 'Deplores',
            'Emphasizes', 'Encourages', 'Endorses', 'Further invites',
            'Further recommends', 'Further requests', 'Further urges',
            'Invites', 'Notes', 'Proclaims', 'Reaffirms', 'Recommends',
            'Regrets', 'Requests', 'Resolves', 'Strongly condemns',
            'Strongly urges', 'Supports', 'Urges'
        ];

        const LEADERBOARD_SEED = [
            { rank: 1, name: 'Arjuna Pratama', school: 'SMA Negeri 1 Jakarta', xp: 12500, badges: 8, flag: 'ðŸ‡®ðŸ‡©' },
            { rank: 2, name: 'Sarah Chen', school: 'Raffles Institution Singapore', xp: 11800, badges: 7, flag: 'ðŸ‡¸ðŸ‡¬' },
            { rank: 3, name: 'Amir Hassan', school: 'MRSM Terendak Malaysia', xp: 10200, badges: 6, flag: 'ðŸ‡²ðŸ‡¾' },
            { rank: 4, name: 'Priya Sharma', school: 'DPS International New Delhi', xp: 9800, badges: 6, flag: 'ðŸ‡®ðŸ‡³' },
            { rank: 5, name: 'Liu Wei', school: 'Beijing No.4 High School', xp: 9200, badges: 5, flag: 'ðŸ‡¨ðŸ‡³' },
            { rank: 6, name: 'Emma Thompson', school: 'Eton College UK', xp: 8900, badges: 5, flag: 'ðŸ‡¬ðŸ‡§' },
            { rank: 7, name: 'Carlos Rodriguez', school: 'Colegio San AgustÃ­n', xp: 8400, badges: 4, flag: 'ðŸ‡ªðŸ‡¸' },
            { rank: 8, name: 'Yuki Tanaka', school: 'Tokyo Int\'l School', xp: 7800, badges: 4, flag: 'ðŸ‡¯ðŸ‡µ' },
            { rank: 9, name: 'Fatima Al-Rashid', school: 'American School Dubai', xp: 7200, badges: 3, flag: 'ðŸ‡¦ðŸ‡ª' }
        ];

        const CHAIR_SCRIPTS = {
            opening: [
                "The committee will come to order. I call this session of the {council} to order. The topic under consideration is {topic}. We will begin with the General Speakers List.",
                "Distinguished delegates, I hereby call to order this session. The agenda for this committee is {topic}. Please ensure your placards are visible and be ready to be recognized.",
                "Good morning, distinguished delegates. The {council} is now in session. Today we address the pressing matter of {topic}. I trust delegates have reviewed the background guide."
            ],
            gsl: ["The chair recognizes the delegate of {country} for a 90-second opening statement.", "The delegate of {country} has the floor for their opening remarks.", "Please proceed, delegate of {country}. You have 90 seconds."],
            moderated: ["The chair opens the floor for motions.", "Are there any motions on the floor?", "The committee will now move into moderated caucus. The topic is {topic}."],
            unmoderated: ["The chair recognizes a motion for an unmoderated caucus of {time} minutes for the purpose of informal consultation.", "We will now break for {time} minutes of unmoderated caucus. Please use this time productively."],
            voting: ["The committee will now move to a vote on the draft resolution {res}. Those in favor, please indicate.", "We are now in the voting procedure. The chair calls for a vote on the working paper before us."]
        };

        const DELEGATE_ATTACKS = [
            "The delegate of {attacker} challenges: How will the proposed measures be financed, and who bears the financial burden?",
            "The delegation of {attacker} questions: Does this resolution respect the sovereignty of member states, or does it impose external conditions?",
            "{attacker}'s delegation asks: What enforcement mechanism ensures compliance with operative clause {n}?",
            "The delegate of {attacker} raises a point: How does this proposal address the root causes rather than merely the symptoms?",
            "{attacker} challenges: Will this resolution disproportionately burden developing nations while exempting historical polluters?",
            "The delegation of {attacker} contends: This resolution lacks specificity. What are the measurable targets and timelines?",
            "{attacker}'s delegate argues: The preambulatory language contradicts established precedents from Resolution {year}/{n}.",
            "The delegate of {attacker} demands: What consultation process included the most affected communities in drafting this proposal?"
        ];

        /* ================================================
           MUNVERSE â€” GAME STATE MANAGER
           ================================================ */

        const GameState = (() => {
            const KEY = 'munverse-v1';

            const DEFAULT = {
                player: { name: 'Delegate', gender: 'male', outfitColor: '#4FC3F7', avatarEmoji: 'ðŸ§‘', xp: 0, level: 1, badges: [], completedSims: 0, representedCountries: [] },
                session: { council: null, country: null, topic: null, paperContent: { s1: '', s2: '', s3: '', s4: '' }, speechText: '', blocAllies: [], resolution: { pre: [], op: [] }, crisisHandled: false },
                scores: { research: 0, speech: 0, diplomacy: 0, negotiation: 0, resolution: 0 },
                history: []
            };

            let state = JSON.parse(JSON.stringify(DEFAULT));

            // Load from localStorage
            try {
                const saved = localStorage.getItem(KEY);
                if (saved) state = Object.assign(JSON.parse(JSON.stringify(DEFAULT)), JSON.parse(saved));
            } catch (e) { console.warn('State load error:', e); }

            function save() {
                try { localStorage.setItem(KEY, JSON.stringify(state)); } catch (e) { }
            }

            function getLevelInfo(xp) {
                if (xp < 500) return { level: 1, title: 'Observer', next: 500, pct: Math.round((xp / 500) * 100) };
                if (xp < 1500) return { level: 2, title: 'Junior Delegate', next: 1500, pct: Math.round(((xp - 500) / 1000) * 100) };
                if (xp < 3000) return { level: 3, title: 'Delegate', next: 3000, pct: Math.round(((xp - 1500) / 1500) * 100) };
                if (xp < 5000) return { level: 4, title: 'Senior Delegate', next: 5000, pct: Math.round(((xp - 3000) / 2000) * 100) };
                if (xp < 8000) return { level: 5, title: 'Lead Delegate', next: 8000, pct: Math.round(((xp - 5000) / 3000) * 100) };
                if (xp < 12000) return { level: 6, title: 'Ambassador', next: 12000, pct: Math.round(((xp - 8000) / 4000) * 100) };
                return { level: 7, title: 'Secretary-General', next: null, pct: 100 };
            }

            return {
                get() { return state; },

                getPlayer() { return state.player; },
                getSession() { return state.session; },
                getScores() { return state.scores; },

                setSession(key, value) {
                    state.session[key] = value;
                    save();
                },

                setScore(key, value) {
                    state.scores[key] = value;
                    save();
                },

                addXP(amount, label) {
                    state.player.xp += amount;
                    const info = getLevelInfo(state.player.xp);
                    const prevLevel = state.player.level;
                    state.player.level = info.level;
                    save();
                    showXPGain(amount, label);
                    if (info.level > prevLevel) {
                        showToast('ðŸŽ‰ Level Up!', `You are now a ${info.title}!`, 'badge');
                    }
                    updateNavXP();
                    return info;
                },

                unlockBadge(id) {
                    if (!state.player.badges.includes(id)) {
                        state.player.badges.push(id);
                        const ach = ACHIEVEMENTS.find(a => a.id === id);
                        if (ach) {
                            showToast(`${ach.emoji} Achievement Unlocked!`, ach.name + ' â€” ' + ach.desc, 'badge');
                            this.addXP(ach.xp, 'Achievement');
                        }
                        save();
                        return true;
                    }
                    return false;
                },

                getLevelInfo() { return getLevelInfo(state.player.xp); },

                setPlayer(updates) {
                    state.player = { ...state.player, ...updates };
                    save();
                },

                recordCountry(countryId) {
                    if (!state.player.representedCountries.includes(countryId)) {
                        state.player.representedCountries.push(countryId);
                        if (state.player.representedCountries.length >= 3) this.unlockBadge('globe-trotter');
                    }
                },

                saveSessionToHistory() {
                    const entry = {
                        date: new Date().toLocaleDateString(),
                        council: state.session.council,
                        country: state.session.country,
                        topic: state.session.topic,
                        scores: { ...state.scores },
                        totalScore: Math.round(Object.values(state.scores).reduce((a, b) => a + b, 0) / Object.keys(state.scores).length)
                    };
                    state.history.push(entry);
                    state.player.completedSims++;
                    if (state.player.completedSims >= 3) this.unlockBadge('veteran-diplomat');
                    if (entry.totalScore >= 90) this.unlockBadge('best-delegate');
                    save();
                },

                resetSession() {
                    state.session = JSON.parse(JSON.stringify(DEFAULT.session));
                    state.scores = JSON.parse(JSON.stringify(DEFAULT.scores));
                    save();
                },

                hardReset() {
                    state = JSON.parse(JSON.stringify(DEFAULT));
                    save();
                }
            };
        })();

        /* === UI HELPERS === */

        function showToast(title, body, type = 'info') {
            const container = document.getElementById('notification-container');
            if (!container) return;
            const toast = document.createElement('div');
            toast.className = `toast ${type}`;
            const icons = { xp: 'â­', badge: 'ðŸ…', success: 'âœ…', info: 'ðŸ’¬', error: 'âŒ' };
            toast.innerHTML = `<div class="toast-header">${icons[type] || 'ðŸ’¬'} ${title}</div><div class="toast-body">${body}</div>`;
            container.appendChild(toast);
            setTimeout(() => { toast.classList.add('hide'); setTimeout(() => toast.remove(), 300); }, 4000);
            toast.onclick = () => toast.remove();
        }

        function showXPGain(amount, label = '') {
            const el = document.createElement('div');
            el.className = 'xp-float';
            el.textContent = `+${amount} XP ${label ? '(' + label + ')' : ''}`;
            el.style.left = (Math.random() * 40 + 30) + '%';
            el.style.top = (Math.random() * 20 + 40) + '%';
            document.body.appendChild(el);
            setTimeout(() => el.remove(), 1300);
        }

        function updateNavXP() {
            const el = document.getElementById('nav-xp-value');
            const lvl = document.getElementById('nav-level-badge');
            const info = GameState.getLevelInfo();
            if (el) el.textContent = `${GameState.getPlayer().xp.toLocaleString()} XP`;
            if (lvl) lvl.textContent = info.title;
        }

        /* ================================================
           MUNVERSE â€” AI MENTOR ENGINE
           ================================================ */

        const AIMentor = (() => {

            /* RESEARCH RESPONSES per country+topic */
            const RESEARCH_DB = {
                indonesia: {
                    'climate-change': ['Indonesia\'s position balances economic development with environmental responsibility. As an archipelagic nation with 17,000+ islands, we are highly vulnerable to sea-level rise and extreme weather events.', 'Indonesia\'s NDC commits to 29% emission reduction unconditionally, or 41% with international support by 2030. Our forests and peatlands are critical carbon sinks.', 'Indonesia seeks climate financing from developed nations under the CBDR principle. We support the Just Energy Transition Partnership (JETP) framework.'],
                    'human-trafficking': ['Indonesia is a source, transit, and destination country. Our coastal geography makes border control challenging, but Law 21/2007 provides strong legal framework.', 'Indonesian migrant workers in the Gulf states and Malaysia face exploitation risks. We work closely with IOM on victim identification and reintegration programs.', 'Indonesia\'s BNPTKI (National Agency for Placement and Protection of Indonesian Migrant Workers) coordinates international cooperation to protect our diaspora.'],
                    'refugee-crisis': ['Indonesia is not party to the 1951 Refugee Convention, but we cooperate with UNHCR on a pragmatic basis, allowing registered refugees temporary stay.', 'The Rohingya crisis has directly affected Indonesian shores. We provide humanitarian assistance while advocating for ASEAN-level solutions addressing root causes in Myanmar.', 'Indonesia supports the Global Compact on Refugees\' burden-sharing framework and calls for equitable international responsibility.'],
                    'cyber-security': ['BSSN (Badan Siber dan Sandi Negara) is Indonesia\'s cyber security agency established in 2017. We seek international capacity building support.', 'Indonesia experienced significant cyber attacks on government infrastructure and supports binding international norms prohibiting attacks on critical infrastructure.', 'We support ASEAN regional cyber cooperation and seek to adapt the Budapest Convention to reflect developing nation perspectives.'],
                    'ai-governance': ['Indonesia\'s National AI Strategy focuses on AI as an economic development tool. We emphasize AI must bridge, not widen, the digital divide between developed and developing nations.', 'We support UNESCO\'s Recommendation on the Ethics of AI and believe governance frameworks must be culturally sensitive and inclusive.', 'Indonesia advocates for technology transfer provisions in any AI governance framework to ensure developing nations can participate equitably in the AI economy.'],
                    'food-security': ['Indonesia is the world\'s third-largest rice producer and seeks to achieve food sovereignty. Our transmigration program supports agricultural development across the archipelago.', 'We face challenges from land conversion, climate impacts on rice yields, and smallholder farmer vulnerability. Biofortification and precision agriculture offer solutions.', 'Indonesia supports FAO\'s Small Island Developing States food security initiatives and advocates for fair agricultural trade that protects domestic food producers.']
                },
                malaysia: {
                    'climate-change': ['Malaysia supports the Paris Agreement but emphasizes that developed nations must provide climate finance and technology transfer under CBDR before demanding faster emission cuts from developing nations.', 'Our forests, including Borneo rainforests, serve as critical carbon sinks. Any climate framework must provide compensation for forest conservation services.', 'Malaysia has committed to carbon neutrality by 2050 and is pursuing renewable energy expansion, green sukuk bonds, and sustainable palm oil certification.'],
                    'human-trafficking': ['Malaysia hosts 2+ million documented and undocumented migrant workers, many vulnerable to exploitation. Our Prevention and Control of Infectious Diseases Act includes provisions protecting migrants.', 'We have established the Anti-Trafficking in Persons and Anti-Smuggling of Migrants Act 2007 and seek regional cooperation through ASEAN mechanisms.', 'Malaysia works with IOM and NGOs including Tenaganita on victim support. We call for greater cooperation from source countries on document verification.'],
                    'refugee-crisis': ['Malaysia hosts 177,000+ UNHCR-registered refugees, primarily Rohingya. Without formal refugee legal status, many face exploitation and lack of services.', 'We call for developed nations to increase resettlement quotas and burden-sharing. Malaysia cannot be expected to host refugees indefinitely without international support.', 'ASEAN\'s non-interference principle complicates regional responses. Malaysia advocates for a human rights exception when displacement reaches crisis proportions.'],
                    'cyber-security': ['Malaysia\'s Cyber Security Malaysia agency and National Cyber Security Policy provide our domestic framework. We seek greater international cooperation on cybercrime prosecution.', 'Malaysia supports ASEAN-level cyber security cooperation and believes developing nations need capacity building support to defend against sophisticated state-sponsored attacks.', 'We support Budapest Convention principles but note some provisions may conflict with national sovereignty rights over domestic digital infrastructure.'],
                    'ai-governance': ['Malaysia\'s National AI Roadmap 2021-2025 focuses on making Malaysia an ASEAN AI hub. Governance must enable innovation while preventing harm.', 'We support UNESCO\'s AI Ethics framework and advocate for governance that protects cultural and linguistic diversity, not just Western technological norms.', 'Malaysia calls for equitable AI governance that provides developing nations access to AI technologies rather than creating new dependencies on AI-exporting nations.'],
                    'food-security': ['Malaysia\'s National Agrofood Policy aims for greater food self-sufficiency. We advocate for fair trade rules that don\'t unfairly penalize developing nation agricultural exports.', 'Sustainable palm oil remains critical to Malaysia\'s food and economic security. We oppose unilateral trade measures that use environmental standards as non-tariff barriers.', 'Malaysia supports regional ASEAN food security frameworks and FAO technical cooperation programs for smallholder farmer capacity building.']
                },
                china: {
                    'climate-change': ['China is committed to carbon neutrality by 2060 and reaching peak emissions before 2030. We are the world\'s largest investor in renewable energy â€” over $750 billion invested in the past decade.', 'China supports the Paris Agreement but firmly opposes developed nations imposing emission timetables without historical responsibility for cumulative emissions. CBDR must be respected.', 'China\'s Green Silk Road Initiative demonstrates our commitment to green development globally. We provide climate finance to 70+ developing nations without political conditions.'],
                    'human-trafficking': ['China has comprehensive laws against trafficking including harsh criminal penalties. We work with neighboring countries on border control and victim repatriation.', 'China firmly rejects politicized characterizations of our labor programs. We oppose attempts to use anti-trafficking frameworks to interfere in China\'s sovereign labor policies.', 'China supports UNODC\'s capacity building programs and bilateral cooperation agreements with Southeast Asian nations on trafficking prosecution and prevention.'],
                    'refugee-crisis': ['China provides significant bilateral assistance to refugee situations through food aid and infrastructure support, contributing over $30M annually to UNHCR.', 'China upholds the principle of non-interference in internal affairs. Solutions to refugee crises must address root causes, including foreign interference that destabilizes nations.', 'We oppose mandatory refugee quotas as an infringement on national sovereignty. Voluntary international cooperation is more effective than binding redistribution mechanisms.'],
                    'cyber-security': ['China advocates for a UN-led internet governance model under ITU auspices that respects each nation\'s sovereign right to manage cyberspace within its borders.', 'The Budapest Convention was developed without Chinese participation. We support developing a new, more inclusive international cybercrime framework through the UN Ad Hoc Committee.', 'China proposes a Global Initiative on Data Security and calls for binding prohibitions on state-sponsored supply chain attacks â€” a principle all major powers should uphold.'],
                    'ai-governance': ['China is a global AI leader with comprehensive domestic AI regulations including the Algorithm Recommendation Regulation and Generative AI Interim Measures.', 'We support inclusive global AI governance that gives equal voice to all nations, rather than frameworks dominated by Western technology companies and governments.', 'China\'s Global AI Governance Initiative proposes that AI development should benefit all of humanity, not perpetuate existing technological hegemonies.'],
                    'food-security': ['China feeds 20% of the world\'s population on 9% of global arable land â€” a remarkable achievement. Food sovereignty is China\'s core national security priority.', 'China actively invests in African agricultural development, supporting food security for partner nations while creating sustainable economic partnerships.', 'We oppose agricultural trade distortions from developed nation subsidies that undermine developing country farmers. WTO agricultural reform must level the playing field.']
                },
                usa: {
                    'climate-change': ['The United States rejoined the Paris Agreement and has enacted the Inflation Reduction Act â€” the largest climate investment in US history at $369 billion â€” demonstrating our commitment.', 'We lead the Global Methane Pledge with 150+ nations committing to 30% methane reduction by 2030. The US champions ambitious multilateral action.', 'US climate diplomacy supports the Just Energy Transition Partnerships in South Africa, India, Indonesia, and Vietnam, mobilizing billions for clean energy transitions.'],
                    'human-trafficking': ['The US Trafficking Victims Protection Act (TVPA) and its annual TIP Report set the global standard for anti-trafficking policy accountability across 188 countries.', 'The US provides over $150M annually in anti-trafficking foreign assistance programs through USAID, the State Department, and DOJ capacity building initiatives.', 'We champion survivor-centered approaches and support civil society organizations globally. The End Modern Slavery Initiative funds prevention and prosecution programs worldwide.'],
                    'refugee-crisis': ['The United States is historically the world\'s top refugee resettlement nation, with the Biden administration restoring refugee admissions to 125,000 annually after significant cuts.', 'The US contributes approximately $2.8B annually to UNHCR â€” nearly double any other nation â€” demonstrating genuine commitment to global refugee protection.', 'We support the Global Compact on Refugees and advocate for sustainable solutions including development assistance to reduce drivers of displacement.'],
                    'cyber-security': ['The US champions the Budapest Convention as the international standard for cyber cooperation and calls on all nations to join this proven multilateral framework.', 'Through the Counter Ransomware Initiative with 40+ partners, the US leads international cooperation against cybercriminal networks disrupting critical infrastructure.', 'We strongly oppose state-sponsored attacks on critical infrastructure and have established clear attribution and consequence policies to deter malicious cyber behavior.'],
                    'ai-governance': ['President Biden\'s Executive Order on AI establishes the world\'s most comprehensive national AI safety framework, requiring safety testing for frontier AI models.', 'The US leads OECD AI Principles and the AI Safety Institute network, working with 10+ partner nations on frontier AI risk evaluation and international standards.', 'We support an innovation-first governance approach that enables AI\'s transformative economic benefits while managing genuine safety risks through adaptive regulation.'],
                    'food-security': ['The US is the world\'s largest food aid donor, providing over $5.8B annually through USAID\'s Food for Peace and emergency response programs reaching 50+ countries.', 'We champion science-based food security solutions including GMO crops, precision agriculture, and digital agriculture technologies to boost global yields sustainably.', 'The US calls for WTO agricultural trade reform eliminating trade-distorting subsidies while protecting genuine development programs for the world\'s poorest farmers.']
                },
                uk: {
                    'climate-change': ['The UK achieved net-zero by 2050 in legislation and hosted COP26 in Glasgow, securing the Glasgow Climate Pact and accelerating action on coal, cars, cash, and trees.', 'British International Investment channels UK climate finance to developing nations. The UK mobilized Â£11.6B in climate finance from 2016-2021.', 'The UK champions the International Climate Finance framework and supports the Loss & Damage Fund established at COP27 to compensate vulnerable nations.'],
                    'human-trafficking': ['The UK\'s Modern Slavery Act 2015 â€” the first of its kind â€” requires large businesses to report on slavery risks in their supply chains, a model others should adopt.', 'UK International Development funding supports anti-trafficking programs in 25+ countries. We champion survivor-led advocacy in policy development.', 'Despite domestic challenges, the UK maintains its leadership role through funding, policy innovation, and diplomatic pressure on countries with poor trafficking records.'],
                    'refugee-crisis': ['The UK has resettled 30,000+ Syrian refugees and 124,000+ Ukrainians, and established the Afghan Citizens Resettlement Scheme for at-risk Afghans.', 'The UK provides Â£1B+ annually to support refugees in country of origin regions, addressing root causes through development rather than just resettlement.', 'We support the Global Compact on Refugees and its comprehensive refugee response framework as the appropriate international mechanism for burden-sharing.'],
                    'cyber-security': ['The UK\'s National Cyber Security Centre is a global leader in threat intelligence sharing and capacity building. We champion the Paris Call for Trust in Cyberspace.', 'UK supports the Budapest Convention and advocates extending its geographic scope. We believe existing international law, including IHL, applies in cyberspace.', 'Through the Â£22M FCDO Cyber Programme, the UK builds cyber resilience in partner countries, recognizing that cyber security is a development issue.'],
                    'ai-governance': ['The UK hosted the landmark Bletchley Park AI Safety Summit (2023), producing the first international declaration on frontier AI risks and launching the AI Safety Institute Network.', 'UK\'s Pro-innovation AI regulation approach seeks to enable AI benefits while establishing sector-specific safety requirements through existing regulators.', 'We advocate for international cooperation on frontier AI safety evaluation and support establishing an IPCC-like body for AI risk assessment.'],
                    'food-security': ['UK supports food security through Â£3B+ in ODA for agriculture and nutrition. British expertise in agricultural research through CGIAR centers contributes globally.', 'We champion sustainable food systems transformation addressing health, environment, and equity simultaneously â€” not just production quantity.', 'UK advocates for fair agricultural trade rules at WTO that support developing country farmers while eliminating the most trade-distorting domestic support.']
                },
                russia: {
                    'climate-change': ['Russia joined the Paris Agreement and has committed to reducing emissions 30% below 1990 levels by 2030. Our vast forests absorb significant carbon.', 'Russia emphasizes that rapid decarbonization without realistic alternatives would harm developing nations most. An energy transition must be just and realistic.', 'Russian gas can serve as a transition fuel for Europe and Asia while renewable alternatives are developed, supporting global energy security during the transition.'],
                    'human-trafficking': ['Russia has enacted federal anti-trafficking legislation and cooperates with OSCE and UNODC on combating trafficking networks operating across Eurasia.', 'We emphasize that socioeconomic root causes â€” poverty and lack of opportunity â€” must be addressed rather than purely criminal justice approaches.', 'Russia supports regional cooperation frameworks through the CSTO and CIS to combat transnational criminal networks including trafficking operations.'],
                    'refugee-crisis': ['Russia provides humanitarian assistance through bilateral channels and UNHCR contributions. We emphasize that political solutions to root causes are more effective than burden-sharing mechanisms.', 'Russian humanitarian programs support displaced populations in Syria and elsewhere. We oppose politicized refugee assistance that serves geopolitical rather than humanitarian goals.', 'Russia maintains that sovereignty and non-interference principles must guide international refugee responses, rejecting externally imposed quotas as violations of sovereignty.'],
                    'cyber-security': ['Russia proposes a new comprehensive UN convention on cybercrime under ITU jurisdiction, providing all nations equal say in internet governance standards.', 'We believe the Budapest Convention is geographically and ideologically limited, designed to serve Western interests. A truly multilateral framework is needed.', 'Russia supports binding prohibitions on attacks against critical civilian infrastructure and calls for clear international attribution standards before political accusations.'],
                    'ai-governance': ['Russia supports AI development for national security, economic efficiency, and public service delivery. Governance must respect national sovereignty over AI deployment choices.', 'We oppose Western attempts to impose AI governance standards that embed particular cultural values or disadvantage Russian and other nations\' AI development programs.', 'Russia advocates for AI governance through established UN bodies rather than creating new Western-dominated multilateral institutions.'],
                    'food-security': ['Russia is one of the world\'s largest grain exporters, contributing significantly to global food security. We oppose politicizing food supply chains or imposing sanctions on food exports.', 'Sanctions regimes that restrict Russian agricultural exports directly harm food security in Africa and Asia â€” this is a form of economic warfare on vulnerable populations.', 'Russia supports FAO technical programs and provides bilateral grain assistance to partner nations facing food insecurity challenges.']
                },
                france: {
                    'climate-change': ['France pioneered the Paris Agreement in 2015 and continues to champion climate ambition. Our Carbon Border Adjustment Mechanism (CBAM) prevents carbon leakage.', 'France has committed to 40% renewable energy by 2030 and nuclear energy as a key low-carbon tool. We support diverse clean energy pathways for different national contexts.', 'French climate diplomacy through the Breakthrough Energy Initiative and Just Energy Transition Partnerships mobilizes private finance alongside official climate finance.'],
                    'human-trafficking': ['France\'s Sapin II law creates comprehensive anti-trafficking measures including duty of vigilance requirements for corporations operating in high-risk supply chains.', 'We fund international anti-trafficking programs through AFD (Agence FranÃ§aise de DÃ©veloppement) reaching survivor support in 30+ countries.', 'France supports the EU\'s comprehensive Anti-Trafficking Directive and advocates for its principles to be adopted globally through UN framework agreements.'],
                    'refugee-crisis': ['France has received 175,000+ asylum claims annually and exceeded EU relocation commitments. We support the EU\'s New Pact on Migration and Asylum as a model framework.', 'French development cooperation addresses refugee root causes through â‚¬15B in global development aid targeting conflict-affected and fragile states.', 'We champion the humanitarian principles of impartiality and non-discrimination in refugee protection and oppose using refugee status for security screening discrimination.'],
                    'cyber-security': ['France leads the Paris Call for Trust and Security in Cyberspace, now endorsed by 80+ states, 800+ companies, and 400+ civil society organizations globally.', 'The EU\'s NIS2 Directive and Cyber Resilience Act â€” championed by France â€” create the strongest critical infrastructure cyber protection framework globally.', 'France supports applying existing international humanitarian law to cyberspace and establishing clear prohibitions on attacks against civilian cyber infrastructure.'],
                    'ai-governance': ['France champions the EU AI Act as the world\'s first comprehensive AI regulation, establishing risk-based requirements that should serve as a global model.', 'We support human-centric AI governance grounded in fundamental rights, as articulated in the Council of Europe\'s AI Convention â€” the first binding AI treaty.', 'France leads OECD AI Principles implementation and the Global Partnership on AI, ensuring AI governance is inclusive of developing nation perspectives.'],
                    'food-security': ['France supports the EU Common Agricultural Policy which funds sustainable farming transitions while supporting rural communities and food security objectives.', 'French agricultural expertise through CIRAD and INRAE supports developing nation food systems through research partnerships and technology transfer.', 'We champion agroecology and sustainable food systems transformation that simultaneously addresses climate, biodiversity, and nutrition objectives.']
                },
                singapore: {
                    'climate-change': ['Singapore has implemented a carbon tax since 2019, rising to SGD 25/tCO2 in 2024, making us one of the few Asian nations with a robust carbon pricing mechanism.', 'Our Long-Term Low Emissions Development Strategy targets net-zero by 2050. Singapore\'s Green Plan 2030 covers solar, EVs, green buildings, and sustainable aviation.', 'Singapore champions blended finance for climate action in ASEAN and serves as a green finance hub through the Monetary Authority of Singapore\'s Green Finance Industry Taskforce.'],
                    'human-trafficking': ['Singapore\'s Prevention of Human Trafficking Act 2014 includes strong prosecution provisions. We maintain strict regulations on employment agencies handling migrant workers.', 'Singapore cooperates with regional partners through SOMTC (ASEAN Senior Officials Meeting on Transnational Crime) to dismantle trafficking networks operating across the region.', 'We have established dedicated victim support services and the specialized Inter-Agency Taskforce on Trafficking in Persons coordinates our comprehensive response.'],
                    'refugee-crisis': ['Singapore provides significant humanitarian contributions to UNHCR and international humanitarian organizations, recognizing our responsibility despite limited resettlement capacity.', 'As a small island city-state, Singapore\'s unique constraints must be recognized. We contribute expertise, funding, and capacity building rather than direct resettlement.', 'Singapore supports sustainable solutions including development assistance to refugee host countries and addressing root causes through conflict prevention diplomacy.'],
                    'cyber-security': ['Singapore is home to the Global Forum on Cyber Expertise (GFCE) secretariat and leads international cyber capacity building for developing nations.', 'Our CSA (Cyber Security Agency) has established bilateral cyber cooperation agreements with 20+ nations and champions the ASEAN Cybersecurity Cooperation Strategy.', 'Singapore supports the UN GGE\'s existing norms framework and advocates for practical implementation through confidence-building measures rather than new binding instruments.'],
                    'ai-governance': ['Singapore\'s Model AI Governance Framework 2.0 provides practical guidance for responsible AI deployment and has been widely adopted as a voluntary standard in Asia.', 'We chair the Global Partnership on AI\'s Working Group on AI Governance and support inclusive, multi-stakeholder approaches to AI standards development.', 'Singapore advocates for AI governance that enables innovation while protecting fundamental rights â€” opposing both excessive regulation and complete laissez-faire approaches.'],
                    'food-security': ['Singapore\'s 30by30 goal aims for 30% local food production by 2030 through high-tech urban farming. We invest SGD 60M in the Singapore Food Story R&D Programme.', 'We champion food innovation technologies including precision fermentation, vertical farming, and alternative proteins as scalable solutions for global food security.', 'Singapore supports open agricultural trade as essential for food security. As a trade-dependent city-state, we are acutely aware of the costs of agricultural protectionism.']
                },
                israel: {
                    'climate-change': ['Israel has committed to carbon neutrality by 2050 and 30% renewable energy by 2030. Our clean-tech sector develops solutions including desalination, solar, and water efficiency.', 'Israeli climate innovation through organizations like EcoMotion supports developing nations with practical technology solutions including solar microgrids and water recycling.', 'We are disproportionately affected by Middle East desertification and Mediterranean temperature rise, giving Israel strong motivation for ambitious global climate action.'],
                    'human-trafficking': ['Israel has Anti-Trafficking in Persons Law 5766-2006 providing comprehensive criminal penalties. Our courts have prosecuted traffickers in landmark cases.', 'PIBA\'s (Population and Immigration Authority) dedicated anti-trafficking unit identifies and protects victims. We fund rehabilitation centers for survivors.', 'Israel calls for greater international focus on labor trafficking in global supply chains and stronger corporate due diligence requirements.'],
                    'refugee-crisis': ['Israel processes asylum claims under a unique legal framework reflecting our national security context. We provide temporary protection and work authorization to many asylum seekers.', 'Israel welcomes Jewish refugees from persecution globally through the Law of Return. We have absorbed over 2 million immigrants since statehood.', 'We support UNHCR\'s third-country resettlement programs as the appropriate solution for recognized refugees, providing funding for resettlement operations globally.'],
                    'cyber-security': ['Israel is a global cyber security leader. Our Defense Export Controls Agency regulates cyber technology exports to prevent misuse while supporting legitimate security cooperation.', 'Israel supports the Budapest Convention and has strong bilateral cyber cooperation with democratic partners. We have experience defending against sophisticated state-sponsored attacks.', 'We advocate for an international framework prohibiting offensive cyber operations against civilian infrastructure, based on our experience with infrastructure-targeting attacks.'],
                    'ai-governance': ['Israel has a national AI plan focused on applying AI to defense, agriculture, healthcare, and water management. Our AI sector has produced numerous unicorns.', 'We support responsible AI development governance that maintains innovation ecosystems. Excessive regulation would disadvantage smaller innovator nations.', 'Israel shares AI agriculture innovations including crop monitoring AI and precision irrigation algorithms with developing nations through MASHAV international cooperation.'],
                    'food-security': ['Israel\'s agricultural innovations â€” drip irrigation, desalination, precision agriculture â€” are shared with 150+ developing nations through our international cooperation agency MASHAV.', 'Despite arid conditions, Israel achieves high agricultural productivity through technology. Our model demonstrates water and land efficiency solutions applicable globally.', 'Israel supports FAO\'s food security programs and contributes Israeli agricultural expertise to help developing nations boost sustainable food production.']
                }
            };

            const DEFAULT_RESPONSES = [
                "Based on your country's policy position, I would focus on the principles of sovereignty and development rights when addressing this issue.",
                "Your delegation should emphasize multilateral cooperation frameworks and the importance of international burden-sharing mechanisms.",
                "Consider citing relevant UN resolutions and treaty obligations that support your national position on this matter.",
                "Your country's historical stance aligns with advocating for equity and justice in international frameworks addressing this issue.",
                "I recommend emphasizing the technical and financial assistance needs of developing nations in your policy statements."
            ];

            /* SPEECH EVALUATOR */
            function evaluateSpeech(text) {
                const words = text.trim().split(/\s+/).filter(Boolean).length;
                const sentences = text.split(/[.!?]+/).filter(s => s.trim().length > 3).length;

                // Diplomacy: check for diplomatic language
                const dipWords = ['urge', 'call upon', 'encourage', 'reaffirm', 'recognize', 'express', 'support', 'advocate', 'cooperate', 'multilateral', 'international', 'sovereignty', 'resolution', 'delegate', 'committee', 'chair'];
                const dipScore = Math.min(100, Math.round((dipWords.filter(w => text.toLowerCase().includes(w)).length / dipWords.length) * 150) + 40);

                // Structure: intro + body + conclusion markers
                const hasOpening = /thank|pleasure|honor|distinguished|chair|fellow delegate/i.test(text);
                const hasBody = words > 60;
                const hasConclusion = /therefore|conclusion|urge|call upon|support|recommends|finally/i.test(text);
                const structScore = Math.min(100, (hasOpening ? 30 : 0) + (hasBody ? 40 : 20) + (hasConclusion ? 30 : 0));

                // Confidence: assertive language
                const confWords = ['must', 'will', 'strongly', 'firmly', 'clearly', 'unequivocally', 'committed', 'decisive'];
                const confScore = Math.min(100, (confWords.filter(w => text.toLowerCase().includes(w)).length * 15) + 40 + (words > 80 ? 20 : 0));

                // Relevance: word count and coherence
                const relevScore = Math.min(100, Math.round(Math.min(words / 1.5, 60) + (sentences > 3 ? 30 : 10) + Math.random() * 10));

                const overall = Math.round((dipScore + structScore + confScore + relevScore) / 4);

                return {
                    diplomacy: Math.min(100, dipScore + Math.round((Math.random() - 0.5) * 8)),
                    structure: Math.min(100, structScore + Math.round((Math.random() - 0.5) * 8)),
                    confidence: Math.min(100, confScore + Math.round((Math.random() - 0.5) * 8)),
                    relevance: Math.min(100, relevScore + Math.round((Math.random() - 0.5) * 8)),
                    overall, words,
                    feedback: getFeedback(overall, words)
                };
            }

            function getFeedback(score, words) {
                if (words < 40) return "âš ï¸ Your speech is too short. Aim for at least 80 words for a substantive opening statement.";
                if (score >= 85) return "âœ… Excellent speech! You demonstrated strong diplomatic language, clear structure, and compelling arguments aligned with your country's position.";
                if (score >= 70) return "âœ… Good speech with solid diplomatic framing. Consider adding more specific policy proposals and citing relevant UN resolutions.";
                if (score >= 55) return "âš ï¸ Adequate speech. Strengthen your opening with a formal acknowledgment, and ensure your conclusion includes a clear call to action.";
                return "âŒ Your speech needs improvement. Use more diplomatic language, structure your argument clearly (intro, body, conclusion), and align more closely with your country's official position.";
            }

            /* POSITION PAPER EVALUATOR */
            function evaluatePaper(paper) {
                const feedback = [];
                const sections = ['s1', 's2', 's3', 's4'];
                const labels = ['Country Background', 'National Position', 'Past Actions', 'Proposed Solutions'];
                let totalScore = 0;
                sections.forEach((s, i) => {
                    const text = paper[s] || '';
                    const words = text.trim().split(/\s+/).filter(Boolean).length;
                    if (words < 20) feedback.push({ type: 'bad', msg: `âŒ ${labels[i]}: Too brief. Develop this section with at least 3-4 substantive sentences.` });
                    else if (words < 50) feedback.push({ type: 'warn', msg: `âš ï¸ ${labels[i]}: Good start, but expand with more specific evidence and policy details.` });
                    else feedback.push({ type: 'good', msg: `âœ… ${labels[i]}: Well developed with sufficient detail.` });
                    totalScore += words < 20 ? 30 : words < 50 ? 65 : 90;
                });
                const avg = Math.round(totalScore / sections.length);
                return { feedback, score: avg };
            }

            /* GET RESEARCH RESPONSE */
            function getResearchResponse(question, countryId, topicId) {
                const countryData = RESEARCH_DB[countryId];
                if (!countryData) return DEFAULT_RESPONSES[Math.floor(Math.random() * DEFAULT_RESPONSES.length)];
                const topicResponses = countryData[topicId];
                if (!topicResponses) return DEFAULT_RESPONSES[Math.floor(Math.random() * DEFAULT_RESPONSES.length)];

                const q = question.toLowerCase();
                let response = topicResponses[Math.floor(Math.random() * topicResponses.length)];

                // Keyword matching for more relevant responses
                if ((q.includes('position') || q.includes('stance') || q.includes('policy')) && topicResponses[0]) response = topicResponses[0];
                else if ((q.includes('action') || q.includes('program') || q.includes('initiative')) && topicResponses[1]) response = topicResponses[1];
                else if ((q.includes('cooperat') || q.includes('international') || q.includes('partner')) && topicResponses[2]) response = topicResponses[2];

                return response;
            }

            /* CHAIR SCRIPT GENERATOR */
            function getChairScript(phase, context = {}) {
                const scripts = CHAIR_SCRIPTS[phase] || ["The committee will proceed."];
                let script = scripts[Math.floor(Math.random() * scripts.length)];
                script = script.replace('{council}', context.council || 'this committee');
                script = script.replace('{topic}', context.topic || 'the agenda item');
                script = script.replace('{country}', context.country || 'the delegate');
                script = script.replace('{time}', context.time || '15');
                script = script.replace('{res}', context.res || 'A');
                script = script.replace('{n}', context.n || '3');
                return script;
            }

            /* DELEGATE ATTACK GENERATOR */
            function getDelegateAttack(attackerCountry, topicId) {
                const attackers = COUNTRIES.filter(c => c.id !== attackerCountry).map(c => c.name);
                const attacker = attackers[Math.floor(Math.random() * attackers.length)];
                let attack = DELEGATE_ATTACKS[Math.floor(Math.random() * DELEGATE_ATTACKS.length)];
                attack = attack.replace(/{attacker}/g, attacker);
                attack = attack.replace('{n}', Math.floor(Math.random() * 3) + 2);
                attack = attack.replace('{year}', 2018 + Math.floor(Math.random() * 5));
                return { text: attack, attacker };
            }

            /* RESOLUTION FORMAT CHECK */
            function checkResolution(pre, op) {
                const feedback = [];
                if (pre.length < 3) feedback.push({ type: 'warn', msg: 'âš ï¸ Add at least 3 preambulatory clauses to establish the context.' });
                else feedback.push({ type: 'good', msg: `âœ… Good foundation with ${pre.length} preambulatory clauses.` });
                if (op.length < 3) feedback.push({ type: 'warn', msg: 'âš ï¸ Your resolution needs at least 3 operative clauses to be actionable.' });
                else feedback.push({ type: 'good', msg: `âœ… Substantive with ${op.length} operative clauses.` });
                if (op.length > 0 && pre.length > 0) feedback.push({ type: 'good', msg: 'âœ… Resolution format is correct â€” preambulatory clauses precede operative clauses.' });
                return feedback;
            }

            return {
                getResearchResponse,
                evaluateSpeech,
                evaluatePaper,
                getChairScript,
                getDelegateAttack,
                checkResolution
            };
        })();

        /* ================================================
           MUNVERSE â€” MAIN APPLICATION
           ================================================ */

        /* === ROUTER === */
        const ROUTES = {
            '': 'home', home: 'home', avatar: 'avatar', council: 'council',
            country: 'country', topic: 'topic', study: 'study', research: 'research',
            paper: 'paper', quiz: 'quiz', committee: 'committee', speech: 'speech',
            caucus: 'caucus', bloc: 'bloc', workingpaper: 'workingpaper',
            debate: 'debate', voting: 'voting', awards: 'awards',
            analytics: 'analytics', leaderboard: 'leaderboard', crisis: 'crisis'
        };

        const SCREEN_MAP = {
            home: renderHome, avatar: renderAvatar, council: renderCouncil,
            country: renderCountry, topic: renderTopic, study: renderStudy,
            research: renderResearch, paper: renderPaper, quiz: renderQuiz,
            committee: renderCommittee, speech: renderSpeech, caucus: renderCaucus,
            bloc: renderBloc, workingpaper: renderWorkingPaper, debate: renderDebate,
            voting: renderVoting, awards: renderAwards, analytics: renderAnalytics,
            leaderboard: renderLeaderboard, crisis: renderCrisis
        };

        function navigate(route) {
            window.location.hash = '#' + route;
        }

        function router() {
            const hash = window.location.hash.replace('#', '') || 'home';
            const screen = ROUTES[hash] || 'home';
            const renderer = SCREEN_MAP[screen];
            if (renderer) renderer();
            updateNav();
            window.scrollTo(0, 0);
        }

        function updateNav() {
            const nav = document.getElementById('top-nav');
            const hash = window.location.hash.replace('#', '') || 'home';
            if (hash === 'home' || hash === '' || hash === 'avatar') {
                nav.classList.add('hidden');
            } else {
                nav.classList.remove('hidden');
                updateNavXP();
            }
        }

        /* === UTILITY === */
        function getApp() { return document.getElementById('app'); }

        function setHTML(html) {
            const app = getApp();
            app.innerHTML = html;
        }

        function getCountry() {
            const id = GameState.getSession().country;
            return COUNTRIES.find(c => c.id === id) || COUNTRIES[0];
        }

        function getTopic() {
            const id = GameState.getSession().topic;
            return TOPICS.find(t => t.id === id) || TOPICS[0];
        }

        function getCouncil() {
            const id = GameState.getSession().council;
            return COUNCILS.find(c => c.id === id) || COUNCILS[0];
        }

        function typewriter(elementId, text, speed = 20) {
            const el = document.getElementById(elementId);
            if (!el) return;
            el.innerHTML = '';
            let i = 0;
            const cursor = document.createElement('span');
            cursor.className = 'typewriter-cursor';
            el.appendChild(cursor);
            const tick = () => {
                if (i < text.length) {
                    el.insertBefore(document.createTextNode(text[i]), cursor);
                    i++;
                    setTimeout(tick, speed);
                } else {
                    cursor.remove();
                }
            };
            tick();
        }

        function startConfetti() {
            const canvas = document.getElementById('confetti-canvas');
            if (!canvas) return;
            canvas.style.display = 'block';
            const ctx = canvas.getContext('2d');
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
            const particles = [];
            const colors = ['#D4AF37', '#4FC3F7', '#00C896', '#845EF7', '#FF6B9D', '#FCC419', '#FF6348'];
            for (let i = 0; i < 200; i++) {
                particles.push({
                    x: Math.random() * canvas.width,
                    y: Math.random() * canvas.height - canvas.height,
                    r: Math.random() * 6 + 2,
                    color: colors[Math.floor(Math.random() * colors.length)],
                    vy: Math.random() * 3 + 1,
                    vx: (Math.random() - 0.5) * 2,
                    rot: Math.random() * 360,
                    rotSpeed: (Math.random() - 0.5) * 5
                });
            }
            let frame;
            function draw() {
                ctx.clearRect(0, 0, canvas.width, canvas.height);
                particles.forEach(p => {
                    ctx.save();
                    ctx.translate(p.x, p.y);
                    ctx.rotate(p.rot * Math.PI / 180);
                    ctx.fillStyle = p.color;
                    ctx.fillRect(-p.r / 2, -p.r / 2, p.r, p.r * 2);
                    ctx.restore();
                    p.y += p.vy;
                    p.x += p.vx;
                    p.rot += p.rotSpeed;
                    if (p.y > canvas.height) { p.y = -10; p.x = Math.random() * canvas.width; }
                });
                frame = requestAnimationFrame(draw);
            }
            draw();
            setTimeout(() => { cancelAnimationFrame(frame); canvas.style.display = 'none'; ctx.clearRect(0, 0, canvas.width, canvas.height); }, 6000);
        }

        /* ================================================
           SCREEN 1 â€” HOME
           ================================================ */
        function renderHome() {
            const player = GameState.getPlayer();
            const info = GameState.getLevelInfo();
            document.getElementById('top-nav').classList.add('hidden');
            setHTML(`
    <div style="min-height:100vh;position:relative;overflow:hidden;">
      <!-- Hero -->
      <section style="min-height:100vh;display:flex;align-items:center;padding:0 var(--space-xl);">
        <div class="container" style="display:grid;grid-template-columns:1fr 1fr;gap:64px;align-items:center;width:100%;">
          <div style="animation:fadeSlideIn 0.6s ease;">
            <div class="hero-tagline">ðŸŒ MUNverse â€” The MUN Training Simulator</div>
            <h1 class="hero-title">
              Master the Art of<br/>
              <span class="text-gold">Global Diplomacy</span>
            </h1>
            <p class="hero-desc">Experience full-scale Model United Nations conferences with AI-powered mentors, real-time speech evaluation, bloc negotiations, and a gamified learning system that makes you a better delegate every session.</p>

            ${player.xp > 0 ? `
            <div class="card mb-xl" style="padding:var(--space-lg);margin-bottom:var(--space-xl);">
              <div style="display:flex;align-items:center;gap:var(--space-md);margin-bottom:var(--space-md);">
                <div style="font-size:2.5rem;">${player.avatarEmoji || 'ðŸ§‘'}</div>
                <div>
                  <div style="font-family:'Outfit',sans-serif;font-weight:700;">${player.name}</div>
                  <div class="badge badge-gold">${info.title}</div>
                </div>
                <div style="margin-left:auto;text-align:right;">
                  <div style="font-family:'Outfit',sans-serif;font-weight:800;color:var(--gold);font-size:1.3rem;">${player.xp.toLocaleString()}</div>
                  <div style="font-size:0.75rem;color:var(--text-muted);">XP Total</div>
                </div>
              </div>
              <div class="xp-bar"><div class="xp-bar-fill" style="width:${info.pct}%"></div></div>
              <div style="display:flex;justify-content:space-between;margin-top:6px;font-size:0.75rem;color:var(--text-muted);">
                <span>Level ${info.level} â€” ${info.title}</span>
                <span>${info.next ? info.next.toLocaleString() + ' XP to next' : 'MAX LEVEL'}</span>
              </div>
            </div>
            ` : ''}

            <div style="display:flex;gap:var(--space-md);flex-wrap:wrap;">
              <button class="btn btn-gold btn-lg" onclick="navigate('avatar')" id="btn-start-sim">
                ${player.xp > 0 ? 'ðŸŽ® New Simulation' : 'ðŸš€ Start Training'}
              </button>
              ${player.xp > 0 ? `<button class="btn btn-outline-gold btn-lg" onclick="navigate('analytics')" id="btn-view-analytics">ðŸ“Š My Progress</button>` : ''}
            </div>

            <div class="hero-stats" style="margin-top:var(--space-2xl);">
              <div class="hero-stat"><div class="hero-stat-val">18+</div><div class="hero-stat-lbl">Screens</div></div>
              <div class="hero-stat"><div class="hero-stat-val">6</div><div class="hero-stat-lbl">Councils</div></div>
              <div class="hero-stat"><div class="hero-stat-val">9</div><div class="hero-stat-lbl">Countries</div></div>
              <div class="hero-stat"><div class="hero-stat-val">AI</div><div class="hero-stat-lbl">Mentor</div></div>
            </div>
          </div>

          <div class="hero-visual" style="animation:fadeSlideIn 0.8s ease;">
            <div class="globe-container">
              <div class="globe-ring globe-ring-1"></div>
              <div class="globe-ring globe-ring-2"></div>
              <div class="globe-ring globe-ring-3"></div>
              <div class="globe-emoji">ðŸŒ</div>
            </div>
          </div>
        </div>
      </section>

      <!-- Features -->
      <section style="padding:var(--space-4xl) var(--space-xl);background:rgba(255,255,255,0.01);border-top:1px solid var(--border);">
        <div class="container">
          <div class="page-title">
            <h2>Why MUNverse?</h2>
            <p>Everything you need to become a championship delegate</p>
          </div>
          <div class="grid-3 stagger" style="max-width:900px;margin:0 auto;">
            ${[
                    { e: 'ðŸ¤–', t: 'AI Policy Advisor', d: 'Ask your AI advisor any question about your country\'s position on any topic. Get instant, accurate diplomatic guidance.' },
                    { e: 'ðŸŽ¤', t: 'Speech Evaluator', d: 'Record or type your speeches and get scored on Diplomacy, Structure, Confidence, and Relevance with AI feedback.' },
                    { e: 'â­', t: 'XP & Leveling', d: 'Earn XP for research, speeches, resolutions, and awards. Level up from Observer to Secretary-General.' },
                    { e: 'ðŸ¤', t: 'Bloc Formation', d: 'Negotiate alliances with AI-controlled nations on a dynamic political map. Build coalitions and secure votes.' },
                    { e: 'ðŸ“„', t: 'Resolution Builder', d: 'Use the guided wizard to draft working papers with preambulatory and operative clauses, with AI format checking.' },
                    { e: 'ðŸ†', t: 'Awards Ceremony', d: 'Every session ends with Best Delegate, Outstanding Delegate, Best Position Paper, and more â€” complete with confetti!' }
                ].map(f => `
              <div class="card" style="text-align:center;padding:var(--space-xl);">
                <div style="font-size:2.5rem;margin-bottom:var(--space-md);">${f.e}</div>
                <h4 style="color:var(--text-primary);margin-bottom:var(--space-sm);">${f.t}</h4>
                <p style="font-size:0.85rem;">${f.d}</p>
              </div>
            `).join('')}
          </div>
        </div>
      </section>

      <!-- Badges Preview -->
      ${player.badges.length > 0 ? `
      <section style="padding:var(--space-3xl) var(--space-xl);">
        <div class="container" style="max-width:800px;">
          <h3 style="text-align:center;margin-bottom:var(--space-xl);">Your Achievements <span class="badge badge-gold">${player.badges.length}/${ACHIEVEMENTS.length}</span></h3>
          <div class="achievement-grid">
            ${ACHIEVEMENTS.map(a => `
              <div class="achievement-item ${player.badges.includes(a.id) ? 'unlocked' : 'locked'}">
                <div class="achievement-emoji">${a.emoji}</div>
                <div class="achievement-name">${a.name}</div>
                <div class="achievement-xp">+${a.xp} XP</div>
              </div>
            `).join('')}
          </div>
        </div>
      </section>
      ` : ''}
    </div>
  `);
        }

        /* ================================================
           SCREEN 2 â€” AVATAR CREATION
           ================================================ */
        let avatarState = { gender: 'male', outfitColor: '#4FC3F7', emoji: 'ðŸ§‘', name: '' };
        function renderAvatar() {
            document.getElementById('top-nav').classList.add('hidden');
            const avEmojis = { male: ['ðŸ§‘', 'ðŸ‘¨', 'ðŸ§”', 'ðŸ‘¨â€ðŸ’¼', 'ðŸ•µï¸'], female: ['ðŸ‘©', 'ðŸ‘©â€ðŸ’¼', 'ðŸ§•', 'ðŸ’â€â™€ï¸', 'ðŸ§‘â€ðŸ’¼'] };
            const colors = [{ v: '#4FC3F7', n: 'Ocean Blue' }, { v: '#00C896', n: 'Emerald' }, { v: '#845EF7', n: 'Royal Purple' }, { v: '#D4AF37', n: 'Diplomatic Gold' }, { v: '#FF6B9D', n: 'Rose' }, { v: '#FCC419', n: 'Amber' }];
            const saved = GameState.getPlayer();
            if (saved.name) { avatarState.name = saved.name; avatarState.avatarEmoji = saved.avatarEmoji || 'ðŸ§‘'; avatarState.outfitColor = saved.outfitColor || '#4FC3F7'; }

            setHTML(`
    <div class="page" style="min-height:100vh;display:flex;align-items:center;">
      <div class="page-narrow" style="width:100%;margin:0 auto;padding:0 var(--space-lg);">
        <div class="page-title">
          <div style="font-size:0.85rem;color:var(--gold);font-weight:600;letter-spacing:0.1em;text-transform:uppercase;margin-bottom:var(--space-sm);">Step 1 of 4</div>
          <h2>Create Your Delegate</h2>
          <p>Customize your avatar before entering the conference hall</p>
        </div>

        <div style="display:grid;grid-template-columns:1fr 2fr;gap:var(--space-2xl);align-items:start;">
          <!-- Preview -->
          <div class="card" style="text-align:center;padding:var(--space-2xl);position:sticky;top:100px;">
            <div id="preview-avatar" style="width:120px;height:120px;border-radius:50%;margin:0 auto var(--space-lg);display:flex;align-items:center;justify-content:center;font-size:4rem;border:3px solid var(--border-gold);background:var(--bg-elevated);box-shadow:var(--shadow-gold);">ðŸ§‘</div>
            <div id="preview-name" style="font-family:'Outfit',sans-serif;font-weight:700;font-size:1.2rem;color:var(--text-primary);margin-bottom:var(--space-sm);">Your Name</div>
            <div id="preview-outfit" style="display:inline-block;width:40px;height:8px;border-radius:var(--radius-full);background:${avatarState.outfitColor};margin-top:4px;"></div>
          </div>

          <!-- Editor -->
          <div>
            <!-- Name -->
            <div class="card mb-lg">
              <h4 style="margin-bottom:var(--space-md);color:var(--text-primary);">ðŸ‘¤ Delegate Name</h4>
              <input id="avatar-name" class="input-field" type="text" placeholder="Enter your delegate name..." value="${avatarState.name}" maxlength="40" />
            </div>

            <!-- Gender -->
            <div class="card mb-lg">
              <h4 style="margin-bottom:var(--space-md);color:var(--text-primary);">Gender Identity</h4>
              <div style="display:flex;gap:var(--space-md);margin-bottom:var(--space-md);">
                <button class="btn ${avatarState.gender === 'male' ? 'btn-blue' : 'btn-glass'}" onclick="selectGender('male')" id="btn-male">â™‚ Male</button>
                <button class="btn ${avatarState.gender === 'female' ? 'btn-blue' : 'btn-glass'}" onclick="selectGender('female')" id="btn-female">â™€ Female</button>
              </div>
            </div>

            <!-- Avatar Emoji -->
            <div class="card mb-lg">
              <h4 style="margin-bottom:var(--space-md);color:var(--text-primary);">Choose Avatar</h4>
              <div style="display:flex;gap:var(--space-md);flex-wrap:wrap;" id="avatar-options">
                ${avEmojis[avatarState.gender].map(em => `<div class="avatar-option ${em === avatarState.emoji ? 'selected' : ''}" onclick="selectEmoji('${em}')">${em}</div>`).join('')}
              </div>
            </div>

            <!-- Outfit Color -->
            <div class="card mb-xl">
              <h4 style="margin-bottom:var(--space-md);color:var(--text-primary);">ðŸŽ¨ Outfit Color</h4>
              <div style="display:flex;gap:var(--space-md);align-items:center;flex-wrap:wrap;">
                ${colors.map(c => `<div class="color-option ${c.v === avatarState.outfitColor ? 'selected' : ''}" style="background:${c.v};" title="${c.n}" onclick="selectColor('${c.v}')"></div>`).join('')}
              </div>
            </div>

            <button class="btn btn-gold btn-full btn-lg" onclick="saveAvatar()" id="btn-save-avatar">Continue â†’ Choose Council ðŸ›ï¸</button>
            <div style="text-align:center;margin-top:var(--space-md);">
              <a href="#home" style="color:var(--text-muted);font-size:0.85rem;text-decoration:none;">â† Back to Home</a>
            </div>
          </div>
        </div>
      </div>
    </div>
  `);

            document.getElementById('avatar-name').addEventListener('input', e => {
                avatarState.name = e.target.value;
                document.getElementById('preview-name').textContent = e.target.value || 'Your Name';
            });
        }

        window.selectGender = function (g) {
            avatarState.gender = g;
            const emojis = { male: ['ðŸ§‘', 'ðŸ‘¨', 'ðŸ§”', 'ðŸ‘¨â€ðŸ’¼', 'ðŸ•µï¸'], female: ['ðŸ‘©', 'ðŸ‘©â€ðŸ’¼', 'ðŸ§•', 'ðŸ’â€â™€ï¸', 'ðŸ§‘â€ðŸ’¼'] }[g];
            avatarState.emoji = emojis[0];
            document.getElementById('btn-male').className = 'btn ' + (g === 'male' ? 'btn-blue' : 'btn-glass');
            document.getElementById('btn-female').className = 'btn ' + (g === 'female' ? 'btn-blue' : 'btn-glass');
            document.getElementById('avatar-options').innerHTML = emojis.map(em => `<div class="avatar-option ${em === avatarState.emoji ? 'selected' : ''}" onclick="selectEmoji('${em}')">${em}</div>`).join('');
            document.getElementById('preview-avatar').textContent = avatarState.emoji;
        };

        window.selectEmoji = function (em) {
            avatarState.emoji = em;
            document.querySelectorAll('.avatar-option').forEach(el => { el.classList.toggle('selected', el.textContent === em); });
            document.getElementById('preview-avatar').textContent = em;
        };

        window.selectColor = function (c) {
            avatarState.outfitColor = c;
            document.querySelectorAll('.color-option').forEach(el => { el.classList.toggle('selected', el.style.background === c || el.style.backgroundColor === c); });
            document.getElementById('preview-outfit').style.background = c;
        };

        window.saveAvatar = function () {
            const name = document.getElementById('avatar-name').value.trim() || 'Delegate';
            GameState.setPlayer({ name, gender: avatarState.gender, avatarEmoji: avatarState.emoji, outfitColor: avatarState.outfitColor });
            GameState.unlockBadge('first-steps');
            showToast('ðŸ§‘ Avatar Saved!', `Welcome, ${name}! Ready for the conference.`, 'success');
            navigate('council');
        };

        /* ================================================
           SCREEN 3 â€” CHOOSE COUNCIL
           ================================================ */
        function renderCouncil() {
            const session = GameState.getSession();
            setHTML(`
    <div class="page">
      <div class="container">
        <div class="phase-banner">
          <div class="phase-number">2</div>
          <div class="phase-info"><div class="phase-title">Choose Your Council</div><div class="phase-sub">Select the UN body you will represent in this simulation</div></div>
        </div>
        <div class="grid-3 stagger">
          ${COUNCILS.map(c => `
            <div class="council-card ${session.council === c.id ? 'selected' : ''}" onclick="selectCouncil('${c.id}')" id="council-${c.id}" style="${session.council === c.id ? `border-color:${c.color};box-shadow:0 0 30px ${c.color}30;` : ''}" data-color="${c.color}">
              <span class="council-emoji">${c.emoji}</span>
              <div class="council-short" style="color:${c.color};">${c.short}</div>
              <div class="council-name">${c.name}</div>
              <div class="council-desc">${c.desc}</div>
              <div class="council-diff" style="color:${c.color};">${c.diff === 'Beginner' ? 'â­' : c.diff === 'Intermediate' ? 'â­â­' : 'â­â­â­'} ${c.diff}</div>
              ${session.council === c.id ? `<div style="margin-top:var(--space-md);"><span class="badge" style="background:${c.color}20;color:${c.color};border:1px solid ${c.color}50;">âœ“ Selected</span></div>` : ''}
            </div>
          `).join('')}
        </div>
        <div style="text-align:center;margin-top:var(--space-2xl);">
          <button class="btn btn-gold btn-lg" onclick="confirmCouncil()" id="btn-confirm-council" ${!session.council ? 'disabled' : ''}>Continue â†’ Choose Country ðŸŒ</button>
        </div>
      </div>
    </div>
  `);
        }

        window.selectCouncil = function (id) {
            GameState.setSession('council', id);
            document.querySelectorAll('.council-card').forEach(el => {
                const cid = el.id.replace('council-', '');
                const c = COUNCILS.find(x => x.id === cid);
                const sel = cid === id;
                el.classList.toggle('selected', sel);
                el.style.borderColor = sel ? c.color : '';
                el.style.boxShadow = sel ? `0 0 30px ${c.color}30` : '';
            });
            document.getElementById('btn-confirm-council').removeAttribute('disabled');
        };

        window.confirmCouncil = function () {
            if (!GameState.getSession().council) return;
            navigate('country');
        };

        /* ================================================
           SCREEN 4 â€” CHOOSE COUNTRY
           ================================================ */
        function renderCountry() {
            const session = GameState.getSession();
            const byDiff = [
                { level: 1, label: 'â­ Beginner', desc: 'Recommended for first-time delegates' },
                { level: 2, label: 'â­â­ Intermediate', desc: 'Some MUN experience recommended' },
                { level: 3, label: 'â­â­â­ Advanced', desc: 'For experienced delegates only' }
            ];
            setHTML(`
    <div class="page">
      <div class="container" style="max-width:900px;">
        <div class="phase-banner">
          <div class="phase-number">3</div>
          <div class="phase-info"><div class="phase-title">Choose Your Country</div><div class="phase-sub">Select which nation you will represent in committee</div></div>
        </div>
        ${byDiff.map(d => `
          <div class="diff-section">
            <div class="diff-label">
              <span class="diff-stars">${d.label}</span>
              <span class="text-sm text-secondary">â€” ${d.desc}</span>
            </div>
            <div style="display:flex;flex-direction:column;gap:var(--space-sm);">
              ${COUNTRIES.filter(c => c.diff === d.level).map(c => `
                <div class="country-card ${session.country === c.id ? 'selected' : ''}" onclick="selectCountry('${c.id}')" id="country-${c.id}">
                  <div class="country-flag">${c.flag}</div>
                  <div class="country-info">
                    <div class="country-name">${c.name}</div>
                    <div class="country-region">${c.region}</div>
                  </div>
                  <div class="country-stars">${'â­'.repeat(c.diff)}</div>
                  ${session.country === c.id ? '<span class="badge badge-gold">Selected</span>' : ''}
                </div>
              `).join('')}
            </div>
          </div>
        `).join('')}
        <div style="text-align:center;">
          <button class="btn btn-gold btn-lg" onclick="confirmCountry()" id="btn-confirm-country" ${!session.country ? 'disabled' : ''}>Continue â†’ Choose Topic ðŸ“‹</button>
        </div>
      </div>
    </div>
  `);
        }

        window.selectCountry = function (id) {
            GameState.setSession('country', id);
            document.querySelectorAll('.country-card').forEach(el => el.classList.toggle('selected', el.id === 'country-' + id));
            document.getElementById('btn-confirm-country').removeAttribute('disabled');
        };

        window.confirmCountry = function () {
            const c = getCountry();
            GameState.recordCountry(c.id);
            navigate('topic');
        };

        /* ================================================
           SCREEN 5 â€” CHOOSE TOPIC
           ================================================ */
        function renderTopic() {
            const session = GameState.getSession();
            setHTML(`
    <div class="page">
      <div class="container">
        <div class="phase-banner">
          <div class="phase-number">4</div>
          <div class="phase-info"><div class="phase-title">Choose Your Topic</div><div class="phase-sub">Select the agenda item your committee will address</div></div>
        </div>
        <div class="grid-3 stagger">
          ${TOPICS.map(t => `
            <div class="topic-card ${session.topic === t.id ? 'selected' : ''}" onclick="selectTopic('${t.id}')" id="topic-${t.id}" style="${session.topic === t.id ? `border-color:${t.color};box-shadow:0 0 20px ${t.color}30;` : ''}">
              <div class="topic-accent" style="background:${t.color}"></div>
              <div class="topic-emoji">${t.emoji}</div>
              <div class="topic-name" style="color:${session.topic === t.id ? t.color : ''}">${t.name}</div>
              <div class="topic-desc">${t.desc}</div>
              ${session.topic === t.id ? `<div style="margin-top:var(--space-md);"><span class="badge" style="background:${t.color}20;color:${t.color};border:1px solid ${t.color}50;">âœ“ Selected</span></div>` : ''}
            </div>
          `).join('')}
        </div>
        <div style="text-align:center;margin-top:var(--space-2xl);">
          <button class="btn btn-gold btn-lg" onclick="confirmTopic()" id="btn-confirm-topic" ${!session.topic ? 'disabled' : ''}>Start Research Phase ðŸ“š</button>
        </div>
      </div>
    </div>
  `);
        }

        window.selectTopic = function (id) {
            GameState.setSession('topic', id);
            document.querySelectorAll('.topic-card').forEach(el => {
                const tid = el.id.replace('topic-', '');
                const t = TOPICS.find(x => x.id === tid);
                const sel = tid === id;
                el.classList.toggle('selected', sel);
                el.style.borderColor = sel ? t.color : '';
                el.style.boxShadow = sel ? `0 0 20px ${t.color}30` : '';
            });
            document.getElementById('btn-confirm-topic').removeAttribute('disabled');
        };

        window.confirmTopic = function () { navigate('study'); };

        /* ================================================
           SCREEN 6 â€” STUDY GUIDE
           ================================================ */
        function renderStudy() {
            const topic = getTopic(); const country = getCountry();
            setHTML(`
    <div class="page">
      <div class="container">
        <div class="phase-banner">
          <div class="phase-number" style="background:var(--grad-blue);">ðŸ“š</div>
          <div class="phase-info"><div class="phase-title">Phase 1 â€” Research & Study Guide</div><div class="phase-sub">${country.flag} ${country.name} Â· ${topic.emoji} ${topic.name}</div></div>
          <div class="phase-xp">+50 XP per section</div>
        </div>

        <div class="tab-list">
          <button class="tab-btn active" onclick="switchTab(this,'overview')" id="tab-overview">ðŸŒ Overview</button>
          <button class="tab-btn" onclick="switchTab(this,'profile')" id="tab-profile">ðŸ³ï¸ Country Profile</button>
          <button class="tab-btn" onclick="switchTab(this,'terms')" id="tab-terms">ðŸ“– Key Terms</button>
          <button class="tab-btn" onclick="switchTab(this,'sources')" id="tab-sources">ðŸ”— Sources</button>
        </div>

        <!-- Overview -->
        <div class="tab-panel active" id="panel-overview">
          <div class="grid-2" style="gap:var(--space-xl);">
            <div>
              <div class="card mb-lg">
                <div style="color:${topic.color};font-weight:700;font-size:0.8rem;text-transform:uppercase;letter-spacing:0.1em;margin-bottom:var(--space-md);">ðŸ“‹ Background</div>
                <p style="color:var(--text-primary);line-height:1.8;">${topic.background}</p>
              </div>
              <div class="card">
                <div style="color:var(--coral);font-weight:700;font-size:0.8rem;text-transform:uppercase;letter-spacing:0.1em;margin-bottom:var(--space-md);">âš ï¸ Causes</div>
                <ul style="list-style:none;display:flex;flex-direction:column;gap:8px;">
                  ${topic.causes.map(c => `<li style="display:flex;gap:8px;color:var(--text-secondary);font-size:0.9rem;"><span style="color:var(--coral);">â–¸</span>${c}</li>`).join('')}
                </ul>
              </div>
            </div>
            <div>
              <div class="card mb-lg">
                <div style="color:var(--amber);font-weight:700;font-size:0.8rem;text-transform:uppercase;letter-spacing:0.1em;margin-bottom:var(--space-md);">ðŸŒŠ Global Impacts</div>
                <ul style="list-style:none;display:flex;flex-direction:column;gap:8px;">
                  ${topic.impacts.map(i => `<li style="display:flex;gap:8px;color:var(--text-secondary);font-size:0.9rem;"><span style="color:var(--amber);">â–¸</span>${i}</li>`).join('')}
                </ul>
              </div>
              <div class="card" style="background:rgba(212,175,55,0.04);border-color:var(--border-gold);">
                <div style="color:var(--gold);font-weight:700;font-size:0.8rem;text-transform:uppercase;letter-spacing:0.1em;margin-bottom:var(--space-md);">â­ Explore More</div>
                <button class="btn btn-outline-gold btn-full" onclick="navigate('research')">ðŸ’¬ Ask AI Policy Advisor</button>
              </div>
            </div>
          </div>
          <div style="text-align:center;margin-top:var(--space-xl);">
            <button class="btn btn-gold" onclick="earnStudyXP('overview')">âœ… Mark as Read (+50 XP)</button>
          </div>
        </div>

        <!-- Country Profile -->
        <div class="tab-panel" id="panel-profile">
          <div class="card" style="max-width:800px;margin:0 auto;">
            <div style="display:flex;align-items:center;gap:var(--space-lg);margin-bottom:var(--space-xl);">
              <div style="font-size:4rem;">${country.flag}</div>
              <div>
                <h3 style="color:var(--text-primary);margin-bottom:4px;">${country.name}</h3>
                <div class="badge badge-gray">${country.region}</div>
                <div class="badge badge-gold" style="margin-left:8px;">${'â­'.repeat(country.diff)} ${['', 'Beginner', 'Intermediate', 'Advanced'][country.diff]}</div>
              </div>
            </div>
            <p style="color:var(--text-primary);line-height:1.8;margin-bottom:var(--space-xl);">${country.bio}</p>

            <div style="margin-bottom:var(--space-xl);">
              <div style="font-weight:700;color:var(--text-primary);margin-bottom:var(--space-md);">ðŸ“Œ Position on ${topic.name}</div>
              <div class="card" style="background:rgba(0,200,150,0.04);border-color:var(--border-emerald);">
                <p style="color:var(--text-primary);line-height:1.8;">${country.policies[topic.id] || 'No specific policy data available for this combination.'}</p>
              </div>
            </div>

            <div style="display:grid;grid-template-columns:1fr 1fr;gap:var(--space-lg);">
              <div>
                <div style="font-weight:700;color:var(--emerald);margin-bottom:var(--space-sm);font-size:0.9rem;">ðŸ¤ Key Allies</div>
                <div style="display:flex;flex-wrap:wrap;gap:var(--space-sm);">
                  ${country.allies.map(a => { const ally = COUNTRIES.find(c => c.id === a); return ally ? `<span class="badge badge-emerald">${ally.flag} ${ally.name}</span>` : ''; }).join('') || '<span class="text-secondary text-sm">No strong allies on this issue</span>'}
                </div>
              </div>
              <div>
                <div style="font-weight:700;color:var(--coral);margin-bottom:var(--space-sm);font-size:0.9rem;">âš”ï¸ Rivals</div>
                <div style="display:flex;flex-wrap:wrap;gap:var(--space-sm);">
                  ${country.rivals.map(r => { const rival = COUNTRIES.find(c => c.id === r); return rival ? `<span class="badge badge-coral">${rival.flag} ${rival.name}</span>` : ''; }).join('') || '<span class="text-secondary text-sm">No significant rivals</span>'}
                </div>
              </div>
            </div>
          </div>
          <div style="text-align:center;margin-top:var(--space-xl);">
            <button class="btn btn-gold" onclick="earnStudyXP('profile')">âœ… Mark as Read (+50 XP)</button>
          </div>
        </div>

        <!-- Key Terms -->
        <div class="tab-panel" id="panel-terms">
          <div style="max-width:700px;margin:0 auto;display:flex;flex-direction:column;gap:var(--space-md);" class="stagger">
            ${topic.keyTerms.map(kt => `
              <div class="card" style="border-left:3px solid ${topic.color};">
                <div style="font-family:'Outfit',sans-serif;font-weight:700;color:${topic.color};margin-bottom:6px;">${kt.term}</div>
                <p style="font-size:0.92rem;color:var(--text-primary);">${kt.def}</p>
              </div>
            `).join('')}
          </div>
          <div style="text-align:center;margin-top:var(--space-xl);">
            <button class="btn btn-gold" onclick="earnStudyXP('terms')">âœ… Mark as Read (+50 XP)</button>
          </div>
        </div>

        <!-- Sources -->
        <div class="tab-panel" id="panel-sources">
          <div style="max-width:700px;margin:0 auto;">
            <div style="display:flex;flex-direction:column;gap:var(--space-md);" class="stagger">
              ${topic.sources.map((s, i) => `
                <div class="card" style="display:flex;align-items:center;gap:var(--space-md);">
                  <div style="width:36px;height:36px;border-radius:50%;background:var(--grad-blue);display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:0.85rem;flex-shrink:0;">${i + 1}</div>
                  <div>
                    <div style="font-weight:600;color:var(--text-primary);font-size:0.92rem;">${s}</div>
                    <div style="font-size:0.75rem;color:var(--blue);margin-top:2px;">ðŸ“Ž UN Official Document</div>
                  </div>
                </div>
              `).join('')}
            </div>
          </div>
          <div style="text-align:center;margin-top:var(--space-xl);">
            <button class="btn btn-gold" onclick="earnStudyXP('sources')">âœ… Mark as Read (+50 XP)</button>
          </div>
        </div>

        <div class="section-divider"><span>Next Steps</span></div>
        <div style="display:flex;justify-content:center;gap:var(--space-md);flex-wrap:wrap;">
          <button class="btn btn-glass" onclick="navigate('research')">ðŸ’¬ AI Research Assistant</button>
          <button class="btn btn-glass" onclick="navigate('paper')">ðŸ“ Build Position Paper</button>
          <button class="btn btn-gold" onclick="navigate('quiz')">ðŸŽ® Take Quiz (+250 XP)</button>
        </div>
      </div>
    </div>
  `);
        }

        window.switchTab = function (btn, panel) {
            document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
            document.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
            btn.classList.add('active');
            document.getElementById('panel-' + panel).classList.add('active');
        };

        const studyDone = new Set();
        window.earnStudyXP = function (section) {
            if (!studyDone.has(section)) {
                studyDone.add(section);
                GameState.addXP(50, 'Study');
                showToast('ðŸ“š Knowledge Gained!', '+50 XP for completing this section!', 'xp');
                GameState.setScore('research', Math.min(100, GameState.getScores().research + 25));
            } else {
                showToast('âœ… Already Read', 'XP already earned for this section.', 'info');
            }
        };

        /* ================================================
           SCREEN 7 â€” AI RESEARCH CHAT
           ================================================ */
        let chatHistory = [];
        function renderResearch() {
            const country = getCountry(); const topic = getTopic();
            chatHistory = [{
                role: 'bot',
                text: `Greetings, delegate of ${country.flag} ${country.name}! I am your AI Policy Advisor. I can answer questions about ${country.name}'s position on ${topic.name}, provide policy analysis, and help you prepare for debate. What would you like to know?`
            }];
            setHTML(`
    <div class="page">
      <div class="container page-narrow">
        <div class="phase-banner">
          <div class="phase-number" style="background:var(--grad-blue);">ðŸ¤–</div>
          <div class="phase-info"><div class="phase-title">AI Policy Advisor</div><div class="phase-sub">${country.flag} ${country.name} Â· ${topic.emoji} ${topic.name}</div></div>
          <div class="phase-xp">+30 XP per question</div>
        </div>
        <div class="chat-container" id="chat-container">
          <div class="chat-messages" id="chat-messages">${renderChatMsg('bot', 'ðŸ¤–', chatHistory[0].text)}</div>
          <div class="chat-quick-btns">
            ${['What is our country\'s main position?', 'What are our key allies?', 'What proposed solutions should we support?', 'What are the main challenges we face?'].map(q =>
                `<button class="quick-btn" onclick="sendQuickQ('${q.replace(/'/g, "\\'")}')">ðŸ’¬ ${q}</button>`
            ).join('')}
          </div>
          <div class="chat-input-row">
            <input class="chat-input" id="chat-input" type="text" placeholder="Ask your policy advisor..." maxlength="200"/>
            <button class="btn btn-blue btn-sm" onclick="sendChat()" id="btn-chat-send">Send âž¤</button>
          </div>
        </div>
        <div style="text-align:center;margin-top:var(--space-xl);">
          <button class="btn btn-glass" onclick="navigate('paper')">ðŸ“ Build Position Paper â†’</button>
          <button class="btn btn-gold" style="margin-left:var(--space-md);" onclick="navigate('quiz')">ðŸŽ® Take Quiz â†’</button>
        </div>
      </div>
    </div>
  `);
            document.getElementById('chat-input').addEventListener('keydown', e => { if (e.key === 'Enter') sendChat(); });
        }

        function renderChatMsg(role, avatar, text) {
            return `<div class="chat-msg ${role}"><div class="chat-avatar">${avatar}</div><div class="chat-bubble">${text}</div></div>`;
        }

        window.sendQuickQ = function (q) {
            document.getElementById('chat-input').value = q;
            sendChat();
        };

        window.sendChat = function () {
            const input = document.getElementById('chat-input');
            const q = input.value.trim();
            if (!q) return;
            input.value = '';
            const msgs = document.getElementById('chat-messages');
            const country = getCountry(); const topic = getTopic();
            const player = GameState.getPlayer();

            // Add user message
            msgs.insertAdjacentHTML('beforeend', renderChatMsg('user', player.avatarEmoji || 'ðŸ§‘', q));

            // Show typing indicator
            const typingId = 'typing-' + Date.now();
            msgs.insertAdjacentHTML('beforeend', `<div class="chat-msg bot" id="${typingId}"><div class="chat-avatar">ðŸ¤–</div><div class="chat-bubble"><span class="typing-dot"></span><span class="typing-dot"></span><span class="typing-dot"></span></div></div>`);
            msgs.scrollTop = msgs.scrollHeight;

            // Simulate response delay
            setTimeout(() => {
                const el = document.getElementById(typingId);
                if (el) el.remove();
                const response = AIMentor.getResearchResponse(q, country.id, topic.id);
                msgs.insertAdjacentHTML('beforeend', renderChatMsg('bot', 'ðŸ¤–', response));
                msgs.scrollTop = msgs.scrollHeight;
                GameState.addXP(30, 'Research');
                GameState.setScore('research', Math.min(100, GameState.getScores().research + 5));
            }, 1200 + Math.random() * 800);
        };

        /* ================================================
           SCREEN 8 â€” POSITION PAPER BUILDER
           ================================================ */
        let paperStep = 1;
        function renderPaper() {
            const country = getCountry(); const topic = getTopic();
            const session = GameState.getSession();
            paperStep = 1;
            setHTML(`
    <div class="page">
      <div class="container page-narrow">
        <div class="phase-banner">
          <div class="phase-number">ðŸ“</div>
          <div class="phase-info"><div class="phase-title">Position Paper Builder</div><div class="phase-sub">${country.flag} ${country.name} Â· ${topic.emoji} ${topic.name}</div></div>
          <div class="phase-xp">+150 XP on completion</div>
        </div>

        <div class="stepper" id="paper-stepper">
          ${['Country Background', 'National Position', 'Past Actions', 'Proposed Solutions', 'Generate Paper'].map((s, i) => `
            <div class="step-item ${i === 0 ? 'active' : ''}" id="step-item-${i}">
              <div class="step-inner">
                <div class="step-circle" id="step-circle-${i}">${i + 1}</div>
                <div class="step-label">${s}</div>
              </div>
            </div>
            ${i < 4 ? `<div class="step-connector" id="step-conn-${i}"></div>` : ''}
          `).join('')}
        </div>

        <div id="paper-content">
          ${renderPaperStep(1, country, topic, session.paperContent)}
        </div>
      </div>
    </div>
  `);
        }

        function renderPaperStep(step, country, topic, saved) {
            const steps = [
                {
                    n: 1, title: 'Step 1: Country Background', icon: 'ðŸŒ',
                    prompt: `Provide a brief background on ${country.name}'s general stance on international issues and its role in the global community.`,
                    placeholder: `Describe ${country.name}'s position in the international community, its key foreign policy principles, and its general approach to multilateral cooperation...`,
                    key: 's1', hint: `Mention ${country.name}'s region (${country.region}), key alliances, and general diplomatic priorities.`
                },
                {
                    n: 2, title: 'Step 2: National Position', icon: 'ðŸ“Œ',
                    prompt: `What is ${country.name}'s specific position on ${topic.name}? What are your key policy priorities and red lines?`,
                    placeholder: `State ${country.name}'s official position on ${topic.name}, including key priorities, policy objectives, and any non-negotiable positions...`,
                    key: 's2', hint: country.policies[topic.id]?.substring(0, 100) + '...' || 'Research your country\'s official policies.'
                },
                {
                    n: 3, title: 'Step 3: Past Actions', icon: 'ðŸ“œ',
                    prompt: `What actions has ${country.name} already taken regarding ${topic.name}? What legislation, programs, or international agreements is your country party to?`,
                    placeholder: `Describe specific laws, programs, international agreements, and domestic initiatives ${country.name} has undertaken to address ${topic.name}...`,
                    key: 's3', hint: 'Include specific dates, legislation names, or treaty commitments where possible.'
                },
                {
                    n: 4, title: 'Step 4: Proposed Solutions', icon: 'ðŸ’¡',
                    prompt: `What solutions does ${country.name} propose for the committee to adopt? List specific, actionable recommendations.`,
                    placeholder: `Propose 3-5 specific, actionable solutions that ${country.name} recommends the committee endorse. Be specific about mechanisms, funding, and implementation...`,
                    key: 's4', hint: 'Solutions should be realistic, aligned with your country\'s interests, and broadly acceptable to allies.'
                }
            ];

            if (step === 5) {
                const sc = GameState.getScores();
                const paper = GameState.getSession().paperContent;
                const eval_ = AIMentor.evaluatePaper(paper);
                return `
      <div id="paper-final" style="animation:fadeSlideIn 0.4s ease;">
        <div style="text-align:center;margin-bottom:var(--space-xl);">
          <div style="font-size:3rem;margin-bottom:var(--space-md);">ðŸ“„</div>
          <h3 style="color:var(--text-primary);">AI Feedback on Your Position Paper</h3>
          <p>Score: <span style="color:var(--gold);font-weight:800;font-size:1.3rem;">${eval_.score}/100</span></p>
        </div>
        <div style="margin-bottom:var(--space-xl);">
          ${eval_.feedback.map(f => `<div class="feedback-item ${f.type}">${f.msg}</div>`).join('')}
        </div>
        <div class="card" style="margin-bottom:var(--space-xl);background:rgba(212,175,55,0.04);border-color:var(--border-gold);">
          <div style="color:var(--gold);font-weight:700;margin-bottom:var(--space-md);">ðŸ“„ Your Position Paper â€” ${country.flag} ${country.name} on ${topic.name}</div>
          <div style="font-size:0.88rem;color:var(--text-secondary);line-height:1.8;">
            <strong style="color:var(--text-primary);">I. Country Background</strong><br/>${paper.s1 || '(Not completed)'}<br/><br/>
            <strong style="color:var(--text-primary);">II. National Position</strong><br/>${paper.s2 || '(Not completed)'}<br/><br/>
            <strong style="color:var(--text-primary);">III. Past Actions</strong><br/>${paper.s3 || '(Not completed)'}<br/><br/>
            <strong style="color:var(--text-primary);">IV. Proposed Solutions</strong><br/>${paper.s4 || '(Not completed)'}
          </div>
        </div>
        <div style="display:flex;gap:var(--space-md);justify-content:center;">
          <button class="btn btn-glass" onclick="paperStep=4;renderPaperContent()">â† Edit Paper</button>
          <button class="btn btn-gold" onclick="submitPaper()">Submit & Continue to Quiz ðŸŽ®</button>
        </div>
      </div>
    `;
            }

            const s = steps[step - 1];
            return `
    <div style="animation:fadeSlideIn 0.3s ease;">
      <div class="card mb-lg" style="border-color:var(--border-gold);">
        <div style="font-size:1.5rem;margin-bottom:var(--space-sm);">${s.icon}</div>
        <h4 style="color:var(--text-primary);margin-bottom:var(--space-sm);">${s.title}</h4>
        <p style="font-size:0.9rem;">${s.prompt}</p>
      </div>
      <div class="card mb-lg">
        <div style="font-size:0.8rem;color:var(--blue);margin-bottom:var(--space-sm);">ðŸ’¡ Hint: ${s.hint}</div>
        <textarea class="textarea" id="paper-textarea" rows="8" placeholder="${s.placeholder}">${saved[s.key] || ''}</textarea>
        <div style="display:flex;justify-content:space-between;margin-top:var(--space-sm);">
          <span id="paper-wordcount" style="font-size:0.78rem;color:var(--text-muted);">0 words</span>
          <span style="font-size:0.78rem;color:var(--text-muted);">Recommended: 50-150 words</span>
        </div>
      </div>
      <div style="display:flex;justify-content:space-between;">
        ${step > 1 ? `<button class="btn btn-glass" onclick="paperNav(-1)">â† Previous</button>` : '<div></div>'}
        <button class="btn btn-gold" onclick="paperNav(1)">Next Step â†’</button>
      </div>
    </div>
  `;
        }

        window.paperNav = function (dir) {
            const textarea = document.getElementById('paper-textarea');
            const session = GameState.getSession();
            if (textarea && dir === 1) {
                const key = ['', 's1', 's2', 's3', 's4'][paperStep];
                if (key) GameState.setSession('paperContent', { ...session.paperContent, [key]: textarea.value });
            }
            paperStep = Math.max(1, Math.min(5, paperStep + dir));
            renderPaperContent();
        };

        function renderPaperContent() {
            const country = getCountry(); const topic = getTopic();
            const session = GameState.getSession();
            document.getElementById('paper-content').innerHTML = renderPaperStep(paperStep, country, topic, session.paperContent);
            // Update stepper
            for (let i = 0; i < 5; i++) {
                const item = document.getElementById('step-item-' + i);
                const circle = document.getElementById('step-circle-' + i);
                const conn = document.getElementById('step-conn-' + i);
                if (!item) continue;
                item.classList.toggle('active', i === paperStep - 1);
                item.classList.toggle('done', i < paperStep - 1);
                if (conn) conn.classList.toggle('done', i < paperStep - 1);
            }
            // Wordcount
            const ta = document.getElementById('paper-textarea');
            const wc = document.getElementById('paper-wordcount');
            if (ta && wc) {
                ta.addEventListener('input', () => { wc.textContent = ta.value.trim().split(/\s+/).filter(Boolean).length + ' words'; });
                wc.textContent = ta.value.trim().split(/\s+/).filter(Boolean).length + ' words';
            }
        }

        window.submitPaper = function () {
            GameState.addXP(150, 'Position Paper');
            GameState.setScore('resolution', 70);
            GameState.unlockBadge('policy-expert');
            navigate('quiz');
        };

        /* ================================================
           SCREEN 9 â€” QUIZ
           ================================================ */
        let quizState = { current: 0, score: 0, answered: false };
        function renderQuiz() {
            const topic = getTopic();
            quizState = { current: 0, score: 0, answered: false };
            setHTML(`
    <div class="page">
      <div class="container page-narrow">
        <div class="phase-banner">
          <div class="phase-number" style="background:var(--grad-emerald);">ðŸŽ®</div>
          <div class="phase-info"><div class="phase-title">Research Mini-Challenge</div><div class="phase-sub">${topic.emoji} ${topic.name} Â· 5 Questions</div></div>
          <div class="phase-xp">+50 XP per correct answer</div>
        </div>
        <div id="quiz-container"></div>
      </div>
    </div>
  `);
            renderQuizQuestion();
        }

        function renderQuizQuestion() {
            const topic = getTopic();
            const q = topic.quizzes[quizState.current];
            if (!q) { renderQuizResults(); return; }

            document.getElementById('quiz-container').innerHTML = `
    <div style="animation:fadeSlideIn 0.3s ease;">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:var(--space-lg);">
        <div style="font-size:0.85rem;color:var(--text-muted);">Question ${quizState.current + 1} of ${topic.quizzes.length}</div>
        <div style="display:flex;gap:4px;">${topic.quizzes.map((_, i) => `<div style="width:24px;height:4px;border-radius:2px;background:${i <= quizState.current ? 'var(--gold)' : 'var(--bg-elevated)'};transition:background 0.3s;"></div>`).join('')}</div>
        <div style="font-family:'Outfit',sans-serif;font-weight:700;color:var(--gold);">Score: ${quizState.score}/${quizState.current}</div>
      </div>
      <div class="card mb-lg" style="padding:var(--space-xl);">
        <div class="quiz-question">${q.q}</div>
        <div id="quiz-options">
          ${q.opts.map((opt, i) => `<button class="quiz-option" onclick="answerQuiz(${i})" id="qopt-${i}"><span class="quiz-letter">${'ABCD'[i]}</span>${opt}</button>`).join('')}
        </div>
        <div id="quiz-feedback" style="display:none;margin-top:var(--space-md);padding:var(--space-md);border-radius:var(--radius-md);"></div>
      </div>
    </div>
  `;
        }

        window.answerQuiz = function (idx) {
            if (quizState.answered) return;
            quizState.answered = true;
            const topic = getTopic();
            const q = topic.quizzes[quizState.current];
            const correct = idx === q.ans;

            document.querySelectorAll('.quiz-option').forEach((el, i) => {
                if (i === q.ans) el.classList.add('correct');
                else if (i === idx) el.classList.add('wrong');
                el.disabled = true;
            });

            const fb = document.getElementById('quiz-feedback');
            fb.style.display = 'block';
            fb.style.background = correct ? 'rgba(0,200,150,0.08)' : 'rgba(255,99,72,0.08)';
            fb.style.border = `1px solid ${correct ? 'var(--border-emerald)' : 'rgba(255,99,72,0.3)'}`;
            fb.style.color = correct ? 'var(--emerald)' : 'var(--coral)';
            fb.innerHTML = `${correct ? 'âœ… Correct!' : 'âŒ Incorrect.'} ${q.exp}`;

            if (correct) {
                quizState.score++;
                GameState.addXP(50, 'Quiz');
            }

            setTimeout(() => {
                quizState.current++;
                quizState.answered = false;
                renderQuizQuestion();
            }, 2000);
        };

        function renderQuizResults() {
            const total = getTopic().quizzes.length;
            const pct = Math.round((quizState.score / total) * 100);
            if (pct === 100) GameState.unlockBadge('research-ace');
            GameState.setScore('research', Math.min(100, pct));

            document.getElementById('quiz-container').innerHTML = `
    <div style="text-align:center;animation:fadeSlideIn 0.4s ease;padding:var(--space-3xl);">
      <div style="font-size:4rem;margin-bottom:var(--space-lg);">${pct >= 80 ? 'ðŸ†' : pct >= 60 ? 'ðŸŽ¯' : 'ðŸ“š'}</div>
      <h2 style="color:var(--text-primary);margin-bottom:var(--space-sm);">${pct >= 80 ? 'Excellent!' : pct >= 60 ? 'Good Work!' : 'Keep Studying!'}</h2>
      <p style="margin-bottom:var(--space-xl);">You scored <strong style="color:var(--gold);font-size:1.3rem;">${quizState.score}/${total}</strong> (${pct}%)</p>
      <div style="max-width:200px;margin:0 auto var(--space-2xl);">
        <div class="xp-bar"><div class="xp-bar-fill" style="width:${pct}%"></div></div>
        <div style="font-size:0.8rem;color:var(--text-muted);margin-top:6px;">Research Score: ${pct}%</div>
      </div>
      <div style="display:flex;gap:var(--space-md);justify-content:center;flex-wrap:wrap;">
        <button class="btn btn-glass" onclick="navigate('study')">ðŸ“š Review Study Guide</button>
        <button class="btn btn-gold btn-lg" onclick="navigate('committee')">Enter Committee Session ðŸ›ï¸</button>
      </div>
    </div>
  `;
        }

        /* ================================================
           SCREEN 10 â€” COMMITTEE SESSION
           ================================================ */
        function renderCommittee() {
            const council = getCouncil(); const country = getCountry(); const topic = getTopic();
            const chairScript = AIMentor.getChairScript('opening', { council: council.name, topic: topic.name, country: country.name });
            setHTML(`
    <div class="page">
      <div class="container">
        <div class="phase-banner" style="background:rgba(212,175,55,0.08);border-color:var(--border-gold);">
          <div class="phase-number" style="font-size:1.5rem;">âš–ï¸</div>
          <div class="phase-info"><div class="phase-title" style="font-size:1.1rem;">Phase 2 â€” Committee Session</div><div class="phase-sub">${council.emoji} ${council.name} Â· ${topic.emoji} ${topic.name}</div></div>
          <div style="font-family:'Outfit',sans-serif;font-size:0.85rem;color:var(--text-secondary);">ðŸ§‘â€âš–ï¸ Chair: Dr. Amara Johnson</div>
        </div>

        <!-- Chair NPC -->
        <div class="npc-chair">
          <div class="npc-avatar" style="animation:fadeSlideIn 0.6s ease;">ðŸ§‘â€âš–ï¸</div>
          <div>
            <div class="npc-speech-bubble">
              <span id="chair-speech"></span>
            </div>
            <div class="npc-name">ðŸŽ¤ Dr. Amara Johnson â€” Committee Chair</div>
          </div>
        </div>

        <!-- Countries in committee -->
        <div class="card mb-xl">
          <div style="font-weight:700;color:var(--text-primary);margin-bottom:var(--space-md);">ðŸŒ Delegates Present</div>
          <div style="display:flex;flex-wrap:wrap;gap:var(--space-sm);">
            ${COUNTRIES.map(c => `<span class="badge badge-gray ${c.id === country.id ? 'badge-gold' : ''}">${c.flag} ${c.name}${c.id === country.id ? ' (You)' : ''}</span>`).join('')}
          </div>
        </div>

        <!-- Phase navigation -->
        <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:var(--space-lg);margin-bottom:var(--space-xl);">
          ${[
                    { e: 'ðŸŽ¤', t: 'Open Speakers List', d: 'Deliver your opening statement to the committee', route: 'speech', btn: 'Begin GSL' },
                    { e: 'ðŸ’¬', t: 'Caucus', d: 'Request moderated or unmoderated caucus', route: 'caucus', btn: 'Request Caucus' },
                    { e: 'ðŸ¤', t: 'Bloc Formation', d: 'Lobby and negotiate with other delegations', route: 'bloc', btn: 'Start Lobbying' }
                ].map(m => `
            <div class="card card-selectable" onclick="navigate('${m.route}')">
              <div style="font-size:2rem;margin-bottom:var(--space-sm);">${m.e}</div>
              <div style="font-family:'Outfit',sans-serif;font-weight:700;color:var(--text-primary);margin-bottom:4px;">${m.t}</div>
              <p style="font-size:0.82rem;margin-bottom:var(--space-md);">${m.d}</p>
              <button class="btn btn-glass btn-sm">${m.btn} â†’</button>
            </div>
          `).join('')}
        </div>

        <!-- Crisis Event trigger -->
        <div class="card crisis-alert" style="display:flex;align-items:center;gap:var(--space-lg);cursor:pointer;" onclick="navigate('crisis')">
          <div style="font-size:2.5rem;">ðŸš¨</div>
          <div>
            <div style="font-family:'Outfit',sans-serif;font-weight:700;color:var(--coral);">CRISIS ALERT â€” Incoming Event</div>
            <div style="font-size:0.85rem;color:var(--text-secondary);">A crisis situation has emerged requiring immediate committee response</div>
          </div>
          <button class="btn btn-danger btn-sm" style="margin-left:auto;">Handle Crisis â†’</button>
        </div>
      </div>
    </div>
  `);
            setTimeout(() => typewriter('chair-speech', chairScript, 25), 500);
        }

        /* ================================================
           SCREEN 11 â€” SPEECH MODE
           ================================================ */
        function renderSpeech() {
            const country = getCountry(); const topic = getTopic(); const player = GameState.getPlayer();
            setHTML(`
    <div class="page">
      <div class="container page-narrow">
        <div class="phase-banner">
          <div class="phase-number" style="font-size:1.5rem;">ðŸŽ¤</div>
          <div class="phase-info"><div class="phase-title">General Speakers List</div><div class="phase-sub">${country.flag} ${country.name} â€” Opening Statement on ${topic.name}</div></div>
          <div class="phase-xp">+100 XP</div>
        </div>

        <div class="npc-chair" style="margin-bottom:var(--space-lg);">
          <div class="npc-avatar">ðŸ§‘â€âš–ï¸</div>
          <div>
            <div class="npc-speech-bubble">The chair recognizes the delegate of ${country.name}. You have <strong>90 seconds</strong> for your opening statement. Please proceed.</div>
            <div class="npc-name">ðŸŽ¤ Committee Chair</div>
          </div>
        </div>

        <!-- Speech tips -->
        <div class="card mb-lg" style="background:rgba(79,195,247,0.04);border-color:var(--border-blue);">
          <div style="font-weight:700;color:var(--blue);margin-bottom:var(--space-sm);">ðŸ’¡ Speech Tips</div>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:8px;font-size:0.82rem;color:var(--text-secondary);">
            <span>âœ“ Address the Chair ("Honorable Chair...")</span>
            <span>âœ“ State your country's clear position</span>
            <span>âœ“ Cite specific evidence or UN documents</span>
            <span>âœ“ End with a call to action ("...calls upon...")</span>
          </div>
        </div>

        <div class="card mb-lg">
          <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:var(--space-md);">
            <h4 style="color:var(--text-primary);">Your Speech</h4>
            <div style="display:flex;gap:var(--space-sm);align-items:center;">
              <div id="speech-timer" style="font-family:'Outfit',sans-serif;font-weight:700;color:var(--gold);font-size:1.1rem;">90s</div>
              <button class="btn btn-glass btn-sm" id="timer-btn" onclick="toggleTimer()">â–¶ Start Timer</button>
            </div>
          </div>
          <textarea class="textarea" id="speech-textarea" rows="12" placeholder="Honorable Chair, Distinguished Delegates,

On behalf of the delegation of ${country.name}, we wish to express our position on ${topic.name}...

[State your country's position clearly, backed by evidence]

...Therefore, the delegation of ${country.name} calls upon this committee to...

Thank you."></textarea>
          <div style="display:flex;justify-content:space-between;margin-top:var(--space-sm);">
            <span id="speech-wordcount" style="font-size:0.78rem;color:var(--text-muted);">0 words (recommended: 100-150)</span>
            <span style="font-size:0.78rem;color:var(--text-muted);">Country: ${country.flag} ${country.name}</span>
          </div>
        </div>

        <div style="display:flex;gap:var(--space-md);justify-content:center;">
          <button class="btn btn-glass" onclick="navigate('committee')">â† Back to Committee</button>
          <button class="btn btn-gold btn-lg" onclick="submitSpeech()" id="btn-submit-speech">Submit for Evaluation ðŸ“Š</button>
        </div>

        <!-- Evaluation Result (hidden initially) -->
        <div id="speech-eval" style="display:none;margin-top:var(--space-xl);animation:fadeSlideIn 0.4s ease;"></div>
      </div>
    </div>
  `);

            let timerRunning = false, timerLeft = 90, timerInterval;
            window.toggleTimer = function () {
                if (timerRunning) {
                    clearInterval(timerInterval);
                    timerRunning = false;
                    document.getElementById('timer-btn').textContent = 'â–¶ Resume';
                } else {
                    timerRunning = true;
                    document.getElementById('timer-btn').textContent = 'â¸ Pause';
                    timerInterval = setInterval(() => {
                        timerLeft--;
                        document.getElementById('speech-timer').textContent = timerLeft + 's';
                        if (timerLeft <= 10) document.getElementById('speech-timer').style.color = 'var(--coral)';
                        if (timerLeft <= 0) { clearInterval(timerInterval); document.getElementById('speech-timer').textContent = 'â° Time!'; }
                    }, 1000);
                }
            };

            const ta = document.getElementById('speech-textarea');
            const wc = document.getElementById('speech-wordcount');
            ta.addEventListener('input', () => { wc.textContent = ta.value.trim().split(/\s+/).filter(Boolean).length + ' words (recommended: 100-150)'; });

            window.submitSpeech = function () {
                const text = ta.value.trim();
                if (text.length < 20) { showToast('âš ï¸ Too Short', 'Write at least a few sentences for your speech.', 'error'); return; }
                const eval_ = AIMentor.evaluateSpeech(text);
                GameState.setSession('speechText', text);
                GameState.setScore('speech', eval_.overall);
                GameState.addXP(100, 'Speech');
                GameState.unlockBadge('first-speech');
                clearInterval(timerInterval);

                const colors = { diplomacy: 'var(--gold)', structure: 'var(--blue)', confidence: 'var(--emerald)', relevance: 'var(--purple)' };
                document.getElementById('speech-eval').style.display = 'block';
                document.getElementById('speech-eval').innerHTML = `
      <div class="card" style="border-color:var(--border-gold);">
        <h3 style="color:var(--text-primary);margin-bottom:var(--space-lg);text-align:center;">AI Speech Evaluation</h3>
        <div style="display:grid;grid-template-columns:repeat(2,1fr);gap:var(--space-md);margin-bottom:var(--space-xl);" class="stagger">
          ${Object.entries(colors).map(([k, c]) => `
            <div class="score-reveal" style="text-align:center;padding:var(--space-md);border-radius:var(--radius-lg);background:rgba(255,255,255,0.03);border:1px solid ${c.replace('var(', '').replace(')', '').includes('#') ? c : 'rgba(255,255,255,0.1)'};">
              <div style="font-size:1.8rem;font-family:'Outfit',sans-serif;font-weight:800;color:${c};">${eval_[k]}</div>
              <div style="font-size:0.75rem;text-transform:uppercase;letter-spacing:0.08em;color:var(--text-muted);">${k}</div>
              <div style="margin-top:8px;height:4px;background:var(--bg-elevated);border-radius:2px;overflow:hidden;"><div style="height:100%;background:${c};width:${eval_[k]}%;transition:width 1s ease;"></div></div>
            </div>
          `).join('')}
        </div>
        <div style="text-align:center;margin-bottom:var(--space-lg);">
          <div style="font-size:3rem;font-family:'Outfit',sans-serif;font-weight:900;color:${eval_.overall >= 80 ? 'var(--gold)' : eval_.overall >= 60 ? 'var(--blue)' : 'var(--coral)'};">${eval_.overall}</div>
          <div style="color:var(--text-secondary);">Overall Score / 100 Â· ${eval_.words} words</div>
        </div>
        <div class="feedback-item ${eval_.overall >= 70 ? 'good' : eval_.overall >= 50 ? 'warn' : 'bad'}">${eval_.feedback}</div>
        <div style="display:flex;gap:var(--space-md);justify-content:center;margin-top:var(--space-xl);">
          <button class="btn btn-glass" onclick="navigate('committee')">â† Committee</button>
          <button class="btn btn-gold" onclick="navigate('workingpaper')">Draft Resolution ðŸ“„</button>
        </div>
      </div>
    `;
                document.getElementById('speech-eval').scrollIntoView({ behavior: 'smooth' });
            };
        }

        /* ================================================
           SCREEN 12 â€” CAUCUS
           ================================================ */
        function renderCaucus() {
            const topics = ['Root causes and background', 'Economic dimensions', 'Human rights implications', 'National sovereignty considerations', 'Proposed mechanisms and funding'];
            setHTML(`
    <div class="page">
      <div class="container page-narrow">
        <div class="phase-banner">
          <div class="phase-number">ðŸ’¬</div>
          <div class="phase-info"><div class="phase-title">Caucus Selection</div><div class="phase-sub">Request a formal or informal discussion period</div></div>
        </div>
        <div class="grid-2" style="gap:var(--space-xl);margin-bottom:var(--space-xl);">
          <div class="card card-selectable" id="moderated-card" onclick="selectCaucus('moderated')" style="padding:var(--space-2xl);text-align:center;">
            <div style="font-size:3rem;margin-bottom:var(--space-lg);">ðŸŽ™ï¸</div>
            <h3 style="color:var(--text-primary);margin-bottom:var(--space-sm);">Moderated Caucus</h3>
            <p style="margin-bottom:var(--space-lg);">Formal, structured discussion with the Chair recognizing speakers on a specific sub-topic. Delegates make short speeches.</p>
            <div style="display:flex;flex-wrap:wrap;gap:var(--space-sm);justify-content:center;">
              <span class="badge badge-blue">Formal</span><span class="badge badge-gray">1-2 min speeches</span><span class="badge badge-gray">Chair moderates</span>
            </div>
          </div>
          <div class="card card-selectable" id="unmoderated-card" onclick="selectCaucus('unmoderated')" style="padding:var(--space-2xl);text-align:center;">
            <div style="font-size:3rem;margin-bottom:var(--space-lg);">ðŸ¤</div>
            <h3 style="color:var(--text-primary);margin-bottom:var(--space-sm);">Unmoderated Caucus</h3>
            <p style="margin-bottom:var(--space-lg);">Informal networking period where delegates move freely to lobby, negotiate, and form blocs. No formal speaking order.</p>
            <div style="display:flex;flex-wrap:wrap;gap:var(--space-sm);justify-content:center;">
              <span class="badge badge-emerald">Informal</span><span class="badge badge-gray">Free movement</span><span class="badge badge-gray">Negotiation time</span>
            </div>
          </div>
        </div>
        <!-- Moderated sub-topics -->
        <div id="moderated-options" style="display:none;" class="card mb-xl">
          <h4 style="color:var(--text-primary);margin-bottom:var(--space-md);">ðŸŽ¯ Moderated Caucus Sub-Topic</h4>
          <div style="display:flex;flex-direction:column;gap:var(--space-sm);" id="sub-topic-list">
            ${topics.map((t, i) => `<button class="quiz-option" onclick="selectSubTopic(${i},'${t.replace(/'/g, "\\'")}')"><span class="quiz-letter">${i + 1}</span>${t}</button>`).join('')}
          </div>
        </div>
        <div id="unmoderated-options" style="display:none;" class="card mb-xl" style="background:rgba(0,200,150,0.04);border-color:var(--border-emerald);">
          <h4 style="color:var(--emerald);margin-bottom:var(--space-md);">ðŸ¤ Unmoderated Caucus â€” Lobby Mode</h4>
          <p style="margin-bottom:var(--space-md);">Use this time to approach other delegations and build support for your resolution. The chair grants <strong>15 minutes</strong> of unmoderated caucus.</p>
          <button class="btn btn-emerald" onclick="navigate('bloc')">Start Bloc Formation & Lobbying ðŸ—ºï¸</button>
        </div>
      </div>
    </div>
  `);
        }

        let selectedCaucus = null;
        window.selectCaucus = function (type) {
            selectedCaucus = type;
            document.getElementById('moderated-card').classList.toggle('selected', type === 'moderated');
            document.getElementById('unmoderated-card').classList.toggle('selected', type === 'unmoderated');
            document.getElementById('moderated-options').style.display = type === 'moderated' ? 'block' : 'none';
            document.getElementById('unmoderated-options').style.display = type === 'unmoderated' ? 'block' : 'none';
        };

        window.selectSubTopic = function (i, topic) {
            document.querySelectorAll('#sub-topic-list .quiz-option').forEach((el, j) => el.classList.toggle('correct', j === i));
            showToast('ðŸŽ™ï¸ Caucus Granted', `Moderated caucus on: ${topic}`, 'success');
            GameState.addXP(30, 'Caucus');
            setTimeout(() => navigate('speech'), 1500);
        };

        /* ================================================
           SCREEN 13 â€” BLOC FORMATION
           ================================================ */
        function renderBloc() {
            const myCountry = getCountry();
            const positions = [
                { id: 'indonesia', x: '48%', y: '55%' }, { id: 'malaysia', x: '53%', y: '57%' }, { id: 'singapore', x: '55%', y: '60%' },
                { id: 'china', x: '60%', y: '40%' }, { id: 'russia', x: '55%', y: '30%' }, { id: 'france', x: '40%', y: '32%' },
                { id: 'usa', x: '20%', y: '38%' }, { id: 'uk', x: '38%', y: '28%' }, { id: 'israel', x: '47%', y: '42%' }
            ];

            let blocAllies = GameState.getSession().blocAllies || [];

            setHTML(`
    <div class="page">
      <div class="container">
        <div class="phase-banner">
          <div class="phase-number">ðŸ¤</div>
          <div class="phase-info"><div class="phase-title">Bloc Formation â€” Political Map</div><div class="phase-sub">${myCountry.flag} ${myCountry.name} Â· Build your coalition</div></div>
          <div class="phase-xp">+50 XP per ally Â· +200 XP for bloc</div>
        </div>

        <div style="display:grid;grid-template-columns:2fr 1fr;gap:var(--space-xl);">
          <!-- Map -->
          <div>
            <div class="bloc-map" id="bloc-map">
              ${positions.map(p => {
                const c = COUNTRIES.find(x => x.id === p.id);
                if (!c) return '';
                const isPlayer = c.id === myCountry.id;
                const isAlly = blocAllies.includes(c.id);
                const isAlly_ = myCountry.allies.includes(c.id);
                return `
                  <div class="bloc-node ${isPlayer ? 'player' : isAlly ? 'allied' : ''}" style="left:${p.x};top:${p.y};transform:translate(-50%,-50%);" id="bnode-${c.id}" onclick="${!isPlayer ? `inviteAlly('${c.id}')` : ''}" title="${c.name}">
                    <div class="bloc-node-flag" style="${isAlly_ && !isAlly ? 'border-color:rgba(0,200,150,0.4);' : ''}">${c.flag}</div>
                    <div class="bloc-node-name">${c.name}</div>
                    ${isPlayer ? '<div style="font-size:0.6rem;color:var(--gold);font-weight:700;">YOU</div>' : ''}
                  </div>
                `;
            }).join('')}
            </div>
            <div style="display:flex;gap:var(--space-md);margin-top:var(--space-md);font-size:0.78rem;color:var(--text-muted);">
              <span>ðŸŸ¡ You</span><span style="color:var(--emerald);">ðŸŸ¢ Allied</span><span>â¬œ Neutral</span>
              <span style="color:var(--text-secondary);margin-left:auto;">Click countries to invite to your bloc</span>
            </div>
          </div>

          <!-- Sidebar -->
          <div>
            <div class="card mb-lg">
              <h4 style="color:var(--text-primary);margin-bottom:var(--space-md);">ðŸ¤ Your Bloc</h4>
              <div style="display:flex;flex-direction:column;gap:var(--space-sm);" id="bloc-list">
                <div class="badge badge-gold">${myCountry.flag} ${myCountry.name} (You)</div>
                ${blocAllies.map(id => { const c = COUNTRIES.find(x => x.id === id); return c ? `<div class="badge badge-emerald">${c.flag} ${c.name}</div>` : '' }).join('')}
                ${blocAllies.length === 0 ? '<div style="font-size:0.82rem;color:var(--text-muted);">No allies yet. Click countries on the map to invite them.</div>' : ''}
              </div>
            </div>

            ${myCountry.allies.length > 0 ? `
            <div class="card mb-lg" style="background:rgba(0,200,150,0.04);border-color:var(--border-emerald);">
              <div style="font-size:0.78rem;color:var(--emerald);font-weight:700;margin-bottom:var(--space-sm);">ðŸ’¡ SUGGESTED ALLIES</div>
              ${myCountry.allies.map(id => { const c = COUNTRIES.find(x => x.id === id); return c ? `<button class="btn btn-glass btn-sm" style="width:100%;margin-bottom:6px;justify-content:flex-start;" onclick="inviteAlly('${c.id}')">${c.flag} Invite ${c.name}</button>` : '' }).join('')}
            </div>
            ` : ''}

            <div class="card">
              <div style="font-size:0.78rem;color:var(--text-muted);margin-bottom:var(--space-sm);">BLOC STRENGTH</div>
              <div style="font-family:'Outfit',sans-serif;font-size:2rem;font-weight:800;color:var(--gold);margin-bottom:4px;">${blocAllies.length + 1}</div>
              <div style="font-size:0.82rem;color:var(--text-secondary);">Countries Â· ${blocAllies.length >= 2 ? 'âœ… Bloc formed!' : `Need ${2 - blocAllies.length} more for minimum bloc`}</div>
            </div>
          </div>
        </div>

        <div style="display:flex;gap:var(--space-md);justify-content:center;margin-top:var(--space-xl);">
          <button class="btn btn-glass" onclick="navigate('committee')">â† Committee</button>
          <button class="btn btn-gold btn-lg" onclick="finalizeBloc()">Continue â†’ Draft Resolution ðŸ“„</button>
        </div>
      </div>
    </div>
  `);
        }

        window.inviteAlly = function (id) {
            const c = COUNTRIES.find(x => x.id === id);
            const myCountry = getCountry();
            const session = GameState.getSession();
            let allies = session.blocAllies || [];

            if (allies.includes(id)) {
                showToast('â„¹ï¸ Already Allied', `${c.name} is already in your bloc.`, 'info');
                return;
            }

            // AI decision: allies more likely to accept, rivals less likely
            const isAlly = myCountry.allies.includes(id);
            const isRival = myCountry.rivals.includes(id);
            const accepted = isRival ? Math.random() > 0.8 : isAlly ? Math.random() > 0.1 : Math.random() > 0.4;

            if (accepted) {
                allies = [...allies, id];
                GameState.setSession('blocAllies', allies);
                GameState.addXP(50, 'Alliance');
                showToast(`ðŸ¤ Alliance Formed!`, `${c.flag} ${c.name} has joined your bloc!`, 'success');
                const node = document.getElementById('bnode-' + id);
                if (node) node.classList.add('allied');
                const list = document.getElementById('bloc-list');
                if (list) list.insertAdjacentHTML('beforeend', `<div class="badge badge-emerald bounce-in">${c.flag} ${c.name}</div>`);
                if (allies.length >= 2) GameState.unlockBadge('master-negotiator');
            } else {
                showToast(`âŒ Invitation Rejected`, `${c.flag} ${c.name} has declined your invitation at this time.`, 'info');
                const node = document.getElementById('bnode-' + id);
                if (node) node.classList.add('rejected');
            }
        };

        window.finalizeBloc = function () {
            const allies = GameState.getSession().blocAllies;
            if (allies.length > 0) {
                GameState.addXP(100, 'Bloc Formation');
                GameState.setScore('negotiation', Math.min(100, allies.length * 30 + 40));
                showToast('ðŸŽ‰ Bloc Finalized!', `Your coalition of ${allies.length + 1} nations is ready!`, 'success');
            }
            navigate('workingpaper');
        };

        /* ================================================
           SCREEN 14 â€” WORKING PAPER (Resolution Builder)
           ================================================ */
        let wpState = { pre: [], op: [] };
        function renderWorkingPaper() {
            const country = getCountry(); const topic = getTopic();
            wpState = { pre: [], op: [] };
            setHTML(`
    <div class="page">
      <div class="container">
        <div class="phase-banner">
          <div class="phase-number">ðŸ“„</div>
          <div class="phase-info"><div class="phase-title">Phase 3 â€” Working Paper & Draft Resolution</div><div class="phase-sub">${country.flag} ${country.name} Â· ${topic.emoji} ${topic.name}</div></div>
          <div class="phase-xp">+150 XP on completion</div>
        </div>

        <div class="grid-2" style="gap:var(--space-xl);">
          <!-- Clause Pools -->
          <div>
            <div class="card mb-lg">
              <h4 style="color:var(--gold);margin-bottom:var(--space-md);">ðŸ“‹ Preambulatory Clauses</h4>
              <p style="font-size:0.82rem;margin-bottom:var(--space-md);">Drag or click to add to your resolution (establish context & background)</p>
              <div class="clause-pool" id="pre-pool">
                ${PREAMBULATORY_CLAUSES.slice(0, 20).map(c => `<div class="clause-chip" onclick="addClause('pre','${c}')" title="Click to add">${c}</div>`).join('')}
              </div>
            </div>
            <div class="card">
              <h4 style="color:var(--emerald);margin-bottom:var(--space-md);">âš¡ Operative Clauses</h4>
              <p style="font-size:0.82rem;margin-bottom:var(--space-md);">Actions the resolution takes (Decides, Calls Upon, Encourages, etc.)</p>
              <div class="clause-pool" id="op-pool">
                ${OPERATIVE_CLAUSES.slice(0, 20).map(c => `<div class="clause-chip" onclick="addClause('op','${c}')" title="Click to add">${c}</div>`).join('')}
              </div>
            </div>
          </div>

          <!-- Resolution Preview -->
          <div>
            <div class="card" style="height:100%;">
              <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:var(--space-lg);">
                <h4 style="color:var(--text-primary);">ðŸ“œ Draft Resolution</h4>
                <button class="btn btn-glass btn-sm" onclick="clearResolution()">ðŸ—‘ Clear</button>
              </div>
              <div style="font-family:'Outfit',sans-serif;font-size:0.8rem;color:var(--text-muted);margin-bottom:var(--space-md);">
                <strong style="color:var(--gold);">FORUM:</strong> ${getCouncil().name}<br/>
                <strong style="color:var(--gold);">TOPIC:</strong> ${topic.name}<br/>
                <strong style="color:var(--gold);">SPONSORS:</strong> ${country.name}${GameState.getSession().blocAllies.map(id => { const c = COUNTRIES.find(x => x.id === id); return c ? ', ' + c.name : '' }).join('')}
              </div>

              <!-- Preambulatory section -->
              <div style="margin-bottom:var(--space-lg);">
                <div style="font-size:0.78rem;color:var(--gold);font-weight:700;text-transform:uppercase;letter-spacing:0.1em;margin-bottom:var(--space-sm);">Preambulatory Clauses</div>
                <div id="pre-drop" class="clause-drop-zone">
                  <div class="clause-drop-placeholder" id="pre-placeholder">Click preambulatory clauses above to add them here...</div>
                </div>
              </div>

              <!-- Operative section -->
              <div style="margin-bottom:var(--space-lg);">
                <div style="font-size:0.78rem;color:var(--emerald);font-weight:700;text-transform:uppercase;letter-spacing:0.1em;margin-bottom:var(--space-sm);">Operative Clauses</div>
                <div id="op-drop" class="clause-drop-zone">
                  <div class="clause-drop-placeholder" id="op-placeholder">Click operative clauses above to add them here...</div>
                </div>
              </div>

              <!-- AI Check -->
              <div id="wp-feedback" style="display:none;margin-bottom:var(--space-lg);"></div>

              <div style="display:flex;gap:var(--space-sm);">
                <button class="btn btn-glass btn-sm" onclick="checkResolution()">ðŸ¤– AI Format Check</button>
                <button class="btn btn-gold btn-sm" onclick="submitResolution()">Submit Resolution â†’</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  `);
        }

        window.addClause = function (type, word) {
            const zone = document.getElementById(type + '-drop');
            const placeholder = document.getElementById(type + '-placeholder');
            if (placeholder) placeholder.style.display = 'none';
            const idx = wpState[type].length + 1;
            const clauseText = type === 'pre' ? 'that significant progress in addressing ' + getTopic().name + ' requires coordinated multilateral action...' :
                'member states to strengthen international cooperation frameworks on ' + getTopic().name + '...';
            wpState[type].push({ word, text: clauseText });

            const el = document.createElement('div');
            el.className = 'clause-item';
            el.innerHTML = `
    <span class="clause-number">${idx}.</span>
    <span class="clause-word">${word}</span>
    <input style="flex:1;background:transparent;border:none;outline:none;color:var(--text-secondary);font-size:0.82rem;font-family:'Inter',sans-serif;" value="${clauseText}" placeholder="Complete the clause..."/>
    <span class="clause-remove" onclick="this.parentElement.remove()">âœ•</span>
  `;
            zone.appendChild(el);
        };

        window.clearResolution = function () {
            wpState = { pre: [], op: [] };
            document.getElementById('pre-drop').innerHTML = '<div class="clause-drop-placeholder" id="pre-placeholder">Click preambulatory clauses above to add them here...</div>';
            document.getElementById('op-drop').innerHTML = '<div class="clause-drop-placeholder" id="op-placeholder">Click operative clauses above to add them here...</div>';
            document.getElementById('wp-feedback').style.display = 'none';
        };

        window.checkResolution = function () {
            const preClauses = document.querySelectorAll('#pre-drop .clause-item');
            const opClauses = document.querySelectorAll('#op-drop .clause-item');
            const feedback = AIMentor.checkResolution(Array.from(preClauses), Array.from(opClauses));
            const fb = document.getElementById('wp-feedback');
            fb.style.display = 'block';
            fb.innerHTML = feedback.map(f => `<div class="feedback-item ${f.type}">${f.msg}</div>`).join('');
        };

        window.submitResolution = function () {
            const preClauses = document.querySelectorAll('#pre-drop .clause-item').length;
            const opClauses = document.querySelectorAll('#op-drop .clause-item').length;
            if (preClauses < 2 || opClauses < 2) {
                showToast('âš ï¸ Incomplete', 'Add at least 2 preambulatory and 2 operative clauses.', 'error');
                return;
            }
            GameState.addXP(150, 'Resolution Draft');
            GameState.unlockBadge('resolution-author');
            GameState.setScore('resolution', Math.min(100, (preClauses + opClauses) * 8 + 40));
            showToast('ðŸ“„ Resolution Submitted!', `Draft resolution with ${preClauses + opClauses} clauses accepted.`, 'success');
            navigate('debate');
        };

        /* ================================================
           SCREEN 15 â€” DEBATE MODE
           ================================================ */
        let debateRound = 0, debateScore = 0;
        function renderDebate() {
            const country = getCountry();
            debateRound = 0; debateScore = 0;
            const attack = AIMentor.getDelegateAttack(country.id, getTopic().id);
            setHTML(`
    <div class="page">
      <div class="container page-narrow">
        <div class="phase-banner">
          <div class="phase-number">âš”ï¸</div>
          <div class="phase-info"><div class="phase-title">Phase 4 â€” Debate & Defense</div><div class="phase-sub">Defend your resolution against AI delegates</div></div>
          <div class="phase-xp">+100 XP per round</div>
        </div>

        <div style="display:flex;align-items:center;gap:var(--space-lg);margin-bottom:var(--space-xl);">
          <div style="text-align:center;">
            <div style="font-size:3rem;">${country.flag}</div>
            <div style="font-size:0.75rem;color:var(--text-muted);">YOU</div>
          </div>
          <div style="flex:1;height:2px;background:var(--grad-gold);"></div>
          <div style="font-family:'Outfit',sans-serif;font-weight:800;font-size:1rem;color:var(--gold);">VS</div>
          <div style="flex:1;height:2px;background:var(--grad-coral);"></div>
          <div style="text-align:center;">
            <div style="font-size:3rem;">ðŸŒ</div>
            <div style="font-size:0.75rem;color:var(--text-muted);">AI DELEGATES</div>
          </div>
        </div>

        <div id="debate-arena"></div>
      </div>
    </div>
  `);
            renderDebateRound(attack);
        }

        function renderDebateRound(attack) {
            const topic = getTopic();
            document.getElementById('debate-arena').innerHTML = `
    <div style="animation:fadeSlideIn 0.3s ease;">
      <div style="display:flex;justify-content:space-between;align-items:center;margin-bottom:var(--space-lg);">
        <div style="font-size:0.85rem;color:var(--text-muted);">Round ${debateRound + 1} of 3</div>
        <div style="font-family:'Outfit',sans-serif;font-weight:700;color:var(--gold);">Score: ${debateScore}/300</div>
      </div>

      <div class="debate-challenge">
        <div class="debate-challenge-label">ðŸŽ¤ Challenge from AI Delegate</div>
        <div class="debate-challenge-text" id="challenge-text"></div>
        <div class="debate-country" id="challenge-attacker"></div>
      </div>

      <div class="card mb-lg">
        <h4 style="color:var(--text-primary);margin-bottom:var(--space-sm);">Your Response</h4>
        <p style="font-size:0.82rem;margin-bottom:var(--space-md);">Defend your resolution's position. Be diplomatic, specific, and persuasive.</p>
        <textarea class="textarea" id="debate-response" rows="6" placeholder="The delegation of ${getCountry().name} would like to respond to the distinguished delegate..."></textarea>
      </div>

      <div style="display:flex;gap:var(--space-md);justify-content:space-between;">
        <button class="btn btn-glass" onclick="navigate('workingpaper')">â† Back to Resolution</button>
        <button class="btn btn-gold" onclick="submitDebateRound()">Submit Response âš”ï¸</button>
      </div>
    </div>
  `;
            setTimeout(() => {
                typewriter('challenge-text', attack.text, 20);
                document.getElementById('challenge-attacker').textContent = 'â€” ' + attack.attacker + ' Delegation';
            }, 300);
        }

        window.submitDebateRound = function () {
            const response = document.getElementById('debate-response').value.trim();
            if (response.length < 15) { showToast('âš ï¸ Too brief', 'Write a proper response!', 'error'); return; }
            const eval_ = AIMentor.evaluateSpeech(response);
            const roundScore = Math.round(eval_.overall);
            debateScore += roundScore;
            debateRound++;
            GameState.addXP(100, 'Debate');
            GameState.setScore('diplomacy', Math.min(100, Math.round(debateScore / debateRound)));

            if (debateRound >= 3) {
                // Final debate result
                document.getElementById('debate-arena').innerHTML = `
      <div style="text-align:center;animation:fadeSlideIn 0.4s ease;padding:var(--space-3xl);">
        <div style="font-size:4rem;margin-bottom:var(--space-lg);">${debateScore >= 240 ? 'ðŸ†' : debateScore >= 180 ? 'âš”ï¸' : 'ðŸ“š'}</div>
        <h2 style="color:var(--text-primary);margin-bottom:var(--space-sm);">Debate Complete!</h2>
        <p style="margin-bottom:var(--space-xl);">Debate Score: <strong style="color:var(--gold);font-size:1.3rem;">${debateScore}/300</strong></p>
        <p>${debateScore >= 240 ? 'Outstanding performance! You defended your resolution with exceptional diplomacy.' : debateScore >= 180 ? 'Good debate performance. Your arguments were mostly persuasive.' : 'Your responses need more specificity and diplomatic language.'}</p>
        <div style="display:flex;gap:var(--space-md);justify-content:center;margin-top:var(--space-xl);">
          <button class="btn btn-gold btn-lg" onclick="navigate('voting')">Proceed to Vote ðŸ—³ï¸</button>
        </div>
      </div>
    `;
            } else {
                showToast('âš”ï¸ Round ' + debateRound, `Score: ${roundScore}/100 â€” ${roundScore >= 70 ? 'Well argued!' : 'Keep working on your arguments.'}`, roundScore >= 70 ? 'success' : 'info');
                const newAttack = AIMentor.getDelegateAttack(getCountry().id, getTopic().id);
                renderDebateRound(newAttack);
            }
        };

        /* ================================================
           SCREEN 16 â€” VOTING
           ================================================ */
        function renderVoting() {
            const topic = getTopic(); const myCountry = getCountry();
            setHTML(`
    <div class="page">
      <div class="container page-narrow">
        <div class="phase-banner">
          <div class="phase-number">ðŸ—³ï¸</div>
          <div class="phase-info"><div class="phase-title">Phase 5 â€” Voting Procedure</div><div class="phase-sub">Draft Resolution A â€” ${topic.name}</div></div>
          <div class="phase-xp">+100 XP</div>
        </div>

        <div id="voting-content">
          <div class="npc-chair" style="margin-bottom:var(--space-xl);">
            <div class="npc-avatar">ðŸ§‘â€âš–ï¸</div>
            <div>
              <div class="npc-speech-bubble">The committee will now move to a vote on Draft Resolution A on <strong>${topic.name}</strong>. All delegates must vote â€” no abstentions on procedural votes. Cast your delegation's vote now.</div>
              <div class="npc-name">ðŸŽ¤ Committee Chair</div>
            </div>
          </div>

          <h3 style="text-align:center;color:var(--text-primary);margin-bottom:var(--space-xl);">How does ${myCountry.flag} ${myCountry.name} vote?</h3>

          <div style="display:flex;gap:var(--space-xl);justify-content:center;flex-wrap:wrap;margin-bottom:var(--space-2xl);">
            <button class="vote-btn yes" onclick="castVote('yes')" id="vote-yes">
              <span class="vote-btn-icon">âœ…</span>YES â€” In Favor
            </button>
            <button class="vote-btn no" onclick="castVote('no')" id="vote-no">
              <span class="vote-btn-icon">âŒ</span>NO â€” Against
            </button>
            <button class="vote-btn abstain" onclick="castVote('abstain')" id="vote-abstain">
              <span class="vote-btn-icon">â¬œ</span>ABSTAIN
            </button>
          </div>
        </div>
      </div>
    </div>
  `);
        }

        window.castVote = function (vote) {
            const myCountry = getCountry(); const topic = getTopic();
            const allies = GameState.getSession().blocAllies;

            // Simulate AI voting
            const yesCountries = [myCountry.id, ...allies, ...COUNTRIES.filter(c => Math.random() > 0.45 && c.id !== myCountry.id).map(c => c.id)];
            const noCountries = COUNTRIES.filter(c => !yesCountries.includes(c.id) && Math.random() > 0.5).map(c => c.id);
            const abstainCountries = COUNTRIES.filter(c => !yesCountries.includes(c.id) && !noCountries.includes(c.id)).map(c => c.id);

            const yes = yesCountries.length, no = noCountries.length, abstain = abstainCountries.length;
            const total = yes + no + abstain;
            const passed = yes > no;

            GameState.addXP(100, 'Voting');

            document.getElementById('voting-content').innerHTML = `
    <div style="animation:fadeSlideIn 0.4s ease;">
      <div style="text-align:center;margin-bottom:var(--space-2xl);">
        <div style="font-size:1rem;color:var(--text-secondary);margin-bottom:var(--space-md);">Your vote: <strong style="color:${vote === 'yes' ? 'var(--emerald)' : vote === 'no' ? 'var(--coral)' : 'var(--text-secondary)'}">${vote.toUpperCase()}</strong></div>
        <div style="font-size:4rem;margin-bottom:var(--space-md);">${passed ? 'ðŸŽ‰' : 'âŒ'}</div>
        <h2 style="color:${passed ? 'var(--gold)' : 'var(--coral)'};">${passed ? 'RESOLUTION ADOPTED' : 'RESOLUTION FAILED'}</h2>
        <div style="font-family:'Outfit',sans-serif;font-size:0.9rem;color:var(--text-secondary);margin-top:var(--space-sm);">Draft Resolution A on ${topic.name}</div>
      </div>

      <!-- Tally -->
      <div class="card mb-xl">
        <div style="font-weight:700;color:var(--text-primary);margin-bottom:var(--space-lg);">ðŸ“Š Vote Count (${total} delegates)</div>
        <div class="vote-result-row">
          <div class="vote-result-label" style="color:var(--emerald);">âœ… YES</div>
          <div class="vote-result-bar-wrap"><div class="vote-result-fill" style="background:var(--grad-emerald);width:${Math.round(yes / total * 100)}%;"></div></div>
          <div class="vote-result-count" style="color:var(--emerald);">${yes}</div>
        </div>
        <div class="vote-result-row">
          <div class="vote-result-label" style="color:var(--coral);">âŒ NO</div>
          <div class="vote-result-bar-wrap"><div class="vote-result-fill" style="background:var(--grad-coral);width:${Math.round(no / total * 100)}%;"></div></div>
          <div class="vote-result-count" style="color:var(--coral);">${no}</div>
        </div>
        <div class="vote-result-row">
          <div class="vote-result-label">â¬œ ABSTAIN</div>
          <div class="vote-result-bar-wrap"><div class="vote-result-fill" style="background:rgba(255,255,255,0.1);width:${Math.round(abstain / total * 100)}%;"></div></div>
          <div class="vote-result-count">${abstain}</div>
        </div>

        <div style="display:flex;flex-wrap:wrap;gap:6px;margin-top:var(--space-lg);">
          ${COUNTRIES.map(c => {
                const isYes = yesCountries.includes(c.id), isNo = noCountries.includes(c.id);
                return `<span class="badge ${isYes ? 'badge-emerald' : isNo ? 'badge-coral' : 'badge-gray'}" title="${isYes ? 'YES' : isNo ? 'NO' : 'ABSTAIN'}">${c.flag}</span>`;
            }).join('')}
        </div>
      </div>

      <div style="text-align:center;">
        <button class="btn btn-gold btn-lg" onclick="navigate('awards')">ðŸ† Awards Ceremony</button>
      </div>
    </div>
  `;
        };

        /* ================================================
           SCREEN 17 â€” AWARDS CEREMONY
           ================================================ */
        function renderAwards() {
            const player = GameState.getPlayer();
            const scores = GameState.getScores();
            const avg = Math.round(Object.values(scores).reduce((a, b) => a + b, 0) / Object.keys(scores).length);
            const council = getCouncil(); const country = getCountry(); const topic = getTopic();

            GameState.addXP(300, 'Simulation Complete');
            GameState.saveSessionToHistory();

            const awards = [
                { medal: 'ðŸ¥‡', title: 'Best Delegate', winner: avg >= 75 ? player.name : 'The delegation of ' + country.name, given: avg >= 75 },
                { medal: 'ðŸ¥ˆ', title: 'Outstanding Delegate', winner: 'Runner-up Delegation', given: avg >= 60 },
                { medal: 'ðŸ¥‰', title: 'Honorable Mention', winner: 'Third Place Delegation', given: true },
                { medal: 'ðŸ“„', title: 'Best Position Paper', winner: scores.resolution >= 70 ? player.name : 'Distinguished Delegate', given: scores.resolution >= 70 },
                { medal: 'ðŸŽ¤', title: 'Best Speaker', winner: scores.speech >= 70 ? player.name : 'Honorable Delegate', given: scores.speech >= 70 },
                { medal: 'ðŸ¤', title: 'Best Negotiator', winner: scores.diplomacy >= 60 ? player.name : 'Coalition Builder', given: scores.diplomacy >= 60 }
            ];

            startConfetti();

            setHTML(`
    <div class="page">
      <div class="container">
        <div style="text-align:center;margin-bottom:var(--space-2xl);">
          <div style="font-size:4rem;margin-bottom:var(--space-md);animation:medalBounce 0.8s ease;">ðŸ›ï¸</div>
          <h2 class="text-gold">Awards Ceremony</h2>
          <p>${council.emoji} ${council.name} â€” ${topic.name}</p>
        </div>

        <!-- Chair announcement -->
        <div class="npc-chair" style="margin-bottom:var(--space-2xl);">
          <div class="npc-avatar">ðŸ§‘â€âš–ï¸</div>
          <div>
            <div class="npc-speech-bubble" id="awards-speech"></div>
            <div class="npc-name">ðŸŽ¤ Committee Chair â€” Dr. Amara Johnson</div>
          </div>
        </div>

        <!-- Awards Grid -->
        <div class="grid-3 stagger" style="margin-bottom:var(--space-2xl);">
          ${awards.map((a, i) => `
            <div class="award-card" style="animation-delay:${i * 0.15}s;${a.given ? 'border-color:var(--border-gold);' : ''}" >
              <div class="award-medal">${a.medal}</div>
              <div class="award-title" style="color:${a.given ? 'var(--gold)' : 'var(--text-secondary)'};">${a.title}</div>
              <div class="award-winner">${a.given ? a.winner : 'â€”'}</div>
              ${a.given && a.winner === player.name ? `<div class="badge badge-gold" style="margin-top:var(--space-sm);">ðŸŽ‰ That's YOU!</div>` : ''}
            </div>
          `).join('')}
        </div>

        <!-- Overall Score Summary -->
        <div class="card" style="max-width:600px;margin:0 auto var(--space-2xl);border-color:var(--border-gold);background:rgba(212,175,55,0.04);">
          <h3 style="color:var(--gold);text-align:center;margin-bottom:var(--space-xl);">Your Performance Summary</h3>
          <div style="display:flex;flex-direction:column;gap:var(--space-md);">
            ${Object.entries({ Research: scores.research, Speech: scores.speech, Diplomacy: scores.diplomacy, Negotiation: scores.negotiation, Resolution: scores.resolution }).map(([k, v]) => `
              <div class="analytics-bar-row">
                <div class="analytics-bar-label">${k}</div>
                <div class="analytics-bar-track"><div class="analytics-bar-fill" style="width:${v}%;background:var(--grad-gold);"></div></div>
                <div class="analytics-bar-val" style="color:var(--gold);">${v}</div>
              </div>
            `).join('')}
          </div>
          <div style="text-align:center;margin-top:var(--space-xl);padding-top:var(--space-lg);border-top:1px solid var(--border);">
            <div style="font-family:'Outfit',sans-serif;font-size:3rem;font-weight:900;color:var(--gold);">${avg}</div>
            <div style="color:var(--text-secondary);">Overall Score / 100</div>
          </div>
        </div>

        <!-- XP Reward -->
        <div class="card" style="text-align:center;max-width:500px;margin:0 auto var(--space-2xl);background:rgba(212,175,55,0.06);border-color:var(--border-gold);">
          <div style="font-family:'Outfit',sans-serif;font-size:2rem;font-weight:800;color:var(--gold);margin-bottom:4px;">+300 XP</div>
          <div style="color:var(--text-secondary);">Earned for completing the simulation!</div>
          <div style="margin-top:var(--space-md);">
            <div style="font-size:0.82rem;color:var(--text-muted);">Total XP: ${player.xp.toLocaleString()} Â· Level ${GameState.getLevelInfo().level} â€” ${GameState.getLevelInfo().title}</div>
          </div>
        </div>

        <div style="display:flex;gap:var(--space-lg);justify-content:center;flex-wrap:wrap;">
          <button class="btn btn-glass" onclick="navigate('analytics')">ðŸ“Š View Full Analytics</button>
          <button class="btn btn-glass" onclick="navigate('leaderboard')">ðŸ† Leaderboard</button>
          <button class="btn btn-gold btn-lg" onclick="newSimulation()">ðŸŽ® Start New Simulation</button>
        </div>
      </div>
    </div>
  `);

            setTimeout(() => typewriter('awards-speech', `Distinguished delegates, I am honored to close this session of the ${council.name}. Today we have addressed the critical matter of ${topic.name}. Before we adjourn, I am pleased to announce the awards for this session based on outstanding performance. Congratulations to all delegates!`, 20), 800);
        }

        window.newSimulation = function () {
            GameState.resetSession();
            navigate('avatar');
        };

        /* ================================================
           SCREEN 18 â€” ANALYTICS DASHBOARD
           ================================================ */
        function renderAnalytics() {
            const player = GameState.getPlayer();
            const scores = GameState.getScores();
            const info = GameState.getLevelInfo();
            const history = GameState.get().history;

            // SVG Radar Chart
            function radarChart(scores) {
                const cats = ['Research', 'Speech', 'Diplomacy', 'Negotiation', 'Resolution'];
                const vals = [scores.research, scores.speech, scores.diplomacy, scores.negotiation, scores.resolution];
                const cx = 130, cy = 130, r = 100, n = 5;
                const points = cats.map((_, i) => {
                    const angle = (i / n) * Math.PI * 2 - Math.PI / 2;
                    const v = vals[i] / 100;
                    return { x: cx + r * v * Math.cos(angle), y: cy + r * v * Math.sin(angle), lx: cx + (r + 20) * Math.cos(angle), ly: cy + (r + 20) * Math.sin(angle), label: cats[i], val: vals[i] };
                });
                const gridR = [0.25, 0.5, 0.75, 1];
                const gridCircles = gridR.map(rv => {
                    const pts = cats.map((_, i) => { const a = (i / n) * Math.PI * 2 - Math.PI / 2; return `${cx + r * rv * Math.cos(a)},${cy + r * rv * Math.sin(a)}`; }).join(' ');
                    return `<polygon points="${pts}" fill="none" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>`;
                }).join('');
                const axes = cats.map((_, i) => { const a = (i / n) * Math.PI * 2 - Math.PI / 2; return `<line x1="${cx}" y1="${cy}" x2="${cx + r * Math.cos(a)}" y2="${cy + r * Math.sin(a)}" stroke="rgba(255,255,255,0.1)" stroke-width="1"/>`; }).join('');
                const poly = `<polygon points="${points.map(p => `${p.x},${p.y}`).join(' ')}" fill="rgba(212,175,55,0.15)" stroke="#D4AF37" stroke-width="2"/>`;
                const dots = points.map(p => `<circle cx="${p.x}" cy="${p.y}" r="4" fill="#D4AF37"/>`).join('');
                const labels = points.map(p => `<text x="${p.lx}" y="${p.ly}" text-anchor="middle" dominant-baseline="middle" fill="#8A93B8" font-size="11" font-family="Inter">${p.label}</text>`).join('');
                return `<svg width="260" height="260" class="analytics-radar">${gridCircles}${axes}${poly}${dots}${labels}</svg>`;
            }

            setHTML(`
    <div class="page">
      <div class="container">
        <div class="page-title">
          <h2>Personal Analytics Dashboard</h2>
          <p>Track your growth as a Model United Nations delegate</p>
        </div>

        <!-- Player Profile Card -->
        <div class="card mb-xl" style="display:flex;align-items:center;gap:var(--space-xl);flex-wrap:wrap;">
          <div style="width:80px;height:80px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:3rem;border:3px solid var(--border-gold);background:var(--bg-elevated);box-shadow:var(--shadow-gold);flex-shrink:0;">${player.avatarEmoji || 'ðŸ§‘'}</div>
          <div style="flex:1;">
            <h3 style="color:var(--text-primary);margin-bottom:4px;">${player.name}</h3>
            <div style="display:flex;gap:var(--space-sm);flex-wrap:wrap;margin-bottom:var(--space-md);">
              <span class="badge badge-gold">Level ${info.level} â€” ${info.title}</span>
              <span class="badge badge-gray">${player.completedSims} Simulations</span>
              <span class="badge badge-purple">${player.badges.length} Badges</span>
            </div>
            <div class="xp-bar-container">
              <div class="xp-bar" style="max-width:400px;">
                <div class="xp-bar-fill" style="width:${info.pct}%;"></div>
              </div>
              <div class="xp-label">${player.xp.toLocaleString()} / ${info.next ? info.next.toLocaleString() : 'MAX'} XP</div>
            </div>
          </div>
          <div style="text-align:right;">
            <div style="font-family:'Outfit',sans-serif;font-size:3rem;font-weight:900;color:var(--gold);">${player.xp.toLocaleString()}</div>
            <div style="font-size:0.8rem;color:var(--text-muted);">Total XP Earned</div>
          </div>
        </div>

        <div class="grid-2" style="gap:var(--space-xl);margin-bottom:var(--space-xl);">
          <!-- Radar Chart -->
          <div class="card">
            <h4 style="color:var(--text-primary);margin-bottom:var(--space-lg);text-align:center;">Skill Radar</h4>
            ${radarChart(scores)}
            <div style="display:grid;grid-template-columns:1fr 1fr;gap:var(--space-sm);margin-top:var(--space-lg);">
              ${Object.entries({ Research: scores.research, Speech: scores.speech, Diplomacy: scores.diplomacy, Negotiation: scores.negotiation, Resolution: scores.resolution }).map(([k, v]) => `
                <div style="display:flex;align-items:center;justify-content:space-between;font-size:0.82rem;">
                  <span style="color:var(--text-secondary);">${k}</span>
                  <span style="font-family:'Outfit',sans-serif;font-weight:700;color:var(--gold);">${v}</span>
                </div>
              `).join('')}
            </div>
          </div>

          <!-- Score Bars -->
          <div class="card">
            <h4 style="color:var(--text-primary);margin-bottom:var(--space-lg);">Score Breakdown</h4>
            ${Object.entries({
                'ðŸ“š Research': scores.research,
                'ðŸŽ¤ Public Speaking': scores.speech,
                'ðŸ¤ Diplomacy': scores.diplomacy,
                'ðŸ’¼ Negotiation': scores.negotiation,
                'ðŸ“„ Resolution Writing': scores.resolution
            }).map(([k, v]) => `
              <div class="analytics-bar-row">
                <div class="analytics-bar-label" style="width:160px;font-size:0.8rem;">${k}</div>
                <div class="analytics-bar-track"><div class="analytics-bar-fill" style="width:${v}%;background:${v >= 80 ? 'var(--grad-emerald)' : v >= 60 ? 'var(--grad-gold)' : 'var(--grad-coral)'};"></div></div>
                <div class="analytics-bar-val" style="color:${v >= 80 ? 'var(--emerald)' : v >= 60 ? 'var(--gold)' : 'var(--coral)'};">${v}</div>
              </div>
            `).join('')}
          </div>
        </div>

        <!-- Simulation History -->
        ${history.length > 0 ? `
        <div class="card mb-xl">
          <h4 style="color:var(--text-primary);margin-bottom:var(--space-lg);">ðŸ“‹ Simulation History</h4>
          <div style="overflow-x:auto;">
            <table class="leaderboard-table">
              <thead><tr><th>#</th><th>Date</th><th>Council</th><th>Country</th><th>Topic</th><th>Score</th></tr></thead>
              <tbody>
                ${history.map((h, i) => {
                const c = COUNCILS.find(x => x.id === h.council); const co = COUNTRIES.find(x => x.id === h.country); const t = TOPICS.find(x => x.id === h.topic);
                return `<tr><td>${i + 1}</td><td>${h.date}</td><td>${c ? c.emoji + ' ' + c.short : h.council}</td><td>${co ? co.flag + ' ' + co.name : h.country}</td><td>${t ? t.emoji + ' ' + t.name : h.topic}</td><td class="lb-xp">${h.totalScore}</td></tr>`;
            }).join('')}
              </tbody>
            </table>
          </div>
        </div>
        ` : ''}

        <!-- Badges -->
        <div class="card mb-xl">
          <h4 style="color:var(--text-primary);margin-bottom:var(--space-lg);">ðŸ… Achievements <span class="badge badge-gold">${player.badges.length}/${ACHIEVEMENTS.length}</span></h4>
          <div class="achievement-grid">
            ${ACHIEVEMENTS.map(a => `
              <div class="achievement-item ${player.badges.includes(a.id) ? 'unlocked' : 'locked'}" title="${a.desc}">
                <div class="achievement-emoji">${a.emoji}</div>
                <div class="achievement-name">${a.name}</div>
                <div class="achievement-xp">+${a.xp} XP</div>
              </div>
            `).join('')}
          </div>
        </div>

        <div style="display:flex;gap:var(--space-md);justify-content:center;">
          <button class="btn btn-glass" onclick="navigate('leaderboard')">ðŸ† View Leaderboard</button>
          <button class="btn btn-gold" onclick="navigate('avatar')">ðŸŽ® New Simulation</button>
        </div>
      </div>
    </div>
  `);
        }

        /* ================================================
           SCREEN 19 â€” LEADERBOARD
           ================================================ */
        function renderLeaderboard() {
            const player = GameState.getPlayer();
            const info = GameState.getLevelInfo();
            const data = [...LEADERBOARD_SEED];

            // Add player
            const playerRank = data.findIndex(d => d.xp < player.xp);
            const rank = playerRank === -1 ? data.length + 1 : playerRank + 1;
            const playerEntry = { rank, name: player.name, school: 'Your School', xp: player.xp, badges: player.badges.length, flag: getCountry().flag, isPlayer: true };
            if (playerRank >= 0) data.splice(playerRank, 0, playerEntry);
            else data.push(playerEntry);
            data.forEach((d, i) => d.rank = i + 1);

            setHTML(`
    <div class="page">
      <div class="container">
        <div class="page-title">
          <h2>ðŸ† Global Leaderboard</h2>
          <p>Top MUNverse delegates worldwide</p>
        </div>

        <div class="tab-list" style="max-width:400px;margin:0 auto var(--space-xl);">
          <button class="tab-btn active" onclick="switchTab(this,'national')" id="tab-national">ðŸŒ National</button>
          <button class="tab-btn" onclick="switchTab(this,'class')" id="tab-class">ðŸŽ“ Class</button>
          <button class="tab-btn" onclick="switchTab(this,'school')" id="tab-school">ðŸ« School</button>
        </div>

        <div class="tab-panel active" id="panel-national">
          <div class="card" style="overflow-x:auto;">
            <table class="leaderboard-table">
              <thead><tr><th>Rank</th><th>Delegate</th><th>School</th><th>XP</th><th>Badges</th></tr></thead>
              <tbody>
                ${data.map(d => `
                  <tr class="${d.isPlayer ? 'player-row' : ''}">
                    <td><span class="lb-rank ${d.rank === 1 ? 'gold' : d.rank === 2 ? 'silver' : d.rank === 3 ? 'bronze' : ''}">${d.rank === 1 ? 'ðŸ¥‡' : d.rank === 2 ? 'ðŸ¥ˆ' : d.rank === 3 ? 'ðŸ¥‰' : '#' + d.rank}</span></td>
                    <td><div class="lb-name-cell"><div class="lb-avatar">${d.flag}</div><div><div style="font-weight:600;font-size:0.9rem;${d.isPlayer ? 'color:var(--gold);' : ''}">${d.name}${d.isPlayer ? ' (You)' : ''}</div><div style="font-size:0.75rem;color:var(--text-muted);">${info.title}</div></div></div></td>
                    <td style="font-size:0.85rem;color:var(--text-secondary);">${d.school}</td>
                    <td class="lb-xp">${d.xp.toLocaleString()}</td>
                    <td><span class="badge badge-purple">${d.badges} ðŸ…</span></td>
                  </tr>
                `).join('')}
              </tbody>
            </table>
          </div>
        </div>

        <div class="tab-panel" id="panel-class">
          <div class="card" style="text-align:center;padding:var(--space-3xl);">
            <div style="font-size:4rem;margin-bottom:var(--space-lg);">ðŸŽ“</div>
            <h3 style="color:var(--text-primary);margin-bottom:var(--space-md);">Class Leaderboard</h3>
            <p>Share your <strong style="color:var(--gold);">Class Code</strong> with your classmates to appear here!</p>
            <div style="margin-top:var(--space-xl);">
              <div class="badge badge-gold" style="font-size:1rem;padding:12px 24px;letter-spacing:0.2em;">MUN-2025-CLASS</div>
            </div>
          </div>
        </div>

        <div class="tab-panel" id="panel-school">
          <div class="card" style="text-align:center;padding:var(--space-3xl);">
            <div style="font-size:4rem;margin-bottom:var(--space-lg);">ðŸ«</div>
            <h3 style="color:var(--text-primary);margin-bottom:var(--space-md);">School Leaderboard</h3>
            <p>Register your school to compete in school rankings!</p>
            <button class="btn btn-gold" style="margin-top:var(--space-xl);">Register School</button>
          </div>
        </div>

        <div style="text-align:center;margin-top:var(--space-xl);">
          <button class="btn btn-glass" onclick="navigate('home')">â† Home</button>
          <button class="btn btn-gold" style="margin-left:var(--space-md);" onclick="navigate('avatar')">ðŸŽ® New Simulation</button>
        </div>
      </div>
    </div>
  `);
        }

        /* ================================================
           SCREEN 20 â€” CRISIS MODE
           ================================================ */
        function renderCrisis() {
            const crisis = CRISES[Math.floor(Math.random() * CRISES.length)];
            setHTML(`
    <div class="page">
      <div class="container page-narrow">
        <div class="phase-banner crisis-alert" style="background:rgba(255,99,72,0.08);border-color:rgba(255,99,72,0.4);">
          <div class="phase-number" style="background:var(--grad-coral);">ðŸš¨</div>
          <div class="phase-info"><div class="phase-title" style="color:var(--coral);">CRISIS ALERT â€” ${crisis.urgency}</div><div class="phase-sub">${crisis.name}</div></div>
          <div class="phase-xp">+300 XP</div>
        </div>

        <div class="npc-chair" style="margin-bottom:var(--space-xl);">
          <div class="npc-avatar" style="border-color:rgba(255,99,72,0.6);">ðŸ§‘â€âš–ï¸</div>
          <div>
            <div class="npc-speech-bubble" style="background:rgba(255,99,72,0.06);border-color:rgba(255,99,72,0.3);" id="crisis-speech"></div>
            <div class="npc-name" style="color:var(--coral);">ðŸŽ¤ Crisis Director</div>
          </div>
        </div>

        <div class="card mb-xl" style="background:rgba(255,99,72,0.04);border-color:rgba(255,99,72,0.3);">
          <div style="font-size:3rem;margin-bottom:var(--space-md);">${crisis.emoji}</div>
          <h3 style="color:var(--coral);margin-bottom:var(--space-md);">${crisis.name}</h3>
          <p style="color:var(--text-primary);line-height:1.8;margin-bottom:var(--space-lg);">${crisis.desc}</p>
          <div style="font-weight:700;color:var(--coral);margin-bottom:var(--space-sm);">âš¡ Your Challenge:</div>
          <p style="color:var(--text-primary);">${crisis.challenge}</p>
        </div>

        <div class="card mb-xl">
          <h4 style="color:var(--text-primary);margin-bottom:var(--space-lg);">Select Your Emergency Response</h4>
          <div style="display:flex;flex-direction:column;gap:var(--space-sm);" id="crisis-options">
            ${crisis.options.map((opt, i) => `<button class="quiz-option" onclick="selectCrisisOption(${i},'${opt.replace(/'/g, "\\'")}',${crisis.best})" id="copt-${i}"><span class="quiz-letter">${'ABCD'[i]}</span>${opt}</button>`).join('')}
          </div>
        </div>
      </div>
    </div>
  `);
            setTimeout(() => typewriter('crisis-speech', `Delegates, a critical situation has developed requiring your IMMEDIATE attention. We must convene an emergency session. ${crisis.desc.split('.')[0]}. I urge all delegations to act with urgency and provide decisive leadership.`, 20), 500);
        }

        window.selectCrisisOption = function (idx, option, best) {
            const correct = idx === best;
            document.querySelectorAll('#crisis-options .quiz-option').forEach((el, i) => {
                if (i === best) el.classList.add('correct');
                else if (i === idx) el.classList.add('wrong');
                el.disabled = true;
            });
            GameState.addXP(300, 'Crisis Response');
            if (correct) {
                GameState.unlockBadge('crisis-survivor');
                showToast('ðŸš¨ Crisis Handled!', 'Excellent response! +300 XP earned.', 'success');
            } else {
                showToast('âš ï¸ Suboptimal Response', `The best response was: ${CRISES.find(c => c.options.includes(option)) || option}`, 'info');
            }
            setTimeout(() => navigate('committee'), 2500);
        };

        /* ================================================
           INITIALIZATION
           ================================================ */

        function init() {
            const tips = ['Loading delegate profiles...', 'Preparing the conference hall...', 'Briefing the Chair...', 'Synchronizing diplomatic databases...', 'Calibrating the AI mentor...'];
            let progress = 0;
            const bar = document.getElementById('loading-progress');
            const tip = document.getElementById('loading-tip');
            const interval = setInterval(() => {
                progress += Math.random() * 25 + 10;
                if (bar) bar.style.width = Math.min(progress, 100) + '%';
                if (tip) tip.textContent = tips[Math.floor(Math.random() * tips.length)];
                if (progress >= 100) {
                    clearInterval(interval);
                    setTimeout(() => {
                        document.getElementById('loading-screen').classList.add('hidden');
                        window.addEventListener('hashchange', router);
                        router();
                        updateNav();
                        updateNavXP();
                    }, 400);
                }
            }, 200);
        }

        window.addEventListener('load', init);

    </script>
</body>

</html>